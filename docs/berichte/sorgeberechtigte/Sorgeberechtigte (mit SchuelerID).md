# Sorgeberechtigte (mit SchuelerID)

[01]:/assets/images/sorgeberechtigte/001.png "Bericht"
[02]:/assets/images/sorgeberechtigte/002.png "Vorschau"
[03]:/assets/images/sorgeberechtigte/003.png "Speichern"
[04]:/assets/images/sorgeberechtigte/004.png "4"
[05]:/assets/images/sorgeberechtigte/005.png "5"
[06]:/assets/images/sorgeberechtigte/006.png "6"
[07]:/assets/images/sorgeberechtigte/007.png "7"
[08]:/assets/images/sorgeberechtigte/008.png "8"

[![Bericht][01]][01]

Der Bericht ist nicht für den Druck gedacht, sondern dient dazu, die aus Magellan gelesenen Daten aus der Berichtsvorschau heraus als Excel-Datei zu exportieren, die abschließend als CSV-Datei gespeichert werden kann.

## Aufruf

Der Bericht kann aus dem Menü `Kontakte` (vormals Sorgeberechtigte) heraus in der Vorschau aufgerufen werden. Markieren Sie die gewünschten Kontakte (vormals Sorgeberechtigte), klicken `STRG+P` oder wählen `Start > Drucken > Berichte drucken` udn wählen dann die `Vorschau` (`STRG+V`).

## Ausgabe

Der Bericht erzeugt eine Kopfzeile und je dem Kontakt zugewiesenen Schüler eine Datenzeile. Beispiel: Kontakt hat zwei Schüler auf der Unterkarte `Schüler`, ergibt in der Ausgabe zwei Zeilen.

## Daten

Kopfzeile:
`Vorname;Nachname;Kind-ID;E-Mail;Adresse;Postleitzahl;Ort`

Datenzeile:
`SB_Vorname;SB_Nachname;S_ID;SB_E-Mail;SB_Adresse (Straße Hausnummer);SB_Postleitzahl;SB_Ort`

Titel|Inhalt
--|--
Vorname|`Kontakte > Daten > Vorname`
Nachname|`Kontakte > Daten > Nachname`
Kind-ID|SchuelerID (`Schueler > Auswahl > ID`) der unter `Kontakte > Schueler` zugeordneten Schüler
E-Mail|`Schueler > Auswahl > E-Mail`
Adresse|Straße und Hausnummer aus `Kontakte > Daten > Straße`
Postleitzahl| `Kontakte > Daten > PLZ`
Ort|`Kontakte > Daten > Ort`

## Weiterverarbeitung

Rufen Sie die Berichtsvorschau auf:

[![Vorschau][02]][02]

Speichern Sie die Daten aus der Berichtsvorschau heraus als "Microsoft Excel - Nur Daten (*.xlsx)"!

[![Speichern][03]][03]

Starten Sie Excel und laden die Datei. Markieren Sie die erste Spalte und rufen Sie den Punkt `Daten > Datentools > Text in Spalten` auf.

[![Speichern][04]][04]

Wählen Sie "getrennt" und klicken auf "Weiter"!

[![Speichern][05]][05]

Aktivieren Sie nur die Auswahl "Semikolon" und klicken auf "Fertigstellen"! Als Ergebnis werden die Daten jetzt spaltenweise dargestellt. Rufen Sie `Datei > Speichern unter` auf und achten bitte darauf, dass Sie als Dateityp wählen "CSV (Trennzeichen-getrennt) (*.csv)"

[![Speichern][06]][06]

[![Speichern][07]][07]

So sieht die fertige Datei aus, wenn Sie sie beispielsweise im Texteditor aufrufen: 

[![Speichern][08]][08]

