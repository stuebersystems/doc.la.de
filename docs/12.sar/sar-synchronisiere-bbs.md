# Synchronisiere BBS Abwandlung für das Saarland

[1]:/assets/images/saarland/01.png "Autoren"
[2]:/assets/images/saarland/02.png "Abbildung"
[3]:/assets/images/saarland/03.png "Abbildung"
[4]:/assets/images/saarland/04.png "Abbildung"
[5]:/assets/images/saarland/05.png "Abbildung"
[6]:/assets/images/saarland/06.png "Abbildung"
[7]:/assets/images/saarland/07.png "Abbildung"
[8]:/assets/images/saarland/08.png
[9]:/assets/images/saarland/09.png
[10]:/assets/images/saarland/10.png
[11]:/assets/images/saarland/11.png
[12]:/assets/images/saarland/12.png
[13]:/assets/images/saarland/13.png
[14]:/assets/images/saarland/14.png
[15]:/assets/images/saarland/15.png
[16]:/assets/images/saarland/16.png
[17]:/assets/images/saarland/17.png
[18]:/assets/images/saarland/18.png
[19]:/assets/images/saarland/19.png
[20]:/assets/images/saarland/20.png
[21]:/assets/images/saarland/21.png
[22]:/assets/images/saarland/22.png
[23]:/assets/images/saarland/23.png
[24]:/assets/images/saarland/24.png
[25]:/assets/images/saarland/25.png
[26]:/assets/images/saarland/26.png
[27]:/assets/images/saarland/27.png
[28]:/assets/images/saarland/28.png
[29]:/assets/images/saarland/29.png
[30]:/assets/images/saarland/30.png
[31]:/assets/images/saarland/31.png
[32]:/assets/images/saarland/32.png
[33]:/assets/images/saarland/33.png
[34]:/assets/images/saarland/34.png
[35]:/assets/images/saarland/35.png
[36]:/assets/images/saarland/36.png
[37]:/assets/images/saarland/37.png
[38]:/assets/images/saarland/38.png
[39]:/assets/images/saarland/39.png
[40]:/assets/images/saarland/40.png
[41]:/assets/images/saarland/41.png
[42]:/assets/images/saarland/42.png
[43]:/assets/images/saarland/43.png
[44]:/assets/images/saarland/44.png
[45]:/assets/images/saarland/45.png
[46]:/assets/images/saarland/46.png
[47]:/assets/images/saarland/47.png
[48]:/assets/images/saarland/48.png
[49]:/assets/images/saarland/49.png
[50]:/assets/images/saarland/50.png
[51]:/assets/images/saarland/51.png
[52]:/assets/images/saarland/52.png
[53]:/assets/images/saarland/53.png
[54]:/assets/images/saarland/54.png
[55]:/assets/images/saarland/55.png


Auf der Basis eines unserer Standardskripte (Entwicklungsstand 2005) wurde eine durch Kunden modifizierte Variante des Skripte "Synchronisieren BBS.dws" erstellt.

[![Autoren][1]][1]

**Die nachstehende Anleitung dazu wurde durch das Ministerium für Bildung und Kultur Saarland verfasst.**

Stand: 06.09.2019

## Support

Für nicht autorisierte Änderungen am Quellcode übernimmt STÜBER SYSTEMS weder Gewährleisung noch Support.

## Speicherort

Das Skript wird mit der Installation von MAGELLAN als Server-/Einzelplatzinstallation unter `C:\Users\Public\Documents\Stueber Systems\Magellan 9\Skripte\Saarland` abgelegt.

## Berücksichtigung von Wiederholern in Magellan nach der AO-BS (Ausbildung an Berufsschulen im Saarland)

1. Ausgangssituation

WiederholerInnen sind im Berufsschulmodul und somit im Synchronisierungsskript „Synchronisiere BBS.dws“ bis dato nicht anwenderfreundlich bzw. nicht korrekt berücksichtigt.
Wiederholt ein SchülerIn ein Halbjahr, weil er die Abschlussprüfung nicht bestanden und den Bildungsgang in der Berufsschule nicht erfolgreich absolviert hat, so müssen die Noten des zu wiederholenden Schuljahres (Notenverbesserungen/-verschlechterungen) im Berufsschulmodul entsprechend der AO-BS berücksichtigt werden.
Das Magellan Skript Synchronisiere BBS.dws im Berufsschulmodul überschreibt nicht die wiederholten Halbjahre, sondern fügt sie als neue Halbjahre hinzu. Ebenso werden die wiederholten Halbjahre bei den unterrichteten Stunden (Faktoren der Lernfelder) mitgezählt. Die Gewichtung für die Endnoten musste daher angepasst werden.

Bei einer dreijährigen Ausbildung gilt in der Berufsschulmodul-Matrix folgendes:

[![Abbildung][2]][2]

Die Wiederholung kann demnach in der Klasse 12-1 (Regelfall im kfm. Bereich) oder in der Klasse 12-2 stattfinden. Die erbrachten Leistungen (Noten) sowie die Faktoren (Lernfelder) müssen in diesem Fall entsprechend der Klassenzuordnung berücksichtigt werden:

[![Abbildung][3]][3]

Entweder müssen die J5-Noten oder die J6-Noten im Wiederholfall mit den Noten aus der J7-Spalte überschrieben werden. Dies gilt auch für die entsprechenden Faktoren.
Die Halbjahresnoten sind in der DB-Tabelle Schuelerfachdaten gespeichert und werden beim Synchronisieren (Synchronisiere BBS.dws) in das Berufsschulmodul zeitraummäßig (von links nach rechts) übertragen. Für die Notenkorrektur muss daher dieses Skript angepasst werden. 

Eine 2. Wiederholung muss ebenfalls berücksichtigt werden, zum Beispiel: 

[![Abbildung][4]][4]

Bei der ersten Wiederholung überschreiben die J7-Noten die J5-Noten, bei der 2. Wiederholung die J8-Noten die J6-Noten.
Denkbar ist allerdings auch folgender Fall der ersten und zweiten Wiederholung:

[![Abbildung][5]][5]

Die Faktoren (Unterrichtstunden im Lernfeld) sind ebenfalls entsprechend den Noten anzupassen:

[![Abbildung][6]][6]

Die Zuteilung zu einer Klasse entscheidet nicht nur über die zu wiederholenden Lernfelder, sondern auch über die Faktoren der Lernfelder. Somit müssen nicht nur die zu überschreibenden Noten, sondern auch die zu überschreibenden Faktoren beachtet werden. Für die Endnoten-Faktoren wird nun nicht mehr die Spalte J8 (Faktoren), sondern die J9-Spalte (Faktoren) verwendet.

Für Wiederholer aus 3 1/2 ergibt sich ein weiteres Problem in Magellan:
Beispiel 3 ½ jährige Klasse 1. und 2. Wiederholung:

[![Abbildung][7]][7]

Somit überschreibt die 2. Wiederholung bei 3 ½ jährigen Klassen die 1. Wiederholung die J9-Noten. Diese ist allerdings– wie bereits erwähnt – für die Endnoten reserviert und dürfte somit nicht überschrieben werden.

## 2. Lösungsweg – Anpassung des Synchronisierungsskriptes

Da die meisten Berichte (Crystal Reports) die Endnoten aus der Spalte J9 für die verschiedensten Zeugnisse entnehmen, bleibt diese Spalte unangetastet. Andernfalls müssten sonst sehr viele Berichte angepasst werden.
WiederholerInnen stellen zahlenmäßig den geringsten Aufwand dar, da die Mehrheit der SchülerInnen die Berufsschule erfolgreich absolviert.
Um den Zeitaufwand möglichst gering zu halten, wurde das Skript im Wesentlichen nur bezüglich der WiederholerInnen angepasst. Die Spalte J9 ist damit weiterhin für Endnoten und den zugehörigen Faktorensummen reserviert. Weitere Noten (2. Wiederholung bei einer 3 ½ jährigen Ausbildung) erscheinen nun in der Spalte Zusatznote1 und der zugehörige Faktor in der Spalte Faktor. Bisher wurde die J8-Spalte(Faktoren) als Summenspalte für erteilten Stunden zwecks Gewichtung der Endnoten-Spalte J9 verwendet. Diese Gewichtung wurde bei Wiederholern fehlerhaft berechnet. Dieser Mangel wurde ebenfalls beseitigt.

## 3. Berücksichtigung von WiederholerInnen in Magellan (Anwendung des Skriptes)

### 3.1 Allgemeine Hinweise zum Skript „Synchronisiere BBS.dws“

Schulen ohne Berufsschulklassen sollten das bisherige Synchronisierungsskript verwenden.
Schulen, die in ihren Zeugnisberichten usw. nicht auf das Berufsschulmodul sondern
ausschließlich auf die Tabelle Schuelerfachdaten zugreifen, sollten diese Skriptänderung ebenfalls nicht benutzen. 

Dieses Skript wurde unter Magellan 6 angepasst und getestet. Unter Magellan 7 müsste es auch lauffähig sein.

> **STÜBER SYSTEMS:** Mit der Ausgabe MAGELLAN 9.0.3 wird unter .../Skripte/Saarland ein unter MAGELLAN 9 lauffähiges Skript ausgeliefert.

Folgende Dateien werden vom MBK zur Verfügung gestellt:

* Skriptdatei „Synchronisiere BBS.dws“
* Dokumentation zur Benutzung des angepassten Skriptes (BS-AO-Magellan-WDH.pdf, diese Dokumentation)
* Crystal Report zur Anzeige der WiederholerInnen (Wiederholerliste.rpt) (Nicht Teil der MAGELLAN-Installation)
* Crystal Report für die Schulbescheinigung (Schulbescheinigung.rpt) (Nicht Teil der MAGELLAN-Installation):

### 3.2 Schüler hat bereits den Bildungsgang der Berufsschule erfolgreich abgeschlossen

In diesem Fall besitzt der SchülerIn bereits ein Abschlusszeugnis. In Magellan wird für diesen SchülerIn (diese WiederholerIn) nur eine Schulbescheinigung ausgestellt.

### 3.3 Schüler ist WiederholerIn

### 3.3.1 Schüler- und Klassendaten ändern (Vorarbeiten)

[![Abbildung][8]][8]

Für WiederholerInnen ist die Option Wiederholer (Checkbox) sowie im Feld achprüfung die zugewiesene Klassenstufe 12-1 (zum Beispiel) für die 1. Wiederholung anzugeben.
Die zweite Wiederholung wird im Feld Entscheidung definiert:

[![Abbildung][9]][9]

Folgende Kürzel (Schüsselverzeichnisse) müssen daher angelegt werden:
 Verzeichnisse Weitere Schüsselverzeichnisse Nachprüfungen (1. Wiederholung)

[![Abbildung][10]][10]

[![Abbildung][11]][11]

Die entsprechenden Kürzel sind anzulegen. Die jeweilige Bedeutung ergibt sich aus der Bezeichnung.
Für die 2. Wiederholung ist das Schlüsselverzeichnis Entscheidungen anzulegen:

[![Abbildung][12]][12]

Wichtig ist auch der Jahrgang aus der Tabelle Klassenzeitraum. Dieser ist unter dem Objekt Klasse Register Zeiträume zu pflegen:

[![Abbildung][13]][13]

Die Angabe es Klassen-Jahrganges ist auch wichtig für das Berufsschulmodul. Für jedes neue Ausbildungsjahr ist der Jahrgang um 1 (ein Jahr) zu erhöhen.
Am Ende der Ausbildung müssen folgende Werte vorliegen:

[![Abbildung][14]][14]

### 3.3.2 Benutzung des Synchronisierungsskriptes (Synchronisiere BBS.dws)

#### Notwendige Vorarbeiten

* WiederholerInnen sind als Wiederholer (Checkbox) gekennzeichnet (Schülerdaten);
* Für die erste Wiederholung ist das Nachprüfungs-KZ: WDH1-1HJ oder WDH1-2HJ
eingetragen;
* Für die zweite Wiederholung ist das Nachprüfungs-KZ der ersten Wiederholung sowie
das Entscheidungs-KZ für die zweite Wiederholung: WDH2-1HJ oder WDH2-2HJ
eingegeben;
* Der Klassen-Jahrgang muss entsprechend jährlich gepflegt werden.
Nur wenn die genannten Angaben vorliegen, liefert das Synchronisierungsskript sinnvolle
Ergebnisse.

#### Vorbeugende Sicherungen

* Kopie der Datenbank (Magellan6.fdb) beim ersten Test;
* Orginal-Synchronisierungsskript Synchronisiere BBS.dws (Ordner \...\Skripte) kopieren.

#### Ablauf der Synchronisierung

* Angepasste (neue) Skriptdatei Synchronisiere BBS.dws in den Ordner \...\Skripte
kopieren;
* Synchronisierungsskript im BS-Modul ausführen.

[![Abbildung][15]][15]

> **Hinweis** Da beim Synchronisieren wichtige Hinweise auf Plausibilitäts- und sonstige Fehler (fehlendes Wiederholer-Kennzeichen, obwohl als Wiederholer gekennzeichnet usw.) angezeigt werden, sollte man die WiederholerInnen separat synchronisieren. Beim Durchlauf von 100 Schülern und mehr kann man sonst nur durch Zufall eine Fehlermeldung erkennen. Da man bei der obigen Auswahl nicht erkennt, ob der Schüler ein WiederholerIn ist, sollte man den mitgelieferten Crystal Report
Wiederholerliste.rpt einsetzen. Dieser erzeugt eine Liste der WiederholerInnen pro Klasse.

#### Ort des Synchronisierungsskriptes

[![Abbildung][16]][16]

> **STÜBER SYSTEMS**: Unter MAGELLAN 9 sollte bei einer Standardinstallation der Speicherort auf dem Serverrechner unter `C:\Users\Public\Documents\Stueber Systems\Magellan 9\Skripte` sein.

[![Abbildung][17]][17]

### 3.3.3 Beispiele zum Synchronisierungsskriptes (Synchronisiere BBS.dws)

#### 3.3.3.1 Beispiel1 – dreijährige Ausbildung – erste Wiederholung

Zwei Wiederholer – Schülerin Franz und Schüler Schwarz (Kaufmann/Kauffrau für
Büromanagement)

a) Schülerdaten Franz

[![Abbildung][18]][18]

b) Klassen-Jahrgang der Klasse B12a (Kfm. für Büromanagement)

[![Abbildung][19]][19]

c) Noten der Schülerin Franz im 1. Halbjahr – Halbjahreskonferenz (der Wiederholung):

[![Abbildung][20]][20]

d) Halbjahresnoten der Schülerin Franz im BS-Modul - vor dem Synchronisieren (BS-Modul)

[![Abbildung][21]][21]

e) J5-Noten der Schülerin Franz nach dem Synchronisieren (BS-Modul)

[![Abbildung][22]][22]

Die Halbjahresnoten werden bei der Synchronisierung in die J5-Spalte übertragen und somit die Noten des 5. Halbjahres überschrieben.

f) Schülerdaten Schwarz

[![Abbildung][23]][23]

g) Halbjahresnoten des Schülers Schwarz (Halbjahreskonferenz):

[![Abbildung][24]][24]

h) Benutzung des bisherigen Synchronisierungsskriptes – Schüler Schwarz

Wird das bisherige Synchronisierungsskript „Synchronisiere BBS.dws“ benutzt, erscheint folgende Ausgabe:

[![Abbildung][25]][25]

Die Halbjahresnoten erscheinen in der J7-Spalte, da die Noten aus der Tabelle Schuelerfachdaten zeitraumweise übernommen bzw. spaltenmäßig fortgeschrieben werden. 

i) Benutzung des angepassten Synchronisierungsskriptes – Schüler Schwarz
Wenn mit dem neuen (angepassten) Skript synchronisiert wird, ergibt sich folgendes:

[![Abbildung][26]][26]

Würde der Schüler Schwarz in einer Klasse, welche die Lernfelder des 2. Halbjahres (Fachtafel:
BM 6.HJ) verwendet, zum ersten Mal wiederholen, müsste das Kennzeichen auf WDH1-2HJ gesetzt werden (im kaufm. Bereich eher ein theoretischer Fall):

[![Abbildung][27]][27]

[![Abbildung][28]][28]

Die J7-Noten wurden in die Spalte J6 (zweites Halbjahr) übertragen!!!
Hinweis
Die Endnoten sind hinsichtlich der neuen Halbjahresnoten zu überprüfen!!!

[![Abbildung][29]][29]

Der Schüler kann sich bei der Wiederholung notenmäßig verbessern, aber auch verschlechtern!!!

#### 3.3.3.2 Beispiel2 – dreijährige Ausbildung – zweite Wiederholung

Wiederholer – Schülerin Würth (Kaufmann/Kauffrau im Einzelhandel)

a) Schülerdaten Würth

[![Abbildung][30]][30]

Die Pflege beim Schüler wäre sinnvoll, um die Laufzeit des Ausbildungsvertrages beim Eintritt in die Berufsschule festzulegen. Mit diesem Kennzeichen wären dann (automatisierte) Plausibilitätskontrollen beim Verlängern des usbildungsvertrages (Register Ausbildung) möglich.

b) Klassen-Jahrgang 

[![Abbildung][31]][31]

c) Noten des Halbjahres der 1. Wiederholung – Schülerin Würth

[![Abbildung][32]][32]

d) Noten des Halbjahres der 2. Wiederholung – Schülerin Würth

[![Abbildung][33]][33]

e) Synchronisierung mit dem bisherigen Synchronisierungsskript

[![Abbildung][34]][34]

f) Synchronisierung mit dem neuen (angepassten) Synchronisierungsskript

[![Abbildung][35]][35]

**Hinweis** Die Endnoten sind zu überprüfen!!!

#### 3.3.3.3 Beispiel3 – Dreieinhalbjährige Ausbildung – erste Wiederholung

Wiederholer – Schüler Ludt (Mechatroniker)

a) Schülerdaten Ludt

[![Abbildung][36]][36]

b) Klassen-Jahrgang 

[![Abbildung][37]][37]

c) Noten des Halbjahres der 1. Wiederholung – Schüler Ludt

[![Abbildung][38]][38]

e) Synchronisierung mit dem neuen (angepassten) Synchronisierungsskript

[![Abbildung][39]][39]

[![Abbildung][40]][40]

#### 3.3.3.4 Beispiel4 – Dreieinhalbjährige Ausbildung – zweite Wiederholung

Wiederholer – Schüler Ludt (Mechatroniker)

a) Schülerdaten Ludt

[![Abbildung][41]][41]

b) Klassen-Jahrgang – Klasse Mec13B

[![Abbildung][42]][42]

c) Noten des Halbjahres der 2. Wiederholung – Schüler Ludt

[![Abbildung][43]][43]

Synchronisieren mit dem bisherigen Skript, wobei die Spalte J9 erhalten bleibt:

[![Abbildung][44]][44]

e) Synchronisierung mit dem neuen (angepassten) Synchronisierungsskript

[![Abbildung][45]][45]

[![Abbildung][46]][46]

**Hinweis** Die beim Schüler im Register  Schüler Laufbahn  Allgemein eingetragenen

[![Abbildung][47]][47]

Wiederholungskennzeichen sind zeitraumbezogen. Für die Auswertung gilt immer der
„jüngste“ Zeitraum.

#### 3.3.3.5 Dreieinhalbjährige Ausbildung – grafische Darstellung der Funktion der WDHKennzeichen

[![Abbildung][48]][48]

### 3.4 Faktorensumme bei Nicht-Wiederholern

Die Faktorensumme wird nun neu ermittelt und in der J9-Salte angezeigt:

[![Abbildung][49]][49]

### 3.5 Hinweise und Fehlermeldungen beim Skriptablauf

Wird ein Wiederholer nicht als Wiederholer markiert (Checkbox), besitzt dieser aber
Wiederholungskennzeichen, so wird eine entsprechende Fehlermeldung angezeigt:

[![Abbildung][50]][50]

Wird nicht als Wiederholer erkannt, keine Fehlermeldung!!!

[![Abbildung][51]][51]

Wiederholer-Kennzeichen wird zeitraumbezogen abgespeichert. Der Schüler ist demnach noch Wiederholer. Es muss auf das Wiederholungssymbol geachtet werden!!!

#### 3.6 Testhilfe – Ausgrenzung der Wiederholer im Skript

Das Skript ist so erzeugt worden, dass man die Wiederholer per Kommentar vom Skriptablauf ausgrenzen kann:

[![Abbildung][52]][52]

Auskommentieren per //
