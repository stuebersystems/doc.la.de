# NRW-APO-BK-2018

## Unterschied zum Skript NRW-APO-BK-2012

Dieses Skript berücksichtigt abweichend vom Skript `NRW-APO-BK-2021` die unten fett markierten Passagen der Verordnung.

Auszug aus der APO-BK NRW:

... § 15 (ab 01.08.2018) Zulassung zur Abiturprüfung

(1) Über die Zulassung zur Abiturprüfung entscheidet der allgemeine Prüfungsausschuss in der ersten Konferenz.

(2) Zugelassen wird, wer am Unterricht der Jahrgangsstufen 12 und 13 gemäß der für den Bildungsgang gültigen Stundentafel teilgenommen hat und im Grund- und Leistungskursbereich der Qualifikationsphase (Block I) folgende Bedingungen erfüllt:

1. Es müssen mindestens 32 und höchstens 40 Kurse, darunter die acht Leistungskurse, eingebracht werden. Werden mehr als 32 Kurse eingebracht, kann ein Kurs durch eine Facharbeit nach Absatz 4 Nummer 3 ersetzt werden.
2. Es müssen mindestens 200 Punkte gemäß § 25 Absatz 3 erreicht werden.
3. Von den gemäß Nummer 1 eingebrachten Kursen dürfen

    * a) bei Einbringung von genau 32 Kursen nicht mehr als sechs,
    * b) bei Einbringung von 33 bis 37 Kursen nicht mehr als sieben und
    * c) bei Einbringung von 38 bis 40 Kursen nicht mehr als acht Kurse mit weniger als fünf Punkten in einfacher Gewichtung bewertet worden sein.
  
Darunter dürfen nicht mehr als drei Leistungskurse sein.
Kurse, die mit null Punkten bewertet worden sind, können nicht eingebracht werden. ...

## Verzeichnis Verordnung

Bitte legen Sie unter `Verzeichnisse > Verordnungen` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

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
|Informatik|**Ja**|
|Philosophie|Nein|
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
|Technik|Nein|
|Pädagogik|Nein|
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

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel |Schlüssel |Bedeutung|
|--|--|--|
|1PF |1PF |1. Prüfungsfach|
|2PF |2PF |2. Prüfungsfach|
|3PF |3PF |3. Prüfungsfach|
|4PF |4PF |4. Prüfungsfach|
|5PF |5PF |5. Prüfungsfach|
|Pflicht|Pflicht|Pflichtbereich|
|Freiw|Freiw|freiwillig|

!!! info "Hinweis"

    Über den zugewiesenen Fachstatus werden die Fächer als Leistungskurs (LK) bzw. Grundkurse (GK) identifiziert. D.h. Fächer mit der Zuweisung in der Spalte „Fachstatus“ "1PF/2PF" sind Leistungskurse. Grundkurse werden durch den Fachstatus "nicht 1PF/2PF" identifiziert.

## Unterrichtsart

Die Unterrichtsart muss unter ```Abitur > Qualifikation > Unterrichtsart``` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Unterrichtsart``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel| Schlüssel |Bedeutung|
|--|--|--|
|LK |LK |Leistungskurs  (LK wird für das Abitur und die Fachhochschulreife, nicht durch Unterrichtsart sondern durch Fachstatus "1PF/2PF" identifiziert.)|
|GK| GK |Grundkurs (GK wird für das Abitur und die Fachhochschulreife, nicht durch Unterrichtsart sondern durch nicht erfolgten Eintrag der Fachstatus "1PF/2PF" identifiziert.)|
|DB|DB|Die Unterrichtsart kann verwendet werden, damit die Kursergebnisse beim Initialisieren mit einbezogen werden.|
|Diff|Diff|Die Unterrichtsart kann verwendet werden, damit die Kursergebnisse beim Initialisieren mit einbezogen werden.|
|BU|BU|Die Unterrichtsart kann verwendet werden, damit die Kursergebnisse beim Initialisieren mit einbezogen werden.|
|BÜ|BÜ|Die Unterrichtsart kann verwendet werden, damit die Kursergebnisse beim Initialisieren mit einbezogen werden.|
|BBL|BBL|(Berufsbezogener Lernbereich)Die Unterrichtsart kann verwendet werden, damit die Kursergebnisse beim Initialisieren mit einbezogen werden.|

!!! info "Hinweis"

    Mit der Ausgabe des Skriptes ab Version 6.5.33 werden beim Initialisieren nur noch Kurse berücksichtigt, die mit einer der oben genannten Unterrichtsart markiert sind. Durch diese Änderung werden gezielt Kurse von der Berücksichtigung im Abitur ausgeschlossen. In den Fachdaten erfasste Zeilen, die beispielsweise das Arbeits- und Sozialverhalten beinhalten, bleiben so außen vor.

## Merkmal

Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden.

|Merkmal |Bedeutung|
|--|--|
|A| Fremdsprache Anfänger (2 Kurse müssen eingebracht werden)|
|A12| Fremdsprache, welche erst ab der 12 belegt wird|

## Besondere Lernleistung und Facharbeit

Im Menü Abitur|Prüfung tragen Sie unter „Lernleistung“ das Fach und Thema der Besonderen Lernleistung ein.
Die Endnote der besonderen Lernleistung weisen Sie im Menü Abitur|Prüfung unter „Lernleistung“ im ersten "Punkte" Feld (links) zu.

!!! info "Hinweis"

    Ausgabe der Besonderen Lernleistung bzw. der Facharbeit auf dem Zeugnis der Allgemeinen Fachhochschulreife. 
Auf dem Zeugnis kann wahlweise zwischen einer **Facharbeit** und einer **Besondere Lernleistung** gewählt werden.

* Zur Ausgabe der **Besondere Lernleistung**  müssen Sie im Menü ``Abitur`` unter der Registerkarte ``Prüfung > Lernleistung`` das entsprechende Fach zuweisen und das Optionsfeld ``Lernleistung einbringen`` markieren. Das Thema der besonderen Lernleistung weisen Sie analog dem entsprechenden Feld im Feld "Thema" zu. Die Note für die besondere Lernleistung im Block1 tragen Sie im 1. Notenfeld ganz links ein. Die Noten für Block2 tragen Sie in den 2 Notenfeldern daneben ein.

![Eintragung der besonderen Lernleistung](/assets/images/nrw.apo.bk.2012.bl.png)

* Zur Ausgabe der **Facharbeit** müssen Sie im Menü  ``Abitur``unter der Registerkarte ``Prüfung > Projekt`` das entsprechende Fach zuweisen und das Optionsfeld ``Projekt einbringen`` markieren. Das Thema des Projektes weisen Sie analog dem entsprechenden Feld im Feld "Thema" zu. Die Note für die Facharbeit" im Block1 tragen Sie im 1. Notenfeld ganz links ein. Die Noten für Block2 tragen Sie in den 2 Notenfeldern daneben ein.

![Eintragung der Facharbeit](/assets/images/nrw.apo.bk.2012.fa.png)
