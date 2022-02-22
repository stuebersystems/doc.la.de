# NRW-GES-JZ-HJZ (5-9.1_10.1)

Zeugnis der Gesamtschule Klasse 5-9.1 und 10.1 (Halbjahres- und Jahreszeugnis)

## Fachstatus  

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis> Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.

Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel |  Schlüssel | Bezeichnung	
--|--|--
Pflicht  | Pflicht  | Pflichtfächer
WahlPF > WahlPF  | Wahlpflichtfächer
FörderK  | FörderK | Förderunterricht

## Unterrichtsarten

`Extras > Schlüsselverzeichnisse > Unterrichtsarten`

Die korrekte Ausgabe der Zeugnisbereiche wird im Menü `Schüler > Zeugnis > Fächer` im Feld "Unterrichtsart" ausgewählt. Grundlage bildet das `Schlüsselverzeichnis > Unterrichtsarten`. Für den Zeugnisdruck ist dabei nur der Schlüssel der Unterrichtsart relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis Fachtafeln die Unterrichtsart zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Unterrichtsart nicht pro Schüler und pro Fach vornehmen.

Folgende Unterrichtsarten dürfen im Zeugnisdruck verwendet werden:

Kürzel |  Schlüssel | Zeugnisbereich
--|--|--
AG | AG | Arbeitsgemeinschaft

## Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein.

## Ausdruck

`Ausdruck`

Das Zeugnis/der Bericht muss aus dem Menü `Schüler` gedruckt werden.

## Zeugnisbemerkungen Positionierung

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

## Beurteilungsart

`Klassen > Daten > Beurteilungsart > Benotung durch Noten`

Im Menü `Klassen > Daten` muss im Feld "Beurteilungsart" "Benotung durch Noten" angegeben sein.

## Ausdruck

`Schlüsselverzeichnis > Zeiträume > Ausdruck 2`

Die Ausgabe des Schuljahres erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN `Schlüsselverzeichnis > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck 2".

## Fehlstunden / davon unentschuldigt

`Schüler > Zeugnis > Details`

Die Angabe der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern „Fehlstunden“ und „davon unentschuldigt“ erfolgen.

## Bezeichnung, Schulform und Schulort Ihrer Schule

`Mandaten > Daten 1 > Name 1, Name 2, Name 3`

Tragen Sie die Bezeichnung, Schulform und Schulort Ihrer Schule im Menü `Mandanten > Daten 1`  in den Feldern „Name 1“, „Name 2“ und „Name 3“ ein.

## Zeugnisbemerkungen

`Abitur > Zeugnisbemerkungen`

`Schüler > Zeugnis > Bemerkungen/Formulare`

Bemerkungen Legen Sie im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` oder im Menü `Abitur > Zeugnisbemerkungen` an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren.  
Einen Platzhalter definieren Sie über „``<<“ zum Beginn und „>>``“ zum Ende Ihres Platzhalters, z.B.  So ``<<hier steht Ihr Platzhalter>>``.  

Möglich sind:

Platzhalter | Ausgabe im Bericht
--|--
``<<Name>>`` | Vorname, Vorname2, Namenszusatz und Nachname des Schülers
``<<Nachname>>`` | Nachname des Schülers
``<<Vorname>>`` | Vorname, Vorname2 und Namenszusatz des Schülers
``<<Anrede1>>`` | Er/Sie (je nach Geschlecht des Schülers)
``<<Anrede2>>`` | er/sie (je nach Geschlecht des Schülers)
``<<Anrede3>>`` | seine/ihre (je nach Geschlecht des Schülers)
``<<Anrede4>>`` |  ihm/ihr (je nach Geschlecht des Schülers)
``<<Anrede5>>`` | seinen/ihren (je nach Geschlecht des Schülers)

## Zeugnisbereiche

`Schlüsselverzeichnisse > Fachgruppen (NAWI, GESELL, ARBLEHRE, HF)`

Um die Fächer auf dem Zeugnis in Bereichen auszugeben, legen Sie im `Schlüsselverzeichnis > Fachgruppen` folgende an: 

Kürzel | Schlüssel | Bezeichnung
--|--|--
NAWI | NAWI | Naturwissenschaften
GESELL| GESELL| Gesellschaftslehre
ARBLEHRE | ARBLEHRE | Arbeitslehre
HF | HF | Hauptfach

Diese Fachgruppen weisen Sie später im `Schlüsselverzeichnis > Fächer` im Feld "Gruppe" zu.

## Fachleistungensebene

`Schüler > Zeugnis > Fächer > Niveau (G, E)`

Zuweisung zu Fachleistungensebene:
Die Leistungsstufe tragen Sie im Menu `Schüler > Zeugnis > Fächer` im Feld "Niveau" ein. Die unterschiedlichen Leistungsstufen tragen sie `Schlüsselverzeichnis > Fachniveaus` ein. Wichtig ist der vorgebene Schlüssel.

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
G | G | Grundebene
E  | E | Erweiterungsebene

## Leistungsstufe

`Schüler > Zeugnis > Fächer > Niveau (FOERDER, FOERDERLRS)`

Die Leistungsstufe tragen Sie im Menü `Schüler > Zeugnis > Fächer` im Feld "Niveau" ein. Die unterschiedlichen Leistungsstufen tragen sie `Schlüsselverzeichnis > Fachniveaus` ein. Wichtig ist der vorgebene Schlüssel.

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
FOERDER | FOERDER | Forderunterricht
FOERDERLRS | FOERDERLRS | Forderunterricht LRS

## Jahrgang Klasse

`Klassen > Zeiträume > Zeitraum > Jahrgang`

Im entsprechenden Zeitraum muss im Menü `Klassen > Zeiträume` bei der Klasse des Schülers der Jahrgang im Feld "Jahrgang" eingetragen sein.
