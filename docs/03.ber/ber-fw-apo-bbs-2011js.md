# BER-FW-APO-BBS-2011.js

!!! info "Hinweis"

    Weitere wichtige Informationen finden Sie in der Magellan-Dokumentation im Abschnitt [Regionales > Berlin](https://doc.magellan7.stueber.de/schulverwaltung/regionales/berlin/berlin/) !

## Gültigkeit

!!! info "Hinweis"

    Diese Prüfung gilt aktuell nur für berufliche Gymnasien mit: 
    * Fachrichtung Wirtschaft
    * Fachrichtung Berufliche Informatik mit Schwerpunkt Wirtschaftsinformatik

## Verzeichnis Verordnung in Magellan

Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

|Spalte|Wert|
|--|--|
|Kürzel|beliebig|
|Bezeichnung|beliebig|
|Kategorie|Fachwahl|
|Typ|leer|
|Ab Jahrgang|leer|
|Skript|```...\Ihre Region\Ihr_Skript.js``` (Pfad zur Skriptdatei auf Ihrem Server)|
|Notenart 11|Noten oder Punkte|
|Notenart 12|Punkte|
|Notenart 13|Punkte|
|Notenart 13|Punkte|
|Notenart BBS|leer|
|Gültig von |leer|
|Gültig bis|leer|

## Verordnung in DaVinci hinterlegen

In der Ansicht ``Stammdaten > Klassen`` weisen Sie die Klassen bzw. Jahrgänge mit Kurssystem (Modus „Kurse“) aus und geben das Fachwahlskript an, nach dem die Fachwahl überprüft werden soll. Hinzu kommen ggf. weitere Angaben sind insbesondere für Fachwahlüberprüfungen notwendig, die mehrere Halbjahre überprüfen, z.B. in Berlin.

!!! info "Hinweis"

    In den „Kursplan“ Ansichten wird immer mit der Jahrgangsstufe (Spalte „Stufe“) gearbeitet. Wenn Sie z.b den Jahrgang 12 als eine Klasse „12“ eingegeben haben, sind Jahrgangstufe und Klasse gleichbedeutend. Wenn Sie den Jahrgang 12 in Klassen 12A, 12B, 12C aufteilen, werden alle Schüler dieser Klassen angezeigt. Sie wählen den Jahrgang aus, indem Sie über `Plan > Auswahl` eine Klasse auswählen. Angezeigt wird daraufhin der betreffende Jahrgang.

Die relevanten Spalten in der Ansicht ``Stammdaten > Klassen``:

|Spalte |Beschreibung|
|--|--|
|Modus |Stellen Sie hier „Kurse“ ein, dann kann zwischen diesen Klassen in der Ansicht „Kursplan“ geblättert werden.|
|Stufe |Jahrngsstufe. In den Kursplan-Ansichten wird immer mit der Stufe gearbeitet, nicht mit Klassen.|
|Startjahr |Startjahr der Klasse|
|Halbjahr |Nummer des Halbjahres, in dem sich die Klasse aktuell für diesen Planungszeitraum befindet, d.h. 1, 2, 3, 4, 5, 6 (E1=1, E2=2....Q3=5, Q4=6). Aus Startjahr und Halbjahresindex errechnet sich, welche Fächer der Schüler in diesem Zeitraum bzw. in diesem Halbjahr belegt hat.|
|Schüler|Die Schülerzahl wird automatisch berechnet.|
|Skript  |Geben Sie hier das Fachwahlskript an, das für die Fachwahlüberprüfung sorgt.|
|Verordnungstyp |leer|

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
|Wirtschaft| **Ja** |
|Politik| **Ja** |
|Darstellendes Spiel| **Ja** |
|Evangelische Religion| Nein |
|Katholische Religion| Nein |
|Technik| Nein |
|Pädagogik| Nein |
|Sporttheorie| **Ja** |
|BWL/RW| Nein |
|BWL/VWL| Nein |
|VWL| Nein |
|Seminar| **Ja** |
|Gesundheit| Nein |
|Psychologie| Nein |
|Recht| **Ja** |
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
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel| Schlüssel |Bedeutung|
|--|--|--|
|LK|LK|Leistungskurs|
|GK|GK|Grundkurs|
|FA|FA|Facharbeit|
|ME|ME|Musik-Ensemble|
|Z|Z|Zusatzkurs|

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel |Schlüssel |Bedeutung|
|--|--|--|
|1PF|1PF|1. Prüfungsfach|
|2PF|2PF|2. Prüfungsfach|
|3PF|3PF|3. Prüfungsfach|
|4PF|4PF|4. Prüfungsfach|
|1PFBLL|1PFBLL|1. Prüfungsfach und besondere Lernleistung|
|2PFBLL|2PFBLL|2. Prüfungsfach und besondere Lernleistung|
|3PFBLL|3PFBLL|3. Prüfungsfach und besondere Lernleistung|
|4PFBLL|4PFBLL|4. Prüfungsfach und besondere Lernleistung|
|BLL|BLL|5. Prüfungskomponente besondere Lernleistung|
|PRS|PRS|5.Prüfungskomponente Präsentationsprüfung|
