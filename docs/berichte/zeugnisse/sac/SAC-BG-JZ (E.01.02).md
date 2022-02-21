# SAC-BG-JZ (E.01.02)

E.01.02 Jahreszeugnis des Beruflichen GymnasiumsKlassenstufe 11

## Versetzung Schüler 

`Schüler > Laufbahn > Allgemein > Versetzt`

Im entsprechenden Zeitraum muss der Versetzungsvermerk im Menü `Schüler > Laufbahn > Allgemein` im Feld "Versetzt" eingetragen sein. Entscheidend ist hierbei die Markierung des Zeitraumes im linken Zeitraumfenster.

## Fehltage, Fehlstunden

`Schueler > Zeugnis > Details > Fehltage und/oder Fehlstunden`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern "Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

## Fachstatus 

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.
Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
Wahlb | Wahlb | Wahlfächer bzw. –bereich
Pflicht | Pflicht | Pflichtfach

## Fächerpositionierung

`Schüler > Zeugnis > Fächer > Position`

Für die Sortierung der Fächer auf den Zeugnissen muss im Menü `Schüler > Zeugnis > Fächer` pro Fach eine Position in der Spalte "Position" angegeben werden. Bei der Ausgabe der Fächer auf dem Zeugnis werden die geraden Positionen in der rechten Spalte und die ungeraden Positionen in der linken Spalte ausgegeben. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis der Fachtafeln unter `Schlüsselvezeichnis > Fachtafeln` die Zeugnisposition zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Position nicht pro Schüler und pro Fach vornehmen.

## Schulname 

`Mandanten > Daten > Name 1`

Tragen Sie die Bezeichnung Ihrer Schule im Menü "Mandanten" auf der Registerkarte "Daten 1" im Feld "Name
1" ein.

## Zeiträume 

`Extras > Schlüsselverzeichnis > Zeiträume > Ausdruck 1`

Die Ausgabe des Schuljahres erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN `Schlüsselverzeichnis > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck1".

## Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Schüler` gedruckt werden.

## Zeugnisbemerkungen Positionierung

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

## Benotung 

`Klassen > Daten > Beurteilungsart`

Im Menü "Klassen" muss bei der Klasse des Schülers auf der Registerkarte Daten im Feld "Beurteilungsart" "Benotung durch Punkte" angegeben sein.

## Noten wie o.B., n.B. oder sonstiges

`Schlüsselverzeichnisse > Noten > Füllwerte``

Um ein Fach mit einem bestimmten Füllwert (z.B. "oB" (ohne Bewertung)) auf dem Zeugnis auszugeben, müssen Sie unter `Schlüsselverzeichnisse > Noten` die Noten wie folgt anlegen. Auf dem Zeugnis wird das "Kürzel" ausgegeben.

Kürzel | Bezeichnung | Notenart
--|--|--
beliebig | beliebig | Füllwerte
oB | ohne Bewertung | Füllwerte

## Mandanten / Ort

`Mandanten > Daten 1 > Ort`

Der Schulort (bzw. Ausstellungsort) ergibt sich aufgrund der Eintragung im Menü `Mandanten > Daten 1` im Feld „Ort“.

## Personalisierung Zeugnisbemerkungen
 
`Schüler > Zeugnis > Bemerkungen/Formulare` / `Abitur > Abitur > Zeugnis > Zeugnisbemerkungen` / `Berufsschule > Zeugnisbemerkungen`

Bemerkungen legen Sie entweder im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` ODER im Menü `Abitur > Zeugnis > Zeugnisbemerkungen` ODER `Abitur > Zeugnis > Zeugnisbemerkungen` an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren. 
Einen Platzhalter definieren Sie über „``<<“ zum Beginn und „>>``“ zum Ende Ihres Platzhalters, z.B. So ``<<hier steht Ihr Platzhalter>>``. 

Möglich sind:

Platzhalter in MAGELLAN | Anzeige im Bericht
--|--
``<<VornameV>>`` | Vorname Vorname2
``<<Nachname>>`` | Nachname
``<<NachnameV>>`` | Namenszusatz Nachname
``<<Name>>`` | Vorname Vorname2 Namenszusatz Nachname
``<<Name>>`` | Vorname, Vorname2, Namenszusatz und Nachname des Schülers
``<<Nachname>>`` | Nachname des Schülers
``<<Vorname>>`` | Vorname, Vorname2 und Namenszusatz des Schülers
``<<Er_Sie>>`` | Er/Sie (je nach Geschlecht des Schülers)
``<<Seine_Ihre>>`` | Seine/Ihre (je nach Geschlecht des Schülers)
``<<seine_ihre>>`` | seine/ihre (je nach Geschlecht des Schülers) 
``<<Ihm_Ihr>>`` | Ihm/Ihr (je nach Geschlecht des Schülers) 
``<<ihm_ihr>>`` | ihm/ihr (je nach Geschlecht des Schülers) 
``<<Seinen_Ihren>>`` | Seinen/Ihnen (je nach Geschlecht des Schülers)
``<<seinen_ihren>>`` | seinen/ihnen (je nach Geschlecht des Schülers) 
``<<DerSchueler_DieSchuelerin>>`` | Der Schüler/Die Schülerin je nach Geschlecht des Schülers) 
``<<derSchueler_dieSchuelerin>>`` | der Schüler/die Schülerin (je nach Geschlecht des Schülers)
``<<DemSchueler_DerSchuelerin>>`` | Dem Schüler/Der Schülerin (je nach Geschlecht des Schülers)

## Jahrgang Klasse

`Klassen > Zeiträume > Zeitraum > Jahrgang`

Im entsprechenden Zeitraum muss im Menü Klassen bei der Klasse des Schülers der Jahrgang auf der Registerkarte `Zeiträume > Zeitraum` im Feld "Jahrgang" eingetragen sein.

## Klassenstufe 

`Klassen > Zeiträume > Zeitraum > Klassenstufe`

Im entsprechenden Zeitraum muss im Menü Klassen bei der Klasse des Schülers die Klassenstufe auf der Registerkarte `Zeiträume > Zeitraum` im Feld "Klassenstufe" eingetragen sein.

## Fachrichtung Klasse / Schüler

`Extras > Schlüsselverzeichnisse > Fachrichtungen` UND
`Extras > Schlüsselverzeichnisse > Bildungsänge` 

Um die Fachrichtung der Klasse bzw. die Fachrichtung des Schüler zu bestimmen, gehen Sie bitte wie folgt vor:

1. Fachrichtung: Definieren Sie die Fachrichtungen zunächst im `Schlüsselverzeichnis > Fachrichtungen`. Weisen Sie nun den Bildungsgang im `Schlüsselverzeichnis > Bildungsgänge` im Feld „Fachrichtung“ die entsprechende Fachrichtung zu. 

Die Fachrichtung kann entweder am Bildungsgang der Klasse oder am Bildungsgang des Schülers hängen: 

1. Fachrichtung, Bildungsgang der Klasse: Weisen Sie im Menü `Klassen > Daten` im Feld "Bildungsgang" den Bildungsgang mit der entsprechend zugewiesenen Fachrichtung zu.

3. Fachrichtung, Bildungsgang des Schülers: Weisen Sie im Menü `Schüler > Ausbildung` im Feld "Bildungsgang" den Bildungsgang mit der entsprechend zugewiesenen Fachrichtung dem Schüler zu.

