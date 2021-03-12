# MVP-APO-FG-2019 (in Planung)

Oberstufen- und Abiturprüfungsverordnung
(Abiturprüfungsverordnung - APVO M-V) vom 19. Februar 2019

[Link zur Oberstufen- und Abiturprüfungsverordnung](http://www.landesrecht-mv.de/jportal/portal/page/bsmvprod.psml;jsessionid=78CA6AAE794574D9CB4CAD793DDB3466.jp26?showdoccase=1&st=lr&doc.id=jlr-AbiPrVMVrahmen&doc.part=X&doc.origin=bs)

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
|Informatik|Nein|
|Philosophie|**Ja**|
|Geschichte|**Ja**|
|Physik|**Ja**|
|Chemie|**Ja**|
|Biologie|**Ja**|
|Erdkunde|Nein|
|Sozialkunde|Nein|
|Wirtschaft|Nein|
|Politik|**Ja**|
|Darstellendes Spiel|Nein|
|Evangelische Religion|Nein|
|Katholische Religion|Nein|
|Technik|Nein|
|Pädagogik|Nein|
|Sporttheorie|Nein|
|Seminar|Nein|
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

## Unterrichtsart

Die Unterrichtsart muss unter `Abitur > Qualifikation > Unterrichtsart` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus `Schüler > Zeugnis > Fächer > Unterrichtsart` übernommen werden.
Prüfen Sie bitte unter `Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten`,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel| Schlüssel |Bedeutung|
|--|--|--|
L-Kurs | L  | Leistungskurse (L-Kurse), Kurse auf erhöhtem Anforderungsniveau
G-Kurs | G | Grundkurse (G-Kurse), Kurs auf grundlegendem Anforderungsniveau

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel |Schlüssel |Bedeutung|
|--|--|--|
|1PF |1PF |1. Prüfungsfach|
|2PF |2PF |2. Prüfungsfach|
|3PF |3PF |3. Prüfungsfach|
|4PF |4PF |4. Prüfungsfach|
|5PF |5PF |5. Prüfungsfach (mündlich)|

## Berufliche Fächer / Berufliche Schwerpunktfächer

Beruflichen Fächern und beruflichen Schwerpunktfächern weisen Sie im `Schlüsselverzeichnisse > Fächer` im Feld "Zeugnismerkmal" vorgegebenes Merkmal zu:

Zeugnismerkmal | verwendet für
--|--
BSF | berufliches Schwerpunktfach
BF | berufliche Fach

![`Schlüsselverzeichnisse > Fächer`](/assets/images/MVP/mvp001.png)

## Besondere Lernleistung

Hier müssen Sie im Menü `Abitur > Prüfung` im Bereich „Lernleistung“ das entsprechende Fach zuweisen und das Optionsfeld „Lernleistung einbringen“ markieren. Das Thema der besonderen Lernleistung weisen Sie analog dem entsprechenden Feld im Feld "Thema" zu. Das Gesamtergebnis in einfacher Wertung tragen Sie im 1. Notenfeld ganz links ein.

## Facharbeit

Zur Ausgabe der „Facharbeit“ müssen Sie im Menü  `Abitur > Prüfung` im Bereich "Projekt“ das entsprechende Fach zuweisen und das Optionsfeld „Projekt einbringen“ markieren. Das Thema des Projektes weisen Sie analog dem entsprechenden Feld im Feld "Thema" zu. Das Gesamtergebnis in einfacher Wertung tragen Sie im 1. Notenfeld ganz links ein.