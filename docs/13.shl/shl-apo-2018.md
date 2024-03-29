# SHL-APO-2018

[1]:/assets/images/SHL/shl03.png
[2]:/assets/images/SHL/shl01.png
[3]:/assets/images/SHL/shl02.png

Gemäß Landesverordnung über die Gestaltung der Oberstufe und der Abiturprüfung in den Gymnasien und Gemeinschaftsschulen [(OAPVO) vom 2. Juli 2018](http://www.gesetze-rechtsprechung.sh.juris.de/jportal/;jsessionid=449BEADD591E4B730538EA0AD58846A3.jp10?quelle=jlink&query=GymOAbiPrO+SH&psml=bsshoprod.psml&max=true&aiz=true#jlr-GymOAbiPrOSH2018rahmen).

## Verzeichnis Verordnung

Bitte legen Sie unter `Extras > Schlüsselverzeichnisse > Verordnungen` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

| Spalte       | Wert                                                                        |
| ------------ | --------------------------------------------------------------------------- |
| Kürzel       | beliebig                                                                    |
| Bezeichnung  | beliebig                                                                    |
| Kategorie    | Abitur                                                                      |
| Typ          | leer                                                                        |
| Ab Jahrgang  |  10 für G8 oder 11 für G9                                                   |
| Skript       | ```...\Ihre Region\Ihr_Skript.js``` (Pfad zur Skriptdatei auf Ihrem Server) |
| Notenart 11  | Noten oder Punkte                                                           |
| Notenart 12  | Punkte                                                                      |
| Notenart 13  | Punkte                                                                      |
| Notenart 13  | Punkte                                                                      |
| Notenart BBS | leer                                                                        |
| Gültig von   | leer                                                                        |
| Gültig bis   | leer                                                                        |

## Fachkategorien

Berechnungsskripte erkennen relevante Fächer anhand der Eintragungen unter `Extras > Schlüsselverzeichnisse > Fächer` im Feld "Fachkategorie". 
Dabei müssen, je nach Verordnung, einige Fächer besonders berücksichtigt werden. Für diese Fächer sind die zu verwendenden Fachkategorien fest vorgeschrieben. Alle anderen Fächer können mit einer der übrigen Fachkategorie gekennzeichnet werden oder ohne Fachkategorie geführt werden.

|Fachkategorien|Muss genutzt werden|
|--|--| 
| Fremdsprache          | **Ja**                         |
| Religion/Ethik        | **Ja**                         |
| Deutsch               | **Ja**                         |
| Mathematik            | **Ja**                         |
| Kunst                 | **Ja**                         |
| Musik                 | Nein                           |
| Sport                 | **Ja**                         |
| Informatik            | **Ja**                         |
| Philosophie           | Nein                           |
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

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter `Extras > Schlüsselverzeichnisse > Fächer` in Spalte "Aufgabenbereich" verwendet werden:

|Aufgabenbereich|
|--|
|sprachl.-lit.-künstlerisch|
|gesellschaftswiss.|
|mathem.-nat.-technisch|
|Religion|
|Sport|

## Unterrichtsart

Die Unterrichtsart muss im Bereich `Abitur > Qualifikation` in Spalte "Unterrichtsart" zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus dem Bereich `Schüler > Zeugnis > Fächer` aus der Spalte "Unterrichtsart" übernommen werden.
Prüfen Sie bitte unter `Extras > Schlüsselverzeichnisse > Unterrichtsarten`,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung                   |
| ------ | --------- | --------------------------- |
| PeF    | PeF       | Profil ergänzendes Fach     |
| P-Kurs | P         | Profil gebendes Fach |
| E-Kurs | E         | Fach mit erhöhtem Anforderungsniveau / Kernfach |
| BL     | BL        | Besondere Lernleistung      |

## Fachstatus

Der Fachstatus muss im Bereich `Abitur > Qualifikation` in Spalte "Fachstatus" zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus dem Bereich `Schüler > Zeugnis > Fächer` aus der Spalte "Fachstatus" übernommen werden.
Prüfen Sie bitte unter `Extras > Schlüsselverzeichnisse > Fachstatus`,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel  | Schlüssel | Bedeutung                                               |
| ------- | --------- | ------------------------------------------------------- |
| 1PF     | 1PF       | 1. Prüfungsfach                                         |
| 2PF     | 2PF       | 2. Prüfungsfach                                         |
| 3PF     | 3PF       | 3. Prüfungsfach                                         |
| 4PF     | 4PF       | 4. Prüfungsfach                                         |
| 5PF     | 5PF       | 5. Prüfungsfach                                         |

## Kennzeichnung Fremdsprache Anfänger

Im Bereich `Abitur > Qualifikation` müssen Sie der Fremdsprache Anfänger im Feld "Merkmal" folgenden Eintrag zuweisen. Dieses Merkmal kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus dem Bereich `Schüler > Zeugnis > Fächer` aus der Spalte "Merkmal" übernommen werden.

| Merkmal | Bedeutung                                                 |
| ------- | --------------------------------------------------------- |
| A       | Fremdsprache Anfänger (2 Kurse müssen eingebracht werden) |

## Besondere Lernleistung

### Einbringen in Block I

1) Definieren Sie ein entsprechendes Fach
2) Legen Sie unter `Extras > Schlüsselverzeichnisse > Unterrichtsarten` eine Unterrichtsart mit dem Kürzel `BL` an (falls nicht vorhanden) und weisen Sie diese dem entsprechenden Fach zu.
Im Menü `Abitur > Prüfung` tragen Sie unter `Besondere Lernleistung` das Fach und Thema der Besonderen Lernleistung ein.

### Einbringen in Block II

Im Bereich `Abitur > Qualifikation` weisen Sie dem Fach den Fachstatus `5PF` zu.
Unter `Abitur > Prüfung` tragen Sie unter `Besondere Lernleistung` das Fach, die Punktanzahl im linken Kästchen und das Thema der Besonderen Lernleistung ein. Bitte haken Sie `Lernleistung einbringen` an.

## Präsentationsprüfung

Auf der Registerkarte `Abitur > Qualifikation` weisen Sie dem Fach den Fachstatus `4PF` oder `5PF` (je nach Verordnung) zu.
Im Menü `Abitur > Prüfung` tragen Sie unter Präsentation das Fach, die Punktanzahl im linken Kästchen und das Thema der Präsentation ein. Bitte haken Sie `Präsentationsprüfung einbringen` an.

## Sport

Für die Eingabe der Fachpraxis in Sport geben Sie bitte im Bereich `Abitur > Prüfung` im Feld `Fachpraxis` beim Fach das Fach Sport an. Die Note der Sportfachpraxis geben Sie bitte bei "Note 1" an.
Bei der mdl. Note im 4. Prüfungsfach Sport geben Sie bitte die Note der mdl. Prüfung in Sport an.

## GER-Niveau

Das Berechnungsskript **SHL-APO-2018** ermittelt das GER-Niveau der belegten Fremdsprachen. Dafür müssen folgende Voraussetzungen erfüllt sein:

Legen Sie unter `Extras > Schlüsselverzeichnisse > Sprachreferenzen` folgende Werte an:

| Kürzel | Schlüssel | Bezeichnung  |
| ------ | --------- | ------------ |
| A2/A2+ | A2/A2+    | frei wählbar |
| B2     | B2        | frei wählbar |
| B1     | B1        | frei wählbar |
| B1+    | B1+       | frei wählbar |
| B2/C1  | B2/C1     | frei wählbar |

[![Schlüsselverzeichnis > Sprachreferenzen][1]][1]

Ihre Fremdsprachen müssen unter `Extras > Schlüsselverzeichnisse > Fächer` mit den statitistikrelevanten Schlüsseln befüllt sein. Aktuell werden folgende Schlüssel verwendet:

| Fachschlüssel | Bezeichnung                                              |
| ------------- | -------------------------------------------------------- |
| 216K          | Englisch - 1. Fremdsprache, fortgeführt                  |
| 116           | Englisch - 1. Fremdsprache (Fach)(Kurs, neu begonnen)    |
| 216F          | Englisch - 2. Fremdsprache                               |
| 416K          | Englisch - 2. Fremdsprache, fortgeführt (Kurs)           |
| 316K          | Englisch - 2. Fremdsprache, neu begonnen                 |
| 316F          | Englisch - 3. Fremdsprache                               |
| 222K          | Französisch - 1. Fremdsprache, fortgeführt (Kurs)        |
| 122           | Französisch - 1. Fremdsprache (Fach)(Kurs, neu begonnen) |
| 222F          | Französisch - 2. Fremdsprache (Fach)                     |
| 322K          | Französisch - 2. Fremdsprache, neu begonnen (Kurs)       |
| 422K          | Französisch - 2. Fremdsprache, fortgeführt (Kurs)        |
| 322F          | Französisch - 3. Fremdsprache (Fach)                     |
| 422F          | Französisch - 4. Fremdsprache (Fach)                     |
| 251K          | Spanisch - 1. Fremdsprache, fortgeführt (Kurs)           |
| 251F          | Spanisch - 2. Fremdsprache (Fach)                        |
| 351K          | Spanisch - 2. Fremdsprache, neu begonnen (Kurs)          |
| 451K          | Spanisch - 2. Fremdsprache, fortgeführt (Kurs)           |
| 351F          | Spanisch - 3. Fremdsprache (Fach)                        |
| 451F          | Spanisch - 4. Fremdsprache (Fach)                        |
| 251K          | Dänisch - 1. Fremdsprache, fortgeführt (Kurs)            |
| 251F          | Dänisch - 1. Fremdsprache (Fach)(Kurs, neu begonnen)     |
| 351K          | Dänisch - 2. Fremdsprache (Fach)                         |
| 451K          | Dänisch - 2. Fremdsprache, neu begonnen (Kurs)           |
| 351F          | Dänisch - 2. Fremdsprache, fortgeführt (Kurs)            |
| 451F          | Dänisch - 3. Fremdsprache (Fach                          |
| 451F          | Dänisch - 4. Fremdsprache (Fach)                         |
| 245K          | Russisch - 1. Fremdsprache, fortgeführt (Kurs)           |
| 445F          | Russisch - 2. Fremdsprache, fortgeführt (Kurs)           |
| 345K          | Russisch - 2. Fremdsprache, neu begonnen (Kurs           |
| 345F          | Russisch - 3. Fremdsprache (Fach)                        |
| 445F          | Russisch - 4. Fremdsprache (Fach)                        |
| 445           | Chinesisch                                               |

Wenn diese Bedingungen erfüllt sind, wird über Ausführen des Berechnungsskriptes `Neu berechnen` das erreichte GER-Niveau angezeigt und im Menü `Schüler > Daten 3` im Feld "Referenz" befüllt.

[![Meldefenster][2]][2]

[![Schüler > Daten 3][3]][3]
