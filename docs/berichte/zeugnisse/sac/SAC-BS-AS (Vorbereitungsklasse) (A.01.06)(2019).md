# SAC-BS-AS (Vorbereitungsklasse) (A.01.06)(2019)

`Archiv`

A.01.06 (2019)

## Benotung in Klassen

`Klassen > Daten > Beurteilungsart > Benotung durch Noten`  

Im Menü `Klassen > Daten` muss bei der Klasse des Schülers im Feld Beurteilungsart   `Benotung durch Noten` angegeben sein. (hierbei steht auch ein Feld für die schriftliche Beurteilung des Fachs zur Verfügung) 

## Fachstatus 

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.
Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
Wahlb | Wahlb | Wahlfächer bzw. –bereich
Pflicht | Pflicht | Pflichtfach
Praktikum | Praktikum | Praktikum

## Zugang am / Abgang am 

`Schueler > Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü Schüler > Daten 2 im Feld "Zugang am" bzw. "Abgang am" ein.

## Schulname 

`Mandanten > Daten > Name 1`

Tragen Sie die Bezeichnung Ihrer Schule im Menü "Mandanten" auf der Registerkarte "Daten 1" im Feld "Name
1" ein.

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

## Anzahl der Wochen für Praktikum/Berufspraktische/Praktische Ausbildung

`Schüler > Zeugnis > Fächer`

Die Anzahl der Wochen für das Praktikum bzw. für die Berufspraktische/Praktische Ausbildung weisen Sie einem Fach "Praktikum" bzw. "Berufspraktische/Praktische Ausbildung" im Menü `Schüler > Zeugnis > Fächer` im Feld "Merkmal" zu.

## Bildungsgang und Dauer der „Teilintegration in der Berufsschule“


Den Bildungsgang und die Dauer der „Integration in der Berufsschule“ legen Sie wie folgt an:
1) Definieren Sie ein Fach im Schlüsselverzeichnis > Fächer, weisen Sie dieses im Menü `Schüler > Zeugnis > Fächer` dem Schüler zu. Zusätzlich erhält dieses Fach im Feld "Fachstatus" „Praktikum“ zu. 
2) Diesem Fach weisen Sie im Menü `Schüler > Zeugnis > Fächer` im Feld "Zusatzklasse" die Klasse zu, wo der erfolgte „Bildungsgang“ hinterlegt ist.
3) Die Anzahl der Wochen für die „Integration in der Berufsschule“ weisen Sie im Menü `Schüler > Zeugnis > Fächer` im Feld "Merkmal" zu..

## Personalisierung Zeugnisbemerkungen
 
`Schüler > Zeugnis > Bemerkungen/Formulare` / `Abitur > Abitur > Zeugnis > Zeugnisbemerkungen` / `Berufsschule > Zeugnisbemerkungen`

Bemerkungen legen Sie entweder im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` ODER im Menü `Abitur > Zeugnis > Zeugnisbemerkungen` ODER `Abitur > Zeugnis > Zeugnisbemerkungen` an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren. 
Einen Platzhalter definieren Sie über „``<<“ zum Beginn und „>>``“ zum Ende Ihres Platzhalters, z.B. So ``<<hier steht Ihr Platzhalter>>``. 

Möglich sind:

Platzhalter in Magellan | Anzeige im Bericht
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

## vordefinierte Zeugnisebemerkungen 

`Schüler > Zeugnis > Bemerkungen/Formulare`

Die Bemerkung "Die Beendigung der Berufsschulpflicht gemäß § 28 Absatz 5 Satz 2 SächsSchulG bleibt unberührt." wird standardmäßig auf den Zeugnissen ausgegeben.


