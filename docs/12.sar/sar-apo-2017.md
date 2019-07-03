# SAR-APO-2017

## Quelle

 !!!info "Hinweis"
    Basierend auf der Verordnung (G8-Abitur) [http://www.saarland.de/dokumente/thema_bildung/GOSVO.pdf](http://www.saarland.de/dokumente/thema_bildung/GOSVO.pdf)

## Verzeichnis Verordnung

Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

|Spalte|Wert|
|--|--|
|Kürzel|beliebig|
|Bezeichnung|beliebig|
|Kategorie|Abitur|
|Typ|dieser Eintrag in ```Magellan > Verzeichnisse > Verordnungen > Typ``` kennzeichnet Schulform:|
|Ab Jahrgang|leer|
|Skript|```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server)|
|Notenart 11|Noten oder Punkte|
|Notenart 12|Punkte|
|Notenart 13|Punkte|
|Notenart BBS|leer|
|Gültig von |leer|
|Gültig bis|leer|

## Fachkategorien

Jedem Fach, dass Sie in der Oberstufe verwenden, müssen Sie eine Kategorie unter ```Verzeichnisse > Fächer > Kategorie``` zuweisen.
Folgende Fachkategorien werden durch das Abiturqualifikationsskript verwendet, bitte verwenden Sie nur die gekennzeichneten Fachkategorien.

|Fachkategorien|Wird vom Skript berücksichtigt|
|--|--|
|Fremdsprache| **Ja** |
|Religion/Ethik| **Ja** |
|Deutsch| **Ja** |
|Mathematik| **Ja** |
|Kunst| **Ja** |
|Musik| **Ja** |
|Sport| **Ja** |
|Informatik| **Ja** |
|Philosophie| **Ja** |
|Geschichte| **Ja** |
|Physik| **Ja** |
|Chemie| **Ja** |
|Biologie| **Ja** |
|Erdkunde| **Ja** |
|Sozialkunde| **Ja** |
|Wirtschaft| Nein |
|Politik| **Ja**|
|Darstellendes Spiel| bitte **Kunst** verwenden   |
|Evangelische Religion| bitte **Religion/Ethik** verwenden |
|Katholische Religion| bitte **Religion/Ethik** verwenden |
|Technik| Nein |
|Pädagogik| Nein|
|Sporttheorie| Nein |
|BWL/RW| Nein|
|BWL/VWL| Nein |
|VWL| Nein |
|Seminar| **Ja** |
|Gesundheit| Nein |
|Psychologie| Nein |
|Recht| Nein |
|Literatur| Nein |

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
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```, dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel|Schlüssel |Bedeutung|
|--|--|--|
|E-Kurs|E |E-Kurs / Fach mit erhöhtem Anforderungsniveau|
|G-Kurs|G|G-Kurs / Fach mit grundlegendem Anforderungsniveau|
|NF|NF|Neigungsfach|

!!!warning: "Wichtig"
    Unterrichtsart kann mit "Kurs" oder mit "E-Kurs" und "G-Kurs" oder einer beliebigen anderen Bezeichnung gewählt werden. Das Seminarfach kann ebenfalls beliebig durch die Unterrichtsart gekennzeichnet werden.
Das Neigungsfach wir durch die 'Unterrichtsart "NF" gekennzeichnet.

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```, dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel |Schlüssel |Bedeutung|
|--|--|--|
|1PF|1PF|1. Prüfungsfach|
|2PF|2PF|2. Prüfungsfach|
|3PF|3PF|3. Prüfungsfach|
|4PF|4PF|4. Prüfungsfach|
|5PF|5PF|5. Prüfungsfach (nur mündlich) Pflichtbereich
|abgew|abgew|abgewählt|

## Merkmal

Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden.

|Merkmal |Bedeutung|
|--|--|
|2|Das 2x zählende Fach muss mit "2" in der Spalte "Merkmal" vermerkt werden.|
|B|2. Fremdsprache Anfänger|
