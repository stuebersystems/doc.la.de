# BER-APO-2010

> #### warning::Wichtig!
>
> Weitere wichtige Informationen finden Sie in der MAGELLAN-Dokumentation im Abschnitt [Bundeslandspezifisch > Berlin](https://doc.magellan6.stueber.de/bundeslaender/berlin/berlin.html)!



##Verzeichnis Verordnung
Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

|Spalte|Wert|
|--|--|
|Kürzel|beliebig|
|Bezeichnung|beliebig|
|Kategorie|Abitur|
|Typ|bitte tragen Sie vor der Synchronisation der Schüler ins Abiturmodul bei G8 eine !0, sonst eine 11 ein|
|Ab Jahrgang|leer|
|Skript|```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server)|
|Notenart 11|Noten oder Punkte|
|Notenart 12|Punkte|
|Notenart 13|Punkte|
|Notenart 13|Punkte|
|Notenart BBS|leer|
|Gültig von |leer|
|Gültig bis|leer|


##Fachkategorien
Jedem Fach, dass Sie in der Oberstufe verwenden, müssen Sie eine Kategorie unter ```Verzeichnisse > Fächer > Kategorie``` zuweisen.
Folgende Fachkategorien werden durch das Abiturqualifikationsskript verwendet, bitte verwenden Sie nur die gekennzeichneten Fachkategorien.

|Fachkategorien|Wird vom Skript berücksichtigt|
|--|--|--|
|Fremdsprache|JA|
|Religion/Ethik|JA|
|Deutsch|JA|
|Mathematik|JA|
|Kunst|JA|
|Musik||
|Sport|JA|
|Informatik|JA|
|Philosophie||
|Geschichte|JA|
|Physik|JA|
|Chemie|JA|
|Biologie|JA|
|Erdkunde|JA|
|Sozialkunde|JA|
|Wirtschaft|JA|
|Politik|JA|
|Darstellendes Spiel||
|Evangelische Religion||
|Katholische Religion||
|Technik||
|Pädagogik||
|Sporttheorie|JA|
|BWL/RW||
|BWL/VWL||
|VWL||
|Seminar||
|Gesundheit||
|Psychologie||
|Recht|||
|Literatur|||

##Aufgabenbereiche
Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter ```Verzeichnisse > Fächer > Spalte Aufgabenbereich``` verwendet werden:

|Aufgabenbereich|
|--|
|sprachl.-lit.-künstlerisch|
|gesellschaftswiss.|
|mathem.-nat.-technisch|
|Religion|
|Sport|

##Unterrichtsart
Die Unterrichtsart muss unter ```Abitur > Qualifikation > Unterrichtsart``` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Unterrichtsart``` übernommen werden. 
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel|	Schlüssel	|Bedeutung|
|--|--|--|
|LK|LK|Leistungskurs|
|GK|GK|Grundkurs|


##Fachstatus
Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden. 
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel	|Schlüssel	|Bedeutung|
|--|--|--|
|1PF|1PF|1. Prüfungsfach|
|2PF|2PF|2. Prüfungsfach|
|3PF|3PF|3. Prüfungsfach|
|4PF|4PF|4. Prüfungsfach|
|5PF|5PF|5. Prüfungsfach|
|Pflicht|Pflicht|Pflicht|

##Merkmal
Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden. 

>Werden Sportarten aus mehreren Halbjahren mit ins Abiturmenü übertragen, werden sie aneinandergefügt.
> Beispiel: 
> 1.Halbjahr Badminton BM, 2.Halbjahr Fußball wird beim Synchronisieren als BMFB ins ```Menü Abitur > Qualifikation > Merkmal``` übernommen.


|Gruppe|Merkmal|Bedeutung|
|--|--|--|
|Gruppe A Sportarten|GY|Gymnastik/Tanz|
|Gruppe A Sportarten|LE|Leichtathletik|
|Gruppe A Sportarten|SW|Schwimmen|
|Gruppe A Sportarten|TU|Turnen|
|Gruppe B Sportarten|BM|Badminton|
|Gruppe B Sportarten|BB|Basketball|
|Gruppe B Sportarten|FB|Fußball|
|Gruppe B Sportarten|HB|Handball|
|Gruppe B Sportarten|HC|Hockey|
|Gruppe B Sportarten|TS|Tennis|
|Gruppe B Sportarten|TT|Tischtennis|
|Gruppe B Sportarten|VB|Volleyball|
|Gruppe C Sportarten|FE|Fechten|
|Gruppe C Sportarten|FI|Fitnesssport|
|Gruppe C Sportarten|JU|Judo|
|Gruppe C Sportarten|KA|Kanusport|
|Gruppe C Sportarten|RU|Rudern|
|Gruppe C Sportarten|SK|Skifahren|
|Gruppe C Sportarten|SL|Skilanglauf|
|Gruppe C Sportarten|SU|Surfen|



