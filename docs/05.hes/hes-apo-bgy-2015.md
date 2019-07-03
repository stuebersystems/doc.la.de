# HES-APO-BGY-2015

Abiturqualifikationsberechnung Hessen für berufliche Gymnasien nach der Abiturprüfungsordnung vom 20. Juli 2009, in der letzten Fassung vom 1. April 2015.

## Verzeichnis Verordnung

Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

| Spalte  | Wert |
|--------------|------------------------------------------|
| Kürzel  | beliebig  |
| Bezeichnung  | beliebig  |
| Kategorie | Abitur  |
| Typ   | leer oder "WI" für Wirtschaft  |
| Ab Jahrgang  | leer |
| Skript  | ```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server) |
| Notenart 11  | Noten oder Punkte   |
| Notenart 12  | Punkte  |
| Notenart 13  | Punkte  |
| Notenart 13  | Punkte  |
| Notenart BBS | leer |
| Gültig von   | leer |
| Gültig bis   | leer |

## Fachkategorien

Jedem Fach, dass Sie in der Oberstufe verwenden, müssen Sie eine Kategorie unter ```Verzeichnisse > Fächer > Kategorie``` zuweisen.
Folgende Fachkategorien werden durch das Abiturqualifikationsskript verwendet, bitte verwenden Sie nur die gekennzeichneten Fachkategorien.

| Fachkategorien | Wird vom Skript berücksichtigt |
|--|--|
| **Fremdsprache** |**Ja**|
| **Religion/Ethik** |**Ja**|
| **Deutsch** |**Ja**|
| **Mathematik** |**Ja**|
| **Kunst** |**Ja**|
| Musik |Nein|
| **Sport** |**Ja**|
| **Informatik**|**Ja**|
| Philosophie |Nein|
| **Geschichte**|**Ja**|
| **Physik**|**Ja**|
| **Chemie**|**Ja**|
| **Biologie**|**Ja**|
| Erdkunde|Nein|
| Sozialkunde |Nein|
| **Wirtschaft** | Ja ( fürs Fach "Wirtschaft und Politik" Fachrichtung WI) |
| **Politik** |**Ja**|
| **Darstellendes Spiel** |**Ja**|
| **Evangelische Religion** | bitte **Religion/Ethik** verwenden|
| **Katholische Religion**| bitte **Religion/Ethik** verwenden|
| Technik |Nein|
| Pädagogik |Nein|
| Sporttheorie |Nein|
| **BWL/RW**| Ja, für das Fach "Rechnungswesen" Fachrichtung WI) |
| **BWL/VWL** | Ja, für das Fach "Wirtschaftslehre" Fachrichtungen WI) |
| VWL|Nein|
| Seminar |Nein|
| Gesundheit|Nein|
| Psychologie |Nein|
| Recht |Nein|
| **Literatur** |**Ja**|

## Aufgabenbereiche

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter ```Verzeichnisse > Fächer > Spalte Aufgabenbereich``` verwendet werden:

| Aufgabenbereich  |
|----------------------------|
| sprachl.-lit.-künstlerisch |
| gesellschaftswiss.  |
| mathem.-nat.-technisch  |
| Religion  |
| Sport   |

## Unterrichtsart

Die Unterrichtsart muss unter ```Abitur > Qualifikation > Unterrichtsart``` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Unterrichtsart``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung  |
|--------|-----------|---------------|
| LK  | LK | Leistungskurs |
| GK  | GK | Grundkurs  |
| FA  | FA | Facharbeit |

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung |
|--------|-----------|------------------------------------------|
| 1PF | 1PF  | 1. Prüfungsfach  |
| 2PF | 2PF  | 2. Prüfungsfach  |
| 3PF | 3PF  | 3. Prüfungsfach  |
| 4PF | 4PF  | 4. Prüfungsfach  |
| 5PF | 5PF  | 5. Prüfungsfach  |
| 5PFBLL | 5PFBLL | 5. Prüfungsfach und besondere Lernleistung |
| Ersatz | Ersatz | Ersatz  |

## Merkmal

Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden.

| Merkmal | Bedeutung |
|---------|------------------------------------------|
| A  | Fremdsprache Anfänger (2 Kurse müssen eingebracht werden) |
