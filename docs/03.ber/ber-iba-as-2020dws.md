# BER-IBA-AS-2020.dws

Grundlage: Verordnung über die Integrierte Berufsausbildungsvorbereitung IBA-VO vom 22.07.2019

*Letzte Änderung: 19.06.2020*

Mit Hilfe des Berechnungsskriptes _BER-IBA-AS-2020.dws_ können Sie für den Bildungsgang **Integrierte Berufsausbildungsvorbereitung**  die Endnoten (Jahresnotendurchschnitte) der Teilbereiche Fachtheorie und Fachpraxis (als Mittelwert der Halbjahresnotendurchschnitte gemäß Anlage 4 Abschnitt B der Verordnung über die integrierte Berufsausbildungsvorbereitung) sowie die Duchschnittsnote des Bildungsganges Integrierte Berufsausbildungsvorbereitung berechnen lassen.

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

![Geben Sie hier die Berechnungsverordnung mit der Kategorie „Versetzung“ ein.](\assets\images\IBA\IBA15.png)

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

Die Durchschnitte der Halbjahresnoten pro Fach erfassen Sie im Menü `Schüler > Zeugnis > Leistungen` im Feld "Durchschnitt". Dieses Feld ermöglicht Noten als Kommawert (Beispiel 1,4) zu erfassen. Fächer, für die es keine Bewertung gibt, also *ohne Bewertung* sind, weisen Sie im Menü `Schüler > Zeugnis > Leistungen` im Feld "Endnote" den Füllwert "o.B." zu.

![`Schüler > Zeugnis > Leistungen` Voreinstellungen](\assets\images\IBA\IBA18.png)

!!! info "Hinweis"

    Das Berechnungsskript kann auch Füllwerte verarbeiten. Dazu zählt Folgendes: o.B. + o.B. = o.B., o.B. + Note = Note.
    Ist der gebildete Durchschnitt bei Fachtheorie bzw. Fachpraxis des berufsfeldbezogenen Unterrichts im Ergebnis "o.B.", so wird im Durchschnitt eine "0" gespeichert.

**Füllwerte**:
Sollten Ihnen die gewünschten Füllwerte nicht zur Verfügung stehen, legen Sie diese bitte unter `Extras > Schlüsselverzeichnisse > Noten` an.

![Füllwerte anlegen](\assets\images\IBA\IBA20.png)

!!! warning "Wichtig"

    Aktivieren Sie für den Schüler unter `Schüler > Zeugnis > Leistungen` das Optionsfeld `Durchschnitt`. Auf der rechten Seite der Registerkarte erscheint nun eine zusätzliche Leiste.

1. Für die automatische Berechnung der Gesamtnote für den berufsfeldübergreifenden Unterricht und den Wahlunterricht werden die Noten der Fächer mit der Unterrichtsart "BÜ" und "WahlB" im Menü `Schüler > Zeugnis > Leistungen` im Feld "Durchschnitt" aus dem 1. Halbjahr und dem 2. Halbjahr des Schülers herangezogen.
2. Für die automatische Berechnung der Gesamtnote für den Fachtheorie- und Fachpraxisunterricht werden die Noten der Fächer mit der Unterrichtsart "FachT" und "FachP" im Menü `Schüler > Zeugnis > Leistungen` im Feld "Durchschnitt" aus dem 1. Halbjahr und dem 2. Halbjahr des Schülers herangezogen.

### Gesamtnotenberechnung durchführen

Im Feld "Prüfungsverordnung" wählen Sie über das Drop Down Menü die vorab im `Schlüsselverzeichnis > Verordnungen` definierte Prüfungsverordnung aus.(basierend auf dem Skript *BER-IBA-AS-2020.dws*)
 
Im Feld "Status" wählen Sie `Abschluss berechnen`. Die Berechnung gemäß Skript stoßen Sie über die Schaltfläche `Neu berechnen` an. 

Durch die Berechnung werden automatisch folgende Felder befüllt:

| Feld | Note für...     |
|--------|-----------
Endnote | Endoten der Fächer mit dem Fachstatus "FachT", "FachP" und "BÜ" sowie Fächer mit dem Fachstatus "Wahlb" für das entsprechende Halbjahr (Halbjahresnote)
Endnote (Gesamt) | Jahresendoten der Fächer mit dem Fachstatus "FachT", "FachP" und "BÜ" sowie Fächer mit dem Fachstatus "Wahlb" aus 1. Halbjahr und 2. Halbjahr
Durchschnitt 1 | Endnote (Jahresnotendurchschnitt) des Teilbereiches Fachtheorie|
Durchschnitt 2 | Endnote (Jahresnotendurchschnitt) des Teilbereiches Fachtpraxis|

Die nachfolgende Abbildung zeigt ein Berechnungsbeispiel für den IBA Bildungsgang für das 2. Halbjahr in Berlin. Sie sehen die Voreinstellungen und die Werte, die durch das Skript berechnet werden.

![Berechnung](\assets\images\IBA\IBA19.png)

!!! info "Hinweis"

    Die eingetragenen Noten in Feld "Durchschnitt" können jederzeit geändert werden. Durch erneutes Ausführen des Berechnungsskriptes wird die Berechnung neu durchgeführt.
    Die berechnete "Endnote (Gesamt)" kann manuell im Feld "Endnote (Gesamt)" geändert werden. Die Endnoten (gesamt) werden in das Abschlusszeugnis IBA, IBA mit MSA und IBA mit EBBR übergeben.

## Sonstiges für den Zeugnisdruck

### Fächer des berufsfeldbezogenen Unterrichts (Lernfelder) anlegen

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

### Betriebliche Lernaufgabe - Endnote

Um für die "Betriebliche Lernaufgabe - Endnote" die "Gesamtstunden" und eine "Note" auf dem Zeugnis ausgeben zu können, legen Sie bitte ein Fach für diese "Betriebliche Lernaufgabe" im `Schlüsselverzeichnis > Fächer` mit folgendem Kürzel an:

Kürzel | Schlüssel | Bezeichnung
--|--|--
BLE | leer | beliebig

Weisen Sie dieses Fach dem Schüler im Menü `Schüler > Zeugnis > Fächer` zu. Tragen Sie im Feld "Faktor" die "Gesamtstunden" ein. Die Endnote erfassen Sie für dieses Fach im Menü `Schüler > Zeugnis > Leistungen` im Feld "Endnote (Gesamt)".

![Fach für die Betriebliche Lernaufgabe anlegen, um Endnote ausgeben zu können](\assets\images\IBA\IBA17.png)

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

![Betriebspraktikum wurde bestanden/nicht bestanden](\assets\images\IBA\IBA05.png)

![Ausgabe auf dem Zeugnis > Betriebspraktikum wurde bestanden/nicht bestanden](\assets\images\IBA\IBA06.png)

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

![Vertragsnummer des Betriebspraktikums](\assets\images\IBA\IBA04.png)

### Prüfungsfächer - Präsentationsprüfung für MSA / EBBR

Für die Ausgabe des Faches der Präsentationsprüfung weisen Sie diesem Fach im Menü `Schüler > Zeugnis > Fächer` im Feld "Fachstatus" den Eintrag "4PF" zu. Grundlage bildet das `Schlüsselverzeichnis > Fachstatus`.

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
4PF | 4PF |  4. Prüfungsfach

Die Noten der Präsentationsprüfung erfassen Sie im Menü `Schüler > Zeugnis > Leistungen` in folgenden Feldern:

Spalte | Note für..
--|--
Zusatz Note 1 | Gesamtnote
Schriftl. Note 1 | Präsentationsprüfung
Mündl. Note | ggf. zusätzliche mündliche Prüfung

Das Thema der Präsentationsprüfung erfassen Sie im Menü `Schüler > Zeugnis > Leistungen`im Feld "Beurteilungstexte".

### Zeugnisbemerkungen für MSA / EBBR Zeugnis

Damit Zeugnisbemerkungen, die nur für das Abschlusszeugnis IBA über MSA bzw. Abschlusszeugnis IBA über EBBR nicht auf dem IBA Abschlusszeugnis (Schul Z 591) ausgegeben werden, beachten Sie bitte folgendes.

Bei den Zeugnisbemerkungen müssen verschiedene Typen der Bemerkung unterschieden werden. Die Unterscheidung erfolgt durch den Eintrag in der Spalte "Merkmal" im Menü `Schüler > Zeugnis > Bemerkungen/Formulare`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung auswählen und zuweisen. 

Erfolgt keine Eingabe in der Spalte "Merkmal", so wird diese Bemerkung nur auf dem IBA Abschlusszeugnis (Schul Z 591) ausgegeben. 
Für das Abschlusszeugnis IBA über den mittleren Schulabschluss (Schul Z 593) verwenden Sie bitte im Feld "Merkmal" den Eintrag "MSA", für das Abschlusszeugnis IBA  über die erweiterte Berufsbildungsreife (Schul Z 592) verwenden Sie im Feld "Merkmal" den Eintrag "EBBR".
