# NRW-BLNW-OS

## Gültigkeit

Für die Verwendung am Oberstufenkolleg Bielefeld. 

Bitte beachten Sie ergänzend die Voraussetzungen für **Unterrichtsarten, Fachstatus, Fachkategorien und Aufgabenbereiche** für das dazugehörige Berechnungsskript unter [https://doc.la.stueber.de/08.nrw/nrw-apo-os-2020/](https://doc.la.stueber.de/08.nrw/nrw-apo-os-2020/).

## Ausdruck

Bitte markieren Sie die Schüler im Menü `Abitur` oder im Menü `Schüler` und rufen den Bericht über STRG+Z im Unterverzeichnis `Nordrhein-Westfalen` auf. **Der Bericht liest die Fächer und Ergebnisse aus den in das Menü `Abitur` synchronisierten Daten, die Stammdaten aus dem Menü `Schüler`.**

## Welche Fächer werden ausgegeben

`Abitur > Qualifikation > Q1-Q4` <br/>`Abitur > Qualifikation > Q1 Bestanden - Q4 Bestanden`

Es werden nur die Fachzeilen ausgegeben, für die in den Halbjahren Q1-Q4 ein Eintrag unter `Q1 Bestanden`-`Q4 Bestanden` ein Eintrag erfolgte ODER in in einem Halbjahr zwischen Q1 und Q4 ein Punktwert eingetragen wurde.

## Praktikumsbescheinigung

Liegt eine Praktikumsbescheinigung für einen Schüler vor, tragen Sie bitte den Wert `Ja` unter Merkmal-A10 (umbenannt in `Praktikum`), die Bescheinigung gibt den Hinweis aus und unterdrückt den Text "Praktikumsbescheinigung liegt nicht vor".

[![Schülereintrag][2]][2]

[2]:/assets/images/nrw/07.png

Bereiten Sie hierfür bitte einmalig folgende Punkte in Magellan vor:

Feld ``Merkmal A10`` in `Praktikum` umbenennen:

* Öffnen Sie in Magellan bitte den Punkt `Extras > Bezeichnunngen anpassen` und wählen die Zeile für den Bewerber-/Schülereintrag `Merkmal A10` aus. 
* Ersetzen Sie in der Spalte `durch` den Eintrag durch `Praktikum`.
*  Die Ansicht im Programm aktualisiert sich durch einen Wechsel des Menüpunktes, schalten Sie beispielsweise vom Menü `Schüler` auf `Klassen` und wieder zuück.

[![Merkmalsfeld umbenennen][1]][1]

[1]:/assets/images/nrw/06.png

Wert `Ja` im Verzeichnis anlegen:

* Öffnen Sie bitte den Punkt `Extras > Schlüsselverzeichnisse > Merkmale (Schüler)`. 
* Erzeugen Sie über das Plus eine neue Zeile und tragen bitte folgende Werte in die neue Zeile ein. 
* Verbindliich sind die Angaben in den Spalten `Kürzel` und `Bereich`. 
* Speichern Sie den Eintrag und schließen das Verzeichnis.

Kürzel|Schlüssel|Bezeichnung|Bereich
--|--|--|--
**Ja**|leer|Bescheinigung <br/>liegt vor|**Merkmal A10**