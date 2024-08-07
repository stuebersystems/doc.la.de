# NRW-APO-2012

Abiturqualifikationsberechnung für Gymnasien in Nordrhein-Westfalen.

Quelle: [https://bass.schul-welt.de/9607.htm#13-32nr3.1p7](https://bass.schul-welt.de/9607.htm#13-32nr3.1p7)

## Gemischte Klassen nach G8 und G9

Wenn Sie Schüler die nach 12 und Schüler die nach 13 Jahren ihr Abitur ablegen möchten gemeinsam in einer Klasse verwalten möchten, gehen Sie bitte folgendermaßen vor.

### Klassen

| Beispiel für Klassenkürzel | `Klassen > Zeiträume > Allgemein > Jahrgang` | Bemerkung |
|---|---|---|
| E-Phase | 11 | in dieser Klasse sind gemeinsam Schüler: <br/> - des Jahrgangs 10 (G8) <br/> - des Jahrgangs 11 (G9) |
| Q1/Q2-Phase | 12 | in dieser Klasse sind gemeinsam Schüler: <br/> - des Jahrgangs 11 (G8) <br/> - des Jahrgangs 12 (G9) |
| Q3/Q4-Phase | 13 | in dieser Klasse sind gemeinsam Schüler: <br/> - des Jahrgangs 12 (G8) <br/> - des Jahrgangs 13 (G9) |

!!! info "Hinweis"

    Bitte achten Sie darauf, dass unter `Daten3 > Fremdsprachenfolge` für die Schüler die Besuchsjahre individuell nach G8 und G9 eingetragen werden. Die Eintragung kann auch per gesammelt mit dem Assistenten unter `Schüler > Bearbeiten > Sammelzuweisung` erfolgen. Nachfolgend ein Beispiel für die G9-Schüler einer gemischten Klasse.

![Bitte geben Sie in gemischten Klassen die Jahrgänge wie im oben stehenden Beispiel ein](/assets/images/nrw.apo-2012.png)

![Bitte richten Sie für dieses Beispiel die Zeile im Verzeichnis Verordnungen wie abgebildet ein](/assets/images/nrw.apo-2012.01.png)

## Verzeichnis Verordnung

Bitte legen Sie unter `Verzeichnisse > Verordnungen` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

| Spalte | Wert |
| --- | --- |
| Kürzel | beliebig |
| Bezeichnung | beliebig |
| Kategorie | Abitur |
| Typ | leer |
| Ab Jahrgang | leer |
| Skript | `...Ihre RegionIhr_Skript.dws` (Pfad zur Skriptdatei auf Ihrem Server) |
| Notenart 11 | Noten oder Punkte |
| Notenart 12 | Punkte |
| Notenart 13 | Punkte |
| Notenart 13 | Punkte |
| Notenart BBS | leer |
| Gültig von | leer |
| Gültig bis | leer |

## Fachkategorien

Berechnungsskripte erkennen relevante Fächer anhand der Eintragungen unter `Extras > Schlüsselverzeichnisse > Fächer > Fachkategorie`. 
Dabei müssen, je nach Verordnung, einige Fächer besonders berücksichtigt werden. Für diese Fächer sind die zu verwendenden Fachkategorien fest vorgeschrieben. Alle anderen Fächer können mit einer der übrigen Fachkategorie gekennzeichnet werden oder ohne Fachkategorie geführt werden.

|Fachkategorien|Muss genutzt werden|
|--|--|
Fremdsprache | **Ja**
Religion/Ethik | **Ja** |
Deutsch | **Ja**
Mathematik | **Ja**
Kunst | **Ja**
Musik | **Ja**
Sport | **Ja**
Informatik | **Ja**
Philosophie | **Ja**
Geschichte | **Ja**
Physik | **Ja**
Chemie | **Ja**
Biologie | **Ja**
Erdkunde | **Ja**
Sozialkunde | **Ja**
Wirtschaft | **Ja**
Politik | Nein
Darstellendes Spiel |Nein
Evangelische Religion |Nein
Katholische Religion |Nein
Technik |Nein
Pädagogik |**Ja**
Sporttheorie |Nein
BWL/RW |Nein
BWL/VWL |Nein
VWL |Nein
Seminar |Nein
Gesundheit |Nein
Psychologie|Nein
Recht |Nein
Literatur | **Ja**

## Aufgabenbereiche

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter `Verzeichnisse > Fächer > Spalte Aufgabenbereich` verwendet werden:

| Aufgabenbereich |
| --- |
| sprachl.-lit.-künstlerisch |
| gesellschaftswiss. |
| mathem.-nat.-technisch |
| Religion |
| Sport |

## Fachmerkmale

Unter `Extras > Schlüsselverzeichnisse > Fächer > Zeugnismerkmal` können besondere Merkmale für instrumentale und vokale Kurse eingetragen werden.

Zeugnismerkmal | Bedeutung
--|--
INST|Merkmal für instrumentalen Kurs
VOKA|Merkmal für vokalen Kurs

## Unterrichtsart

Die Unterrichtsart muss unter `Abitur > Qualifikation > Unterrichtsart` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus `Schüler > Zeugnis > Fächer > Unterrichtsart` übernommen werden.  
Prüfen Sie bitte unter `Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten`,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung |
| --- | --- | --- |
| LK | LK | Leistungskurs |
| GK | GK | Grundkurs |

## Fachstatus

Der Fachstatus muss unter `Abitur > Qualifikation > Fachstatus` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus `Schüler > Zeugnis > Fächer > Fachstatus` übernommen werden.  
Prüfen Sie bitte unter `Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus`,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung |
| --- | --- | --- |
| Pflicht | Pflicht | Pflichtbereich (kein Eintrag wird wie Pflicht gewertet) |
| 1PF | 1PF | 1. Prüfungsfach (weiteres Leistungskursfach)|
| 2PF | 2PF | 2. Prüfungsfach (Profil bildendes Leistungskursfach|
| 3PF | 3PF | 3. Prüfungsfach (Grundkursfach)|
| 4PF | 4PF | 4. Prüfungsfach (Grundkursfach)|
| 5PF | 4PF | 5. Prüfungsfach (Grundkursfach)|
|ZusatzK|ZusatzK|Zusatzkurs|
|Projekt|Projekt|Projekt|

## Besondere Lernleistung

Im Rahmen der für die Abiturprüfung vorgesehene Punktzahl kann Schülern/Innen eine besondere Lernleistung angerechnet werden, die im Rahmen oder im Umfang eines mindesten zwei Halbjahre umfassenden Kurses erbracht werden.

Weisen Sie dem Fach der "besonderen Lernleistung" auf der Registerkarte `Qualifikation` den Fachstatus "BLL" zu und führen das entsprechende Skript aus.

Im Menü `Abitur` wird auf der Registerkarte `Prüfung` in der Registerkarte `Lernleistung` das jeweilige Fach automatisch eingetragen. Damit die BLL in die Berechnung aufgenommen wird,  
setzen Sie den Haken vor `Lernleistung einbringen`. Das Thema der besonderen Lernleistung tragen Sie im Feld `Thema` ein, die Gesamtnote geben Sie links im ersten Feld  ein.

![Die BLL wird durch das Auslösen des Skriptes eingetragen.](/assets/images/nrw-apo-2012-besondere_lernleistung.png)

## Leistung mündlich erbracht

Sie können in Magellan unter Abitur > Qualifikation > Layout anpassen pro Kurshalbjahr eine Spalte zum Markieren, ob eine Leistung mündlich erbracht wurde einblenden. Bitte markieren Sie dort die mündliche Leistung für ausgewählte Fächer und Halbjahre. Diese Eingabe wird vom Skript für die Festlegung des Profils ausgewertet.

![Blenden Sie die Spalten unter "Layout anpassen" ein und markieren per Häkchen, falls eine Leistung mündlich erbracht wurde.](/assets/images/E1_Q4_muendlich.png)

## Merkmal

Das Merkmal muss unter `Abitur > Qualifikation > Merkmal` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus `Schüler > Zeugnis > Fächer > Merkmal` übernommen werden.

| Merkmal | Bedeutung |
| --- | --- |
| A | Fremdsprache Anfänger (2 Kurse müssen eingebracht werden) |
