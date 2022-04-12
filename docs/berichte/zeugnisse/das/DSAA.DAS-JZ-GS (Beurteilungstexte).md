# DS.AA.DAS-JZ-GS (Beurteilungstexte)

[6]:/assets/images/DAS/das06.png


## Anmerkungen

Dieser Bericht basiert auf dem Bericht`DAS-GS-GY (Klasse 3-10).rpt`. Abweichend vom orginialen Bericht gibt es vier feste Logos im Zeugnisfuß, zwei Platzhalter für Zeugnislogos, die in MAGELLAN hinterlegt werden können. Zusätzlich wird in diesem Bericht nicht das Arbeits- und Sozialverhalten der Schüler ausgegeben.

Jahres- und Halbjahreszeugnis der Klassenstufe 3-10, Schulformen: 

* Grundschule
* Hauptschule
* Realschule
* Orientierungsstufe
* Gymnasium

## Logodateien

`Mandanten > Daten > Logo1 und Logo2`

Im Fuß des Zeugnisses sind vier Bildateien fest integriert. Im Kopf des Zeugnisses werden zwei weitere Bilddateien ausgegeben, die Sie unter `Mandanten > Daten2 > Logo1 und Logo2` hinterlegen können.
Dabei wird die dem Feld `Logo 1` hinterlegte Datei links gezeigt, die dem Feld `Logo 2` hinterlegte Datei rechts gezeigt.

## Beurteilungsart

`Klassen > Daten > Beurteilungsart > Beurteilungstexte > Noten`

Im Menü `Klassen` muss bei der Klasse des Schülers auf der Registerkarte `Daten` im Feld Beurteilungsart "Noten" angegeben sein,
hierbei steht auch ein Feld für die schriftliche Beurteilung des Fachs zur Verfügung.

## Zeiträume

`Extras > Schlüsselverzeichnisse > Zeiträume`

Die Ausgabe des Schulhalbjahres/Schuljahres erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN unter `Extras > Schlüsselverzeichnisse > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck1" und "Art".

[![Ausgabe Schulhalbjahr/Schuljahr auf dem Zeugnis][22]][22]

[![`Schlüsselverzeichnisse > Zeiträume`][23]][23]

## Versetzungsvermerk

`Extras > Schlüsselverzeichnisse > Zeiträume > Art`

Ein Versetzungsvermerk wird nur beim Ausdruck aus dem 2. Halbjahr ausgegeben. Der Bericht prüft beim Durck den Eintrag im `Schlüsselverzeichnisse > Zeiträume` im Feld "Art". (1. Halbjahr - kein Versetzungsvermerk, 2. Halbjahr - Versetzungsvermerk wird ausgegeben)

`Schüler > Laufbahn > Allgemein > Versetzt`

Im entsprechenden Zeitraum muss der Versetzungsvermerk im Menü `Schüler > Laufbahn > Allgemein` im Feld "Versetzt" eingetragen sein.

## Klassenjahrgang

`Klassen > Zeiträume > Zeitraum > Jahrgang`

Im entsprechenden Zeitraum muss im Menü `Klassen` bei der Klasse des Schülers der Jahrgang auf der Registerkarte `Zeiträume` im Feld "Jahrgang" eingetragen sein.

## Schulart

`Schüler > Laufbahn > Allgemein > Schulart` oder `Klasse > Daten > Schulart` 

Die Schulart des Schülers tragen Sie im aktuellen Zeitraum im Menü `Schüler > Laufbahn > Allgemein > Schulart` oder im `Klasse > Daten` im Feld "Schulart" ein. Grundlage hierfür bildet das `Schlüsselverzeichnis > Schularten`. Das Zeugnis fragt die "Bezeichnung" aus dem `Schlüsselverzeichnis > Schularten` ab, diese müssen wie folgt erfasst werden: 

Kürzel | Schlüssel | Bezeichnung
--|--|--
beliebig (GS) | leer | Grundschule
beliebig (GYM) | leer | Gymnasium
beliebig (HS) | leer | Hauptschule
beliebig (OS) | leer | Orientierungsstufe
beliebig (RS) | leer | Realschule

Was gibt der Bericht aus:
Für Schüler deren Klassenjahrgang nicht höher als Jahrgang 10 ist, wird die Schulart aus `Schüler > Laufbahn > Schulart` gelesen. Es werden die oben genannten Werte erwartet.
Sollte dort nichts erfasst sein, wird die Klassenschulart unter `Klassen > Daten > Schulart` ausgelesen, soweit die Einträge den Vorgaben entsprechen.

## Fehlzeiten

`Schueler > Zeugnis > Details > Fehltage und/oder Fehlstunden`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern "Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

## Arbeitsgemeinschaften

`Extras > Schlüsselverzeichnisse > Unterrichtsarten`
`Extras > Schlüsselverzeichnisse > Fächer`

Legen Sie zunächst die an Ihrer Schule angebotenen Arbeitsgemeinschaften als Fach im `Schlüsselverzeichnis > Fächer` an. Anschließend hinterlegen Sie diese im Menü `Schüler > Zeugnis > Fächer`. 

Damit das Zeugnis diese Fächer als Arbeitsgemeinschaften wertet, müssen Sie zusätzlich jedem dieser zugewiesenen Fächer in der Spalte "Unterrichtsart" den Eintrag "AG" zuweisen. Grundlage bildet das `Schlüsselverzeichnis > Unterrichtsarten`. Für den Zeugnisdruck ist dabei nur der Schlüssel der Unterrichtsart relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis Fachtafeln die Unterrichtsart zuweisen können. 

Folgende Unterrichtsarten dürfen im Zeugnisdruck verwendet werden:

Kürzel |  Schlüssel | Zeugnisbereich
--|--|--
AG | AG | Arbeitsgemeinschaft

[![Zuweisung Arbeitsgemeinschaften][24]][24]

## Fachpositionen

`Schüler > Zeugnis > Fächer > Position`

Für die Sortierung der Fächer auf den Zeugnissen muss im Menü `Schüler > Zeugnis > Fächer` pro Fach eine Position in der Spalte "Position" angegeben werden. Bei der Ausgabe der Fächer auf dem Zeugnis werden die geraden Positionen in der rechten Spalte und die ungeraden Positionen in der linken Spalte ausgegeben. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis der
Fachtafeln unter `Schlüsselvezeichnis > Fachtafeln` die Zeugnisposition zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Position nicht pro Schüler und pro Fach vornehmen.

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

## Endnote

`Schüler > Zeugnis > Leistungen > Endnote`

Die Noten der Fächer tragen Sie im Menü `Schüler > Zeugnis > Leistungen` in der Spalte "Endnote" ein. Grundlage bildet das `Schlüsselverzeichnis > Noten`.

## Ort des Druckdatums

`Mandanten > Daten 1 > Ort`

Der Ort des Druckdatums ergibt sich aufgrund der Eintragung im Menü `Mandanten > Daten 1` im Feld "Ort".

## Noten

`Extras > Schlüsselverzeichnisse > Noten > Füllwerte`

Arbeitsgemeinschaften (AGs) an denen der Schüler teilgenommen hat, müssen mit der Note "teilgenommen" gekennzeichnet werden. Legen Sie dazu unter `Extras > Schlüsselverzeichnisse > Noten` eine Note "teilgenommen" an.

Kürzel | Schlüssel | Bezeichnung | Notenart
--|--|--|--
n.b. | n.b. | teilgenommen | Füllwerte

## Hauptfach

`Schüler > Zeugnis > Fächer > Hauptfach`

Unterfächer die einem Hauptfach zugeordnet werden sollen, kennzeichnen Sie im Menü `Schüler > Zeugnis > Fächer` im Feld "Haupfach". Dort weisen Sie dem Unterfach das entsprechende Hauptfach zu. Damit die Fächer auf dem Zeugnis in der gewünschten Reihenfolge ausgegeben wird, weisen Sie den Fächern entsprechende Positionen zu. 
Machen Sie dabei zwischen Unter-  und Hauptfächern keine Unterschiede und positionieren diese in der gewünschten chronologischen Reihenfolge. Beachten Sie dabei, dass ein Hauptfach eine niedrigere Position als ein Unterfach haben muss und dass keine anderen Fächer zwischen Hauptfach und Unterfach positioniert werden.

## Zeugnisbemerkungen

`Extras > Schlüsselverzeichnisse > Zeugnisbemerkungen`

Zeugnisbemerkungen können im `Schlüsselverzeichnis > Zeugnisbemerkungen` vordefiniert werden oder beim Schüler individuell formuliert werden.

`Schüler > Zeugnis > Bemerkungen/Formulare`

`Abitur > Abitur > Zeugnis > Zeugnisbemerkungen`

`Berufsschule > Zeugnisbemerkungen`

Bemerkungen legen Sie je nach Zeugnis entweder im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` ODER im Menü `Abitur > Zeugnis > Zeugnisbemerkungen` ODER `Abitur > Zeugnis > Zeugnisbemerkungen` an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren.  
Einen Platzhalter definieren Sie über „`<<“ zum Beginn und „>>`“ zum Ende Ihres Platzhalters, z.B.  So `<<hier steht Ihr Platzhalter>>`.  

Möglich sind:

Platzhalter in MAGELLAN | Anzeige im Bericht
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

