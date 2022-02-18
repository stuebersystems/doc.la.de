# MVP-BS-AS-AZ

## Noten

`Klassen > Daten > Beurteilungsart > Beurteilungstexte > Noten`

Im Menü Klassen muss bei der Klasse des Schülers auf der Registerkarte Daten im Feld Beurteilungsart "Noten" angegeben sein.
(hierbei steht auch ein Feld für die schriftliche Beurteilung des Fachs zur Verfügung)

## Zugang am / Abgang am

`Schueler > Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü `Schüler > Daten 2` im Feld "Zugang am" bzw. "Abgang am" ein.

## Unterrichtsarten

`Extras > Schlüsselverzeichnisse > Unterrichtsarten`

Die korrekte Ausgabe der Zeugnisbereiche wird im Menü `Schüler > Zeugnis > Fächer` im Feld "Unterrichtsart" ausgewählt. Grundlage bildet das `Schlüsselverzeichnis > Unterrichtsarten`. Für den Zeugnisdruck ist dabei nur der Schlüssel der Unterrichtsart relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis Fachtafeln die Unterrichtsart zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Unterrichtsart nicht pro Schüler und pro Fach vornehmen.

Folgende Unterrichtsarten dürfen im Zeugnisdruck verwendet werden:

Kürzel |  Schlüssel | Zeugnisbereich
--|--|--
BU | BU | Fachbezogener / Berufsbezogener Lernbereich
BÜ | BÜ | Fachübergreifender / Berufsübergreifender Lernbereich

## Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Schüler` gedruckt werden.

## Zeugnisbemerkungen

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

## Fehlstunden

`Schüler > Zeugnis > Details > Fehlstunden / davon unentschuldigt`

Die Angabe der Fehlstunden muss im entsprechenden Zeitraum im Menü Schüler > Zeugnis > Details in den Feldern „Fehlstunden“ und „davon unentschuldigt“ erfolgen.

## Schulname

`Mandaten > Daten 1 > Name 1, Name 2, Name 3`

Tragen Sie die Bezeichnung, Schulform und Schulort Ihrer Schule im Menü `Mandanten > Daten 1`  in den Feldern „Name 1“, „Name 2“ und „Name 3“ ein.

# Zeugnisbemerkungen

`Abitur > Zeugnisbemerkungen`

`Schüler > Zeugnis > Bemerkungen/Formulare`

Bemerkungen Legen Sie im MenüSchüler > Zeugnis > Bemerkungen/Formulare oder im Menü Abitur > Zeugnisbemerkungen an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren.  
Einen Platzhalter definieren Sie über „``<<“ zum Beginn und „>>``“ zum Ende Ihres Platzhalters, z.B.  So ``<<hier steht Ihr Platzhalter>>``.  

Möglich sind:

Platzhalter | Ausgabe im Bericht
--|--
````<<Name>>```` | Vorname, Vorname2, Namenszusatz und Nachname des Schülers
``<<Nachname>>`` | Nachname des Schülers
``<<Vorname>>`` | Vorname, Vorname2 und Namenszusatz des Schülers
``<<Anrede1>>`` | Er/Sie (je nach Geschlecht des Schülers)
``<<Anrede2>>`` | er/sie (je nach Geschlecht des Schülers)
``<<Anrede3>>`` | seine/ihre (je nach Geschlecht des Schülers)
``<<Anrede4>>`` |  ihm/ihr (je nach Geschlecht des Schülers)
``<<Anrede5>>`` | seinen/ihren (je nach Geschlecht des Schüler
