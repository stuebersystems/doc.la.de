# SAC-APO-BGY-2017

Abiturqualifikationsberechnung gemäß Verordnung des Sächsischen Staatsministeriums für Kultus über Berufliche Gymnasien im Freistaat Sachsen (Schulordnung Berufliche Gymnasien – BGySO).

## Verzeichnis Verordnung
Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.


| Spalte       | Wert                                     |
|--------------|------------------------------------------|
| Kürzel       | beliebig                                 |
| Bezeichnung  | beliebig                                 |
| Kategorie    | Abitur                                   |
| Typ          | leer oder "WI" für Wirtschaftswissenschaften |
| Ab Jahrgang  | leer                                     |
| Skript       | ```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server) |
| Notenart 11  | Noten                                    |
| Notenart 12  | Punkte                                   |
| Notenart 13  | Punkte                                   |
| Notenart BBS | leer                                     |
| Gültig von   | leer                                     |
| Gültig bis   | leer                                     |




## Fachkategorien
Jedem Fach, dass Sie in der Oberstufe verwenden, müssen Sie eine Kategorie unter ```Verzeichnisse > Fächer > Kategorie``` zuweisen.
Folgende Fachkategorien werden durch das Abiturqualifikationsskript verwendet:

|Fachkategorien|Wird vom Skript berücksichtigt|
|--|--|
|Fremdsprache|JA|
|Religion/Ethik|JA|
|Deutsch|JA|
|Mathematik|JA|
|Kunst|JA|
|Musik|JA|
|Sport|JA|
|Informatik||
|Philosophie||
|Geschichte|JA|
|Physik|JA|
|Chemie|JA|
|Biologie|JA|
|Erdkunde|JA|
|Sozialkunde|JA|
|Wirtschaft|JA|
|Politik||
|Darstellendes Spiel||
|Evangelische Religion||
|Katholische Religion||
|Technik||
|Pädagogik||
|Sporttheorie||
|BWL/RW||
|BWL/VWL||
|VWL||
|Seminar||
|Gesundheit||
|Psychologie||
|Recht||
|Literatur||

## Aufgabenbereiche
Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter ```Verzeichnisse > Fächer > Spalte Aufgabenbereich``` verwendet werden:


| Aufgabenbereich            |
|----------------------------|
| sprachl.-lit.-künstlerisch |
| gesellschaftswiss.         |
| mathem.-nat.-technisch     |
| Religion                   |
| Sport                      |



## Unterrichtsart
Die Unterrichtsart muss unter ```Abitur > Qualifikation > Unterrichtsart``` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Unterrichtsart``` übernommen werden. 
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.


| Kürzel | Schlüssel | Bedeutung     |
|--------|-----------|---------------|
| LK     | LK        | Leistungskurs |
| GK     | GK        | Grundkurs     |


## Fachstatus
Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden. 
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.


| Kürzel | Schlüssel | Bedeutung       |
|--------|-----------|-----------------|
| 1PF    | 1PF       | 1. Prüfungsfach |
| 2PF    | 2PF       | 2. Prüfungsfach |
| 3PF    | 3PF       | 3. Prüfungsfach |
| 4PF    | 4PF       | 4. Prüfungsfach |
| 5PF    | 5PF       | 5. Prüfungsfach |



## Besondere Lernleistung
Die „Besondere Lernleistung“ muss mit schriftlicher und mündlicher Note auf der Prüfungsregisterkarte (```Abitur > Prüfung > Lernleistung```) eingegeben werden. Bitte tragen Sie die schriftliche Note links in das erste Feld und die mündliche Note in das zweite Feld ein. Soll die Leistung mit eingebracht werden, aktivieren Sie bitte das Häkchen ```Lernleistung einbringen```.

## Merkmal
Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Es kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden. 


| Merkmal | Bedeutung                                |
|---------|------------------------------------------|
| B       | Neu einsetzende Fremdsprache, 2 Kurse müssen eingebracht werden (entspricht dem Niveau B) |



Alle anderen Fremdsprachen haben automatisch das Niveau A, dazu muss in Spalte `Merkmal` nichts eingetragen werden.

