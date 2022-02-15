# BER-BS-HJZ (Bescheinigung 2006)

## Zeugnisbemerkungen
 
`Abitur > Zeugnisbemerkungen` oder `Schüler > Zeugnis > Bemerkungen/Formulare`

Bemerkungen Legen Sie im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` oder im Menü `Abitur > Zeugnisbemerkungen` an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren. 
Einen Platzhalter definieren Sie über „`<<“ zum Beginn und „>>`“ zum Ende Ihres Platzhalters, z.B. So `<<hier steht Ihr Platzhalter>>`. 

Möglich sind:

Platzhalter | Ausgabe im Bericht
--|--
`<<Name>>` | Vorname, Vorname2, Namenszusatz und Nachname des Schülers
`<<Nachname>>` | Nachname des Schülers
`<<Vorname>>` | Vorname, Vorname2 und Namenszusatz des Schülers
`<<Anrede1>>` | Er/Sie (je nach Geschlecht des Schülers)
`<<Anrede2>>` | er/sie (je nach Geschlecht des Schülers)
`<<Anrede3>>` | seine/ihre (je nach Geschlecht des Schülers)
`<<Anrede4>>` | ihm/ihr (je nach Geschlecht des Schülers)
`<<Anrede5>>` | seinen/ihren (je nach Geschlecht des Schülers)

## Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein. Das Zeugnisdatum kann auch per Sammelzuweisung zugewiesen werden, den Aufruf für die Sammelzuweisung finden Sie am oberen Rand der Karte `Details`.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

## Berechnung Schulhalbjahr

´Schlüsselverzeichnis > Zeiträume > Art´ UND ´Klassen > Zeiträume > Jahrgang´

Die Ausgabe des Schulhalbjahres errechnet sich aufgrund der Definition des aktuellen Zeitraums in MAGELLAN unter ´Schlüsselverzeichnis > Zeiträume > Art´ und aus dem Menü ´Klassen > Zeiträume > Jahrgang´.
z.B.
1 Jahrgang = 1. und 2. HJ

## Fehltage und/oder Fehlstunden 

`Schueler > Zeugnis > Details > Fehltage und/oder Fehlstunden`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern "Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

## Schriftart 

Damit das Zeugnis/der Bericht korrekt ausgedruckt wird, muss die vom Senat für den Zeugnisdruck vorgegebene Schriftart SenBJS auf Ihrem Rechner installiert sein.

## Fachstatus 

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.

Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
Bkomp| Bkomp | Berufsfachliche Kompetenz
WahlPF | WahlPF | Wahlpflichtfächer
FachT | FachT | Fachtheoretischer Bereich

## Merkmale für Zeugnisbemerkungen

`Schüler > Zeugnis > Bemerkungen/Formulare > Merkmale`

Bei den Zeugnisbemerkungen müssen verschiedene Typen der Bemerkung unterschieden werden. Die Unterscheidung erfolgt durch den Eintrag in der Spalte "Merkmal" unter Schlüsselverzeichnis Zeugnisbemerkungen, falls es sich um allgemeingültige Zeugnisbemerkungen handelt, oder beim Schüler, falls Sie diesem eine individuelle Zeugnisbemerkung zuweisen möchten. Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Bemerkungen/Formulare`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung auswählen und zuweisen. Erfolgt keine Eingabe in der Spalte "Merkmal", so wird die Bemerkung unter "allgemeinen Bemerkungen" auf dem Zeugnisdruck ausgegeben.

Folgende Kürzel im Feld "Merkmal" dürfen für den Zeugnisdruck verwendet werden:

## Fächerpositionierung

`Schüler > Zeugnis > Fächer > Position`

Für die Sortierung der Fächer auf den Zeugnissen muss im Menü `Schüler > Zeugnis > Fächer` pro Fach eine Position in der Spalte "Position" angegeben werden. Bei der Ausgabe der Fächer auf dem Zeugnis werden die geraden Positionen in der rechten Spalte und die ungeraden Positionen in der linken Spalte ausgegeben. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis der
Fachtafeln unter `Schlüsselvezeichnis > Fachtafeln` die Zeugnisposition zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Position nicht pro Schüler und pro Fach vornehmen.

## Beruf Schüler

`Schüler > Ausbildung > Ausbildungbetriebe > Beruf`

Tragen Sie im Menü `Schüler > Ausbildung` im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Beruf" den Beruf ein. Grundlage bildet das Schlüsselverzeichnis Berufe. 