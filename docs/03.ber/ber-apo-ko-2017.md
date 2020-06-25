# BER-APO-KO-2017

!!! info "Hinweis"

    Weitere wichtige Informationen finden Sie in der MAGELLAN-Dokumentation im Abschnitt [Regionales > Berlin](https://doc.magellan7.stueber.de/schulverwaltung/regionales/berlin/berlin/) !

## Allgemein

In diesem Skript werden für die korrekte Berechnung unter `Abitur > Qualifikation` drei als Leistungskurse markierte Fachzeilen erwartet, die nicht als 1. oder 2. Prüfungsfach erfasst wurden (Unterrichtsart LK und nicht Fachstatus 1PF oder 2PF). Der 3.Leistungskurs wird in der Berechnung wie ein Grundkurs behandelt.

## Verzeichnis Verordnung

Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

|Spalte|Wert|
|--|--|
|Kürzel|beliebig|
|Bezeichnung|beliebig|
|Kategorie|Abitur|
|Typ|bitte leer lassen|
|Ab Jahrgang|bitte leer lassen|
|Skript|```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server)|
|Notenart 11|Noten oder Punkte|
|Notenart 12|Punkte|
|Notenart 13|Punkte|
|Notenart 13|Punkte|
|Notenart BBS|leer|
|Gültig von |leer|
|Gültig bis|leer|

![Eingetragene Verordnungszeile unter Verzeichnisse > Verordnungen](/assets/images/ber-apo-ko-2017.00.png)

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
|Philosophie|Nein|
|Geschichte|**Ja**|
|Physik|**Ja**|
|Chemie|**Ja**|
|Biologie|**Ja**|
|Erdkunde|**Ja**|
|Sozialkunde|**Ja**|
|Wirtschaft|**Ja**|
|Politik|**Ja**|
|Darstellendes Spiel|**Ja**|
|Evangelische Religion|Nein|
|Katholische Religion|Nein|
|Technik|Nein|
|Pädagogik|Nein|
|Sporttheorie|**Ja**|
|BWL/RW|Nein|
|BWL/VWL|Nein|
|VWL|Nein|
|Seminar|**Ja**|
|Gesundheit|Nein|
|Psychologie|Nein|
|Recht|Nein|
|Literatur|Nein|

## Aufgabenbereiche

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter `Schlüsselzerzeichnis > Fächer` in der Spalte "Aufgabenbereich" verwendet werden:

|Aufgabenbereich|
|--|
|sprachl.-lit.-künstlerisch|
|gesellschaftswiss.|
|mathem.-nat.-technisch|
|Religion|
|Sport|

## Unterrichtsart

Die Unterrichtsart muss im Menü `Abitur > Qualifikation` im Feld " Unterrichtsart" zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus dem Menü `Schüler > Zeugnis > Fächer` aus dem Feld "Unterrichtsart" übernommen werden.
Prüfen Sie bitte im `Schlüsselverzeichnis > Unterrichtsarten`,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel| Schlüssel |Bedeutung|
|--|--|--|
|LK|LK|Leistungskurs|
|GK|GK|Grundkurs|
|Z|Z|Zusatz-/und Ergänzungskurse|
|M|M|Musik-Ensemble|

## Fachstatus

Der Fachstatus muss im Menü `Abitur > Qualifikation` im Feld "Fachstatus"  zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus dem Menü `Schüler > Zeugnis > Fächer` aus dem Feld "Fachstatus" übernommen werden.
Prüfen Sie bitte unter `Schlüsselverzeichnis > Fachstatus`,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel |Schlüssel |Bedeutung|
|--|--|--|
|1PF|1PF|1. Prüfungsfach|
|2PF|2PF|2. Prüfungsfach|
|3PF|3PF|3. Prüfungsfach|
|4PF|4PF|4. Prüfungsfach|
|5PF|5PF|5. Prüfungsfach (nur verwenden wenn es eine Präsentationsprüfung ist), BLL siehe unten|
|Pflicht|Pflicht|Pflichtbereich (kein Eintrag wird wie Pflicht gewertet)|

## 5. Prüfungskomponente

Bei der 5 Prüfungskomponente wird zwischen einer „Präsentation“ und der „Besonderen Lernleistung“ unterschieden. Gehen Sie jeweils wie folgt vor:

### Präsentationprüfung

Bei der "Präsentation" weisen Sie dem entsprechenden Fach im Menü `Abitur > Qualifikation` in der Spalte „Fachstatus“ den Wert „5 PF“ zu und führen das entsprechende Skript aus.
Durch das Berechnungskript wird im Menü `Abitur > Prüfung` im Feld „5. PF“ das Fach eingetragen.  Dort tragen die mündliche Note im Feld "Mündliche Note" ein.

![Menü Abitur > Qualifikation](/assets/images/berlin/ber-apo-ko-2017.02.png)

### Besondere Lernleistung

Zur Ausgabe der besonderen Lernleistung müssen Sie im Menü `Abitur > Prüfung` in der Registerkarte „Lernleistung“ das entsprechende Fach zuweisen und das Optionsfeld `„Lernleistung einbringen“` markieren.

Die schriftl Note für das "1. Gutachten bzw. schriftliche Note für die besondere Lernleistung" tragen Sie im 1. Punktefeld ganz links ein.
Die mdl. Note für die besondere Lernleistung tragen Sie im 2. Punktefeld ein.
Das Berechnungsskript fügt automatisch im 3. Punktfeld die Gesamtnote für die Besondere Lernleistung ein.
