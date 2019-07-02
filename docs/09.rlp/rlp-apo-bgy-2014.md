# RLP-APO-BGY-2014

## Verzeichnis Verordnung
Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

|Spalte|Wert|
|--|--|
|Kürzel|beliebig|
|Bezeichnung|beliebig|
|Kategorie|Abitur|
|Typ|Das Skript erwartet die Eingabe des Typs in MAGELLAN unter ```Verzeichnisse > Verordnungen``` in der Spalte Typ. In DAVINCI tragen Sie den Wert bitte auf dem Stammdatenregister Klassen bei Verordnungstyp ein. Folgende Werte können genutzt werden|
||"TK" für Fachrichtung "Technik"|
||"WI" für Fachrichtung "Wirtschaft"|
||"GS" für Fachrichtung "Gesundheit und Soziales"|
|Ab Jahrgang|leer|
|Skript|```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server)|
|Notenart 11|Noten oder Punkte|
|Notenart 12|Punkte|
|Notenart 13|Punkte|
|Notenart 13|Punkte|
|Notenart BBS|leer|
|Gültig von |leer|
|Gültig bis|leer|


## Fachkategorien
Jedem Fach, dass Sie in der Oberstufe verwenden, müssen Sie eine Kategorie unter ```Verzeichnisse > Fächer > Kategorie``` zuweisen.
Folgende Fachkategorien werden durch das Abiturqualifikationsskript verwendet, bitte verwenden Sie nur die gekennzeichneten Fachkategorien.

|Fachkategorien|Wird vom Skript berücksichtigt|
|--|--|--|
|Fremdsprache|JA|
|Religion/Ethik|JA|
|Deutsch|JA|
|Mathematik|JA|
|Kunst|JA|
|Musik|JA|
|Sport|JA|
|Informatik|JA|
|Philosophie||
|Geschichte|JA|
|Physik|JA|
|Chemie|JA|
|Biologie|JA|
|Erdkunde|JA|
|Sozialkunde|JA|
|Wirtschaft||
|Politik||
|Darstellendes Spiel|JA|
|Evangelische Religion||
|Katholische Religion||
|Technik||
|Pädagogik|JA|
|Sporttheorie||
|BWL/RW|JA|
|BWL/VWL||
|VWL|JA|
|Seminar||
|Gesundheit|JA|
|Psychologie|JA|
|Recht||
|Literatur|||

>Erdkunde, Sozialkunde und Geschichte werden als Gemeinschaftskunde erkannt.

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

|Kürzel|	Schlüssel	|Bedeutung|
|--|--|--|
|LK	|LK	|Leistungskurs|
|GK|	GK	|Grundkurs|
|FA|	FA	|Facharbeit|

## Fachstatus
Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden. 
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel	|Schlüssel	|Bedeutung|
|--|--|--|
|1PF	|1PF	|1. Prüfungsfach|
|2PF	|2PF	|2. Prüfungsfach|
|3PF	|3PF	|3. Prüfungsfach|
|4PF	|4PF	|4. Prüfungsfach|
|5PF	|5PF	|5. Prüfungsfach|
|Pflicht|Pflicht|Pflichtbereich (kein Eintrag wird wie Pflicht gewertet)|
|Freiw|Freiw|Freiwillig|

## zweite Fremdsprache 

![Beschriftung](/assets/images/rlp_bgy_2014_auszug.jpg)

>Damit die zweite Fremdsprache wird erkannt, dürfen Sie im Status weder 1PF-5PF, noch Pflicht oder "leer" verwenden. Bitte verwenden Sie den Fachstatus "Freiw".



## Merkmal
Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden. 

|Merkmal	|Bedeutung|
|--|--|
|A|	Fremdsprache Anfänger|
