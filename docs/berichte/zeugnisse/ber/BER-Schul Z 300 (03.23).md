# BER-Schul Z 300 (03.23)

Schul Z 300 - Zeugnis der Einführungsphase - ISS GS BG (03.23)

[1]:/assets/images/Berlin/schulz300.png "BER-Schul Z 300 (11.19)"

![BER-Schul Z 300 (11.19)][1]

## Versetzungsvermerk

`Schüler > Laufbahn > Allgemein > Versetzt`
`Klasse > Zeiträume > Jahrgang`
`Schüler > Daten1 > Vorname`
`Schüler > Daten1 > Geschlecht`

Im entsprechenden Zeitraum muss der Versetzungsvermerk im Menü `Schüler > Laufbahn > Allgemein` im Feld "Versetzt"  und der Klassenjahrgang eingetragen sein. Je nach für den Schüler erfassten Geschlecht, wird der Satz formuliert:

Geschlecht|Pronomen/Vorname
--|--
weiblich|Sie
männlich|Er
divers|Vorname
leer|Vorname

## Fehlzeiten

### Fehltage und/oder Fehlstunden

`Schueler > Zeugnis > Details > Fehltage und/oder Fehlstunden`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern "Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

### Versäumnisse

`Schüler > Zeugnis > Details > Versäumnisse`

Tragen Sie die "Verspätungen" im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` im Feld "Versäumnisse" ein.

## Fremdsprachen

### von bis

`Schüler > Daten 3 > Von/Bis`
 
Tragen Sie das Von/Bis (erwartet wird der Jahrgang) der belegten Fremdsprachen in den Feldern "von/bis" ein.

### Fremdsprachenfolge

`Schüler > Daten 3 > 1./2./3./4. Fremdsprache`

Tragen Sie im Menü `Schüler > Daten 3` beim entsprechenden Schüler die Fremdsprache im aktuellen Zeitraum unter "Fremdsprachenfolge" ein. Damit Ihnen hier Fremdsprachen im Auswahlmenü angeboten werden, müssen Sie unter `Schlüsselverzeichnis > Fächer` im Feld "Kategorie" aus dem Pull-Down-Menü "Fremdsprache" zugewiesen haben.

## Bemerkungstext zur Ausgabe eines Beiblattes

`Schüler > Zeugnis > Bemerkungen/Formulare > Merkmale`

Die Ausgabe des Bemerkungstext: "Ein Beiblatt (Schul Z 620) ist Bestandteil dieses Zeugnisses:

☐ ja

☐ nein

1)." wird wie folgt gesteuert:

Liegt eine Zeugnisbemerkung mit dem Merkmal "Beiblatt" beim Schüler vor, kommt der Text in der Bemerkung: “Ein Beiblatt (Schul Z 620) ist Bestandteil dieses Zeugnisses.”

Liegt dieses Merkaml nicht vor, kommt der Text in der Bemerkung: “Ein Beiblatt (Schul Z 620) ist nicht Bestandteil dieses Zeugnisses.”

## Allgemeines

### Schulname und -bezirk

`Mandanten > Daten > Name 1` <br/>`Mandanten > Daten > Name 2`<br/>`Mandanten > Daten 1 > Name 3`

Tragen Sie die Bezeichnung Ihrer Schule im Menü "Mandanten" auf der Registerkarte "Daten 1" im Feld "Name1" ein.<br/>
Tragen Sie die Namenszusätze Ihrer Schule im Menü `Mandanten > Daten 1` im Feld "Name 2" ein.<br/>
Tragen Sie den Bezirk Ihrer Schule im Menü `Mandanten > Daten 1` im Feld "Name 3" ein.

Wenn der Name 2 und der Name 3 gefüllt sind, werden die beiden Inhalte mit einem Komma getrennt in derselben Zeile gezeigt.

### Zeiträume

`Extras > Schlüsselverzeichnis > Zeiträume > Ausdruck 1`<br/>`Extras > Schlüsselverzeichnis > Zeiträume > Art`

Die Ausgabe des Schuljahres erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN `Schlüsselverzeichnis > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck1".
Die Ausgabe des Schulhalbjahres ergibt sich aufgrund der Definition des aktuellen Zeitraums in MAGELLAN unter `Schlüsselverzeichnis > Zeiträume` im Feld "Art".

ZeitraumArt 1.Halbjahr ergibt = "1. Schulhalbjahr " + {Zeitraeume.Ausdruck1} Beispiel: 1.Schulhalbjahr 2022/23<br/>
ZeitraumArt leer oder 2.Halbjahr = "Schuljahr " + {Zeitraeume.Ausdruck1} Beispiel: Schuljahr 2022/23

### Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein. Das Zeugnisdatum kann auch per Sammelzuweisung zugewiesen werden, den Aufruf für die Sammelzuweisung finden Sie am oberen Rand der Karte `Details`.

### Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.
Der Bericht muss aus dem Menu `Drucken > Zeugnis Drucken` (Strg + Z) gedruckt werden.

## Versetzung

`Schüler > Laufbahn > Allgemein > Versetzt`

Im entsprechenden Zeitraum muss der Versetzungsvermerk im Menü `Schüler > Laufbahn > Allgemein` im Feld "Versetzt" eingetragen sein.

## Fächer

### Unterrichtsarten

`Extras > Schlüsselverzeichnisse > Unterrichtsarten`

Die korrekte Ausgabe der Zeugnisbereiche wird im Menü `Schüler > Zeugnis > Fächer` im Feld "Unterrichtsart" ausgewählt. Grundlage bildet das `Schlüsselverzeichnis > Unterrichtsarten`. Für den Zeugnisdruck ist dabei nur der Schlüssel der Unterrichtsart relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis Fachtafeln die Unterrichtsart zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Unterrichtsart nicht pro Schüler und pro Fach vornehmen.

Folgende Unterrichtsarten dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
WahlPF | WahlPF | Wahlpflichtunterricht
Wahl | Wahl | Wahlunterricht

### Fächerpositionierung

 `Schüler > Zeugnis > Fächer (Position) bzw. Abitur > Qualifikation (Position)`

Für die Sortierung der Fächer auf den Zeugnissen muss im Menü "Schüler" bei jedem Schüler auf der Registerkarte Zeugnis > Fächer bzw. im Menü Abitur bei jedem Schüler auf der Registerkarte "Qualifikation" pro Fach eine Position in der Spalte "Position" angegeben werden.

### Sport

Um das Fach Sport oben in der rechten Spalte zu zeigen, darf die Unterrichtsart nicht WahlPF oder Wahl sein und unter `Extras > Schlüsselverzeichnisse > Fächer` muss für das Fach Sport der gleichnamige Aufgabenbereich gewählt sein. 
Gibt es mehr als eine Zeile Sport, beispielsweise einen Sportzusatzkurs, werden die Zeilen in der Reihenfolge der verwendeten Fachposition gezeigt.

### Gliederung der Fächer

`Schüler > Zeugnis > Fächer`

Gliederung Pflichtunterricht, Wahlpflichtunterricht und Wahlunterricht (BER):
Im Zeugnis werden die Fächer wie folgt ausgegeben:
Spalte 1 (links)- hier erscheint der „Pflichtunterricht“
Spalte 2 (rechts) - hier erscheinen untereinander zunächst die Fächer des „Wahlpflichtunterrichtes“ und darunter die Fächer des „Wahlunterrichts“

## Benotung

`Klassen > Daten > Beurteilungsart`

Im Menü "Klassen" muss bei der Klasse des Schülers auf der Registerkarte Daten im Feld "Beurteilungsart" "Benotung durch Punkte" angegeben sein.

## Zeugnisbemerkungen

### Bemerkung anlegen

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

### Merkmale

`Schüler > Zeugnis > Bemerkungen/Formulare > Merkmale`

Bei den Zeugnisbemerkungen müssen verschiedene Typen der Bemerkung unterschieden werden. Die Unterscheidung erfolgt durch den Eintrag in der Spalte "Merkmal" unter Schlüsselverzeichnis Zeugnisbemerkungen, falls es sich um allgemeingültige Zeugnisbemerkungen handelt, oder beim Schüler, falls Sie diesem eine individuelle Zeugnisbemerkung zuweisen möchten. Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Bemerkungen/Formulare`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung auswählen und zuweisen. Erfolgt keine Eingabe in der Spalte "Merkmal", so wird die Bemerkung unter "allgemeinen Bemerkungen" auf dem Zeugnisdruck ausgegeben.

Bitte beachten Sie, dass Zeugnis nur Zeugnisbemerkungen ohne Merkmalseintrag ausgibt, das Merkmal `Beiblatt` ist für den Hinweis auf ein Beiblatt reserviert.

### Platzhalter

`Schüler > Zeugnis > Bemerkungen/Formulare`und `Abitur > Abitur > Zeugnis > Zeugnisbemerkungen` und `Berufsschule > Zeugnisbemerkungen`

Bemerkungen legen Sie entweder im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` ODER im Menü `Abitur > Zeugnis > Zeugnisbemerkungen` ODER `Abitur > Zeugnis > Zeugnisbemerkungen` an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren. 
Einen Platzhalter definieren Sie über „`<<“ zum Beginn und „>>`“ zum Ende Ihres Platzhalters, z.B. So `<<hier steht Ihr Platzhalter>>`. 

Möglich sind:

Platzhalter in MAGELLAN | Anzeige im Bericht
--|--
`<<VornameV>>` | Vorname Vorname2
`<<Nachname>>` | Nachname
`<<NachnameV>>` | Namenszusatz Nachname
`<<Name>>` | Vorname Vorname2 Namenszusatz Nachname
`<<Name>>` | Vorname, Vorname2, Namenszusatz und Nachname des Schülers
`<<Nachname>>` | Nachname des Schülers
`<<Vorname>>` | Vorname, Vorname2 und Namenszusatz des Schülers
`<<Er_Sie>>` | Er/Sie (je nach Geschlecht des Schülers)
`<<Seine_Ihre>>` | Seine/Ihre (je nach Geschlecht des Schülers)** 
`<<seine_ihre>>` | seine/ihre (je nach Geschlecht des Schülers)** 
`<<Ihm_Ihr>>` | Ihm/Ihr (je nach Geschlecht des Schülers)** 
`<<ihm_ihr>>` | ihm/ihr (je nach Geschlecht des Schülers)** 
`<<Seinen_Ihren>>` | Seinen/Ihnen (je nach Geschlecht des Schülers)** 
`<<seinen_ihren>>` | seinen/ihnen (je nach Geschlecht des Schülers)** 
`<<DerSchueler_DieSchuelerin>>` | Der Schüler/Die Schülerin je nach Geschlecht des Schülers)** 
`<<derSchueler_dieSchuelerin>>` | der Schüler/die Schülerin (je nach Geschlecht des Schülers)** 
`<<DemSchueler_DerSchuelerin>>` | Dem Schüler/Der Schülerin (je nach Geschlecht des Schülers)

