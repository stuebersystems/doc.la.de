# DSAA.DAS-JZ-GS (Beurteilungstexte)

[1]:/assets/images/DAS/das37.png "Ausgabe Schulhalbjahr/Schuljahr auf dem Zeugnis"
[2]:/assets/images/DAS/das23.png "Schlüsselverzeichnisse > Zeiträume"

## Logodateien

`Mandanten > Daten > Logo1 und Logo2`

Im Fuß des Zeugnisses sind vier Bildateien fest integriert. Im Kopf des Zeugnisses werden zwei weitere Bilddateien ausgegeben, die Sie unter `Mandanten > Daten2 > Logo1 und Logo2` hinterlegen können.
Dabei wird die dem Feld `Logo 1` hinterlegte Datei links gezeigt, die dem Feld `Logo 2` hinterlegte Datei rechts gezeigt.

## Zeiträume

`Extras > Schlüsselverzeichnisse > Zeiträume`

Die Ausgabe des Schulhalbjahres/Schuljahres erfolgt aufgrund der Definition des aktuellen Zeitraums in Magellan unter `Extras > Schlüsselverzeichnisse > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck1" und "Art".

[![Ausgabe Schulhalbjahr/Schuljahr auf dem Zeugnis][1]][1]

[![`Schlüsselverzeichnisse > Zeiträume`][2]][2]

## Versetzungsvermerk

`Extras > Schlüsselverzeichnisse > Zeiträume > Art`

Ein Versetzungsvermerk wird nur beim Ausdruck aus dem 2. Halbjahr ausgegeben. Der Bericht prüft beim Durck den Eintrag im `Schlüsselverzeichnisse > Zeiträume` im Feld "Art". (1. Halbjahr - kein Versetzungsvermerk, 2. Halbjahr - Versetzungsvermerk wird ausgegeben)

`Schüler > Laufbahn > Allgemein > Versetzt`

Im entsprechenden Zeitraum muss der Versetzungsvermerk im Menü `Schüler > Laufbahn > Allgemein` im Feld "Versetzt" eingetragen sein.

## Klassenjahrgang

`Klassen > Zeiträume > Zeitraum > Jahrgang`

Im entsprechenden Zeitraum muss im Menü `Klassen` bei der Klasse des Schülers der Jahrgang auf der Registerkarte `Zeiträume` im Feld "Jahrgang" eingetragen sein.

## Mandanten

`Mandanten > Daten > Name 1`

Tragen Sie die Bezeichnung Ihrer Schule im Menü "Mandanten" auf der Registerkarte "Daten 1" im Feld "Name 1" ein.

`Mandanten > Daten > Name 2`

Tragen Sie die Namenszusätze Ihrer Schule im Menü `Mandanten > Daten 1` im Feld "Name 2" ein.

## Schulleiter, Klassenleiter

`Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter `Mandanten > Daten1` im Feld "Schulleiter" eingetragen werden. Bitte achten Sie darauf, das dem zugrunde liegenden Lehrereintrag ein Geschlecht unter `Lehrer > Daten1` zugewiesen wurde.

`Klassen > Zeiträume > Zeitraum > Klassenleiter`

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü `Klassen > Zeiträume` bei der jeweiligen Klasse im Feld "Klassenleiter" eingetragen werden. Bitte achten Sie darauf, das dem zugrunde liegenden Lehrereintrag ein Geschlecht unter `Lehrer > Daten 1` zugewiesen wurde.

## Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein. Das Zeugnisdatum kann auch per Sammelzuweisung zugewiesen werden, den Aufruf für die Sammelzuweisung finden Sie am oberen Rand der Karte `Details`.

## Zeugnisbemerkungen

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

## Text des persönlichen Briefes

Die Ausgabe erfolgt aus einer Zeugnisbemerkung heraus. Weisen Sie über  `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen` ein Zeugnisbemerkung zu.

Folgende Kürzel im Feld "Merkmal" dürfen für den Zeugnisdruck verwendet werden:

Merkmal | Bedeutung
--|--
PB | Personalisierte Bemerkungen für die Ausgabe des persönlichen Briefes

## Ort des Druckdatums

`Mandanten > Daten 1 > Ort`

Der Ort des Druckdatums ergibt sich aufgrund der Eintragung im Menü `Mandanten > Daten 1` im Feld "Ort".

## Zeugnisbemerkungen

`Extras > Schlüsselverzeichnisse > Zeugnisbemerkungen`

Zeugnisbemerkungen können im `Schlüsselverzeichnis > Zeugnisbemerkungen` vordefiniert werden oder beim Schüler individuell formuliert werden.

`Schüler > Zeugnis > Bemerkungen/Formulare`

`Abitur > Abitur > Zeugnis > Zeugnisbemerkungen`

`Berufsschule > Zeugnisbemerkungen`

Bemerkungen legen Sie je nach Zeugnis entweder im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` ODER im Menü `Abitur > Zeugnis > Zeugnisbemerkungen` ODER `Abitur > Zeugnis > Zeugnisbemerkungen` an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren.  
Einen Platzhalter definieren Sie über „`<<“ zum Beginn und „>>`“ zum Ende Ihres Platzhalters, z.B.  So `<<hier steht Ihr Platzhalter>>`.  

Möglich sind:

Platzhalter in Magellan | Anzeige im Bericht
--|--
`<<VornameV>>` | Vorname Vorname2
`<<Nachname>>` | Nachname
`<<NachnameV>>` | Namenszusatz Nachname
`<<Name>>` | Vorname Vorname2 Namenszusatz Nachname
`<<Name>>` | Vorname, Vorname2, Namenszusatz und Nachname des Schülers
`<<Nachname>>`  |  Nachname des Schülers
`<<Vorname>>` |  Vorname, Vorname2 und Namenszusatz des Schülers
`<<Er_Sie>>` |  Er/Sie (je nach Geschlecht des Schülers)
`<<Seine_Ihre>>` | Seine/Ihre (je nach Geschlecht des Schülers)
`<<seine_ihre>>` |  seine/ihre (je nach Geschlecht des Schülers)
`<<Ihm_Ihr>>` |  Ihm/Ihr (je nach Geschlecht des Schülers)
`<<ihm_ihr>>` |  ihm/ihr (je nach Geschlecht des Schülers)
`<<Seinen_Ihren>>` |  Seinen/Ihnen (je nach Geschlecht des Schülers)
`<<seinen_ihren>>` |  seinen/ihnen (je nach Geschlecht des Schülers) 
`<<DerSchueler_DieSchuelerin>>` |  Der Schüler/Die Schülerin je nach Geschlecht des Schülers) 
`<<derSchueler_dieSchuelerin>>`  | der Schüler/die Schülerin  (je nach Geschlecht des Schülers) 
`<<DemSchueler_DerSchuelerin>>`  |  Dem Schüler/Der Schülerin (je nach Geschlecht des Schülers)

