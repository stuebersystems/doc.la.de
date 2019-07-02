# RLP-APO-2014

## Verzeichnis Verordnung
Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

|Spalte|Wert|
|--|--|
|Kürzel|beliebig|
|Bezeichnung|beliebig|
|Kategorie|Abitur|
|Typ|G8 oder G9 <br/>Diese Eingabe ist für den Druck der Abiturzeugnisse sowie Punktekreditkarte wichtig. Nur so kann der Bericht die richtigen Halbjahre ausgeben|
|Ab Jahrgang|G8= 10<br/>G9= leer<br/>Diese Eingabe muss bitte vor der Synchronisation der Schüler ins Menü Abitur erfolgen.|
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
|--|--|
|Fremdsprache|JA|
|Religion/Ethik|JA|
|Deutsch|JA|
|Mathematik|JA|
|Kunst|JA|
|Musik|JA|
|Sport|JA|
|Informatik|JA|
|Philosophie|JA|
|Geschichte|JA|
|Physik|JA|
|Chemie|JA|
|Biologie|JA|
|Erdkunde|JA|
|Sozialkunde|JA|
|Wirtschaft|JA|
|Politik|JA|
|Darstellendes Spiel|JA|
|Evangelische Religion|-|
|Katholische Religion|-|
|Technik|-|
|Pädagogik|-|
|Sporttheorie|JA|
|BWL/RW|-|
|BWL/VWL|-|
|VWL|-|
|Seminar|JA|
|Gesundheit|-|
|Psychologie|-|
|Recht|-|
|Literatur|-|

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
|LK	|LK|Leistungskurs|
|GK|GK|Grundkurs|
|FA|FA|Facharbeit|



## Fachstatus
Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden. 
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

> #### warning::Wichtig!
>
> Die Prüfungsfächer 1. bis 3. müssen nicht eingetragen werden, das Skript besetzt den Fachstatus für die Leistungskurse automatisch. Dabei wird auch die Gewichtung (einfach oder doppelt) der Leistungskurssumme von MAGELLAN übernommen. Der Leistungskurs mit der geringsten Summe wird einfach gewertet, es sei denn, Sie haben einen Sportleistungskurs für den der praktische Teil nicht erfüllt wurde, mit ` ST ` im Feld `Merkmal` gekennzeichnet.

|Kürzel	|Schlüssel	|Bedeutung|
|--|--|--|
|1PF	|1PF	|1. Prüfungsfach|
|2PF	|2PF	|2. Prüfungsfach|
|3PF	|3PF	|3. Prüfungsfach|
|4PF	|4PF	|4. Prüfungsfach|
|5PF	|5PF	|5. Prüfungsfach|
|Pflicht|Pflicht|Pflichtbereich (kein Eintrag wird als "Pflicht" gewertet)
|Ersatz	|Ersatz	|Ersatzfach für Sport im Falle eines Sportattestes|
|Freiw|Freiw|Freiwillig|


> #### danger::Achtung!
>
> Bitte tragen Sie keine Prüfungsfächer von Hand unter MAGELLAN > Abitur > Prüfung ein, das führt zu Problemen, da das Skript die Prüfungsfächer 1.-3. selbstständig vergibt und anschließend das Fach und die letzte Note auf die Karte Prüfungen kopiert!

## Merkmal
Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden. 

|Merkmal	|Bedeutung|
|--|--|
|A|	Fremdsprache Anfänger|
|ST|Ein Leistungskurs mit dem Merkmal "ST" (ST=Sportheorie) wird mit dem Fachstatus 3.PF markiert und einfach gewertet.<br/><br/>Verwenden Sie diesen Eintrag wenn der Praxisteil für die Sport nicht erfüllt werden konnte.

