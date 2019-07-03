# NRW-APO-BK-2012/NRW-APO-BK-2011

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
|--|--|
|**Fremdsprache**|**Ja**|
|**Religion/Ethik**|**Ja**|
|**Deutsch**|**Ja**|
|**Mathematik**|**Ja**|
|**Kunst**|**Ja**|
|Musik|NEIN|
|**Sport**|**Ja**|
|**Informatik**|**Ja**|
|Philosophie|NEIN|
|**Geschichte**|**Ja**|
|**Physik**|**Ja**|
|**Chemie**|**Ja**|
|**Biologie**|**Ja**|
|**Erdkunde**|**Ja**|
|**Sozialkunde**|**Ja**|
|**Wirtschaft**|**Ja**|
|Politik|NEIN|
|Darstellendes Spiel|NEIN|
|Evangelische Religion|NEIN|
|Katholische Religion|NEIN|
|Technik|NEIN|
|Pädagogik|NEIN|
|Sporttheorie|NEIN|
|BWL/RW|NEIN|
|BWL/VWL|NEIN|
|VWL|NEIN|
|Seminar|NEIN|
|Gesundheit|NEIN|
|Psychologie|NEIN|
|Recht|NEIN|
|Literatur|NEIN|

## Aufgabenbereiche

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter ```Verzeichnisse > Fächer > Spalte Aufgabenbereich``` verwendet werden:

|Aufgabenbereich|
|--|
|sprachl.-lit.-künstlerisch|
|gesellschaftswiss.|
|mathem.-nat.-technisch|
|Religion|
|Sport|

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
|Pflicht|Pflicht|Pflichtbereich|
|Freiw|Freiw|freiwillig|


>Über den zugewiesenen Fachstatus werden die Fächer als Leistungskurs (LK) bzw. Grundkurse (GK) identifiziert. D.h. Fächer mit der Zuweisung in der Spalte „Fachstatus“ "1PF/2PF" sind Leistungskurse. Grundkurse werden durch den Fachstatus "nicht 1PF/2PF" identifiziert.

## Unterrichtsart
Die Unterrichtsart muss unter ```Abitur > Qualifikation > Unterrichtsart``` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Unterrichtsart``` übernommen werden. 
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel|	Schlüssel	|Bedeutung|
|--|--|--|
|LK	|LK	|Leistungskurs  (LK wird für das Abitur und die Fachhochschulreife, nicht durch Unterrichtsart sondern durch Fachstatus "1PF/2PF" identifiziert.)|
|GK|	GK	|Grundkurs (GK wird für das Abitur und die Fachhochschulreife, nicht durch Unterrichtsart sondern durch nicht erfolgten Eintrag der Fachstatus "1PF/2PF" identifiziert.)|
|DB|DB|Die Unterrichtsart kann verwendet werden, damit die Kursergebnisse beim Initialisieren mit einbezogen werden.|
|BU|BU|Die Unterrichtsart kann verwendet werden, damit die Kursergebnisse beim Initialisieren mit einbezogen werden.|
|BÜ|BÜ|Die Unterrichtsart kann verwendet werden, damit die Kursergebnisse beim Initialisieren mit einbezogen werden.|

> #### danger::Achtung!
>
> Mit der Ausgabe des Skriptes ab Version 6.5.33 werden beim Initialisieren nur noch Kurse berücksichtigt, die mit einer der oben genannten Unterrichtsart markiert sind. Durch diese Änderung werden gezielt Kurse von der Berücksichtigung im Abitur ausgeschlossen. In den Fachdaten erfasste Zeilen, die beispielsweise das Arbeits- und Sozialverhalten beinhalten, bleiben so außen vor.
 
## Merkmal

Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden. 

|Merkmal	|Bedeutung|
|--|--|
|A|	Fremdsprache Anfänger (2 Kurse müssen eingebracht werden)|
|A12|	Fremdsprache, welche erst ab der 12 belegt wird|

## Besondere Lernleistung und Facharbeit

Im Menü Abitur|Prüfung tragen Sie unter „Lernleistung“ das Fach und Thema der Besonderen Lernleistung ein.
Die Endnote der besonderen Lernleistung weisen Sie im Menü Abitur|Prüfung unter „Lernleistung“ im ersten "Punkte" Feld (links) zu.

> #### primary::Hinweis
>
> Ausgabe der Besonderen Lernleistung bzw. der Facharbeit auf dem Zeugnis der Allgemeinen Fachhochschulreife. 
Auf dem Zeugnis kann wahlweise zwischen einer **Facharbeit** und einer **Besondere Lernleistung** gewählt werden.

* Zur Ausgabe der **Besondere Lernleistung**  müssen Sie im Menü ``Abitur`` unter der Registerkarte ``Prüfung > Lernleistung`` das entsprechende Fach zuweisen und das Optionsfeld ``Lernleistung einbringen`` markieren. Das Thema der besonderen Lernleistung weisen Sie analog dem entsprechenden Feld im Feld "Thema" zu. Die Note für die besondere Lernleistung im Block1 tragen Sie im 1. Notenfeld ganz links ein. Die Noten für Block2 tragen Sie in den 2 Notenfeldern daneben ein. 

![Eintragung der besonderen Lernleistung](/assets/nrw.apo.bk.2012.bl.png)

* Zur Ausgabe der **Facharbeit** müssen Sie im Menü  ``Abitur``unter der Registerkarte ``Prüfung > Projekt`` das entsprechende Fach zuweisen und das Optionsfeld ``Projekt einbringen`` markieren. Das Thema des Projektes weisen Sie analog dem entsprechenden Feld im Feld "Thema" zu. Die Note für die Facharbeit" im Block1 tragen Sie im 1. Notenfeld ganz links ein. Die Noten für Block2 tragen Sie in den 2 Notenfeldern daneben ein.

![Eintragung der Facharbeit](/assets/nrw.apo.bk.2012.fa.png)