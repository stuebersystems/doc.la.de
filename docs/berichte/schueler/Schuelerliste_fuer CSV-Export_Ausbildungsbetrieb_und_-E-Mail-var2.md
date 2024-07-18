# Schülerliste (für CSV-Export) Ausbildungsbetrieb und -E-Mail(Var2)

[01]:/assets/images/schueler/002.var2.png "Bericht"
[02]:/assets/images/schueler/005.png "Vorschau"
[03]:/assets/images/schueler/006.png "Speichern"
[04]:/assets/images/schueler/007.png "4"
[05]:/assets/images/schueler/008.png "5"
[06]:/assets/images/schueler/009.png "6"
[07]:/assets/images/schueler/010.png "7"
[08]:/assets/images/schueler/011.png "8"
[09]:/assets/images/schueler/004.png "aktueller Betrieb"

[![Bericht][01]][01]

Der Bericht ist nicht für den Druck gedacht, sondern dient dazu, die aus Magellan gelesenen Daten aus der Berichtsvorschau heraus als Excel-Datei zu exportieren, die abschließend als CSV-Datei gespeichert werden kann.

## Aufruf

Der Bericht kann aus dem Menü `Schüler` heraus in der Vorschau aufgerufen werden. Markieren Sie die gewünschten Schüler, klicken `STRG+P` oder wählen `Start > Drucken > Berichte drucken` und wählen dann die `Vorschau` (`STRG+V`).

## Ausgabe

Der Bericht erzeugt je markierten Schüler eine Datenzeile (ohne Kopfzeile). 
Als aktueller Betrieb wird für den Schüler der Betrieb ausgegeben, der am unteren Fensterrand unter `Schüler > Ausbildung > Ausbildung` erfasst ist. Bitte beachten Sie, dass dieser Wert zeitraumbezogen abweichen kann.

[![aktueller Betrieb][09]][09]

## Daten

Kopfzeile: keine

Datenzeile: <br/>`Schueler.ID;Schueler.Nachname;Schueler.Vorname;Betrieb.Name1;Betrieb.Name2;Betrieb.ID;Betrieb.Email;Betrieb.Telefon;Betriebekontakte.Telefon;Betriebkontakte.Mobil;Klasse.Kürzel;Betriebekontakte.ID;Betriebekontakte.Nachname:Betriebekontakte.Vorname;Betriebkontakte.Email`

Titel|Inhalt
--|--
Schueler.ID|`Schülerauswahlliste > ID`
Schueler.Nachname| `Schüler > Daten1 > Nachname`
Schueler.Vorname| `Schüler > Daten1 > Nachname`
Betrieb.Name1|`Betriebe > Daten > Name1`
Betrieb.Name2|`Betriebe > Daten > Name2`
Betrieb.ID|`Betriebe > Daten > ID`
Betrieb.Email|`Betriebe > Daten > E-Mail`
Betrieb.Telefon|`Betriebe > Daten > Telefon`
Betriebekontakte.Telefon|`Betriebe > Kontakte > Telefon`<br/> Für den dem Schüler unter `Schüler > Ausbildung` für den aktuellen Ausbildungsdatensatz zugeordneten Kontakt
Betriebekontakte.Mobil|`Betriebe > Kontakte > Mobil`<br/> Für den dem Schüler unter `Schüler > Ausbildung` für den aktuellen Ausbildungsdatensatz zugeordneten Kontakt
Klasse.Kürzel| aktuelle Schüler-Klasse, Wert aus `Klassen > Daten > Kürzel`
Betriebekontakte.ID|`Schueler > Ausbildung > Ausbilderkontakt`
BetriebeKontakte.Nachname|`Betriebe > Kontakte > Nachname`<br/> Für den dem Schüler unter `Schüler > Ausbildung` für den aktuellen Ausbildungsdatensatz zugeordneten Kontakt
BetriebeKontakte.Vorname|`Betriebe > Kontakte > Vorname`<br/> Für den dem Schüler unter `Schüler > Ausbildung` für den aktuellen Ausbildungsdatensatz zugeordneten Kontakt
Betriebekontakte.Email|`Betriebe > Kontakte > TelE-Mailefon`<br/> Für den dem Schüler unter `Schüler > Ausbildung` für den aktuellen Ausbildungsdatensatz zugeordneten Kontakt

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
