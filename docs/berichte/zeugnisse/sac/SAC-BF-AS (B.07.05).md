# SAC-BF-AS (B.07.05)


`Archiv`

B.07.05

## Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Schüler` gedruckt werden.

## Zeugnisbemerkungen Positionierung

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

## Beurteilungsart Klasse

`Klassen > Daten > Beurteilungsart > Benotung durch Noten`

Im Menü "Klassen" muss bei der Klasse des Schülers auf der Registerkarte Daten im Feld "Beurteilungsart" "Benotung durch Noten" angegeben sein.

## Fachstatus 

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.
Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
BerufS | BerufS | Berufsbezogener /Fachrichtungsbezogner Lernbereich
Pflicht | Pflicht | Allgemeiner / Berufsübergreifender / Fachrichtungsübergreifender Lernbereich
Wahlb | Wahlb | Wahlfächer bzw. –bereich
Praktikum | Praktikum | Praktikum
BPraktikum | BPraktikum | Berufspraktische/Praktische Ausbildung

## Zugang am / Abgang am 

`Schueler > Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü Schüler > Daten 2 im Feld "Zugang am" bzw. "Abgang am" ein.

## Beruf der Klasse 

`Klassen > Daten > Beruf`

Weisen Sie im Menü `Klassen > Daten` den Beruf im Feld "Beruf" zu. Grundlage bildet das `Schlüsselverzeichnis > Berufe`. Für den Zeugnisdruck ist nur der Wert in der Spalte "Schlüssel" relevant, das Kürzel kann beliebig gewählt werden.

## Fächerpositionierung

`Schüler > Zeugnis > Fächer > Position`

Für die Sortierung der Fächer auf den Zeugnissen muss im Menü `Schüler > Zeugnis > Fächer` pro Fach eine Position in der Spalte "Position" angegeben werden. Bei der Ausgabe der Fächer auf dem Zeugnis werden die geraden Positionen in der rechten Spalte und die ungeraden Positionen in der linken Spalte ausgegeben. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis der Fachtafeln unter `Schlüsselvezeichnis > Fachtafeln` die Zeugnisposition zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Position nicht pro Schüler und pro Fach vornehmen.

## Anzahl der Wochen für Praktikum/ Berufspraktische/Praktische Ausbildung

`Schüler > Zeugnis > Fächer`

Die Anzahl der Wochen für das Praktikum bzw. für die Berufspraktische/Praktische Ausbildung weisen Sie einem Fach "Praktikum" bzw. "Berufspraktische/Praktische Ausbildung" im Menü `Schüler > Zeugnis > Fächer` im Feld "Merkmal" zu. 

## Schulname 

`Mandanten > Daten > Name 1`

Tragen Sie die Bezeichnung Ihrer Schule im Menü "Mandanten" auf der Registerkarte "Daten 1" im Feld "Name
1" ein.

## SchulleiterIn 

`Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter `Mandanten > Daten1` im Feld "Schulleiter" eingetragen werden.

## KlassenleiterIn 

`Klassen > Zeiträume > Zeitraum > Klassenleiter`

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü `Klassen > Zeiträume` bei der jeweiligen Klasse im Feld "Klassenleiter" eingetragen werden.

## Platzhalter f. Zeugnisbemerkungen 

`Abitur > Zeugnisbemerkungen` / `Schüler > Zeugnis > Bemerkungen/Formulare`

Bemerkungen Legen Sie im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` oder im Menü Abitur > Zeugnisbemerkungen an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren. 
Einen Platzhalter definieren Sie über „``<<“ zum Beginn und „>>``“ zum Ende Ihres Platzhalters, z.B. So ``<<hier steht Ihr Platzhalter>>``. 

Möglich sind:

Platzhalter | Ausgabe im Bericht
--|--
``<<Name>>`` | Vorname, Vorname2, Namenszusatz und Nachname des Schülers
``<<Nachname>>`` | Nachname des Schülers
``<<Vorname>>`` | Vorname, Vorname2 und Namenszusatz des Schülers
``<<Anrede1>>`` | Er/Sie (je nach Geschlecht des Schülers)
``<<Anrede2>>`` | er/sie (je nach Geschlecht des Schülers)
``<<Anrede3>>`` | seine/ihre (je nach Geschlecht des Schülers)
``<<Anrede4>>`` | ihm/ihr (je nach Geschlecht des Schülers)
``<<Anrede5>>`` | seinen/ihren (je nach Geschlecht des Schülers)


