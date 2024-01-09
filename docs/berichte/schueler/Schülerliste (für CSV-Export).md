Schülerliste (für CSV-Export).rpt

[1]:/assets/images/berichte.schueler/002.png "Export nach PDF"
[2]:/assets/images/berichte.schueler/003.png "Bericht"

Dieser Bericht ist eine spezielle Anfertigung um Daten im CSV-Format zu erhalten. 

[![Bericht][2]][2]

## Aufruf

Bitte markieren Sie im Menü `Schüler` die gewünschten Datensätze und starten den Druck per STRG+P oder über `Extras > Berichte drucken`.

## Ausgabe

Der Bericht gibt je beim Schüler unter `Daten1 > Familie` zugewiesenen Kontakt (Verweise auf das Menü `Kontakte` (früher Sorgeberechtigte)) eine Zeile aus, also ggfs. mehrere Zeilen. <br/>Schüler, denen kein Kontakt zugewiesen wurde, werden dennoch ausgegeben.

Um die in der Vorschau gezeigten Daten weiter in dieser Form verarbeiten zu können, wählen Sie bitte aus der Druckvorschau den Export als PDF-Datei und speichern an einer beliebigen Stelle. Kopieren Sie anschließend die Zeilen aus der PDF-Datei, fügen Sie in eine Textdatei ein und speichern die Datei für die weitere Verwendung.
Der Weg die Daten aus der Vorschau direkt als Exceldatei oder als CSV-Datei zu speichern ist möglich, führt allerdings nicht zum gleichen Ergebnis.

[![Export nach PDF][1]][1]

## Felder

Titel|Quelle in MAGELLAN
--|--
Schülernr.| `Schüler > Merkmale > MerkmalB1`
Schüler|`Schüler > Daten1 > Vorname` <br/>`Schüler > Daten1 > Vorname` <br/>Ausgabe als `Nachname,Vorname`
Status|`Schüler > Merkmale > MerkmalB1` [Kürzel]
Klasse|`Klassen > Daten > Kürzel`
Anrede|`Kontakte > Daten > Anrede`
Nachname| `Kontakte > Daten > Nachname`
Vorname| `Kontakte > Daten > Vorname`
Zusatz|`Kontakte > Daten > Ergänzung`
Straße|`Kontakte > Daten > Straße`
PLZ|`Kontakte > Daten > PLZ`
Ort|`Kontakte > Daten > Ort`
Land|`Kontakte > Daten > Ortsteil`
Email 1|`Kontakte > Daten > E-Mail`
