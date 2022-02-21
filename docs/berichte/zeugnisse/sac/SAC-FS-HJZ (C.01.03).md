# SAC-FS-HJZ (C.01.03)

C.01.03

## Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Schüler` gedruckt werden.

## Zeugnisbemerkungen Positionierung

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

## Fachstatus 

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.
Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Bezeichnung
--|--|--
WahlPF | WahlPF | Wahlpflichtfach
Wahlb | Wahlb | Wahlfächer bzw. –bereich
Pflicht | Pflicht | Pflichtfach
BerufS | BerufS | Berufsbezogener Lernbereich

## Ausdruck

Der Bericht muss aus dem Menu `Drucken > Zeugnis Drucken` (Strg + Z) gedruckt werden.

## Fächerpositionierung

`Schüler > Zeugnis > Fächer > Position`

Für die Sortierung der Fächer auf den Zeugnissen muss im Menü `Schüler > Zeugnis > Fächer` pro Fach eine Position in der Spalte "Position" angegeben werden. Bei der Ausgabe der Fächer auf dem Zeugnis werden die geraden Positionen in der rechten Spalte und die ungeraden Positionen in der linken Spalte ausgegeben. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis der Fachtafeln unter `Schlüsselvezeichnis > Fachtafeln` die Zeugnisposition zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Position nicht pro Schüler und pro Fach vornehmen.

## KlassenleiterIn 

`Klassen > Zeiträume > Zeitraum > Klassenleiter`

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü `Klassen > Zeiträume` bei der jeweiligen Klasse im Feld "Klassenleiter" eingetragen werden.

## Zeiträume 

`Extras > Schlüsselverzeichnis > Zeiträume > Ausdruck 1`

Die Ausgabe des Schuljahres erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN `Schlüsselverzeichnis > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck1".

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
FHReife | FHReife| Zusatzausbildung zum Erwerb der Fachhochschulreife

`Schüler > Ausbildung > Ausbildungbetriebe > Bildungsgang`

Tragen Sie im Menü `Schüler > Ausbildung` im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Bildungsgang" ein. Grundlage bildet das `Schlüsselverzeichnis >  Bildungsgänge`.

## Berufsfeld der Klasse

`Klassen > Daten > Berufsfeld`

Weisen Sie im aktuellen Zeitraum im Menü `Klasse > Daten` das Berufsfeld im Feld "Berufsfeld" zu. Grundlage bildet das `Schlüsselverzeichnis > Berufsfelder`.

## Schulname 

`Mandanten > Daten > Name 1`

Tragen Sie die Bezeichnung Ihrer Schule im Menü "Mandanten" auf der Registerkarte "Daten 1" im Feld "Name
1" ein.

## SchulleiterIn 

`Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter `Mandanten > Daten1` im Feld "Schulleiter" eingetragen werden.

## Schulart der Klasse

`Klasse > Daten > Schulart`

Tragen Sie im aktuellen Zeitraum im Menü `Klasse > Daten` die Schulfart im Feld "Schulart" ein. Grundlage hierfür bildet das `Schlüsselverzeichnis > Schularten`.

## Mandanten / Ort

`Mandanten > Daten 1 > Ort`

Der Schulort (bzw. Ausstellungsort) ergibt sich aufgrund der Eintragung im Menü `Mandanten > Daten 1` im Feld „Ort“.

Fachrichtung und Schwerpunkt

Die Fachrichtung und der Schwerpunkt im Kopf des Zeugnisses werden aus der Bezeichnung der Fachrichtung und des Schwerpunktes des Schüler-Bildungsgangs ausgelesen.

1. Legen Sie die gewünschten Werte unter `Extras > Schlüsselverzeichnisse` in den Verzeichnissen `Schwerpunkt` und `Fachrichtung` an. Der später im Zeugnis erscheinende Wert ist der Eintrag aus dem Feld `Bezeichnung`.
2. Weisen Sie unter `Extras > Schlüsselverzeichnisse > Bildungsgang` in den Felder `Fachrichtung` und `Schwerpunkt` die gewünschten Werte zu.
3. Weisen Sie den Schülern unter `Schüler > Ausbildung` für die aktuelle Ausbildung den Bildungsgang zu, diese Information kann auch per Sammelzuweisung verteilt werden.


