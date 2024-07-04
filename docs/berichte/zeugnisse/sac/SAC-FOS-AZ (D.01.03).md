# SAC-FOS-AZ (D.01.03)

D.01.03 Abgangszeugnis der Fachoberschule

## Fachstatus 

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.
Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Bezeichnung
--|--|--
FA | FA | Facharbeit
FachP | FachP | Fachpraxis im Berufsfeld
Pflicht | Pflicht | Pflichtfach

## Fächerpositionierung

`Schüler > Zeugnis > Fächer > Position`

Für die Sortierung der Fächer auf den Zeugnissen muss im Menü `Schüler > Zeugnis > Fächer` pro Fach eine Position in der Spalte "Position" angegeben werden. Bei der Ausgabe der Fächer auf dem Zeugnis werden die geraden Positionen in der rechten Spalte und die ungeraden Positionen in der linken Spalte ausgegeben. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis der Fachtafeln unter `Schlüsselvezeichnis > Fachtafeln` die Zeugnisposition zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Position nicht pro Schüler und pro Fach vornehmen.

## Fachrichtung der Fachoberschule

`Extras > Schlüsselverzeichnis > Bildungsgänge`

Die Fachrichtung entspricht dem Bildungsgang des Schülers bzw. der Klasse. 

Weisen Sie entweder dem Schüler (wenn innerhalb einer Klasse Schüler mit unterschiedlichen Fachrichtungen sind) oder der Klasse den Bildungsgang zu. Jeder Bildungsgang hat eine entsprechende Fachrichtung. Der Bericht fragt die Bezeichnung des Bildungsganges ab.

[![Fachrichtung des Bildungsganges][2]][2]

[![Fachrichtung des Bildungsganges - Schüler][3]][3]
[![Fachrichtung des Bildungsganges - Klasse][4]][4]


[2]:/assets/images/sachsen/sac03.png "Fachrichtung"
[3]:/assets/images/sachsen/sac04.png "Fachrichtung des Schülers"
[4]:/assets/images/sachsen/sac05.png "Fachrichtung der Klasse"


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

## Beurteilungsart Klasse

`Klassen > Daten > Beurteilungsart > Benotung durch Noten`

Im Menü "Klassen" muss bei der Klasse des Schülers auf der Registerkarte Daten im Feld "Beurteilungsart" "Benotung durch Noten" angegeben sein.

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

## Zeugnisbemerkungen vordefinieren

`Extras > Schlüsselverzeichnisse > Zeugnisbemerkungen`

Zeugnisbemerkungen können im `Schlüsselverzeichnis > Zeugnisbemerkungen` vordefiniert werden oder beim Schüler individuell formuliert werden.

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

## Facharbeit

`Schlüsselverzeichnis > Fächer`

Facharbeit (Thema und Note der Facharbeit): Unter Schlüsselverzeichnisse > Fächer muss ein beliebiges Fach angelegt werden (z.B. Facharbeit). Ordnen Sie dem Schüler dieses Fach unter Zeugnis > Fächer zu und tragen Sie im Feld "Fachstatus" den Wert "FA" zu. Grundlage bildet das `Schlüsselverzeichnis > Fachstatus`.

Die Note der Facharbeit tragen Sie unter Zeugnis > Leistungen im Feld "Endote" ein.
Das Thema der Facharbeit tragen Sie unter "Zeugnis > Leistungen“ im Feld "Beurteilung" ein.

## vordefinierte Zeugnisbemerkung

`Schüler > Zeugnis > Bemerkungen/Formulare`

Um auf dem Zeugnis die Bemerkung "Abschlussprüfung "ERSTMALIG / ENDGÜLTIG" nicht bestanden / Wiederholung "EINMALIG / NICHT" auszuweisen, tragen Sie im Menü Schüler > Zeugnis > Bemerkungen/Formulare den entsprechenden Bemerkungstext ein.

## Schuform Klasse 

`Extras > Schlüsselverzeichnis > Schulformen`

Grundlage für die Ausgabe "EINJÄHRIGEN / ZWEIJÄHRIGEN" Bildungsgang bildet das `Schlüsselverzeichnis > Schulformen`. Tragen Sie die Schulform im Menü `Klassen > Daten` im Feld „Schulform“ ein.
Abgefragt wird der Schlüssel!

Bsp.:

Kürzel | Schlüssel | Bezeichnung
--|--|--
FOS 12L(v) | 14 | Fachoberschule 12L
FOS 12L(t)| 15 | Fachoberschule 12L
FOS/FOS | 140 | Fachoberschule

