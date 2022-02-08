# BER-BF-AS (Z 522-542).rpt

Schul Z 522-542

## Fachstatus

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.

Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Bezeichnung
--|--|--
1 PF | 1 PF | 1. Prüfungsfach
2 PF | 2 PF | 2. Prüfungsfach
3 PF | 3 PF | 3. Prüfungsfach
4 PF | 4 PF | 4. Prüfungsfach
AG | AG | Arbeitsgemeinschaften

## Zugang am und/oder Abgang am

`Schueler > Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü `Schüler > Daten 2` im Feld "Zugang am" bzw. "Abgang am" ein.

## Zeugnisnoten

`Schüler > Zeugnis > Leistungen`

Tragen Sie im Menü `Schüler > Zeugnis > Leistungen` im Feld "Endnote" die Jahresnote, im Feld "Schriftl. Note 1" die schriftliche Note und im Feld "Mündl. Note" die mündliche Note ein.

## SchulleiterIn

`Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter `Mandanten > Daten1` im Feld "Schulleiter" eingetragen werden. Bitte achten Sie darauf, das dem zugrunde liegenden Lehrereintrag ein Geschlecht unter `Lehrer > Daten1` zugewiesen wurde.

## Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein. Das Zeugnisdatum kann auch per Sammelzuweisung zugewiesen werden, den Aufruf für die Sammelzuweisung finden Sie am oberen Rand der Karte `Details`.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

## Zeugnisbemerkungen

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

## Noten der Fächer

`Schüler > Zeugnis > Leistungen > Endnote`

Die Noten der Fächer tragen Sie im Menü `Schüler > Zeugnis > Leistungen` in der Spalte "Endnote" ein. Grundlage bildet das `Schlüsselverzeichnis > Noten`.

## Ausdruc

Der Bericht muss aus dem Menu `Drucken > Zeugnis Drucken` (Strg + Z) gedruckt werden.

## Noten der Prüfungsfächer**

`Schüler > Zeugnis > Leistungen > Endnote (Gesamt)`

Tragen Sie im Menü `Schüler > Zeugnis > Leistungen` im Feld „Endnote (Gesamt)“ die Noten der Prüfungen ein.

## Facharbeit

`Schüler > Zeugnis > Bemerkungen/Formulare > Merkmal (FA)`

Zur Ausgabe der "Facharbeit"/"Präsentationsprüfung" gehen Sie wie folgt vor:

1. Dem Fach in dem die "Facharbeit"/"Präsentationsprüfung" erfolgt, weisen Sie im Menü `Schüler > Zeugnis > Fächer` im Feld "Fachstatus" "4PF" zu. 
2. Tragen Sie im Menü `Schüler > Zeugnis > Leistungen` im Feld „Endnote (Gesamt)“ die Noten der Prüfungen ein.
3. Das Thema der "Facharbeit"/"Präsentationsprüfung" tragen Sie im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen` als Zeugnisbemerkung ein. Kennzeichnen Sie die "Facharbeit"/"Präsentationsprüfung" über das Merkmal "FA".

## Zeugnisbemerkunge

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
