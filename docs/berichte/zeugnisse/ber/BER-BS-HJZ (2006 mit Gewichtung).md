# BER-BS-HJZ (2006 mit Gewichtung)

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

## Berechnung Schulhalbjahr

´Schlüsselverzeichnis > Zeiträume > Art´ UND ´Klassen > Zeiträume > Jahrgang´

Die Ausgabe des Schulhalbjahres errechnet sich aufgrund der Definition des aktuellen Zeitraums in MAGELLAN unter ´Schlüsselverzeichnis > Zeiträume > Art´ und aus dem Menü ´Klassen > Zeiträume > Jahrgang´.
z.B.
1 Jahrgang = 1. und 2. HJ

## Fachstatus

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.

Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
Bkomp| Bkomp | Berufsfachliche Kompetenz
WahlPF | WahlPF | Wahlpflichtfächer
FachT | FachT | Fachtheoretischer Bereich

## Fächerpositionierung

`Schüler > Zeugnis > Fächer > Position`

Für die Sortierung der Fächer auf den Zeugnissen muss im Menü `Schüler > Zeugnis > Fächer` pro Fach eine Position in der Spalte "Position" angegeben werden. Bei der Ausgabe der Fächer auf dem Zeugnis werden die geraden Positionen in der rechten Spalte und die ungeraden Positionen in der linken Spalte ausgegeben. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis der
Fachtafeln unter `Schlüsselvezeichnis > Fachtafeln` die Zeugnisposition zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Position nicht pro Schüler und pro Fach vornehmen.

## Beruf Schüler

`Schüler > Ausbildung > Ausbildungbetriebe > Beruf`

Tragen Sie im Menü `Schüler > Ausbildung` im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Beruf" den Beruf ein. Grundlage bildet das Schlüsselverzeichnis Berufe. 

## Zeiträume

`Extras > Schlüsselverzeichnisse > Zeiträume > Ausdruck 1`

Die Ausgabe des Schulhalbjahres erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN unter `Schlüsselverzeichnisse > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck1".

## Ausgabe des Schulhalbjahres

`Extras > Schlüsselverzeichnisse > Zeiträume > Art`

Die Ausgabe des Schulhalbjahres erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN unter `Schlüsselverzeichnis > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Art". Tragen Sie den von und bis Zeitraum unter "Von" und "Bis" ein.