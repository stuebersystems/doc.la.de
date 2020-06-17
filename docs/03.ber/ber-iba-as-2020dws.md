# BER-IBA-AS-2020.dws

Mit Hilfe des Berechnungsskriptes _BER-IBA-AS-2020.dws_ können Sie für den Bildungsgang **Integrierte Berufsausbildungsvorbereitung**  die Endnoten (Jahresnotendurchschnitte) der Teilbereiche Fachtheorie und Fachpraxis (als Mittelwert der Halbjahresnotendurchschnitte gmäß Anlage 4 Abschnitt B der Verordnung über die integrierte Berufsausbildungsvorbereitung) sowie die Duchschnittsnote des Bildungsganges Integrierte Berufsausbildungsvorbereitung berechnen lassen.

Grundlage: Verordnung über die Integrierte Berufsausbildungsvorbereitung IBA-VO vom 22.07.2019

Im folgenden Kapitel beschreiben wir Ihnen die Vorgehensweise.

## Vorbereitungen

Zur Berechnung der Endnoten der Teilbereiche Fachtheorie und Fachpraxis sowie der Duchschnittsnote des Bildungsganges IBA innerhalb eines Schuljahres (1. Halbjahr / 2. Halbjahr) gehören folgende Aufgaben:

1. Berechnungsverordnung definieren
2. Fächer der Schüler für den gewünschten Zeitraum einer Zeugnisausgabe  eingeben.
3. Noten pro Fach der Schüler für den gewünschten Zeitraum zur Berechnung eingeben
4. Berechnung ausführen

### 1. Berechnungsverordnung definieren

Bitte legen Sie unter `Schlüsselverzeichnisse > Verordnungen` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten.

| Spalte | Wert|
|---|---|
| Kürzel| beliebig                                 |
| Bezeichnung  | beliebig                                 |
| Kategorie    | Versetzung                               |
| Typ          | leer                                     |
| Ab Jahrgang  | leer                                     |
| Skript       | `...\Ihre Region\Ihr_Skript.dws` (Pfad zur Skriptdatei auf Ihrem Server) hier _BER-IBA-AS-2020.dws_ |
| Notenart 11  | leer                                     |
| Notenart 12  | leer                                     |
| Notenart 13  | leer                                     |
| Notenart BBS | leer                                     |
| Gültig von   | leer                                     |
| Gültig bis   | leer                                     |

!!! warning "Wichtig"

    Das Skript BER-IBA-AS-2020.dws wird im Menü `Schüler > Zeugnis > Leistungen` ausgeführt und muss im `Schlüsselverzeichnis > Verordnung` mit der Kategorie „Versetzung“ angelegt werden.

![Geben Sie hier die Berechnungsverordnung mit der Kategorie „Versetzung“ ein.](..\assets\images\IBA\IBA15.png)

### 2. Fächer der Schüler eingeben

!!! warning "Wichtig"

    Für die Fächer sind folgenden Unterscheidungen zwingende Voraussetzung.

#### Berufsfeldübergreifender/berufsfeldbezogener Unterricht

Fächern des berufsfeldübergreifenden bzw. berufsfeldbezogenen Unterricht weisen Sie im Menü `Schüler > Zeugnis > Fächer` folgende Unterrichtsarten zu. Grundlage dafür bildet das `Schlüsselverzeichnis > Unterrichtsarten`. 

|Kürzel |Schlüssel|Bezeichnung|
|--|--|--|
|BÜ|BÜ |Berufs/Fachübergreifender Lernbereich|
|FachT| FachT |Berufsbezogener Lernbereich / Fachtheorie|
|FachP| FachP |Berufsbezogener Lernbereich / Fachpraxis|

#### Wahlunterricht

Fächer des Wahlunterrichtes weisen Sie im Menü `Schüler > Zeugnis > Fächer` im Feld "Fachstatus" den Eintrag "WahlB" zu. Prüfen Sie bitte unter `Schlüsselverzeichnisse > Fachstatus`, dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung       |
|--------|-----------|-----------------|
| WahlB  | WahlB     | Wahlbereich     |

#### Betriebliche Lernaufgaben

Neben dem Wahlunterricht und den berufsfeldübergreifenden bzw. berufsfeldbezogenern Unterricht muss auch die Betriebliche Lernaufgabe benotet werden. Gehen Sie dafür wie folgt vor:

Legen Sie im `Schlüsselverzeichnisse > Fächer` drei Fächer für die Betrieblichen Lernaufgaben an, entscheidend ist der Eintrag im Feld "Schlüssel", dieser muss wie folgt hinterlegt sein:

| Kürzel | Schlüssel | Bezeichnung       |
|--------|-----------|-----------------|
| LA1 (beliebig)| LA1 | Betriebliche Lernaufgabe 1 (beliebig) |
| LA2 (beliebig)| LA2 | Betriebliche Lernaufgabe 2 (beliebig)|
| LA3 (beliebig)| LA3 | Betriebliche Lernaufgabe 3 (beliebig)|

Weisen Sie diese Fächer ebenfalls im Menü `Schüler > Zeugnis > Fächer` dem Schüler zu.  

#### 3. Noten der Fächer eingeben

Die Durchschnitte der Halbjahresnoten pro Fach erfassen Sie im Menü `Schüler > Zeugnis > Leistungen` im Feld "Durchschnitt". Dieses Feld ermöglicht Noten als Kommawert (Beispiel 1,4) zu erfassen.

![Schüler > Zeugnis > Leistungen](..\assets\images\IBA\IBA16.png)

!!! warning "Wichtig"

    Aktivieren Sie für den Schüler unter `Schüler > Zeugnis > Leistungen` das Optionsfeld `Durchschnitt`. Auf der rechten Seite der Registerkarte erscheint nun eine zusätzliche Leiste.

1. Für die Berechnung der Jahresendnoten, die auf das Zeugnis übergeben werden, werden die Noten der Fächer aus dem Feld "Durchschnitt" aus dem 1. Halbjahr und dem 2. Halbjahr des Schülers herangezogen.
2. Für die automatische Berechnung der Gesamtnote für den Fachtheorie- und Fachpraxisunterricht werden die Noten der Fächer mit der Unterrichtsart "FachT" und "FachP" im Menü `Schüler > Zeugnis > Leistungen` im Feld "Durchschnitt" aus dem 1. Halbjahr und dem 2. Halbjahr des Schülers herangezogen.

### Gesamtnotenberechnung durchführen

Im Feld "Prüfungsverordnung" wählen Sie über das Drop Down Menü die vorab im `Schlüsselverzeichnis > Verordnungen` definierte Prüfungsverordnung aus.(basierend auf dem Skript *BER-IBA-AS-2020.dws*) 
 
Im Feld "Status" wählen Sie `Abschluss berechnen`. Die Berechnung gemäß Skript stoßen Sie über die Schaltfläche `Neu berechnen` an. 

Durch die Berechnung werden automatisch folgende Felder befüllt:

| Feld | Note für...     |
|--------|-----------
Endnote | Endoten der Fächer mit dem Fachstatus "FachT", "FachP" und "BÜ" sowie Fächer mit dem Fachstatus "Wahlb"
Endnote (Gesamt) | Jahresendoten der Fächer mit dem Fachstatus "FachT", "FachP" und "BÜ" sowie Fächer mit dem Fachstatus "Wahlb"
Durchschnitt 1 | Endnote (Jahresnotendurchschnitt) des Teilbereiches Fachtheorie|
Durchschnitt 2 | Endnote (Jahresnotendurchschnitt) des Teilbereiches Fachtpraxis|

Die nachfolgende Abbildung zeigt ein Berechnungsbeispiel für den IBA Bildungsgang für das 2. Halbjahr in Berlin. Sie sehen die Voreinstellungen und die Werte, die durch das Skript berechnet werden.

![Berechnung](..\assets\images\IBA\IBA09.png)

!!! info "Hinweis"

   Die berechnete "Endnote" kann jederzeit manuell im Feld "Endnote" geändert werden. Durch erneutes Ausführen des Berechnungsskriptes wird diese Note nicht mehr überschrieben, das Skript gibt Ihnen im Meldefenster den Hinweis "Endnote für "Fach XY" manuell eingegeben (berechneter Wert wäre 2)".

![Meldefenster nach Notenänderung im Feld "Endnote" und erneuter Berechnung durch das Skript](..\assets\images\IBA\IBA10.png)

## Sonstiges für den Zeugnisdruck

### Fächer des berufsfeldebezogenen Unterrichts (Lernfelder) anlegen

`Extras > Schlüsselverzeichnisse > Fächer > Merkmal`

Ihre Lernfelder erfassen Sie im  `Schlüsselverzeichnisse > Fächer`. Im Feld "Bezeichnung" tragen Sie die Lernfeldbezeichnung ein. Die Lernfeldnummer geben Sie bitte im Feld "Zeugnismerkmal" (Merkmal) ein.

Kürzel | Schlüssel | Bezeichnung | Merkmal
--|--|--|--
beliebig | beliebig | Sich im Berufsfeld orientieren | LF1

Der Bericht liest den Eintrag aus Feld "Merkmal" aus und setzt dahinter die Fachbezeichnung aus Feld "Bezeichnung".

### Qualifizierungsbausteine anlegen

Ein Lernfeld kann durch einen Qualifizierungsbaustein gemäß § 11 der Verordnung über die Integrierte Berufsausbildungsvorbereitung ersetzt werden. Die Titelbezeichnung beginnt in diesem Fall mit „QB:“

Sollte dies beim Schüler zutreffen, legen Sie im `Schlüsselverzeichnis > Fächer` den entsprechenden Qualifizierungsbaustein als Fach an. Beachten Sie, dass dieses Fach im Feld "Merkmal" den Eintrag "QB:" erhält. 

Weisen Sie dieses Fach im Menü `Schüler > Zeugnis > Fächer` anstelle des zugewiesenen Lernfeldes zu. Beachten Sie, dass Sie diesem  Qualifizierungsbaustein im Feld "Unterrichtart" entweder "FachT" oder "FachP" zuweisen.

Anstelle des Lernfeldes wird nun der Qualifizierungsbaustein auf dem Zeugnis ausgegeben.

`Extras > Schlüsselverzeichnisse > Fächer > Merkmal`

Ihre Lernfelder erfassen Sie im  `Schlüsselverzeichnisse > Fächer`. Im Feld "Bezeichnung" tragen Sie die Lernfeldbezeichnung ein. Die Lernfeldnummer geben Sie bitte im Feld "Zeugnismerkmal" (Merkmal) ein.

Kürzel | Schlüssel | Bezeichnung | Merkmal
--|--|--|--
beliebig | beliebig | Sich im Berufsfeld orientieren | LF1

Der Bericht liest den Eintrag aus Feld "Merkmal" aus und setzt dahinter die Fachbezeichnung aus Feld "Bezeichnung".

## Betriebliche Lernaufgabe - Endnote

Um für die "Betriebliche Lernaufgabe - Endnote" die "Gesamtstunden" und eine "Note" auf dem Zeugnis ausgeben zu können, legen Sie bitte ein Fach für diese "Betriebliche Lernaufgabe" im `Schlüsselverzeichnis > Fächer` mit folgendem Kürzel an:

Kürzel | Schlüssel | Bezeichnung
--|--|--
BLE | leer | beliebig

Weisen Sie dieses Fach dem Schüler im Menü `Schüler > Zeugnis > Fächer` zu. Tragen Sie im Feld "Faktor" die "Gesamtstunden" ein. Die Endnote erfassen Sie für dieses Fach im Menü `Schüler > Zeugnis > Leistungen` im Feld "Endnote (Gesamt)".

![Fach für die Betriebliche Lernaufgabe anlegen, um Endnote ausgeben zu können](..\assets\images\IBA\IBA17.png)

### Betriebspraktikum 1./2. oder 3. bestanden/nicht bestanden

Ob im Zeugnis das Betriebspraktikum 1./2. oder 3. als "bestanden" oder "nicht bestanden" ausgegeben wird, hängt vom Eintrag im Menü `Schüler > Zeugnis > Fächer`  im Feld "Merkmal" ab.

1. Legen Sie im `Schlüsselverzeichnisse > Fächer` drei Fächer für die Betrieblichen Lernaufgaben an, entscheidend ist der Eintrag im Feld "Schlüssel", dieser muss wie folgt hinterlegt sein:

 Kürzel | Schlüssel | Bezeichnung 
--------|-----------|-----------------
LA1 (beliebig)| LA1 | Betriebliche Lernaufgabe 1 (beliebig)
LA2 (beliebig)| LA2 | Betriebliche Lernaufgabe 2 (beliebig)
LA3 (beliebig)| LA3 | Betriebliche Lernaufgabe 3 (beliebig)

2. Weisen Sie diese Fächer im Menü `Schüler > Zeugnis > Fächer` dem Schüler zu.

3. Die Betriebliche Lernaufgabe 1,/2./3.  bezieht sich auf das jeweilige Praktikum 1./2./3. Ein Eintrag "N" im Feld "Merkmal" bei der entsprechenden Lernaufgabe steuert die Ausgabe "nicht bestanden". Bleibt das Feld "Merkmal" leer, wird das Praktikum als "bestanden" ausgegeben.

![Betriebspraktikum wurde bestanden/nicht bestanden](..\assets\images\IBA\IBA05.png)

![Ausgabe auf dem Zeugnis > Betriebspraktikum wurde bestanden/nicht bestanden](..\assets\images\IBA\IBA06.png)

3. Die Noten der Betriebliche Lernaufgabe 1,/2./3. tragen Sie im im Menü `Schüler > Zeugnis > Leistungen` im Feld "Endnote" ein. 

### Betriebspraktikum 1./2. oder 3. - erfolgt im 1. oder 2.HJ?

Tragen Sie den Betrieb des Praktikums im Menü `Schüler > Ausbildung` im Bereich „Praxibetrieb“ ein. Wenn Sie die Schaltfläche `+`oder `Editieren` anklicken, können Sie einen Praxisbetrieb zuweisen bzw. bearbeiten. Im Feld "Praxisbetrieb" hinterlegen Sie den Betrieb. 
Erfassen Sie weiterhin in den Feldern `Praxis von` und `bis` den Zeitraum des Praktikums und die `Vertragsnummer` wie folgt:

Eintrag für | Eingabe wie folgt
--|--
1. Praktikum | LA1HJ1 
2. Praktikum | LA2HJ1 oder LA2HJ2
3. Praktikum | LA3

Anhand der Vertragsnummer kann der Bericht die "Betriebliche Lernaufgabe", die auch benotet wird, dem 1./2./3 Betriebspraktikum zuordnen. Zudem wird ein Bezug des Betriebspraktikums zum 1. Halbjahr bzw. 2. Halbjahr hergestellt.

![Vertragsnummer des Betriebspraktikums](..\assets\images\IBA\IBA04.png)
