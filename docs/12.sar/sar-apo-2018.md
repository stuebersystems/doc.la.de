# SAR-APO-2018 (GOS 2.0)

## Quelle

!!! info "Hinweis"

     Basierend auf der Verordnung zur Änderung der Verordnung [– Schul-und Prüfungsordnung über die gymnasiale Oberstufe und die Abiturprüfung im Saarland vom 17. April 2018]

## Verzeichnis Verordnung

Bitte legen Sie unter `Verzeichnisse > Verordnungen` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

| Spalte       | Wert                                     |
|--------------|------------------------------------------|
| Kürzel       | beliebig                                 |
| Bezeichnung  | beliebig                                 |
| Kategorie    | Abitur                                   |
| Typ          | dieser Eintrag in `MAGALLAN> Verzeichnisse > Verordnungen > Typ` kennzeichnet Schulform: |
| Ab Jahrgang  | leer                                       |
| Skript       | ```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server) |
| Notenart 11  | leer _(Einführungsphase, Gymnasien: Klassenstufe 10, Gemeinschaftsschule: Klassenstufe 11)_ |
| Notenart 12  | Punkte _(Hauptphase, Gymnasien: 11/1 und 11/2, Gemeinschaftsschule: 12/1 und 12/2)_      |
| Notenart 13  | Punkte  _(Hauptphase, Gymnasien: 12/1 und 12/2, Gemeinschaftsschule: 13/1 und 13/2)_     |
| Notenart BBS | leer                                     |
| Gültig von   | leer                                     |
| Gültig bis   | leer                                     |

## Fachkategorien

Berechnungsskripte erkennen relevante Fächer anhand der Eintragungen unter `Extras > Schlüsselverzeichnisse > Fächer > Fachkategorie`.
Dabei müssen, je nach Verordnung, einige Fächer besonders berücksichtigt werden. Für diese Fächer sind die zu verwendenden Fachkategorien fest vorgeschrieben. Alle anderen Fächer können mit einer der übrigen Fachkategorie gekennzeichnet werden oder ohne Fachkategorie geführt werden.

|Fachkategorien|Muss genutzt werden|
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

## Seminarfach

Legen Sie als Seminarfach bitte eine Fach mit der Fachkategorien "Seminar" an. Das Seminarfach erhält die Unterrichtsart  "G-Kurs".

## Die Besondere Lernleistung

Zur Ausgabe der besonderen Lernleistung müssen Sie im Menü `Abitur“` auf der Registerkarte `Prüfung > Lernleistung` das entsprechende **Fach** zuweisen. Das Thema der besonderen Lernleistung weisen Sie analog dem entsprechenden Feld im Feld **Thema** zu.

Das Ergebnis tragen Sie bitte im Feld **Punkte** ganz links ein.

Die Vorschlagsautomatik weist Sie darauf hin, ob das Einbringen der Lernleistung günstiger ist, als das Einringen des Seminarfaches. 

Wenn Sie diese einbringen wollen, setzen Sie nun den Haken vor **Lernleistung einbringen und** tragen Sie unter `Abitur > Qualifikation` anstelle der Seminarfach-Noten für diese beiden Halbjahre die Noten der Besonderen Lernleistung ein. Die Noten müssen den Präfix "bL" haben.

Das `Verzeichnis > Noten` müssen Sie entsprechend für die Noten der Besonderen Lernleistung anpassen.

Notenkürzel|Bezeichnung|Notenwert| Notenart
-|-|-|-
bL00|ungenügend|0|Punktwert
bL01|mangelhaft|1|Punktwert
bL02|mangelhaft|2|Punktwert
bL03|mangelhaft|3|Punktwert
bL04|ausreichend|4|Punktwert
bL05|ausreichend|5|Punktwert
bL06|ausreichend|6|Punktwert
bL07|befriedigend|7|Punktwert
bL08|befriedigend|8|Punktwert
bL09|befriedigend|9|Punktwert
bL10|gut|10|Punktwert
bL11|gut|11|Punktwert
bL12|gut|12|Punktwert
bL13|sehr gut|13|Punktwert
bL14|sehr gut|14|Punktwert
bL15|sehr gut|15|Punktwert

Führen Sie danach das Berechnungsskript erneut aus.
