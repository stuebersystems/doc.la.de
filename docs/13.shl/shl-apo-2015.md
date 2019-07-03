# SHL-APO-2015

## Verzeichnis Verordnung

Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

| Spalte       | Wert                                                                         |
| ------------ | ---------------------------------------------------------------------------- |
| Kürzel       | beliebig                                                                     |
| Bezeichnung  | beliebig                                                                     |
| Kategorie    | Abitur                                                                       |
| Typ          | leer                                                                         |
| Ab Jahrgang  | leer                                                                         |
| Skript       | ```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server) |
| Notenart 11  | Noten oder Punkte                                                            |
| Notenart 12  | Punkte                                                                       |
| Notenart 13  | Punkte                                                                       |
| Notenart 13  | Punkte                                                                       |
| Notenart BBS | leer                                                                         |
| Gültig von   | leer                                                                         |
| Gültig bis   | leer                                                                         |

## Fachkategorien

Jedem Fach, dass Sie in der Oberstufe verwenden, müssen Sie eine Kategorie unter ```Verzeichnisse > Fächer > Kategorie``` zuweisen.
Folgende Fachkategorien werden durch das Abiturqualifikationsskript verwendet, bitte verwenden Sie nur die gekennzeichneten Fachkategorien.

| Fachkategorien        | Wird vom Skript berücksichtigt |
| --------------------- | ------------------------------ |  
| Fremdsprache          | **Ja**                         |
| Religion/Ethik        | **Ja**                         |
| Deutsch               | **Ja**                         |
| Mathematik            | **Ja**                         |
| Kunst                 | **Ja**                         |
| Musik                 | Nein                           |
| Sport                 | **Ja**                         |
| Informatik            | **Ja**                         |
| Philosophie           | **Ja**                         |
| Geschichte            | **Ja**                         |
| Physik                | **Ja**                         |
| Chemie                | **Ja**                         |
| Biologie              | **Ja**                         |
| Erdkunde              | **Ja**                         |
| Sozialkunde           | Nein                           |
| Wirtschaft            | **Ja**                         |
| Politik               | **Ja**                         |
| Darstellendes Spiel   | Nein                           |
| Evangelische Religion | Nein                           |
| Katholische Religion  | Nein                           |
| Technik               | Nein                           |
| Pädagogik             | Nein                           |
| Sporttheorie          | Nein                           |
| BWL/RW                | Nein                           |
| BWL/VWL               | Nein                           |
| VWL                   | Nein                           |
| Seminar               | Nein                           |
| Gesundheit            | Nein                           |
| Psychologie           | Nein                           |
| Recht                 | Nein                           |
| Literatur             | Nein                           |

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

| Kürzel | Schlüssel | Bedeutung                   |
| ------ | --------- | --------------------------- |
| PeF    | PeF       | Profil ergänzendes Fach     |
| P      | P         | Profil                      |
| E      | E         | Fach mit erweitertem Niveau |
| BL     | BL        | Besondere Lernleistung      |

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden.

Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel  | Schlüssel | Bedeutung                                               |
| ------- | --------- | ------------------------------------------------------- |
| 1PF     | 1PF       | 1. Prüfungsfach                                         |
| 2PF     | 2PF       | 2. Prüfungsfach                                         |
| 3PF     | 3PF       | 3. Prüfungsfach                                         |
| 4PF     | 4PF       | 4. Prüfungsfach                                         |
| 5PF     | 5PF       | 5. Prüfungsfach                                         |
| Pflicht | Pflicht   | Pflichtbereich (kein Eintrag wird wie Pflicht gewertet) |

## Merkmal

Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden.

| Merkmal | Bedeutung                                                 |
| ------- | --------------------------------------------------------- |
| A       | Fremdsprache Anfänger (2 Kurse müssen eingebracht werden) |

## Besondere Lernleistung

**Einbringen in Block I:**

1) Definieren Sie ein entsprechendes Fach
2) Legen Sie unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten``` eine Unterrichtsart mit dem Kürzel BL an (falls nicht vorhanden) und weisen Sie diese dem entsprechenden Fach zu
Im Menü ```Abitur > Prüfung``` tragen Sie unter ```Besondere Lernleistung``` das Fach und Thema der Besonderen Lernleistung ein.

**Einbringen in Block II:**

Auf der Registerkarte ```Abitur > Qualifikation``` weisen Sie dem Fach den Fachstatus 5. PF zu.
Im Menü ```Abitur > Prüfung``` tragen Sie unter ```Besondere Lernleistung``` das Fach, die Punktanzahl im linken Kästchen und das Thema der Besonderen Lernleistung ein. Bitte haken Sie ```Lernleistung einbringen``` an.

## Präsentationsprüfung

Auf der Registerkarte ```Abitur > Qualifikation``` weisen Sie dem Fach den Fachstatus 4. PF oder 5.PF (je nach Verordnung) zu.
Im Menü Abitur|Prüfung tragen Sie unter Präsentation das Fach, die Punktanzahl im linken Kästchen und das Thema der Präsentation ein. Bitte haken Sie ```Präsentationsprüfung einbringen``` an.

## Sport

Für die Eingabe der Fachpraxis in Sport geben Sie bitte auf der Registerkarte ``Prüfung`` im Feld ``Fachpraxis`` bei Fach das Fach Sport an. Die Note der Sportfachpraxis geben Sie bitte bei Note 1 an. Bei der mdl. Note im 4. Prüfungsfach Sport geben Sie bitte die Note der mdl. Prüfung in Sport an.
