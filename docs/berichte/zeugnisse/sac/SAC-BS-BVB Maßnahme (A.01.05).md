# SAC-BS-BVB Maßnahme (A.01.05)

A.01.05 Berufsvorbereitende Bildungsmaßnahme der Bundesagentur für Arbeit

## Beurteilungsart Klasse

`Klassen > Daten > Beurteilungsart > Benotung durch Noten` 

Im Menü `Klassen > Daten` muss bei der Klasse des Schülers im Feld Beurteilungsart `Benotung durch Noten` angegeben sein. (hierbei steht auch ein Feld für die schriftliche Beurteilung des Fachs zur Verfügung)

## Fachstatus 

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.
Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Bezeichnung
--|--|--
WahlPF | WahlPF | Wahlpflichtfach
Pflicht | Pflicht | Pflichtfach
BerufS | BerufS | Berufsbezogener Lernbereich

## Schulname 

`Mandanten > Daten > Name 1`

Tragen Sie die Bezeichnung Ihrer Schule im Menü "Mandanten" auf der Registerkarte "Daten 1" im Feld "Name
1" ein.

## SchulleiterIn 

`Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter `Mandanten > Daten1` im Feld ""Schulleiter"" eingetragen werden.

## KlassenleiterIn 

`Klassen > Zeiträume > Zeitraum > Klassenleiter`

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü `Klassen > Zeiträume` bei der jeweiligen Klasse im Feld ""Klassenleiter"" eingetragen werden.

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

## Endnote

`Schüler > Zeugnis > Leistungen > Endnote`

Die Noten der Fächer tragen Sie im Menü `Schüler > Zeugnis > Leistungen` in der Spalte "Endnote" ein. Grundlage bildet das `Schlüsselverzeichnis > Noten`.

## Noten wie o.B., n.B. oder sonstiges

`Schlüsselverzeichnisse > Noten > Füllwerte`

Um ein Fach mit einem bestimmten Füllwert (z.B. "oB" (ohne Bewertung)) auf dem Zeugnis auszugeben, müssen Sie unter `Schlüsselverzeichnisse > Noten` die Noten wie folgt anlegen. Auf dem Zeugnis wird das "Kürzel" ausgegeben.

Kürzel | Bezeichnung | Notenart
--|--|--
beliebig | beliebig | Füllwerte
oB | ohne Bewertung | Füllwerte

## Mandanten / Ort

`Mandanten > Daten 1 > Ort`

Der Schulort (bzw. Ausstellungsort) ergibt sich aufgrund der Eintragung im Menü `Mandanten > Daten 1` im Feld „Ort“.

## Differenzierung berufsbezogene Bereiche 

`Schüler > Zeugnis > Fächer > Gruppe`

Unterschiedliche berufsbezogene Bereiche differenzieren Sie, indem Sie den "Berufsbezogenen Bereich" den jeweiligen Fächern im Menü `Schüler > Zeugnis > Fächer` im Feld "Gruppe" zuweisen. Grundlage dafür bildet das `Schlüsselverzeichnis > Fachgruppen`. Beachten Sie zudem, dass sie den berufsbezogenen Fächern ausserdem den Fachstatus "BerufS" zuweisen.

## Zeugnisbemerkungen

 `Schüler > Zeugnis > Bemerkungen/Formulare` / `Abitur > Abitur > Zeugnis > Zeugnisbemerkungen`ODER
`Berufsschule > Zeugnisbemerkungen`

Bemerkungen legen Sie entweder im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` ODER im Menü `Abitur > Zeugnis > Zeugnisbemerkungen` ODER `Abitur > Zeugnis > Zeugnisbemerkungen` an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren.  
Einen Platzhalter definieren Sie über „<<“ zum Beginn und „>>“ zum Ende Ihres Platzhalters, z.B.  So `<<hier steht Ihr Platzhalter>>`.  

Möglich sind:

Platzhalter in MAGELLAN | Anzeige im Bericht
--|--
``<<Vorname>>`` | Vorname Vorname2
``<<Nachname>>`` | Nachname
``<<NachnameV>>`` | Namenszusatz Nachname
``<<Name>>`` | Vorname Vorname2 Namenszusatz Nachname
``<<Name>>`` | Vorname, Vorname2, Namenszusatz und Nachname des Schülers
``<<Nachname>>``  |  Nachname des Schülers
``<<Vorname>>`` |  Vorname, Vorname2 und Namenszusatz des Schülers
``<<Er_Sie>>`` |  Er/Sie (je nach Geschlecht des Schülers)
``<<Seine_Ihre>>`` | Seine/Ihre (je nach Geschlecht des Schülers)     
``<<seine_ihre>>`` |  seine/ihre (je nach Geschlecht des Schülers) 
``<<Ihm_Ihr>>`` |  Ihm/Ihr (je nach Geschlecht des Schülers) 
``<<ihm_ihr>>`` |  ihm/ihr (je nach Geschlecht des Schülers) 
``<<Seinen_Ihren>>`` |  Seinen/Ihnen (je nach Geschlecht des Schülers) 
``<<seinen_ihren>>`` |  seinen/ihnen (je nach Geschlecht des Schülers) 
``<<DerSchueler_DieSchuelerin>>`` |  Der Schüler/Die Schülerin je nach Geschlecht des Schülers)
``<<derSchueler_dieSchuelerin>> `` | der Schüler/die Schülerin  (je nach Geschlecht des Schülers) 
``<<DemSchueler_DerSchuelerin>> `` |  Dem Schüler/Der Schülerin (je nach Geschlecht des Schülers)

