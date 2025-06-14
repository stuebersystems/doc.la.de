# MVP-APO-FG-1999

## Verzeichnis Verordnung

Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

|Spalte|Wert|
|--|--|
|Kürzel|beliebig|
|Bezeichnung|beliebig|
|Kategorie|Abitur|
|Typ|Verordnungskürzel in Magellan "Extras> Verordnungen" kennzeichnet Schulform:|
||AW = Fachgymnasium Agrarwirtschaft|
||EW = Fachgymnasium Ernährungswirtschaft|
||WS = Fachgymnasium Wirtschaft|
||TK = Fachgymnasium Technik|
||SP = Fachgymnasium Sozialpädagogik|
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
|Informatik|Nein|
|Philosophie|**Ja**|
|Geschichte|**Ja**|
|Physik|**Ja**|
|Chemie|**Ja**|
|Biologie|**Ja**|
|Erdkunde|**Ja**|
|Sozialkunde|**Ja**|
|Wirtschaft|**Ja**|
|Politik|Nein|
|Darstellendes Spiel|Nein|
|Evangelische Religion|Nein|
|Katholische Religion|Nein|
|Technik|**Ja**|
|Pädagogik|**Ja**|
|Sporttheorie|Nein|
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

## Merkmal

Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden.

|Fachkürzel |Bemerkung| Merkmal|
|--|--|--|
|SPOPR |Sport-Praxis |Syntax: AAAAAAAA|
|||Angabe der Sportart für jedes der 4 Qualifikationshalbjahre: <br/><br/>**Mannschaftssportarten:**<br/>BB = Basketball<br/>BM = Badminton<br/>FB = Fussball<br/>HB = Handball<br/>HC = Hockey<br/>RB = Rugby<br/>TS = Tennis<br/>TT = Tischtennis<br/>VB = Volleyball <br/> <br/>**Individualsportarten:**<br/>GT Geräteturnen<br/>GY = Gymnastik<br/>JU = Judo<br/>KA = Kanusport<br/>LE = Leichtathletik<br/>RU = Rudern<br/>SW = Schwimmen<br/>TA = Tanz<br/>TR = Trampolinturnen|
