# MVP-APO-FG-2019

[04]:/assets/images/MVP/004.png "Besondere Lernleistung"
[05]:/assets/images/MVP/005.png "Facharbeit"

Oberstufen- und Abiturprüfungsverordnung (Abiturprüfungsverordnung - APVO M-V)* Vom 19. Februar 2019
Gesamtausgabe in der Gültigkeit vom 26.07.2022 bis 31.07.2024  ([APVO M-V](https://www.landesrecht-mv.de/bsmv/document/jlr-AbiPrVMVrahmen))

## Verzeichnis Verordnung

Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

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

## Verzeichnis Fächer

Bei Fächer, die auf dem Zeugnis als "berufliches Schwerpunktfach" oder "berufliches Fach" ausgeiwesen werden sollen, müssen Sie in der Spalte `Zeugnismerkmal` die folgenden Werte eintragen

|Zeugnismerkmal|Bedeutung|
|--|--|
|BFS|berufliches Schwerpunktfach|
|BF|berufliches Fach|


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
|Informatik|Nein|
|Philosophie|**Ja**|
|Geschichte|**Ja**|
|Physik|**Ja**|
|Chemie|**Ja**|
|Biologie|**Ja**|
|Erdkunde|Nein|
|Sozialkunde|Nein|
|Wirtschaft|Nein|
|Politik|**Ja**|
|Darstellendes Spiel|Nein|
|Evangelische Religion|Nein|
|Katholische Religion|Nein|
|Technik|Nein|
|Pädagogik|Nein|
|Sporttheorie|Nein|
|Seminar|Nein|
|BWL/RW|Nein|
|BWL/VWL|Nein|
|VWL|Nein|
|Seminar|Nein|
|Gesundheit|Nein|
|Psychologie|Nein|
|Recht|Nein|
|Literatur|Nein|

## Aufgabenbereiche

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter ```Verzeichnisse > Fächer > Spalte Aufgabenbereich``` verwendet werden:

|Aufgabenbereich|
|--|
|sprachl.-lit.-künstlerisch|
|gesellschaftswiss.|
|mathem.-nat.-technisch|
|Religion|
|Sport|

## Unterrichtsart

Die Unterrichtsart muss unter ```Abitur > Qualifikation > Unterrichtsart``` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Unterrichtsart``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel| Schlüssel |Bedeutung|
|--|--|--|
|HF|HF|Hauptfach|
|GF|GF|Grundfach|

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel |Schlüssel |Bedeutung|
|--|--|--|
|1PF |1PF |1. Prüfungsfach|
|2PF |2PF |2. Prüfungsfach|
|3PF |3PF |3. Prüfungsfach|
|4PF |4PF |4. Prüfungsfach|
|5PF |5PF |5. Prüfungsfach (mündlich)|
|FA|FA|Facharbeit|

## Facharbeit

`Extras > Schlüsselverzeichnisse > Fachstatus` <br/>`Abitur > Qualifikation > Unterrichtsart`<br/>`Abitur > Prüfungen > Projekte`

Markieren Sie auf der Qualifikationskarte die Fachzeile der Facharbeit mit dem Fachstatus `FA`. Bitte tragen Sie die Leistungen für ein oder zwei Halbjahre mit ein. Wenn die Facharbeit nicht berücksichtigt werden soll, dürfen diese Werte nicht eingebracht werden.
Beim Auslösen des Berechnungsskriptes wird das Fach und dessen Ergebnisse mit auf die Karte `Prüfung` übergeben und dort auf der Unterkarte `Projekt` gezeigt.
Die Punktwert eines 1. Halbjahres aus Block 1 wird unter `Note 1` und eine eventueller 2. Punktwert eines 2. Halbjahres aus Block 1 wird unter `Note 2` für die Facharbeit auf die Unterkarte `Projekt` übertragen.   
Erfassen Sie das Thema bitte im im gleichnamige Feld `Thema`.
Die Summe beider Noten wird auf dem Zeugnisse auf der Seite 3 ausgegeben. Soll nur ein Halbjahr in die Ausgabe auf Seite 3 einbezogen werden, so muss entweder `Note 1` oder `Note 2` auf die Unterkarte `Projekt` gelöscht werden.

[![Facharbeit][05]][05]

## Besondere Lernleistung

`Extras > Schlüsselverzeichnisse > Unterrichtsarten` <br/>`Abitur > Qualifikation > Unterrichtsart`

Anstelle der 4. oder 5. mündlichen Prüfung ist auch eine „Besondere Lernleistung“ möglich.
Bitte erfassen Sie das `Fach`, das `Thema` und die `Punkte` der Besonderen Lernleistung unter `Abitur > Prüfung > Lernleistung` in den gleichnamigen Feldern.

Beim Auslösen des Berechnungsskriptes wird das Fach mit den Fächern für das 4. und 5.Prüfungsfach verglichen und wenn es gleich ist, wird die Note, die Sie im ersten Punktefeld links für die Lernleistung erfasst haben als Ergebnis für die mündliche Prüfung des Fachs gewertet.
Erfassen Sie das Thema bitte im im gleichnamige Feld `Thema`.

[![Besondere Lernleistung][04]][04]