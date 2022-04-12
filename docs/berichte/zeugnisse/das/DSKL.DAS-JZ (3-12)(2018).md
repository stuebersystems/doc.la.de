# DSKL.DAS-JZ (3-12)(2018)

## Schuljahr

Die Ausgabe des Schuljahres erfolgt aufgrund der Definition des aktuellen Zeitraums in Magellan unter `Verzeichnisse > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte `Ausdruck1`.

## Versetzungsvermerk

Im entsprechenden Zeitraum muss der Versetzungsvermerk im Menü `Schüler` auf der Registerkarte `Laufbahn` unter `Allgemein` im Feld `Versetzt` eingetragen sein. Entscheidend ist hierbei die Markierung des Zeitraumes im linken Zeitraumfenster.

## Fehlzeiten

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler` auf der Registerkarte `Zeugnis` unter `Details` in den Feldern `Fehltage`, `davon unentschuldigt`, `Fehlstunden` und `davon unentschuldigt` erfolgen.

## Fachstatus

Für die Ausgabe der Fächer (außer den Arbeits- und Sozialverhalten) kann im Feld `Fachstatus` jedes beliebige Kürzel gewählt werden. Eine Eingabe ist allerdings nicht zwingend notwendig (außer bei den Arbeits- und Sozialverhalten).
Für den Zeugnisdruck ist der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis der Fachtafeln unter `Verzeichnisse > Fachtafeln` den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das Schlüsselverzeichnis `Verzeichnisse > Weitere Schlüsselverzeichnisse > Fachstati`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.

Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
ASV | ASV | Arbeits- und Sozialverhalten
AG | AG | Arbeitsgemeinschaft

## Fachpositionen

Für die Sortierung der Fächer auf den Zeugnissen muss im Menü `Schüler` bei jedem Schüler auf der Registerkarte `Zeugnis` unter `Fächer` pro Fach eine Position in der Spalte `Position` angegeben werden. Bei der Ausgabe der Fächer auf dem Zeugnis werden die geraden Positionen in der rechten Spalte und die ungeraden Positionen in der linken Spalte ausgegeben. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis der Fachtafeln unter `Verzeichnisse > Fachtafeln` die Zeugnisposition zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Position nicht pro Schüler und pro Fach vornehmen.

## Schulleiter, Klassenlehrer

`Mandanten > Daten1 > Schulleiter` <br/>`Klassen > Zeiträume > Klassenleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter Mandanten im Register `Daten1` im Feld `Schulleiter` eingetragen werden!

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü `Klassen` bei der jeweiligen Klasse in der Registerkarte
`Zeiträume` im Feld `Klassenleiter` eingetragen werden!

## Zeugnisdatum

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler` auf Registerkarte `Zeugnis` unter `Details` im Feld `Zeugnisdatum` eingetragen sein.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Schüler` gedruckt werden.

## Zeugnisbemerkungen

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler` auf der Registerkarte `Zeugnis` unter `Zeugnis`.
Wenn Sie die Schaltfläche `Hinzufügen` anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für
den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung
auswählen und zuweisen.

### Zeugnismerkmal

Bei den Zeugnisbemerkungen müssen verschiedene Typen der Bemerkung unterschieden werden. Die Unterscheidung erfolgt durch den Eintrag in der Spalte `Merkmal` unter `Verzeichnisse > Zeugnisbemerkungen`, falls es sich um allgemeingültige Zeugnisbemerkungen handelt, oder beim Schüler, falls Sie diesem eine individuelle Zeugnisbemerkung zuweisen möchten. Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler` auf der Registerkarte `Zeugnis`
unter `Zeugnis`. Wenn Sie die Schaltfläche `Hinzufügen` anklicken, können Sie eine Zeugnisbemerkung auswählen und zuweisen. Erfolgt keine Eingabe in der Spalte `Merkmal`, so wird die Bemerkung unter `allgemeinen Bemerkungen` auf dem Zeugnisdruck ausgegeben.

Folgende Kürzel im Feld `Merkmal` dürfen für den Zeugnisdruck verwendet werden:

Merkmal | Bedeutung
--|--
ASV | Arbeits- und Sozialverhalten

### Zeugnisbemerkungsposition

Für die Ausgabe der Zeugnisbemerkungen muss über das Feld `Position` eine Reihenfolge (Nummerierung) vorgegeben
werden.Z.B. für die Ausgabe der ersten Bemerkung `1`, für die Ausgabe der zweiten Bemerkung `2` usw.

### Platzhalter für Bemerkungen

Bemerkungen Legen Sie im Menü `Schüler` unter `Zeugnis > Zeugnis` oder im Menü `Abitur` unter `Zeugnis` in
`Zeugnisbemerkungen` an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren.
Einen Platzhalter definieren Sie über ```<<` zum Beginn und `>>``` zum Ende Ihres Platzhalters, z.B. So ``<<hier steht Ihr
Platzhalter>>``.
Möglich sind:

Platzhalter|Inhalt
--|--
``<<Name>>`` | Vorname, Vorname2, Namenszusatz und Nachname des Schülers
``<<Nachname>>`` | Nachname des Schülers
``<<Vorname>>`` | Vorname, Vorname2 und Namenszusatz d es Schülers
``<<Anrede1>>`` | Er/Sie (je nach Geschlecht des Schülers)
``<<Anrede2>>`` | er/sie (je nach Geschlecht des Schülers)
``<<Anrede3>>`` | seine/ihre (je nach Geschlecht des Schülers)
``<<Anrede4>>`` | ihm/ihr (je nach Geschlecht des Schülers)
``<<Anrede5>>`` | seinen/ihren (je nach Geschlecht des Schülers)

## Klassenjahrgang, Schulart

Das Zeugnis ist von der 5. bis zur 12. Klasse konzipiert. Die richtige Ausgabe errechnet sich aus dem Jahrgang.
Im entsprechenden Zeitraum muss im Menü `Klassen` bei der Klasse des Schülers auf der Registerkarte `Zeiträume` unter `Zeitraum` der Jahrgang im Feld `Jahrgang` angegeben sein.

Bis einschließlich der 10. Klasse erfolgt die Ausgabe nach Klassenjahrgang, ab der 11. gemäß Qualifikationsphase.
Bis zur 10. Klasse müssen Sie auch die `Schulart` eintragen. Sie können dem Schüler seine `Schulart` individuell oder
klassenweise zuweisen. Vorrang bei der Ausgabe hat die `Schulart` nach Schüler, falls Sie die `Schulart` klassenweise
ausgeben möchten lassen Sie das Feld `Schulart` im Menu `Schüler > Laufbahn > Allgemein` beim Schüler leer.

1. Schulart schülerweise: Tragen Sie im Menü `Schüler` im aktuellen Zeitraum auf der Registerkarte `Laufbahn > Allgemein` die Schulart im Feld `Schulart` ein. Grundlage hierfür bildet das Schlüsselverzeichnis `Verzeichnisse > Weitere Schlüsselverzeichnisse > Schularten`.
2. Schulart klassenweise: Tragen Sie im Menü `Klasse` im aktuellen Zeitraum auf der Registerkarte `Daten` die Schulart im Feld `Schulart` ein. Grundlage hierfür bildet das Schlüsselverzeichnis `Verzeichnisse > Weitere Schlüsselverzeichnisse > Schularten`.

Schulart der Klasse

Tragen Sie im Menü `Klasse` im aktuellen Zeitraum auf der Registerkarte `Daten` die Schulart im Feld `Schulart` ein. Grundlage hierfür bildet das Schlüsselverzeichnis `Verzeichnisse > Weitere Schlüsselverzeichnisse > Schularten`. Der Bericht fragt die `Bezeichnung` der Schulart ab, Vorgaben sind:
Kürzel (beliebig) Bezeichnung (wie folgt einzutragen)

Kürzel|Bezeichnung
--|--
GS |Grundschule
RS |Realschule
GY |Gymnasium
HS |Hauptschule

## Noten

Beim Anlegung Ihrer Noten im Schlüsselverzeichnis `Noten` weisen Sie Ihrer Note die entsprechende Notenart `Punktwert` oder `Notenwert` zu, da die Unterscheidung für Berechnungen benötigt wird.

## Vermerk bei Fremdsprachenhinweis

### Schulart Gymnasium

Fach Englisch - Ausweisung auf Zeugnis: Englisch (1. Fremdsprache)<br/>
Fach Französisch – Ausweisung auf Zeugnis: Französisch (2. Fremdsprache) oder<br/>
Fach Latein – Ausweisung auf Zeugnis: Latein (2. Fremdsprache)<br/>

### Vermerk Wahlpflichfach

Schulart Realschule und Hauptschule<br/>
Fach NaWi – Ausweisung auf Zeugnis: Naturwissenschaften (Wahlpflichtfach)<br/>
Fach Französisch – Ausweisung auf Zeugnis: Französisch (Wahlpflichtfach)<br/>
Der Bericht fragt für die Ausgabe (Wahlpflichtfach) und (1./2./3. Fremdsprache) in Klammern gesetzt die Fachbezeichnung ab.
