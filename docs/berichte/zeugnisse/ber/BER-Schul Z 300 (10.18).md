# BER-Schul Z 300 (10.18)

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

## Bezirk der Schule	

`Mandanten > Daten 1 > Name 3`

Tragen Sie den Bezirk Ihrer Schule im Menü `Mandanten > Daten 1` im Feld "Name 3" ein.

## Benotung

`Klassen > Daten > Beurteilungsart`

Im Menü "Klassen" muss bei der Klasse des Schülers auf der Registerkarte Daten im Feld "Beurteilungsart" "Benotung durch Punkte" angegeben sein.

## Zeiträume

`Extras > Schlüsselverzeichnis > Zeiträume > Art`

Die Ausgabe des Schulhalbjahres ergibt sich aufgrund der Definition des aktuellen Zeitraums in MAGELLAN unter `Schlüsselverzeichnis > Zeiträume` im Feld "Art"

## Versäumnisse

`Schüler > Zeugnis > Details > Versäumnisse`

Tragen Sie die "Verspätungen" im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` im Feld "Versäumnisse" ein.

## Ausdruck

Der Bericht muss aus dem Menu `Drucken > Zeugnis Drucken` (Strg + Z) gedruckt werden.

## Schulname

`Mandanten > Daten > Name 2`

Tragen Sie die Namenszusätze Ihrer Schule im Menü `Mandanten > Daten 1` im Feld "Name 2" ein.

## Platzhalter in Zeugnisbemerkungen

`Schüler > Zeugnis > Bemerkungen/Formulare` oder `Abitur > Abitur > Zeugnis > Zeugnisbemerkungen` oder
`Berufsschule > Zeugnisbemerkungen`

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

## Gliederung der Fächer

`Schüler > Zeugnis > Fächer`

Gliederung Pflichtunterricht, Wahlpflichtunterricht und Wahlunterricht (BER):
Im Zeugnis werden die Fächer wie folgt ausgegeben:

Spalte|Was erscheint
--|--
Spalte 1 (links)| hier erscheint der „Pflichtunterricht“
Spalte 2 (rechts)| hier erscheinen untereinander zunächst die Fächer des „Wahlpflichtunterrichtes“ und darunter die Fächer des „Wahlunterrichts“