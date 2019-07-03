# SAR-APO-2007

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
Folgende Fachkategorien werden durch das Abiturqualifikationsskript verwendet:

|Fachkategorien|
|--|--|
|Fremdsprache|
|Religion/Ethik|
|Deutsch|
|Mathematik|
|Kunst|
|Musik|
|Sport|
|Informatik|
|Philosophie|
|Geschichte|
|Physik|
|Chemie|
|Biologie|
|Erdkunde|
|Sozialkunde|
|Wirtschaft|
|Politik|
|Darstellendes Spiel|
|Sporttheorie|
|Seminar|


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
|E-Kurs	|E	|E-Kurs / Fach mit erhöhtem Anforderungsniveau|
|G-Kurs|G	|G-Kurs / Fach mit grundlegendem Anforderungsniveau|
|NF|NF|Neigungsfach|

## Fachstatus
Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden. 
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel	|Schlüssel	|Bedeutung|
|--|--|--|
|1PF	|1PF	|1. Prüfungsfach (E-Kurs)|
|2PF	|2PF	|2. Prüfungsfach (E-Kurs)|
|3PF	|3PF	|3. Prüfungsfach (G-Kurs)|
|4PF	|4PF	|4. Prüfungsfach (G-Kurs oder Neigungsfach)|
|5PF	|5PF	|5. Prüfungsfach (nur mündlich), beliebiges weiteres Fach|
|Pflicht|Pflicht|Pflichtbereich (kein Eintrag wird wie Pflicht gewertet)|
|abgew|abgew|abgewählt|

## Merkmal
Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden. 

|Merkmal	|Bedeutung|
|--|--|
|A|	Fremdsprache Anfänger (2 Kurse müssen eingebracht werden)|

## Die Besondere Lernleistung
Laut der zugrundliegenden Abiturverordnung muss die besondere Lernleistung im Kursbereich und nicht im Prüfungsbereich eingebracht werden. Aus diesem Grund müssen die einzubringenden Noten der besonderen Lernleistung als normale Fachnoten auf der Registerkarte "Abitur|Qualifikation" eingegeben werden und nicht wie sonst üblich auf der Registerkarte "Abitur|Prüfung".