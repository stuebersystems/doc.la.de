# NRW-BK-AZ (Anlage D30)

## Jahrgang Klasse

`Klassen > Zeiträume > Zeitraum > Jahrgang`

Im entsprechenden Zeitraum muss im Menü `Klassen > Zeiträume` bei der Klasse des Schülers der Jahrgang im Feld "Jahrgang" eingetragen sein.

## Zeugniskonferenzdatum

`Schueler > Zeugnis > Details > Zeugniskonferenz am`

Im entsprechenden Zeitraum muss das Datum der Zeugniskonferenz im Menü `Schüler > Zeugnis > Details` im Feld "Zeugniskonferenz am" eingetragen sein.

## Unterrichtsarten

`Extras > Schlüsselverzeichnisse > Unterrichtsarten`

Die korrekte Ausgabe der Zeugnisbereiche wird im Menü `Schüler > Zeugnis > Fächer` im Feld "Unterrichtsart" ausgewählt. Grundlage bildet das `Schlüsselverzeichnis > Unterrichtsarten`. Für den Zeugnisdruck ist dabei nur der Schlüssel der Unterrichtsart relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis Fachtafeln die Unterrichtsart zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Unterrichtsart nicht pro Schüler und pro Fach vornehmen.

Folgende Unterrichtsarten dürfen im Zeugnisdruck verwendet werden:

Kürzel |  Schlüssel | Zeugnisbereich
--|--|--
BU | BU | Berufsbezogener Lernbereich 
BÜ | BÜ | Berufsübergreifender Lernbereich
DB | DB | Differenzierungsbereich

## Bildungsgang der Klasse

`Klassen > Daten > Bildungsgang`

Weisen Sie unter `Klassen > Daten` im Feld "Bildungsgang" zu. Grundlage bildet das `Schlüsselverzeichnis > Bildungsgänge`.

## SchulleiterIn  

`Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter `Mandanten > Daten1` im Feld "Schulleiter" eingetragen werden. Bitte achten Sie darauf, das dem zugrunde liegenden Lehrereintrag ein Geschlecht unter `Lehrer > Daten1` zugewiesen wurde.

## Zeiträume

`Extras > Schlüsselverzeichnis > Zeiträume > Ausdruck 1`

Die Ausgabe des Schuljahres erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN `Schlüsselverzeichnis > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck1".

## Versetzung

`Schüler > Laufbahn > Allgemein > Versetzt`

Im entsprechenden Zeitraum muss der Versetzungsvermerk im Menü `Schüler > Laufbahn > Allgemein` im Feld "Versetzt" eingetragen sein.

## Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Schüler` gedruckt werden.

## Zeugnisbemerkungen Positionierung

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

## Dienstbez 

`Lehrer > Daten 2 > Dienstbez.`

Die Dienstbezeichnung des Schulleiters/Lehrers tragen Sie im Menü `Lehrer > Daten 2` im Feld "Dienstbez." ein. Grundlage für das Zuweisen einer Dienstbezeichnung bildet das `Schlüsselverzeichnis > Dienstbezeichnungen`.

## Mandanten / Ort

`Mandanten > Daten 1 > Ort`

Der Schulort (bzw. Ausstellungsort) ergibt sich aufgrund der Eintragung im Menü `Mandanten > Daten 1` im Feld „Ort“.

## Ausdruck

`Ausdruck`

Der Bericht muss aus dem Menu `Drucken > Zeugnis Drucken` (Strg + Z) gedruckt werden.

## von / bis-Datum

`Extras > Schlüsselverzeichnisse > Zeiträume > Von / Bis`

Die Ausgabe des "vom" und "bis" Datums erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN im `Schlüsselverzeichnis > Zeiträume`. Ausgegeben wird hierbei der Eintrag in den Spalten "von" und "bis".

## Zeugnisbemerkungen

`Schüler > Zeugnis > Bemerkungen/Formulare`

Sie können Zeugnisbemerkungen über Platzhalter personalisieren und Anreden und Namen des Schülers auf dem Zeugnis ausgeben.  
Einen Platzhalter definieren Sie über „``<<“ zum Beginn und „>>``“ zum Ende Ihres Platzhalters, z.B.  so ``<<hier steht Ihr Platzhalter>>``.  

Möglich sind:

Platzhalter | Ausgabe im Bericht
--|--
``<<Vorname>>`` | Vorname des Schülers
``<<Nachname>>`` | Nachname des Schülers
``<<Frau>>`` |  Frau
``<<Sie>>`` | Sie
``<<Herr>>`` | Herr
``<<Herrn>>`` | Herrn
``<<Er>>`` | Er

## Religion

`Schüler > Zeugnis > Fächer > Religion`

Beachten Sie bei der Benotung des Faches „Religion“ folgende 4 Fälle:

Eintrag in Spalte „Note“ | Ausgabe „Religion“ | Ausgabe „Note“
--|--|--|--
1-6 | Religion | 0-15
 „–„    (minus)##   | Religion (durchgestrichen)##  | keine Ausgabe
„ab“  (abgewählt)##  | Religion |  „----„
Leer  | kein Eintrag | kein Eintrag

## Zeugnisbemerkungen

`Abitur > Zeugnisbemerkungen`

`Schüler > Zeugnis > Bemerkungen/Formulare`

Bemerkungen Legen Sie im MenüSchüler > Zeugnis > Bemerkungen/Formulare oder im Menü Abitur > Zeugnisbemerkungen an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren.  
Einen Platzhalter definieren Sie über „``<<“ zum Beginn und „>>``“ zum Ende Ihres Platzhalters, z.B.  So ``<<hier steht Ihr Platzhalter>>``.  

Möglich sind:

Platzhalter | Ausgabe im Bericht
--|--
``<<Name>>`` | Vorname, Vorname2, Namenszusatz und Nachname des Schülers
``<<Nachname>>`` | Nachname des Schülers
``<<Vorname>>`` | Vorname, Vorname2 und Namenszusatz des Schülers
``<<Anrede1>>`` | Er/Sie (je nach Geschlecht des Schülers)
``<<Anrede2>>`` | er/sie (je nach Geschlecht des Schülers)
``<<Anrede3>>`` | seine/ihre (je nach Geschlecht des Schülers)
``<<Anrede4>>`` |  ihm/ihr (je nach Geschlecht des Schülers)
``<<Anrede5>>`` | seinen/ihren (je nach Geschlecht des Schülers)