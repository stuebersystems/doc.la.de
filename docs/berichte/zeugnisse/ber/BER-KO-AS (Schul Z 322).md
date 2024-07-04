# BER-KO-AS (Schul Z 322)

Schul Z 322

## Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein. Das Zeugnisdatum kann auch per Sammelzuweisung zugewiesen werden, den Aufruf für die Sammelzuweisung finden Sie am oberen Rand der Karte `Details`.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

## Zeugnisbemerkungen

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

## Fehltage und/oder Fehlstunden

`Schueler > Zeugnis > Details > Fehltage und/oder Fehlstunden`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern "Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

## Ausgabe des Schulhalbjahres 

`Schlüsselverzeichnis > Zeiträume > Art` und `Klassen > Zeiträume > Jahrgang`

Die Ausgabe des Schulhalbjahres errechnet sich aufgrund der Definition des aktuellen Zeitraums in Magellan unter `Schlüsselverzeichnis > Zeiträume > Art` und aus `Klassen > Zeiträume > Jahrgang`.
z.B.

Jahrgang | Ausgabe
--|--
12 | 1. und 2. HJ
13 | 3. und 4. HJ
usw. | usw.

## Schriftart

Damit das Zeugnis/der Bericht korrekt ausgedruckt wird, muss die vom Senat für den Zeugnisdruck vorgegebene Schriftart SenBJS auf Ihrem Rechner installiert sein.

## Noten wie o.B., n.B. oder sonstiges

`Extras > Schlüsselverzeichnisse > Noten > Füllwerte`

Um ein Fach mit einem bestimmten Füllwert (z.B. "oB" (ohne Bewertung)) auf dem Zeugnis auszugeben, müssen Sie unter `Schlüsselverzeichnisse > Noten` die Noten wie folgt anlegen. Auf dem Zeugnis wird das "Kürzel" ausgegeben.

Kürzel | Bezeichnung | Notenart
--|--|--
beliebig | beliebig | Füllwerte
oB | ohne Bewertung | Füllwerte

## Aufgabenbereich

`Extras > Schlüsselverzeichnisse > Fächer > Aufgabenbereich`

Für die korrekte Ausgabe der Zeugnisbereiche wählen Sie unter `Schlüsselverzeichnis > Fächer` für jedes Fach einen Aufgabenbereich aus dem Drop-Down-Menü in der Spalte "Aufgabenbereich" aus. Diese Fächer müssen im Menü `Schüler > Zeugnis > Fächer` zugewiesen sein. Folgende Aufgabenbereiche dürfen im Zeugnisdruck verwendet werden:

Aufgabenbereich| Zeugnisbereich
--|--
sprachl.-lit.-künstlerisch | 1. Aufgabenfeld
gesellschaftswiss. | 2. Aufgabenfeld
mathem.-nat.-technisch | 3. Aufgabenfeld

## Unterrichtsarten

`Extras > Schlüsselverzeichnisse > Unterrichtsarten`

Die korrekte Ausgabe der Zeugnisbereiche wird im Menü `Schüler > Zeugnis > Fächer` im Feld "Unterrichtsart" ausgewählt. Grundlage bildet das `Schlüsselverzeichnis > Unterrichtsarten`. Für den Zeugnisdruck ist dabei nur der Schlüssel der Unterrichtsart relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis Fachtafeln die Unterrichtsart zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Unterrichtsart nicht pro Schüler und pro Fach vornehmen.

Folgende Unterrichtsarten dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
LK | LK | Leistungskurs

## Merkmale für Zeugnisbemerkungen

`Schüler > Zeugnis > Bemerkungen/Formulare > Merkmale`

Bei den Zeugnisbemerkungen müssen verschiedene Typen der Bemerkung unterschieden werden. Die Unterscheidung erfolgt durch den Eintrag in der Spalte "Merkmal" unter Schlüsselverzeichnis Zeugnisbemerkungen, falls es sich um allgemeingültige Zeugnisbemerkungen handelt, oder beim Schüler, falls Sie diesem eine individuelle Zeugnisbemerkung zuweisen möchten. Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Bemerkungen/Formulare`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung auswählen und zuweisen. Erfolgt keine Eingabe in der Spalte "Merkmal", so wird die Bemerkung unter "allgemeinen Bemerkungen" auf dem Zeugnisdruck ausgegeben.

Folgende Kürzel im Feld "Merkmal" dürfen für den Zeugnisdruck verwendet werden:

Merkmal | Bedeutung
--|--
freiw | Text für die Teilnahme an freiwilligen Arbeitsgemeinschaften/Unterrichtsveranstaltungen

## Ausgabe besondere Lernleistung

Um auf dem Zeugnis die besondere Lernleistung einzutragen gehen Sie wie folgt vor:

1. Definieren Sie ein entsprechendes Fach (`Extras > Schlüsselverzeichnisse > Fächer`)
2. Legen Sie unter Schlüsselverzeichnisse > Unterrichtsarten eine Unterrichtsart mit dem Kürzel BL an (falls nicht vorhanden)** und weisen Sie diese dem entsprechenden Fach zu (`Extras > Schlüsselverzeichnisse > Unterrichtsarten`)
3. Im `Schlüsselverzeichnisse > Fachschwerpunkte` geben Sie in der Spalte "Bezeichnung" das Thema der besonderen Lernleistung an (falls nicht vorhanden)** und weisen Sie diese dem entsprechenden Fach zu

## Zeiträume

`Extras > Schlüsselverzeichnis > Zeiträume > Ausdruck 1`

Die Ausgabe des Schuljahres erfolgt aufgrund der Definition des aktuellen Zeitraums in Magellan `Schlüsselverzeichnis > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck1".