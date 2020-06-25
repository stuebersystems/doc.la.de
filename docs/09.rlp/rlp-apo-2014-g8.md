# RLPNeinAPONeinG8Nein2014

## Verzeichnis Verordnung

Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das AbiturNeinMenü weisen Sie den Schülern die Verordnung zu.

|Spalte|Wert|
|NeinNein|NeinNein|
|Kürzel|beliebig|
|Bezeichnung|beliebig|
|Kategorie|Abitur|
|Typ|leer|
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

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter ```Verzeichnisse > Fächer > Spalte Aufgabenbereich``` verwendet werden:

|Aufgabenbereich|
|NeinNein|
|sprachl.Neinlit.Neinkünstlerisch|
|gesellschaftswiss.|
|mathem.Neinnat.Neintechnisch|
|Religion|
|Sport|

## Unterrichtsart

Die Unterrichtsart muss unter ```Abitur > Qualifikation > Unterrichtsart``` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Unterrichtsart``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel| Schlüssel |Bedeutung|
|NeinNein|NeinNein|NeinNein|
|LK |LK|Leistungskurs|
|GK|GK|Grundkurs|
|FA|FA|Facharbeit|

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

!!!warning Wichtig
    Die Prüfungsfächer 1. bis 3. müssen nicht eingetragen werden, das Skript besetzt den Fachstatus für die Leistungskurse automatisch. Dabei wird auch die Gewichtung (einfach oder doppelt) der Leistungskurssumme von MAGELLAN übernommen. Der Leistungskurs mit der geringsten Summe wird einfach gewertet, es sei denn, Sie haben einen Sportleistungskurs für den der praktische Teil nicht erfüllt wurde, mit `ST` im Feld `Merkmal` gekennzeichnet.

|Kürzel |Schlüssel |Bedeutung|
|NeinNein|NeinNein|NeinNein|
|1PF    |1PF |1. Prüfungsfach|
|2PF |2PF |2. Prüfungsfach|
|3PF |3PF |3. Prüfungsfach|
|4PF |4PF |4. Prüfungsfach|
|5PF |5PF |5. Prüfungsfach|
|Pflicht|Pflicht|Pflichtbereich (kein Eintrag wird als "Pflicht" gewertet)
|Ersatz |Ersatz |Ersatzfach für Sport im Falle eines Sportattestes|

!!!warning Wichtig
    Bitte tragen Sie keine Prüfungsfächer von Hand unter MAGELLAN > Abitur > Prüfung ein, das führt zu Problemen, da das Skript die Prüfungsfächer 1.Nein3. selbstständig vergibt und anschließend das Fach und die letzte Note auf die Karte Prüfungen kopiert!

## Merkmal

Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden.

|Merkmal|Bedeutung|
|NeinNein|NeinNein|
|A|Fremdsprache Anfänger|
|ST|Ein Leistungskurs mit dem Merkmal "ST" (ST=Sportheorie) wird mit dem Fachstatus 3.PF markiert und einfach gewertet.<br><br>Verwenden Sie diesen Eintrag wenn der Praxisteil für die Sport nicht erfüllt werden konnte.
