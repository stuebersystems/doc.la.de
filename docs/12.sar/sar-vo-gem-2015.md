# SAR-VO-GEM-2015

## Quelle

Basierend auf der Gemeinschaftsschulverordnung - GemSVO [http://sl.juris.de/sl/gesamt/GemSchulV\_SL\_2012.htm](http://sl.juris.de/sl/gesamt/GemSchulV_SL_2012.htm)

Das Skript berücksichtigt:

Abschlüsse | Details
--|--
Abschluss Jahrgang 9 | Abschluss des JGs 9 mit dem Hauptschulabschluss, den erweiterten Hauptschulabschluss und die Prüfung des Übergangs von Klasse 9 in die Klasse 10.
Abschluss Jahrgang 10 | Abschluss des JGs mit dem Mittleren Bildungsabschluss und den evtl. Übergang nach Klasse 11.

## Vorbereitung

### Schlüsselverzeichnis > Verordnungen

Bitte legen Sie unter `Schlüsselverzeichnis > Verordnungen` für den Jahrgang 9 und Jahrgang 10 jeweils eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim späteren Synchronisieren der Schüler in das Menü `Mittelstufe` weisen Sie den Schülern diese Verordnung zu.

#### Abschluss am Ende der Klasse 9

`Schlüsselverzeichnis > Verordnungen`

| Spalte | Wert |
| --- | --- |
| Kürzel | beliebig |
| Bezeichnung | beliebig (GemSVO) |
| Kategorie | Mittelstufe |
| Typ | SARGEM09 |
| Ab Jahrgang | 9 |
| Skript | `...\Ihre Region\Ihr_Skript.dws` (Pfad zur Skriptdatei auf Ihrem Server (`...\Saarland\SAR-VO-GEM-2015.dws`) |
| Notenart 11 | leer |
| Notenart 12 | leer |
| Notenart 13 | leer |
| Notenart 13 | leer |
| Notenart BBS | leer |
| Gültig von | leer |
| Gültig bis | leer |

#### Abschluss am Ende der Klasse 10

`Schlüsselverzeichnis > Verordnungen`

| Spalte | Wert |
| --- | --- |
| Kürzel | beliebig |
| Bezeichnung | beliebig \(GemSVO\) |
| Kategorie | Mittelstufe |
| Typ | SARGEM10 |
| Ab Jahrgang | 10 |
| Skript | `...\Ihre Region\Ihr_Skript.dws` (Pfad zur Skriptdatei auf Ihrem Server (`...\Saarland\SAR-VO-GEM-2015.dws`) |
| Notenart 11 | leer |
| Notenart 12 | leer |
| Notenart 13 | leer |
| Notenart 13 | leer |
| Notenart BBS | leer |
| Gültig von | leer |
| Gültig bis | leer |

![Verzeichnis Verordnungen](/assets/images/mittelstufe/ms_verordnungen.png)

### Schlüsselverzeichnis > Fächer

Bitte legen Sie im `Schlüsselverzeichnis > Fächer` zusätzlich folgende Fächer an. Das "Kürzel" kann dabei frei gewählt werden, entscheidend ist der Eintrag im Feld "Bezeichnung" wie vorgegeben:

| Kürzel | Schlüssel | Bezeichnung |
| --- | --- | --- |
| GW | nicht relevant | Gesellschaftswissenschaften |
| NW | nicht relevant | Naturwissenschaften |
| WahlPF | nicht relevant | Wahlpflichtbereich |

#### warning::Wichtig

!!! info "Hinweis"

    Vom Skript werden die Fachbezeichnung "Wahlpflichtbereich", "Gesellschaftswissenschaften" und "Naturwissenschaften" abgefragt.

#### Fachkategorien

Jedem Fach, das Sie in der Gemeinschaftsschule verwenden, muss in Magellan unter `Schlüsselverzeichnisse > Fächer` in Spalte "Kategorie"` eine Kategorie zugewiesen sein.  
Folgende Fachkategorien werden vom Berechnungsskript der Mittelstufe verwendet und müssen den Fächern entsprechend zugewiesen werden.

|Fachkategorien|Wird vom Skript berücksichtigt|
|--|--|
|Fremdsprache| **Ja** |
|Religion/Ethik| Nein |
|Deutsch| **Ja** |
|Mathematik| **Ja** |
|Kunst| Nein |
|Musik| Nein |
|Sport| Nein |
|Informatik| Nein |
|Philosophie| Nein |
|Geschichte| **Ja** |
|Physik| **Ja** |
|Chemie| **Ja** |
|Biologie| **Ja** |
|Erdkunde| **Ja** |
|Sozialkunde| **Ja** |
|Wirtschaft| Nein |
|Politik| Nein|
|Darstellendes Spiel| Nein |
|Evangelische Religion| Nein |
|Katholische Religion| Nein |
|Technik| Nein |
|Pädagogik| Nein|
|Sporttheorie| Nein |
|BWL/RW| Nein |
|BWL/VWL| Nein |
|VWL| Nein |
|Seminar| Nein |
|Gesundheit| Nein |
|Psychologie| Nein |
|Recht| Nein |
|Literatur| Nein |

#### Aufgabenbereiche

Folgende Aufgabenbereiche stehen Ihnen in Magellan zur Verfügung und müssen unter `Schlüsselverzeichnisse > Fächer` in der Spalte "Aufgabenbereich" bei den Fächern verwendet d.h. zugewiesen werden:

| Aufgabenbereich |
| --- |
| sprachl.-lit.-künstlerisch |
| gesellschaftswiss. |
| mathem.-nat.-technisch |
| Religion |
| Sport |

### Fremdsprachen

Für die 1. und evtl. 2. Fremdsprache des Schülers muss folgendes beachtet werden:

1. Die Fremdsprachen müssen dem Schüler als Fächer im Menü `Schüler > Zeugnis > Fächer` zugeordnet werden.
2. Für jede dort zugeordnete Fremdsprache muss pro Schüler festgelegt werden, ob dies die 1. bzw. 2. Fremdsprache ist. Dies erfolgt im Menü t `Schüler > Daten 3 > 1. Fremdsprache`  bzw. `2. Fremdsprache`.

![Eingabe der Fremdsprachenfolge](/assets/images/mittelstufe/ms_fs01.png)

!!! info "Hinweis"

    Bitte beachten Sie, dass die unter Ansicht `Schüler > Daten 3 > Fremdsprache` und die unter `Schüler > Zeugnis > Fächer` verwendeten Fächer auf das identische Fach aus `Schlüsselverzeichnis > Fächer` verweisen, ansonsten ist keine Zuordnung möglich!

### Schlüsselverzeichnis > Unterrichtsarten

Die Unterrichtsart muss im Menü `Mittelstufe > Prüfung` in der Spalte `Unterrichtsart` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus `Schüler > Zeugnis > Fächer` aus der Spalte"Unterrichtsart` übernommen werden. (geschieht durch die Synchronisation)
Prüfen Sie bitte im `Schlüsselverzeichnis > Unterrichtsarten`, dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie diese ggf. an.

| Kürzel | Schlüssel | Bedeutung |
| --- | --- | --- |
| E | E | Erweiterungskurs |
| G | G | Grundkurs |
| A | A | Aufbaukurs |

![Unterrichtsarten](/assets/images/mittelstufe/ms_unterrichtsarten01.png)

### Schlüsselverzeichnis > Fachstatus

Der Fachstatus muss im Menü `Mittelstufe > Prüfung` in der Spalte `Fachstatus` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus dem Menü `Schüler > Zeugnis > Fächer` aus der Spalte "Fachstatus" übernommen werden. (geschieht durch die Synchronisation) 
Prüfen Sie bitte im `Schlüsselverzeichnis > Fachstatus`, dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie diese ggf. an.

| Kürzel | Schlüssel | Bedeutung |
| --- | --- | --- |
| Wahlb | Wahlb | Wahlbereich |
| WahlPF | WahlPF | Wahlpflicht |

### Schlüsselverzeichnis > Abschlüsse (Intern)

Bitte legen Sie im `Schlüsselverzeichnis > Abschlüsse (Intern)` zusätzlich den "Hauptschulabschluss" und den "Mittleren Bildungsabschluss" wie folgt an.

| Kürzel | Schlüssel | Bezeichnung |
| --- | --- | --- |
| HSA | 7 | Hauptschulabschluss |
| MBA | 8 | Mittlerer Bildungsabschluss |

### Schlüsselverzeichnis > Abschlussarten

Bitte legen Sie im `Schlüsselverzeichnis > Abschlussarten` folgende Zusatzinformationen an.

| Kürzel | Schlüssel | Bezeichnung |
| --- | --- | --- |
| P | leer | Abschlusszeugnis "Hauptschulabschluss" für Schülerinnen und Schüler, die die Abschlussprüfung bestanden haben |
| ÜH | leer | Abschlusszeugnis „Hauptschulabschluss“ mit Übergangsberechtigung in die Handelsschule, Gewerbeschule, Sozialpflegeschule“ für Schülerinnen und Schüler, die nicht an der Abschlussprüfung teilgenommen haben. |
| PÜH | leer | Abschlusszeugnis „Hauptschulabschluss“ mit Übergangsberechtigung in die Handelsschule, Gewerbeschule, Sozialpflegeschule“ für Schülerinnen und Schüler, die die Abschlussprüfung bestanden haben |
| ÜK10 | leer | Abschlusszeugnis „Hauptschulabschluss“ mit Übergangsberechtigung in die Klassenstufe 10 der Gemeinschaftsschule für Schülerinnen und Schüler, die nicht an der Abschlussprüfung teilgenommen haben |
| PÜK10 | leer | Abschlusszeugnis „Hauptschulabschluss“ mit Übergangsberechtigung in die Klassenstufe 10 der Gemeinschaftsschule für Schülerinnen und Schüler, die die Abschlussprüfung bestanden haben |
| ÜGOS | leer | Mit Übergang Gymnasiale Oberstufe |

![Verzeichnis Abschlussarten](/assets/images/mittelstufe/ms_abschlussarten.png)

## Schüler ins Menü Mittelstufe synchronisieren

### Vorbereitung

Wechseln Sie in Magellan in das Menü `Mittelstufe`. Über  `Start > Schüler synchronisieren` werden die in den Halbjahren pro Schüler erfassten Fach- und Notendaten aus dem Menü  `Schüler > Zeugnis > Leistungen` in das Menü `Mittelstufe > Prüfung` kopiert. Im Menü `Mittelstufe > Auwahl` werden Ihnen die bereits synchronisierten Schüler angezeigt. 

![Synchronisation Mittelstufe](/assets/images/mittelstufe/ms_synch02.png)

Damit die Daten korrekt in die Spalten kopiert werden können, müssen die nachstehenden Daten korrekt erfasst sein.

Magellan extrahiert für die markierten Schüler die Fachdaten der Halbjahre 8.2, 9.1 und 9.2.

Dies ist die Voraussetzung dafür, dass die Abschlussberechnung der Mittelstufe nach Klasse 9 durchgeführt werden kann. 

!!! info "Hinweis"

    Im Menü `Mittelstufe` können für die Schüler selbst keine Fächer bzw. Noten aus den Halbjahren 8.2 bis 9.2 eingetragen werden.

Damit die Synchronisation klappt sind die folgenden Einstellungen wichtig:

| Voraussetzung | Anmerkung |
| --- | --- |
| Zeitraumart | Im `Schlüsselverzeichnis > Zeiträume` muss in der Spalte „Art“ der Eintrag „1. Halbjahr“ bzw. “2. Halbjahr“ gefüllt sein. |
| Jahrgang | Im Menü `Klasse > Zeiträume` im Feld „Jahrgang“ der Eintrag „8“ oder „9“ hinterlegt sein.|
| Abschlussjahrgänge |Im `Schlüsselverzeichnis > Abschlussjahrgänge` müssen die Abschlussjahrgänge angelegt sein. Es genügt dabei die Angabe des Kürzels, der Bezeichnung und der Kategorie "Mittelstufe".
| Verordnungen | Im `Schlüsselverzeichnis > Verordnungen` muss pro verwendeter Verordnung eine Zeile entsprechend der Anleitung pro Skript angelegt sein. Wichtig hierbei ist der Eintrag in Spalte "Ab Jahrgang". **Für die Synchonisation muss der Jahrgang mit dem Wert "9" oder "10" gefüllt werden.** |

![Verzeichnis Abschlussjahrgänge](/assets/images/mittelstufe/ms_abschlussarten01.png) 

![Verzeichnis Verordnungen](/assets/images/mittelstufe/ms_verordnungen.png) 


!!! info "Hinweis"

     Beim Synchronisieren werden die Noten aus dem Menü `Schüler > Zeugnis > LeistungenSchüler` > Zeugnis > Leistungender Spalte „Endnote“ in der `Ansicht "` in das Menü `Mittelstufe` übernommen.

### Schüler für die Abschlussberechnung synchronisieren

Rufen Sie den Assistenten aus dem Menü `Mittelstufe` über `Start > Schüler synchronisieren` auf. Der Assistent bietet Ihnen alle Schüler zum Synchronisieren an, filtern Sie hier nach dem Jahrgang und markieren Sie die Schüler und klicken auf `Weiter`.  

![Assistent zum Schüler synchronisieren](/assets/images/mittelstufe/ms_synch03.png)

Auf der nächsten Karte wählen Sie bitte den `Abschlussjahrgang` und die `Prüfungsordnung` aus und klicken auf `Weiter` und anschließend auf `Fertigstellen`.

![Assistent zum Schüler synchronisieren / weitere Angaben ](/assets/images/mittelstufe/ms_synch04.png)

![Auswahl der Schüler / Fertigstellen](/assets/images/mittelstufe/ms_synch05.png)

Nach der Synchronisieren werden Ihnen im Bereich `Mittelstufe > Auswahl` alle synchronisierten Schüler angezeigt.

Per `Doppelklick` auf den gewünschten Schüler oder über einen Klick auf die Registerkarte `Prüfung` wechseln Sie zur Abschlussberechnung. Auf dieser Registerkarte finden Sie die Fächer, Unterrichtsarten und Notenwerte der Klassen 8.2, 9.1 und 9.2 (für Abschlussberechnung nach Klasse 9) bzw. 9.2, 10.1  und 10.2 (für Abschlussberechnung nach Klasse 10), falls Sie diese Angaben bereits in Magellan unter der Rubrik `Schüler` gemacht haben sollten.

Durch die Synchronisation erfolgen folgende Vorbelegungen:

* Prüfung, ob der Schüler überhaupt an der Abschlussprüfung teilnimmt. Hat der Schüler in allen differenzierten Kursen die Unterrichtsart "E" \(= E-Niveau\) eingestellt, so wird zunächst davon ausgegangen, dass er zur Klasse 10 übergeht. Ist dies der Fall, wird in der die Registerkarte `Auswahl`  in der Spalte `Information` der Wert "Ohne Prüfung" ausgegeben.  
  Trifft dies nicht zu wird in der Spalte `Information` der Wert "Mit Prüfung" ausgegeben. Der Schüler nimmt in diesem Fall an der Abschlussprüfung teil.

* Auf der Registerkarte `Prüfung`  werden pro ausgewähltem Schüler im Bereich `Vornote` die Vornoten der Fächer auf Basis der Punkte in den Klassenstufen 8.2, 9.1 und 9.2 für den Abschluss in Klasse 9 bzw. 9.2, 10.2 und 10.2 für den Abschluss in Klasse 10 ausgegeben.

## Berechnung der Abschlüsse durchführen

Auf der Registerkarte `Prüfung` finden Sie die für den Abschluss relevanten Daten.

Die Registerkarte besteht aus 3 Bereiche:

* Meldungen im oberen Bereich, die das Ergebnis
* Matrix mit den Punkten in der Mitte
* Kriterien für Hauptschulabschluss und erweiterten Hauptschulabschluss auf der rechten Seite

Über die Schaltfläche  `Neu prüfen` führen Sie eine Prüfung der in der Matrix eingegeben Werte aus. Das Ergebnis der Prüfung wird oberhalb der Matrix im Bereich `Meldungen`  ausgegeben.

### Matrix

Die Matrix ist in folgende Spaltenbereiche aufgeteilt:

| Bereiche | Anmerkung |
| --- | --- |
| 8.2 | Hier sind die aufgrund der Synchronisation übertragenen Werte aus dem Halbjahr 8.2 enthalten. Sie stellen die Jahresnoten für den Jahrgang 8 dar|
| 9.1 | Hier sind die aufgrund der Synchronisation übertragenen Werte aus dem Halbjahr 9.1 enthalten. |
| 9.2 | Hier sind die aufgrund der Synchronisation übertragenen Werte aus dem Halbjahr 9.2 enthalten |
| 10.1 | Hier sind die aufgrund der Synchronisation übertragenen Werte aus dem Halbjahr 10.1 enthalten. |
| 10.2 | Hier sind die aufgrund der Synchronisation übertragenen Werte aus dem Halbjahr 10.2 enthalten |
| Vornote | Hier wird automatisch falls relevant die Vornote ausgegeben. |
| Prüfung | Hier werden die Punkte der Prüfung eingetragen. In der Spalte "Pflicht" wird die schriftliche Prüfung in Deutsch und Mathematik eingetragen. In der Spalte "Wahl" wird ein evtl. zusätzliche weitere mündliche Prüfung eingegeben. Entscheidend für die weitere Berechnung ist der Wert in der Spalte "Note". |
| Endnote | In den Spalten "Unterrichtsart" und "Note \(Niveau\)" stehen die berechneten Werte auf der zuletzt in 9.2 (Abschluss Klasse 9) bzw. 10.2 (Abschluss Klasse 10) unterrichteten Unterrichtsart für das Zeugnis. In der Spalten "Abschlussnote" und "Unterrichtsart \(Abschlussnote\)" stehen die für die Abschlussberechnung relevanten Werte. |

!!! info "Hinweis"

    Punkte mit weniger als 4 Punkte werden mit rot hinterlegt.

### Kriterien

Unter den Kriterien werden automatisch die jeweiligen Kriterien für den Hauptschulabschluss bzw. den erweiterten Hauptschulabschluss mit Bezug auf die Paragraphen der Verordnung gefüllt, wenn die Schaltfläche `Neu prüfen` angewählt wurde.

Erfolgt eine Änderung in den Matrix, wird rechts unten der Status mit "Abschluss nicht geprüft" ausgewiesen. Erst mit Drücken der Schaltfläche `Neu prüfen` wird der Status auf `"Abschluss geprüft"` gesetzt.

### Spalte Merkmal

In Magellan finden Sie in der Ansicht `MITTELSTUFE` auf der Registerkarte `Prüfung` die Spalte „Merkmal“. Sie dient dazu, für ein Fach bestimmte Merkmale einzutragen, die für den Ausdruck und die Berechnung verwendet werden können. Folgende Einträge sind möglich: `*`, `**` oder `***`
Hierdurch wird als Zeugnisbemerkung automatisch einer der folgenden ministeriellen Texte  ausgewählt:

Eintrag|Text
---|---
`*` | Der Schüler wurde in den gekennzeichneten Fächern `*` nach einem individuellen Förderplan unterrichtet. Seine Leistungen wurden entsprechend diesem Förderplan bewertet.
`**` | Der Schüler wurde in den gekennzeichneten Fächern `**` im Rahmen seiner sonderpädagogischen Förderung im Bereich Lernen nach einem entsprechenden Förderplan unterrichtet.
`***`|Der Schüler wurde in den gekennzeichneten Fächern `***` im Rahmen seiner sonderpädagogischen Förderung im Bereich geistige Entwicklung nach einem entsprechenden Förderplan unterrichtet.
