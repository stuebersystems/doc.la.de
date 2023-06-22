# NRW-APO-OS-2020

Nachstehend beschreiben wir die vorausgesetzten Eintragungen in MAGELLAN.

## Verordnung und Gültigkeit

Quelle:

```
Abiturqualifikationsberechnung Nordrhein-Westfalen
Oberstufen-Kolleg an der Universität Bielefeld 
Abiturprüfungsordnung vom 20. Juni 2002 in der letzten Änderung vom 01. Mai 2020 
```

## Skriptfunktionalität

Dieses Skript kann die Gesamtqualifikation und die Fachhochschulreife berechnen. Bitte verwenden Sie dabei beim Auslösen des Skriptes unter `Abitur > Qualifikation` im Feld `Status` die Unterpunkte `Gesamtqualifikation berechnen` oder `Fachhochschulreife berechnen`.

Für den Status `Fachhochschulreife` wählen Sie im Feld `HJ eingebracht` bitte den Zeitraum `Q1-Q2`, `Q2-Q3` oder `Q3-Q4` aus und markieren die gewünschten Kurse.

### Markieren und Berechnen

Um die Gesamtqualifikation und Fachhochschulreife zu berechnen, markieren Sie die gewünschten Kurse. Dafür aktivieren Sie bitte das Häkchen vor `Manuell Markieren` und klicken die gewünschten Kurse an. Die markierten Kurse werden gelb hinterlegt dargestellt.

![Markieren](\assets\images\nrw\04.png)

Klicken Sie auf die Schaltfläche `Berechnen` um Meldung zu erzeugen. Das Meldungsfenster zeigt die Ergebnisse der Prüfungen des Skriptes an, beispielsweise ob die ausreichend Sf-Kurse markiert wurden, ob die Aufgabenbereiche abgedeckt sind, ob genug weitere Kurse markiert wurden, ob mindestens die Hälfte der Leistungen schriftlich erbracht wurden uws.
Wenn Sie andere Kurse markieren möchten, müssten Sie bitte im Anschluss erneut auf die Schaltfläche `Berechnen` klicken, um eine erneute Prüfung auszulösen.

![Berechnen](\assets\images\nrw\05.png)

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
|Musik|**Ja**|
|Sport|**Ja**|
|Informatik|**Ja**|
|Philosophie|**Ja**|
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

## Prüfungen

Prüfungen können für die GH-Kurse des 3. Prüfungsfach und/oder 4. Prüfungsfach auch in mehreren Fächern des gleichen Aufgabenfeldes abgelegt werden. Beide Fächer müssen in MAGELLAN auf der Qualifikationskarte erscheinen und auswertbar markiert werden, da jeweils nur eine Teil der Kurse der jeweiligen Fachzeile als Prüfungsfächer berücksichtigt werden sollen, auf dem Abiturzeugnis aber nur eins der beiden Fächer erscheinen soll.

1. Beide Fachzeilen werden im Feld Status als Prüfungsfach markiert (Fachstatus `3PF` oder `4PF` ).
2. In der Spalte `Merkmal` wird manuell erfasst (Eintragung `Q1Q2` oder `Q3Q4`), welche Kurse je Fachzeile als Prüfungsfachkurse zu werten sind.
3. Für eine der beiden Zeilen wird in der Spalte `Merkmal` hinter der Kennzeichnung der Kurshalbjahre (`Q1Q2` oder `Q3Q4`) mit einem `*` gekennzeichnet, dass dieses Fach auf dem Abiturzeugnis als Prüfungsfach ausgegeben werden soll.

![Darstellung](/assets/images/nrw.bielefeld/04.png)

Merkmal|Bedeutung|
-----|-----|
Q1Q2 | Q1 und Q2 werden für die Prüfung eingebracht, das Fach selbst wird aber für die Prüfung nicht angezeigt|
Q3Q4 | Q3 und Q4 werden für die Prüfung eingebracht, das Fach selbst wird aber für die Prüfung nicht angezeigt|
Q1Q2* | Q1 und Q2 werden für die Prüfung eingebracht, das Fach selbst wird für die Prüfung angezeigt|
Q3Q4* | Q3 und Q4 werden für die Prüfung eingebracht, das Fach selbst wird für die Prüfung angezeigt|

!!! tipp "Hinweis!"

    Alle drei Informationen (Fachstatus, Zeugnisfach und PF-Kurshalbjahre) können bereits aus `Schüler > Zeugnis > Fächer` synchronisiert werden. Durch den korrekten Eintrag im Feld `Merkmal` wird sichergestellt, dass bei der erneuten Auslösung des Skriptes nicht das verkehrte Fach auf die Prüfungskarte übernommen wird.

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
|**A**| Fremdsprache Anfänger|

## Leistungsarten

Für jedes Fach kann für jedes Kurshalbjahr eine Leistungsart zugewiesen werden. Die Leistungsart kann bereits unter `Schüler > Zeugnis > Leistungen` zugewiesen und auf die Karte `Abitur > Qualifikation` per Synchronisation übertragen werden. Alternativ können Sie die Angabe auch direkt auf der Karte `Abitur > Qualifikation` vornehmen.

Legen Sie in dem Verzeichnis Ihre gewünschten Leistungsarten an, vergeben Sie für jeden Eintrag bitte eine Eingabe in der Spalte `Leistungsart-Art`. Zur Auswahl stehen `mündlich`, `schriftlich` oder `praktisch`.

Zur Prüfung der Leistungsart "Klausur" wird das Kürzel `Klausur` und die Leistungsart-Art `schriftlich` vorausgesetzt.

Kürzel|Bezeichnung|Leistungsart
--|--|--
**KL**|Klausur|**schriftlich**
**FA**|Facharbeit|**schriftlich**
**PR**|Projekt|beliebig

![Beispiel für angelegte Leistungsarten](\assets\images\nrw\01.png)

## Projekt

Bitte legen Sie ein Fach "Projekt" (Kürzel, Bezeichnung) an, dass keine Fachkategorie und keinen Aufgabenbereich hat. Dieses Fach wird mit der Unterrichtsart "Pr" markiert und kann den Schülern unter `Schüler > Zeugnis > Fächer` im gewünschten Zeitraum zugewiesen und benotet. Dieses Fach wird beim Synchronisieren der Schülerdaten ins Menü Abitur übernommen. Es kann für die Abiturberechnung mit markiert werden und wird auch auf dem Abiturzeugnis mit ausgegeben.

Kürzel|Schlüssel|Bezeichnung
--|--|--
Pr|**PR**|Projekt

## Besondere Lernleistung

Im Menü `Abitur > Prüfung` tragen Sie unter „Lernleistung“ das Fach und Thema der Besonderen Lernleistung ein.
Die Endnote der besonderen Lernleistung weisen Sie im Menü `Abitur > Prüfung` unter „Lernleistung“ links im ersten "Punkte" Feld zu.

Das Skript vervierfacht die Note. Das Ergebnis der eingebrachten Lernleistung wird zur Gesamtsumme addiert.

Soll die Lernleistung vom Skript berücksichtigt werden, setzen Sie bitte das Häkchen vor `Lernleistung einbringen`.

![Beispiel für den Eintrag der besonderen Lernleistung](\assets\images\nrw\08.png)