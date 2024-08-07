# DSND.DAS-GS (Klasse 4) (Spezial).rpt

[6]:/assets/images/DAS/das06.png
[7]:/assets/images/DAS/das07.png
[8]:/assets/images/DAS/das08.png
[9]:/assets/images/DAS/das09.png
[10]:/assets/images/DAS/das10.png
[11]:/assets/images/DAS/das11.png
[12]:/assets/images/DAS/das12.png
[13]:/assets/images/DAS/das13.png
[14]:/assets/images/DAS/das14.png
[15]:/assets/images/DAS/das15.png
[16]:/assets/images/DAS/das16.png
[17]:/assets/images/DAS/das17.png
[18]:/assets/images/DAS/das18.png
[19]:/assets/images/DAS/das19.png
[20]:/assets/images/DAS/das20.png
[21]:/assets/images/DAS/das21.png
[22]:/assets/images/DAS/das22.png
[23]:/assets/images/DAS/das23.png
[24]:/assets/images/DAS/das24.png
[25]:/assets/images/DAS/das25.png
[26]:/assets/images/DAS/das26.png
[27]:/assets/images/DAS/das27.png
[28]:/assets/images/DAS/das28.png
[29]:/assets/images/DAS/das29.png
[30]:/assets/images/DAS/das30.png
[31]:/assets/images/DAS/das31.png
[32]:/assets/images/DAS/das32.png

Spezial - Das Zeugnis ist variabel sowohl als Zeugnis (Halbjahres- oder Jahreszeugnis) als auch Abgangszeugnis ausgelegt.

## Differenzierung Halbjahres- oder Jahreszeugnis bzw. Abgangszeugnis

`Schüler > Laufbahn > Abschluss (Abschluss 1)`

Das Zeugnis ist variabel sowohl als Zeugnis (Halbjahres- oder Jahreszeugnis) als auch Abgangszeugnis ausgelegt.

Zwischen Abgangszeugnis und Jahres- oder Halbjahreszeugnis wird durch den Eintrag in  „Abschluss 1“ ( `Schüler > Laufbahn > Abschluss > Abschluss1`) differenziert. Bleibt das Feld leer, handelt es sich Jahres- oder Halbjahreszeugnis. 
Handelt es sich um ein Abgangszeugnis, tragen Sie unter „Abschluss 1“ den Eintrag "Abgang" ein. Grundlage dazu bildet das `Schlüsselverzeichnisse > Abschlüsse Intern`, der Bericht fragt das "Kürzel" "Abgang" ab.

[![Eintragungen in Magellan][10]][10]

[![Ausgabe auf dem Zeugnis, wenn "Abgang" eingetragen][11]][11]

## Schulhalbjahre

`Extras > Schlüsselverzeichnisse > Zeiträume > Ausdruck 1`

Die Ausgabe des Schulhalbjahres erfolgt aufgrund der Definition des aktuellen Zeitraums in Magellan unter `Extras > Schlüsselverzeichnisse > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck1".

## Klassenjahrgang

`Klassen > Zeiträume > Zeitraum > Jahrgang`

Im entsprechenden Zeitraum muss im Menü `Klassen` bei der Klasse des Schülers der Jahrgang auf der Registerkarte `Zeiträume` im Feld "Jahrgang" eingetragen sein.

## Zeugniskonferenzdatum

`Schueler > Zeugnis > Details > Zeugniskonferenz am`

Im entsprechenden Zeitraum muss das Datum der Zeugniskonferenz im Menü "Schüler" unter `Zeugnis > Details` im Feld "Zeugniskonferenz am" eingetragen sein.

## Versetzungsvermerk

`Schueler > Laufbahn > Allgemein > Versetzt`

Im entsprechenden Zeitraum muss der Versetzungsvermerk im Menü `Schüler > Laufbahn > Allgemein` im Feld "Versetzt" eingetragen sein. Entscheidend ist hierbei die Markierung des Zeitraumes im linken Zeitraumfenster.

## Fehlzeiten

`Schueler > Zeugnis > Details > Fehltage und/oder Fehlstunden`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern "Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

## Arbeitsgemeinschaft

[![Ausgabe der Arbeitsgemeinschaften][6]][6]

`Extras > Schlüsselverzeichnisse > Unterrichtsarten`
`Extras > Schlüsselverzeichnisse > Fächer`

Legen Sie zunächst die an Ihrer Schule angebotenen Arbeitsgemeinschaften als Fach im `Schlüsselverzeichnis > Fächer` an. Anschließend hinterlegen Sie diese im Menü `Schüler > Zeugnis > Fächer`. 

Damit das Zeugnis diese Fächer als Arbeitsgemeinschaften wertet, müssen Sie zusätzlich jedem dieser zugewiesenen Fächer in der Spalte "Unterrichtsart" den Eintrag "AG" zuweisen. Grundlage bildet das `Schlüsselverzeichnis > Unterrichtsarten`. Für den Zeugnisdruck ist dabei nur der Schlüssel der Unterrichtsart relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis Fachtafeln die Unterrichtsart zuweisen können. 

Folgende Unterrichtsarten dürfen im Zeugnisdruck verwendet werden:

Kürzel |  Schlüssel | Zeugnisbereich
--|--|--
AG | AG | Arbeitsgemeinschaft

## Ausdruck

`Ausdruck > DIN A 3 Format, doppelseitig`

Das Zeugnis wird in DIN A3 Format und doppelseitig ausgegeben.
Das Zeugnis/der Bericht muss aus dem Menü `Schüler` gedruckt werden.

## Schule

`Mandanten > Daten > Name 1`

Tragen Sie die Bezeichnung Ihrer Schule im Menü "Mandanten" auf der Registerkarte "Daten 1" im Feld "Name
1" ein.

## Namenszusätze Schule

`Mandanten > Daten > Name 2`

Tragen Sie die Namenszusätze Ihrer Schule im Menü `Mandanten > Daten 1` im Feld "Name 2" ein.

[![Name der Schule, Namenszusätz][12]][12]

[![Eintragungen in Magellan][13]][13]

## Ort des Druckdatums

`Mandanten > Daten 1 > Ort`

Der Ort des Druckdatums ergibt sich aufgrund der Eintragung im Menü `Mandanten > Daten 1` im Feld "Ort".


## Schulleiter, Klassenleiter

`Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter `Mandanten > Daten1` im Feld "Schulleiter" eingetragen werden. Bitte achten Sie darauf, das dem zugrunde liegenden Lehrereintrag ein Geschlecht unter `Lehrer > Daten1` zugewiesen wurde.

`Klassen > Zeiträume > Zeitraum > Klassenleiter`

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü `Klassen > Zeiträume` bei der jeweiligen Klasse im Feld "Klassenleiter" eingetragen werden. Bitte achten Sie darauf, das dem zugrunde liegenden Lehrereintrag ein Geschlecht unter `Lehrer > Daten1` zugewiesen wurde.

`Lehrer > Daten 2 > Dienstbez.`

Die Dienstbezeichnung des Schulleiters/Lehrers tragen Sie im Menü `Lehrer > Daten 2` im Feld "Dienstbez." ein. Grundlage für das Zuweisen einer Dienstbezeichnung bildet das `Schlüsselverzeichnis > Dienstbezeichnungen`.

## Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein. Das Zeugnisdatum kann auch per Sammelzuweisung zugewiesen werden, den Aufruf für die Sammelzuweisung finden Sie am oberen Rand der Karte `Details`.

## Zeugnisbemerkungen

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

`Schüler > Zeugnis > Bemerkungen/Formulare`
`Abitur > Abitur > Zeugnis > Zeugnisbemerkungen`
`Berufsschule > Zeugnisbemerkungen`

Bemerkungen legen Sie entweder im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` ODER im Menü `Abitur > Zeugnis > Zeugnisbemerkungen` ODER `Abitur > Zeugnis > Zeugnisbemerkungen` an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren.  
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
`<<Seine_Ihre>>` | Seine/Ihre (je nach Geschlecht des Schüler)      
`<<seine_ihre>>` |  seine/ihre (je nach Geschlecht des Schüler)  
`<<Ihm_Ihr>>` |  Ihm/Ihr (je nach Geschlecht des Schüler)  
`<<ihm_ihr>>` |  ihm/ihr (je nach Geschlecht des Schüler)  
`<<Seinen_Ihren>>` |  Seinen/Ihnen (je nach Geschlecht des Schüler)  
`<<seinen_ihren>>` |  seinen/ihnen (je nach Geschlecht des Schüler)  
`<<DerSchueler_DieSchuelerin>>` |  Der Schüler/Die Schülerin je nach Geschlecht des Schüler)  
`<<derSchueler_dieSchuelerin>>`  | der Schüler/die Schülerin  (je nach Geschlecht des Schüler)  
`<<DemSchueler_DerSchuelerin>>`  |  Dem Schüler/Der Schülerin (je nach Geschlecht des Schülers)

## Enbrea Lernleistungen

Eine Anleitung zum Erfassen von Daten, die in sogenannten komplexen Zeugnisberichten ausgegeben werden, finden Sie [hier](https://doc.magellan.stueber.de/schulverwaltung/howto/enbrea.leistungen/).

`Datenbank > Optionen > Enbrea`

Um die Funktionalitäten zu aktivieren, setzen Sie bitte das Häkchen unter `Datenbank > Optionen > Enbrea > Enbrea Funktionen` aktivieren.

## Arbeits- und Sozialverhalten

`Klassen > Zeiträume > Leistungsprofile definieren > interner Code > ASV`

Bitte weisen im Menü `Klassen > Zeiträume` über die Schalfläche "Leistungsprofile definieren" den Fächern (Name) Sozialverhalten und Arbeitsverhalten im Feld "Interner Code" den Eintrag "ASV" zu.

## Fachpositionen

`Schüler > Zeugnis > Enbrea Leistungen> Position`

Für die Sortierung der Fächer auf sogenannten komplexen Zeugnisberichten muss im Menü `Schüler > Zeugnis > Enbrea Leistungen` pro Fach/Name eine Position in der Spalte "Position" angegeben werden.

