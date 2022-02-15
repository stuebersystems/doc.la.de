# BER-BS-AZ (Schul Z 503)

Schul Z 503

## Fachstatus

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.

Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
BerufS | BerufS | Berufsbezogener /Fachrichtungsbezogner Lernbereich
Pflicht | Pflicht | Allgemeiner / Berufsübergreifender / Fachrichtungsübergreifender Lernbereich
Wahlb | Wahlb | Wahlfächer bzw. –bereich
WahlPF | WahlPF | Wahlpflichtfach

## Beruf Schüler

`Schüler > Ausbildung > Ausbildungbetriebe > Beruf`

Tragen Sie im Menü `Schüler > Ausbildung` im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Beruf" den Beruf ein. Grundlage bildet das Schlüsselverzeichnis Berufe. 

## Schulname 

`Mandanten > Daten > Name 1`

Tragen Sie die Bezeichnung Ihrer Schule im Menü "Mandanten" auf der Registerkarte "Daten 1" im Feld "Name
1" ein.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Berufsschule` gedruckt werden.

## Zegnisbemerkungen Bereich Berufsschule

`Berufsschule > Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Berufsschule > Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

## Bezirk der Schule

`Mandanten > Daten 1 > Name 3`

Tragen Sie den Bezirk Ihrer Schule im Menü `Mandanten > Daten 1` im Feld "Name 3" ein.

## Schriftart

Damit das Zeugnis/der Bericht korrekt ausgedruckt wird, muss die vom Senat für den Zeugnisdruck vorgegebene Schriftart SenBJS auf Ihrem Rechner installiert sein.

## Zeugnisdatum

`Berufsschule > Matrix > Zeugnisdatum`

Tragen Sie das Datum des Abschlusszeugnisses im Menü `Berufsschule > Matrix` im Feld "Zeugnisdatum" ein.

## Endnoten

`Berufsschule > Matrix > Endnote`

Die Noten der Fächer tragen Sie im Menü `Berufsschule > Matrix` in der Spalte "Endnote" ein. Die Gewichtung der Note tragen Sie analog im Feld "Faktor" ein. Grundlage bildet das `Schlüsselverzeichnis > Noten`.

## Noten wie o.B., n.B. oder sonstiges

`Extras > Schlüsselverzeichnisse > Noten > Füllwerte`

Um ein Fach mit einem bestimmten Füllwert (z.B. "oB" (ohne Bewertung)) auf dem Zeugnis auszugeben, müssen Sie unter `Schlüsselverzeichnisse > Noten` die Noten wie folgt anlegen. Auf dem Zeugnis wird das "Kürzel" ausgegeben.

Kürzel | Bezeichnung | Notenart
--|--|--
beliebig | beliebig | Füllwerte
oB | ohne Bewertung | Füllwerte

## Fächerpositionierung

`Schüler > Zeugnis > Fächer > Position``

Die Reihenfolge der Fächer auf dem Zeugnis richtet sich nach der Positionsnummer, die Sie dem jeweiligen Fach in der Spalte "Position" vergeben haben.

## Zugang am/Abgang am bzw. 2. Zugang am/2. Abgang am

`Schüler > Daten 2 > Zugang am/Abgang am bzw. 2. Zugang am/2. Abgang am`

Ist das Feld "2. Zugang am" im Menü `Schüler > Daten 2` gefüllt, wird auf dem Zeugnis "2. Zugang am" und "2. Abgang am" ausgegeben, ansonsten "Zugang am" und "Abgang am".

## Kennzeichnung Note, die sich auf „Gemeinsamer europäischer Referenzrahmen für Sprachen:...bezieht

`Schüler > Zeugnis > Fächer > Faktor`

Zur Kennzeichnung der Note, die sich auf den „Gemeinsamer europäischer Referenzrahmen für Sprachen: Lernen, lehren, beurteilen (GER)“ bezieht, tragen Sie im Menü `Schüler > Zeugnis > Fächer` im Feld „Faktor“ den Wert "2" ein.

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
