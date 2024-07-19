# Schülerliste (für CSV-Export) mit Elterndaten.rpt


[01]:/assets/images/schueler/012.png "Bericht"
[02]:/assets/images/schueler/005.png "Vorschau"
[03]:/assets/images/schueler/006.png "Speichern"
[04]:/assets/images/schueler/007.png "4"
[05]:/assets/images/schueler/008.png "5"
[06]:/assets/images/schueler/009.png "6"
[07]:/assets/images/schueler/010.png "7"
[08]:/assets/images/schueler/011.png "8"


[![Bericht][01]][01]

Der Bericht ist nicht für den Druck gedacht, sondern dient dazu, die aus Magellan gelesenen Daten aus der Berichtsvorschau heraus als Excel-Datei zu exportieren, die abschließend als CSV-Datei gespeichert werden kann.

## Aufruf

Der Bericht kann aus dem Menü `Schüler` heraus in der Vorschau aufgerufen werden. Markieren Sie die gewünschten Schüler, klicken `STRG+P` oder wählen `Start > Drucken > Berichte drucken` und wählen dann die `Vorschau` (`STRG+V`).

## Ausgabe

Der Bericht erzeugt je markierten Schüler eine Datenzeile (mit Kopfzeile). 
Sollten in Textfeldern Anführungszeichen oder Semikola enthalten sein (Beispielsweise als Vorname ist "Klaus ; Gregor "; Bertram"), werden diese vom Bericht verdoppelt, damit Excel sie korrekt als Inhalt interpretiert und nicht als Trennzeichen für neue Spalten.
Für die letzten vier Spalten werden jeweils die Daten des ersten und zweiten erfassten Sorgeberechtigtendatensatzes ausgegeben. Hat der Schüler Sorgeberechtigte, werden die Daten des Dritten nicht ausgegeben.

## Daten

Kopfzeile: `"Nachname";"Vorname";"Vorname2";"Klasse";"Jahrgang";"E-Mail Schüler";"Personalnummer";"Geburtsdatum";"Geburtsort";"Staatsangeh1";"Staatsangeh2";"SB.E-Mail1";"SB.Mobil1";"SB.E-Mail2";"SB.Mobil2"`

Datenzeile: <br/>`Schueler.Nachname;Schueler.Vorname;Schueler.Vorname2;Klassen.Kuerzel;KlassenZeitraeume.Jahrgang;Schueler.EMail;Schueler.Personalnr;Schueler.Geburtsdatum;Schueler.Geburtsort;Staatsangehoerigkeiten_1.Kuerzel;Staatsangehoerigkeiten_2.Kuerzel;Sorgeberechtigten.Email1;Sorgeberechtigten.Email2;Sorgeberechtigten.Mobil1;Sorgeberechtigten.Mobil2`

Titel|Inhalt
--|--
Nachname| Schüler > Daten1 > Nachname
Vorname| Schüler > Daten1 > Vorname
Vorname 2| Schüler > Daten1 > 2.Vorname
Klasse| aktuelle Schülerklasse - Kürzel
Jahrgang| Klasse > Zeiträume > Jahrgang
Email Schüler| Schüler > Daten1 > E-Mail
Personalnummer| Schüler > Daten3 > Personalnummer
Geburtsdatum | Schüler > Daten1 > Geboren am
Geburtsort| Schüler > Daten1 > Geburtsort
Staatsangeh 1| Schüler > Daten1 > Staatsangeh1 - Kürzel
Staatsangeh 2| Schüler > Daten1 > Staatsangeh2 - Kürzel
Email (1 Elternteil)| Kontakte > Daten1 > E-Mail 
Mobil (1 Elternteil)| Kontakte > Daten1 > Mobil
Email (2. Elternteil)| Kontakte > Daten1 > E-Mail
Mobil (2 Elternteil) | Kontakte > Daten1 > Mobil

!!! Tipp "Hinweis!"    
    Nachstehend beschreiben wir Ihnen an einem allgemeinen Beispiel eine mögliche Weiterverarbeitung der Inhalte. Die Bilder sind beispielhaft und beziehen sich ggfs. nicht auf diesen Bericht.

## Weiterverarbeitung

Rufen Sie die Berichtsvorschau auf:

[![Vorschau][02]][02]

Speichern Sie die Daten aus der Berichtsvorschau heraus als "Microsoft Excel - Nur Daten (*.xlsx)"!

[![Speichern][03]][03]

Starten Sie Excel und laden die Datei. Markieren Sie die erste Spalte und rufen Sie den Punkt `Daten > Datentools > Text in Spalten` auf.

[![Speichern][04]][04]

Wählen Sie "getrennt" und klicken auf "Weiter"!

[![Speichern][05]][05]

Aktivieren Sie nur die Auswahl "Semikolon" und klicken auf "Fertigstellen"! 

[![Speichern][06]][06]

Als Ergebnis werden die Daten jetzt spaltenweise dargestellt. Rufen Sie `Datei > Speichern unter` auf und achten bitte darauf, dass Sie als Dateityp wählen "CSV (Trennzeichen-getrennt) (*.csv)"

[![Speichern][07]][07]

So sieht die fertige Datei aus, wenn Sie sie beispielsweise im Texteditor aufrufen: 

[![Speichern][08]][08]
