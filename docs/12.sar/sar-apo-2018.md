# SAR-APO-2018 (GOS 2.0 - in Vorbereitung)

## Quelle

!!! info "Hinweis"

     Basierend auf der Verordnung zur Änderung der Verordnung [– Schul-und Prüfungsordnung über die gymnasiale Oberstufe und die Abiturprüfung im Saarland vom 17. April 2018](http://sl.juris.de/cgi-bin/landesrecht.py?d=http://sl.juris.de/sl/gesamt/OberStV_SL_2007.htm#OberStV_SL_2007_rahmen)

## Verzeichnis Verordnung

Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

| Spalte       | Wert                                     |
|--------------|------------------------------------------|
| Kürzel       | beliebig                                 |
| Bezeichnung  | beliebig                                 |
| Kategorie    | Abitur                                   |
| Typ          | dieser Eintrag in ```Magellan > Verzeichnisse > Verordnungen > Typ``` kennzeichnet Schulform: |
| Ab Jahrgang  | leer                                       |
| Skript       | ```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server) |
| Notenart 11  | leer _(Einführungsphase, Gymnasien: Klassenstufe 10, Gemeinschaftsschule: Klassenstufe 11)_ |
| Notenart 12  | Punkte _(Hauptphase, Gymnasien: 11/1 und 11/2, Gemeinschaftsschule: 12/1 und 12/2)_      |
| Notenart 13  | Punkte  _(Hauptphase, Gymnasien: 12/1 und 12/2, Gemeinschaftsschule: 13/1 und 13/2)_     |
| Notenart BBS | leer                                     |
| Gültig von   | leer                                     |
| Gültig bis   | leer                                     |

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

| Aufgabenbereich            |
|----------------------------|
| sprachl.-lit.-künstlerisch |
| gesellschaftswiss.         |
| mathem.-nat.-technisch     |
| Religion                   |
| Sport                      |

## Unterrichtsart

Die Unterrichtsart muss unter ```Abitur > Qualifikation > Unterrichtsart``` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Unterrichtsart``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```, dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

Die zu belegenden Fächer werden Kurse genannt. Bei den Kursen wird zwischen Kursen, die auf grundlegendem Anforderungsniveau (G-Kurse) und solchen, die auf erhöhtem Anforderungsniveau (L-Kurse) unterschieden:

| Kürzel | Schlüssel | Bedeutung                                |
|--------|-----------|------------------------------------------|
| L-Kurs | L         | L-Kurs / Kurs mit erhöhtem Anforderungsniveau |
| G-Kurs | G         | G-Kurs / Kurs mit grundlegendem Anforderungsniveau |

!!! info "Hinweis"

     Das Seminarfach erhält die Unterrichtsart  "G-Kurs".

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung                |
|--------|-----------|--------------------------|
| 1PF    | 1PF       | 1. Prüfungsfach (L-Kurs) |
| 2PF    | 2PF       | 2. Prüfungsfach (L-Kurs) |
| 3PF    | 3PF       | 3. Prüfungsfach (G-Kurs) |
| 4PF    | 4PF       | 4. Prüfungsfach (G-Kurs) |
| 5PF    | 5PF       | 5. Prüfungsfach (G-Kurs) |

!!!info "Hinweis"
    Die Abiturprüfung erfolgt in vier Fächern schriftlich und in einem Fach mündlich. In den schriftlich geprüften Fächern sind zusätzlich mündliche Prüfungen möglich.

## Merkmal

Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden.

| Merkmal | Bedeutung                                |
|---------|------------------------------------------|
| A       | Fremdsprache Anfänger (2 Kurse müssen eingebracht werden) |

## Die Besondere Lernleistung

Laut der zugrundliegenden Abiturverordnung muss die besondere Lernleistung im Kursbereich und nicht im Prüfungsbereich eingebracht werden. Aus diesem Grund müssen die einzubringenden Noten der besonderen Lernleistung als normale Fachnoten auf der Registerkarte ``Abitur > Qualifikation`` eingegeben werden und nicht wie sonst üblich auf der Registerkarte ``Abitur > Prüfung``.
