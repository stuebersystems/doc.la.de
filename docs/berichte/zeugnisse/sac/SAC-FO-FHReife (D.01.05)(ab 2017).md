# SAC-FO-FHReife (D.01.05)(ab 2017)


D.01.05 Zeugnis über die Zuerkennung der Fachhochschulreife für Schulfremde

## Fachstatus 

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.
Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
Pflicht | Pflicht | Pflichtfach

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

## Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Schüler` gedruckt werden.

## Zeugnisbemerkungen Positionierung

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

## Mandanten / Ort

`Mandanten > Daten 1 > Ort`

Der Schulort (bzw. Ausstellungsort) ergibt sich aufgrund der Eintragung im Menü `Mandanten > Daten 1` im Feld „Ort“.

## Prüfungsvorsitz 

`Schüler > Zeugnis > Details > Prüfungsvorsitz`

Den Prüfungsvorsitz muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` im Feld "Prüfungsvorsitz" eingetragen werden. MAGELLAN greift hier auf das Menü Lehrer zurück.

## automatischen Berechnung der Durchschnittsnote 

`Extras > Schlüsselverzeichnisse > Fächer > Aufgabenbereich`

Da bei der automatischen Berechnung der Durchschnittsnote die Fächer Religion, Ethik und Sport nicht mit einfliessen, ist es zwingend erforderlich den jeweiligen Fächern im `Schlüsselverzeichnis > Fächer` im Feld "Aufgabenbereich" die Werte "Religion" oder "Sport" zuzuweisen.

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

