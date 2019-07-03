# BRE-APO-2010

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


## Fachkategorien
Jedem Fach, dass Sie in der Oberstufe verwenden, müssen Sie eine Kategorie unter ```Verzeichnisse > Fächer > Kategorie``` zuweisen.
Folgende Fachkategorien werden durch das Abiturqualifikationsskript verwendet, bitte verwenden Sie nur die gekennzeichneten Fachkategorien.

|Fachkategorien|Wird vom Skript berücksichtigt|
|--|--|--|
|Fremdsprache|**Ja**|
|Religion/Ethik|**Ja**|
|Deutsch|**Ja**|
|Mathematik|**Ja**|
|Kunst|**Ja**|
|Musik||
|Sport|**Ja**|
|Informatik|**Ja**|
|Philosophie||
|Geschichte|**Ja**|
|Physik|**Ja**|
|Chemie|**Ja**|
|Biologie|**Ja**|
|Erdkunde||
|Sozialkunde||
|Wirtschaft||
|Politik|**Ja**|
|Darstellendes Spiel||
|Evangelische Religion||
|Katholische Religion||
|Technik||
|Pädagogik||
|Sporttheorie||
|Seminar||
|BWL/RW||
|BWL/VWL||
|VWL||
|Seminar||
|Gesundheit||
|Psychologie||
|Recht||
|Literatur|||


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
|LK|LK|Leistungskurs|
|GK|GK|Grundkurs|

## Fachstatus
Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden. 
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel	|Schlüssel	|Bedeutung|
|--|--|--|
|1PF|1PF|1. Prüfungsfach|
|2PF|2PF|2. Prüfungsfach|
|3PF|3PF|3. Prüfungsfach|
|4PF|4PF|4. Prüfungsfach|
|Pflicht|Pflicht|Pflichtbereich (kein Eintrag wird wie Pflicht gewertet)|

## Merkmal
Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden. 

>Werden Sportarten aus mehreren Halbjahren mit ins Abiturmenü übertragen, werden sie aneinandergefügt.
> Beispiel: 
> 1.Halbjahr Badminton BM, 2.Halbjahr Fußball wird beim Synchronisieren als BMFB ins ```Menü Abitur > Qualifikation > Merkmal``` übernommen.


|Typ|Merkmal|Bedeutung|
|--|--|--|
|Fremdsprache|A|Fremdsprache Anfänger (ein Kurs aus 13 muss eingebracht und durchgehend belegen werden)|
|Fremdsprache|B|Fortgesetzte Fremdsprache (muss eingebracht und durchgehend belegen werden)|
|Mannschaftssportarten|BB|Basketball|
|Mannschaftssportarten|BM|Badminton|
|Mannschaftssportarten|FB|Fußball|
|Mannschaftssportarten|HB|Handball|
|Mannschaftssportarten|HC|Hockey|
|Mannschaftssportarten|RB|Rugby|
|Mannschaftssportarten|TS|Tennis|
|Mannschaftssportarten|TT|Tischtennis|
|Mannschaftssportarten|VB|Volleyball|
|Mannschaftssportarten|MA|Weitere|
|Mannschaftssportarten|MB|Weitere|
|Mannschaftssportarten|MC|Weitere|
|Individualsportarten|GT|Geräteturnen|
|Individualsportarten|GY|Gymnastik|
|Individualsportarten|JU|Judo|
|Individualsportarten|KA|Kanusport|
|Individualsportarten|LE|Leichtathletik|
|Individualsportarten|RU|Rudern|
|Individualsportarten|SW|Schwimmen|
|Individualsportarten|TA|Tanz|
|Individualsportarten|TR|Trampolinturnen|
|Individualsportarten|IA|Weitere|
|Individualsportarten|IB|Weitere|
|Individualsportarten|IC|Weitere|

