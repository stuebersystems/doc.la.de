# NRW-APO-OS-2020

Diese Anleitung wird aktuell noch überarbeitet!!!

## Verordnung und Gültigkeit

Quelle:

```
Abiturqualifikationsberechnung Nordrhein-Westfalen
Oberstufen-Kolleg an der Universität Bielefeld 
Abiturprüfungsordnung vom 20. Juni 2002 in der letzten Änderung vom 01. Mai 2020 
```

## Feld Status

Dieses Skript kann die Gesamtqualifikation und die Fachhochschulreife berechnen. Bitte verwenden Sie dabei beim Auslösen des Skriptes unter `Abitur > Qualifikation` im Feld `Status` die Unterpunkte `Gesamtqualifikation berechnen` oder `Fachhochschulreife berechnen`.

## Verzeichnis Verordnungen

Bitte legen Sie unter `Verzeichnisse > Verordnungen` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

|Spalte|Wert|
|--|--|
|Kürzel|beliebig|
|Bezeichnung|beliebig|
|Kategorie|Abitur|
|Typ|leer|
|Ab Jahrgang|leer|
|Skript|```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server)|
|Notenart 11|Noten oder Punkte|
|Notenart 12|Punkte|
|Notenart 13|Punkte|
|Notenart 13|Punkte|
|Notenart BBS|leer|
|Gültig von |leer|
|Gültig bis|leer|

![Beispiel für Eintrag im Verzeichnis Verordnungen](\assets\images\nrw\02.png)

## Fachkategorien

Berechnungsskripte erkennen relevante Fächer anhand der Eintragungen unter `Extras > Schlüsselverzeichnisse > Fächer > Fachkategorie`. 
Dabei müssen, je nach Verordnung, einige Fächer besonders berücksichtigt werden. Für diese Fächer sind die zu verwendenden Fachkategorien fest vorgeschrieben. Alle anderen Fächer können mit einer der übrigen Fachkategorie gekennzeichnet werden oder ohne Fachkategorie geführt werden.

|Fachkategorien|Muss genutzt werden|
|--|--|
|Fremdsprache|**Ja**|
|Religion/Ethik|**Ja**|
|Deutsch|**Ja**|
|Mathematik|**Ja**|
|Kunst|**Ja**|
|Musik|Nein|
|Sport|**Ja**|
|Informatik|**Ja**|
|Philosophie|Nein|
|Geschichte|**Ja**|
|Physik|**Ja**|
|Chemie|**Ja**|
|Biologie|**Ja**|
|Erdkunde|**Ja**|
|Sozialkunde|Nein|
|Wirtschaft|**Ja**|
|Politik|**Ja**|
|Darstellendes Spiel|Nein|
|Evangelische Religion|Nein|
|Katholische Religion|Nein|
|Technik|Nein|
|Pädagogik|**Ja**|
|Sporttheorie|Nein|
|BWL/RW|Nein|
|BWL/VWL|Nein|
|VWL|Nein|
|Seminar|**Ja**|
|Gesundheit|Nein|
|Psychologie|**Ja**|
|Recht|**Ja**|
|Literatur|**Ja**|

## Aufgabenbereiche

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter `Verzeichnisse > Fächer > Spalte Aufgabenbereich` verwendet werden:

|Aufgabenbereich|
|--|
|sprachl.-lit.-künstlerisch|
|gesellschaftswiss.|
|mathem.-nat.-technisch|
|Religion|
|Sport|

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel |Schlüssel |Bedeutung|
|--|--|--|
|1PF |1PF |1. Prüfungsfach|
|2PF |2PF |2. Prüfungsfach|
|3PF |3PF |3. Prüfungsfach|
|4PF |4PF |4. Prüfungsfach|
|5PF |5PF |5. Prüfungsfach|
|Pflicht|Pflicht|Pflichtbereich|

## Unterrichtsarten

Die Unterrichtsart muss unter ```Abitur > Qualifikation > Unterrichtsart``` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Unterrichtsart``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

Die Kürzel und Bezeichnungen sind frei wählbar, das Skript prüft die in der Spalte `Schlüssel` hinterlegten Werte, hier dürfen nur die nachstehenden Werte genutzt werden.

Kürzel|Schlüssel|Bezeichnung
--|--|--
Ba|**GK**|Basiskurs
Bü|**GK**|Brückenkurs
Ge|**GK**|Grundkurs der Eingangsphase
Gh|**GK**|Grundkurs der Hauptphase
GK|**GK**|Grundkus
Ges|**LK**|Studienfachbezogneer Grundkurs der Eingangsphase
Sf|**LK**|Studienfachkurs
Pr|**PR**|Projekt

## Merkmal

Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden.

|Merkmal|Bedeutung|
|--|--|
|A| Fremdsprache Anfänger (2 Kurse müssen eingebracht werden)|

## Leistungsarten

Für jedes Fach kann für jedes Kurshalbjahr eine Leistungsart zugewiesen werden. Die Leistungsart kann bereits unter `Schüler > Zeugnis > Leistungen` zugewiesen und auf die Karte `Abitur > Qualifikation` per Synchronisation übertragen werden. Alternativ können Sie die Angabe auch direkt auf der Karte `Abitur > Qualifikation` vornehmen.

Legen Sie in dem Verzeichnis Ihre gewünschten Leistungsarten an, vergeben Sie für jeden Eintrag bitte eine Eingabe in der Spalte `Leistungsart-Art`. Zur Auswahl stehen `mündlich`, `schriftlich` oder `praktisch`. 

!!! danger "Achtung"

    Das Skript erkennt Klausuren am vergebenen Kürzel und der Art.

Kürzel|Bezeichnung|Leistungsart
--|--|--
**Klausur**|Klausur|**schriftlich**

![Beispiel für angelegte Leistungsarten](\assets\images\nrw\01.png)

