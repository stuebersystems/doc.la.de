# BER-IBA-HJ-2020.dws

Grundlage: Verordnung über die Integrierte Berufsausbildungsvorbereitung IBA-VO vom 22.07.2019

*Letzte Änderung: 12.06.2020*

Mit Hilfe des Berechnungsskriptes _BER-IBA-HJ-2020.dws_ können Sie für den Bildungsgang **Integrierte Berufsausbildungsvorbereitung** die Gesamtnote der Fachtheorie und Fachpraxis für das aktuelle Halbjahr für den Berufsfeldbezogenen Unterricht berechnen lassen.

Die Gesamtnote der Fachtheorie und Fachpraxis errechnet sich aus den gewichteten Halbjahresnotendurchschnitten der jeweiligen Lernfeldnoten gemäß der Verordnung über die Integrierte Berufsausbildungsvorbereitung Anlage 4 Abschnitt B.

Im folgenden Kapitel beschreiben wir Ihnen die Vorgehensweise.

## Vorbereitungen

Zur Berechnung der Gesamtnote innerhalb eines Zeitraums gehören folgende Aufgaben:

1. Berechnungsverordnung definieren
2. Fächer der Schüler für den gewünschten Zeitraum einer Zeugnisausgabe eingeben.
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
| Skript       | `...\Ihre Region\Ihr_Skript.dws` (Pfad zur Skriptdatei auf Ihrem Server) hier _BER-IBA-HJ-2020.dws_ |
| Notenart 11  | leer                                     |
| Notenart 12  | leer                                     |
| Notenart 13  | leer                                     |
| Notenart BBS | leer                                     |
| Gültig von   | leer                                     |
| Gültig bis   | leer                                     |

!!! warning "Wichtig"

    Das Skript BER-IBA-HJ-2020.dws wird im Menü `Schüler > Zeugnis > Leistungen` ausgeführt und muss im `Schlüsselverzeichnis > Verordnung` mit der Kategorie „Versetzung“ angelegt werden.

![Geben Sie hier die Berechnungsverordnung mit der Kategorie „Versetzung“ ein.](/assets/images/IBA/IBA01.png)

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

Neben dem Wahlunterricht und den berufsfeldübergreifenden bzw. berufsfeldbezogenen Unterricht muss auch die Betriebliche Lernaufgabe benotet werden. Gehen Sie dafür wie folgt vor:

Legen Sie im `Schlüsselverzeichnisse > Fächer` drei Fächer für die Betrieblichen Lernaufgaben an, entscheidend ist der Eintrag im Feld "Schlüssel", dieser muss wie folgt hinterlegt sein:

| Kürzel | Schlüssel | Bezeichnung       |
|--------|-----------|-----------------|
| LA1 (beliebig)| LA1 | Betriebliche Lernaufgabe 1 (beliebig) |
| LA2 (beliebig)| LA2 | Betriebliche Lernaufgabe 2 (beliebig)|
| LA3 (beliebig)| LA3 | Betriebliche Lernaufgabe 3 (beliebig)|

Weisen Sie diese Fächer ebenfalls im Menü `Schüler > Zeugnis > Fächer` dem Schüler zu.  

#### 3. Noten der Fächer eingeben

Die Durchschnitte der Halbjahresnoten pro Fach erfassen Sie im Menü `Schüler > Zeugnis > Leistungen` im Feld "Durchschnitt". Dieses Feld ermöglicht Noten als Kommawert (Beispiel 1,4) zu erfassen. Fächer, für die es keine Bewertung gibt, also *ohne Bewertung* sind, weisen Sie im Menü `Schüler > Zeugnis > Leistungen` im Feld "Endnote" den Füllwert "o.B." zu.

![Schüler > Zeugnis > Leistungen](/assets/images/IBA/IBA07.png)

!!! info "Hinweis"

    Das Berechnungsskript kann auch Füllwerte verarbeiten. Dazu zählt Folgendes: o.B. = o.B.
    Ist der gebildete Durchschnitt bei Fachtheorie bzw. Fachpraxis des berufsfeldbezogenen Unterrichts im Ergebnis "o.B.", so wird im Durchschnitt eine "0" gespeichert.

**Füllwerte**:
Sollten Ihnen die gewünschten Füllwerte nicht zur Verfügung stehen, legen Sie diese bitte unter `Extras > Schlüsselverzeichnisse > Noten` an.

![Füllwerte anlegen](/assets/images/IBA/IBA20.png)

!!! warning "Wichtig"

    Aktivieren Sie für den Schüler unter `Schüler > Zeugnis > Leistungen` das Optionsfeld `Durchschnitt`. Auf der rechten Seite der Registerkarte erscheint nun eine zusätzliche Leiste.

1. Für die Berechnung der Halbjahresendnoten, die auf das Zeugnis übergeben werden, werden die Noten der Fächer aus dem Feld "Durchschnitt" herangezogen.
2. Für die automatische Berechnung der Gesamtnote für den Fachtheorie- und Fachpraxisunterricht werden die Noten der Fächer mit der Unterrichtsart "FachT" und "FachP" im Menü `Schüler > Zeugnis > Leistungen` im Feld "Durchschnitt" herangezogen.

![Schüler > Zeugnis > Leistungen](/assets/images/IBA/IBA08.png)

### Gesamtnotenberechnung durchführen

Im Feld "Prüfungsverordnung" wählen Sie über das Drop Down Menü die vorab im `Schlüsselverzeichnis > Verordnungen` definierte Prüfungsverordnung aus. (basierend auf dem Skript *BER-IBA-HJ-2020.dws*) 
 
Im Feld "Status" wählen Sie `Abschluss berechnen`. Die Berechnung gemäß Skript stoßen Sie über die Schaltfläche `Neu berechnen` an. 

Durch die Berechnung wird automatisch folgende Felder befüllt:

| Feld | Note für...     |
|--------|-----------
Endnote | Endoten der Fächer mit dem Fachstatus "FachT", "FachP" und "BÜ" sowie Fächer mit dem Fachstatus "Wahlb"
Durchschnitt 1 | Fachtheorie - gesamt|
Durchschnitt 2 | Fachpraxis - gesamt|

Die nachfolgende Abbildung zeigt ein Berechnungsbeispiel für den IBA Bildungsgang für das 1. Halbjahr in Berlin. Sie sehen die Voreinstellungen und die Werte, die durch das Skript berechnet werden.

![Berechnung](/assets/images/IBA/IBA09.png)

!!! info "Hinweis"

   Die berechnete "Endnote" kann jederzeit manuell im Feld "Endnote" geändert werden. Durch erneutes Ausführen des Berechnungsskriptes wird diese Note nicht mehr überschrieben, das Skript gibt Ihnen im Meldefenster den Hinweis "Endnote für "Fach XY" manuell eingegeben (berechneter Wert wäre 2)".

![Meldefenster nach Notenänderung im Feld "Endnote" und erneuter Berechnung durch das Skript](/assets/images/IBA/IBA10.png)

## Sonstiges für den Zeugnisdruck

### Fächer des berufsfeldbezogenen Unterrichts (Lernfelder) anlegen

Ihre Lernfelder erfassen Sie im `Schlüsselverzeichnisse > Fächer`. Im Feld "Bezeichnung" tragen Sie die Lernfeldbezeichnung ein. Die Lernfeldnummer geben Sie bitte im Feld "Zeugnismerkmal" (Merkmal) ein.

Kürzel | Schlüssel | Bezeichnung | Merkmal
--|--|--|--
beliebig | beliebig | Sich im Berufsfeld orientieren | LF1

Der Bericht liest den Eintrag aus Feld "Merkmal" aus und setzt dahinter die Fachbezeichnung aus Feld "Bezeichnung".

### Qualifizierungsbausteine anlegen

Ein Lernfeld kann durch einen Qualifizierungsbaustein gemäß § 11 der Verordnung über die Integrierte Berufsausbildungsvorbereitung ersetzt werden. Die Titelbezeichnung beginnt in diesem Fall mit „QB:“

Sollte dies beim Schüler zutreffen, legen Sie im `Schlüsselverzeichnis > Fächer` den entsprechenden Qualifizierungsbaustein als Fach an. Beachten Sie, dass dieses Fach im Feld "Merkmal" den Eintrag "QB:" erhält. 

Weisen Sie dieses Fach im Menü `Schüler > Zeugnis > Fächer` anstelle des zugewiesenen Lernfeldes zu. Beachten Sie, dass Sie diesem Qualifizierungsbaustein im Feld "Unterrichtart" entweder "FachT" oder "FachP" zuweisen.

Anstelle des Lernfeldes wird nun der Qualifizierungsbaustein auf dem Zeugnis ausgegeben.

### Betriebspraktikum 1./2. oder 3. bestanden/nicht bestanden

Ob im Zeugnis das Betriebspraktikum 1./2. oder 3. als "bestanden" oder "nicht bestanden" ausgegeben wird, hängt vom Eintrag im Menü `Schüler > Zeugnis > Fächer` im Feld "Merkmal" ab.

1. Legen Sie im `Schlüsselverzeichnisse > Fächer` drei Fächer für die Betrieblichen Lernaufgaben an, entscheidend ist der Eintrag im Feld "Schlüssel", dieser muss wie folgt hinterlegt sein:

 Kürzel | Schlüssel | Bezeichnung 
--------|-----------|-----------------
LA1 (beliebig)| LA1 | Betriebliche Lernaufgabe 1 (beliebig)
LA2 (beliebig)| LA2 | Betriebliche Lernaufgabe 2 (beliebig)
LA3 (beliebig)| LA3 | Betriebliche Lernaufgabe 3 (beliebig)

2. Weisen Sie diese Fächer im Menü `Schüler > Zeugnis > Fächer` dem Schüler zu.

3. Die Betriebliche Lernaufgabe 1./2./3. bezieht sich auf das jeweilige Praktikum 1./2./3. Ein Eintrag "N" im Feld "Merkmal" bei der entsprechenden Lernaufgabe steuert die Ausgabe "nicht bestanden". Bleibt das Feld "Merkmal" leer, wird das Praktikum als "bestanden" ausgegeben.

![Betriebspraktikum wurde bestanden/nicht bestanden](/assets/images/IBA/IBA05.png)

![Ausgabe auf dem Zeugnis > Betriebspraktikum wurde bestanden/nicht bestanden](/assets/images/IBA/IBA06.png)

4. Die Noten der Betriebliche Lernaufgabe 1,/2./3. tragen Sie im Menü `Schüler > Zeugnis > Leistungen` im Feld "Endnote" ein. 

### Betriebspraktikum 1., 2. oder 3. - erfolgt im 1. oder 2.HJ?

Tragen Sie den Betrieb des Praktikums im Menü `Schüler > Ausbildung` im Bereich „Praxisbetrieb“ ein. Wenn Sie die Schaltfläche `+`oder `Editieren` anklicken, können Sie einen Praxisbetrieb zuweisen bzw. bearbeiten. Im Feld "Praxisbetrieb" hinterlegen Sie den Betrieb. 
Erfassen Sie weiterhin in den Feldern `Praxis von` und `bis` den Zeitraum des Praktikums und die `Vertragsnummer` wie folgt:

Eintrag für | Eingabe wie folgt
--|--
1. Praktikum | LA1HJ1 
2. Praktikum | LA2HJ1 oder LA2HJ2
3. Praktikum | LA3

Anhand der Vertragsnummer kann der Bericht die "Betriebliche Lernaufgabe", die auch benotet wird, dem 1./2./3 Betriebspraktikum zuordnen. Zudem wird ein Bezug des Betriebspraktikums zum 1. Halbjahr bzw. 2. Halbjahr hergestellt.

![Vertragsnummer des Betriebspraktikums](/assets/images/IBA/IBA04.png)
