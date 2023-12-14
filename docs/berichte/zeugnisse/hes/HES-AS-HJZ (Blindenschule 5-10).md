# HES-AS-HJZ (Blindenschule 5-10)

![HES-AS-HJZ (Blindenschule 5-10)](assets/images/hes/001.png)

## Ausdruck

Der Bericht wird aus dem Menü Schüler ausgegeben, bitte markieren Sie die gewünschten Schüler in der Liste und drücken dann `STRG+Z` oder wählen `Start > Drucken > Zeugnisse drucken`.

## Schulart

`Klassen > Merkmale > MerkmalA6`<br/>`Extras > Schlüsselverzeichnisse > Merkmale (Klassen)`

Die Bezeichnung der Schulart, zum Beispiel ob berufliches oder normales Gymnasium, weisen Sie der jeweiligen Klasse im Menu `Klassen > Merkmale > Merkmal A6` zu. Grundlage bildet das Schlüsselverzeichnis `Extras > Schlüsselverzeichnisse > Merkmale (Klassen)` und ausgegeben wird die Bezeichnung.

## Klassenjahrgang

`Klassen > Zeiträume > Jahrgang`

Im entsprechenden Zeitraum muss im Menü Klassen bei der Klasse des Schülers auf der Registerkarte "Zeiträume" unter "Zeitraum" der Jahrgang im Feld "Jahrgang" angegeben sein.

## Beurteilungsart

`Klassen > Daten > Beurteilungsart`

Die Beurteilungsart der Klassen muss bitte auf Noten gestellt werden.

## Noten

`Schüler > Zeugnis > Leistungen`

Die Note je Fach wird im Feld `Endnote` erwartet.

## Fehlzeiten

`Schüler > Zeugnis > Details`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü "Schüler" auf der Registerkarte "Zeugnis" unter "Details" in den Feldern Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

## Fachstatus

`Schüler > Zeugnis > Fächer`<br/>`Extras Schlüsselverzeichnisse > Fachtafeln`<br/>`Extras Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü "Schüler" auf der Registerkarte "Zeugnis" unter "Fächer" den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden.
Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis der Fachtafeln unter `Extras Schlüsselverzeichnisse > Fachtafeln` den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das Schlüsselverzeichnis `Extras Schlüsselverzeichnisse > Fachstatus`. Wenn Sie dann den Schülern
diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen. Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel|Schlüssel|Zeugnisbereich
--|--|--
WahlPF|WahlPF|Wahlpflichtfach

## Position

`Schüler > Zeugnis > Fächer > Position`

Für die Sortierung der Fächer auf den Zeugnissen muss im Menü "Schüler" bei jedem Schüler auf der Registerkarte "Zeugnis" unter "Fächer" pro Fach eine Position in der Spalte "Position" angegeben werden. Bei der Ausgabe der Fächer auf dem Zeugnis werden die geraden Positionen in der rechten Spalte und die ungeraden Positionen
in der linken Spalte ausgegeben. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis der Fachtafeln unter ``Extras > Schlüsselverzeichnisse > Fachtafeln`` die Zeugnisposition zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Position nicht pro Schüler und pro Fach vornehmen.

## Schulleiter

`Lehrer > Daten > Geschlecht`<br/>`Mandant > Daten > Schulleiter`

Der Schulleiter muss unter Mandanten im Register "Daten1" im Feld "Schulleiter" eingetragen werden. Bitte prüfen Sie, ob für den Lehrer auf den Sie verweisen, das Geschlecht eingetragen ist.

## Klassenlehrer

`Klassen > Zeiträume > Klassenleiter1`<br/>`Lehrer > Daten > Geschlecht`

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü "Klassen" bei der jeweiligen Klasse in der Registerkarte "Zeiträume" im Feld "Klassenleiter" eingetragen werden.

## Zeugnisdatum

`Schüler > Zeugnis > Zeugnisdetails`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü "Schüler" auf Registerkarte "Zeugnis" unter "Details" im Feld "Zeugnisdatum" eingetragen sein. Hierfür können Sie auch die Sammelzuweisung verwenden, die Ihnen auf der Karte mit angeboten wird.

## Zeugnisbemerkungen

`Schüler > Zeugnis > Zeugnisbemerkungen`<br/>`Extras > Schlüsselverzeichnisse > Zeugnisbemerkungen`

### Position

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü "Schüler" auf der Registerkarte "Zeugnis" unter "Zeugnis". Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen. Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung)
vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

### Platzhalter

Bemerkungen legen Sie unter `Schüler > Zeugnis > Zeugnisbemerkungen` an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren.  
Einen Platzhalter definieren Sie über „<<“ zum Beginn und „>>“ zum Ende Ihres Platzhalters, z.B.  So <<hier steht Ihr Platzhalter>>.  

Möglich sind:

``<<Name>>  ``             -->   Vorname, Vorname2, Namenszusatz und Nachname des Schülers
``<<Nachname>> ``      -->    Nachname des Schülers
``<<Vorname>>  `` 	      --->		   Vorname, Vorname2 und Namenszusatz des Schülers
``<<Anrede1>> ``        	--->		    Er/Sie 		(je nach Geschlecht des Schülers)
``<<Anrede2>> ``        	---> 		   er/sie 		(je nach Geschlecht des Schülers)
``<<Anrede3>>   ``      	--->    		seine/ihre	 (je nach Geschlecht des Schülers)
``<<Anrede4>>  ``       	---> 		    ihm/ihr		 (je nach Geschlecht des Schülers)
``<<Anrede5>>    ``     	---> 	    	seinen/ihren	 (je nach Geschlecht des Schülers)
  

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         
