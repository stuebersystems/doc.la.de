# SAR-VO-GEM-2015

## Quelle

Basierend auf der Gemeinschaftsschulverordnung - GemSVO [http://sl.juris.de/sl/gesamt/GemSchulV\_SL\_2012.htm](http://sl.juris.de/sl/gesamt/GemSchulV_SL_2012.htm)

Das Skript zunächst berücksichtigt:

1. den Abschluss des Jahrgangs 9 mit dem Hauptschulabschluss, den erweiterten Hauptschulabschluss und die Prüfung des Übergangs von Klasse 9 in die Klasse 10.
2. den Abschluss des Jahrgangs 10 mit dem Mittleren Bildungsabschluss und den evtl. Übergang nach Klasse 11.

## Vorbereitung

### Verzeichnis Verordnungen

Bitte legen Sie unter `Verzeichnisse > Verordnungen` für Jahrgang 9 und Jahrgang 10 jeweils eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim späteren Synchronisieren der Schüler in das Mittelstufen-Menü weisen Sie den Schülern die Verordnung zu.

#### Für den Abschluss am Ende der Klasse 9

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

#### Für den Abschluss am Ende der Klasse 10

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

![Verzeichnis Verordnungen](/assets/images/MS_Verordnung.png)

### Verzeichnis Fächer

Bitte legen Sie in Ihrem Fächerverzeichnis zusätzlich folgende Fächer wie folgt unter `Verzeichnisse > Fächer` an. Das Kürzel kann dabei frei gewählt werden.

| Kürzel | Schlüssel | Bezeichnung |
| --- | --- | --- |
| GW | nicht relevant | Gesellschaftswissenschaften |
| NW | nicht relevant | Naturwissenschaften |
| WahlPF | nicht relevant | Wahlpflichtbereich |

#### warning::Wichtig!

!!! info "Hinweis"

    Vom Skript werden die Fachbezeichnung "Wahlpflichtbereich", "Gesellschaftswissenschaften" und "Naturwissenschaften" abgefragt.

#### Fachkategorien

Jedem Fach, das Sie in der Gemeinschaftsschule verwenden, müssen Sie eine Kategorie unter `Verzeichnisse > Fächer > Kategorie` zuweisen.  
Folgende Fachkategorien werden durch das Mittelstufenskript verwendet, bitte verwenden Sie nur die gekennzeichneten Fachkategorien.

| Fachkategorien | Wird vom Skript berücksichtigt |
| --- | --- |
| Fremdsprache | x |
| Deutsch | x |
| Mathematik | x |
| Geschichte | x |
| Physik | x |
| Chemie | x |
| Biologie | x |
| Erdkunde | x |
| Sozialkunde | x |

#### Aufgabenbereiche

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter `Verzeichnisse > Fächer > Spalte Aufgabenbereich` verwendet werden:

| Aufgabenbereich |
| --- |
| sprachl.-lit.-künstlerisch |
| gesellschaftswiss. |
| mathem.-nat.-technisch |
| Religion |
| Sport |

### Fremdsprachen

Für die 1. und evtl. 2. Fremdsprache des Schülers muss folgendes beachtet werden

1. Die Fremdsprachen müssen dem Schüler als Fächer unter `Ansicht "Schüler" > Zeugnis > Fächer` zugeordnet werden. 
2. Für jede dort zugeordnete Fremdsprache muss pro Schüler festgelegt werden, ob dies die 1. bzw. 2. Fremdsprache ist. Dies erfolgt unter `Ansicht "Schüler" > Daten 3 > Fremdsprache 1`  bzw. `Fremdsprache 2`.

!!! info "Hinweis"

    Bitte beachten Sie, dass die unter Ansicht `Schüler > Daten 3 > Fremdsprache` und die unter `Schüler > Zeugnis > Fächer`verwendeten Fächer auf das identische Fach aus `Verzeichnisse > Fächer`verweisen, ansonsten ist keine Zuordnung möglich!

### Verzeichnis Unterrichtsarten

Die Unterrichtsart muss unter `Mittelstufe > Unterrichtsart` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus `Schüler > Zeugnis > Fächer > Unterrichtsart` übernommen werden.  
Prüfen Sie bitte unter `Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten`, dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie diese ggfs. an.

| Kürzel | Schlüssel | Bedeutung |
| --- | --- | --- |
| E | E | Erweiterungskurs |
| G | G | Grundkurs |
| A | A | Aufbaukurs |

### Verzeichnis Fachstatus

Der Fachstatus muss unter `Mittelstufe > Fachstatus` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus `Schüler > Zeugnis > Fächer > Fachstatus` übernommen werden.  
Prüfen Sie bitte unter `Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus`, dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie diese ggfs. an.

| Kürzel | Schlüssel | Bedeutung |
| --- | --- | --- |
| Wahlb | Wahlb | Wahlbereich |
| WahlPF | WahlPF | Wahlpflicht |

### Verzeichnis Abschlüsse (Intern)

Bitte legen Sie in Ihrem Verzeichnis der Abschlüsse (Intern) zusätzlich den Hauptschulabschluss und den Mittleren Bildungsabschluss wie folgt unter Verzeichnisse &gt; Abschlüsse (Intern) an.

| Kürzel | Schlüssel | Bezeichnung |
| --- | --- | --- |
| HSA | leer | Hauptschulabschluss |
| MBA | leer | Mittlerer Bildungsabschluss |

### Verzeichnis Abschlussarten

Bitte legen Sie in Ihrem Verzeichnis der Abschlussarten folgende Zusatzinformationen wie folgt unter Verzeichnisse &gt; Weitere Schlüsselverzeichnisse an.

| Kürzel | Schlüssel | Bezeichnung |
| :--- | :--- | :--- |
| P | leer | Abschlusszeugnis "Hauptschulabschluss" für Schülerinnen und Schüler, die die Abschlussprüfung bestanden haben |
| ÜH | leer | Abschlusszeugnis „Hauptschulabschluss“ mit Übergangsberechtigung in die Handelsschule, Gewerbeschule, Sozialpflegeschule“ für Schülerinnen und Schüler, die nicht an der Abschlussprüfung teilgenommen haben. |
| PÜH | leer | Abschlusszeugnis „Hauptschulabschluss“ mit Übergangsberechtigung in die Handelsschule, Gewerbeschule, Sozialpflegeschule“ für Schülerinnen und Schüler, die die Abschlussprüfung bestanden haben |
| ÜK10 | leer | Abschlusszeugnis „Hauptschulabschluss“ mit Übergangsberechtigung in die Klassenstufe 10 der Gemeinschaftsschule für Schülerinnen und Schüler, die nicht an der Abschlussprüfung teilgenommen haben |
| PÜK10 | leer | Abschlusszeugnis „Hauptschulabschluss“ mit Übergangsberechtigung in die Klassenstufe 10 der Gemeinschaftsschule für Schülerinnen und Schüler, die die Abschlussprüfung bestanden haben |
| ÜGOS | leer | Mit Übergang Gymnasiale Oberstufe |

![Mittelstufenansicht](/assets/images/mittelstufe/ms_ansicht_mittelstufe.png)

## Schüler synchronisieren

Wechseln Sie in MAGELLAN in den Bereich `Mittelstufe`. Mit der Aktion `Mittelstufe > Auswahl > Schüler synchronisieren` werden die in den Halbjahren pro Schüler erfassten Fach- und Notendaten unter `Ansicht "Schüler" > Zeugnis > Leistungen` auf die Registerkarte "Prüfung" kopiert. Damit die Daten korrekt in die Spalten kopiert werden können, müssen die nachstehenden Daten korrekt erfasst sein.

MAGELLAN extrahiert für die markierten Schüler die Fachdaten der Halbjahre 8.2, 9.1 und 9.2.

Dies ist die Voraussetzung dafür, dass die Abschlussberechnung der Mittelstufe nach Klasse 9 durchgeführt werden kann. In der Ansicht `Mittelstufe` können für die Schüler selbst keine Fächer bzw Noten aus den Halbjahren 8.2 bis 9.2 eintragen werden.

Damit die Synchronisation klappt sind die folgenden Einstellungen wichtig:

| Voraussetzung | Anmerkung |
| --- | --- |
| Zeitraumart | Im Verzeichnis der Zeiträume muss das Feld „Art“ mit dem Wert „1. Halbjahr“ bzw. “2. Halbjahr“ gefüllt sein. |
| Jahrgang | Bei jeder Klasse/Jahrgang muss auf der Registerkarte „Zeiträume“ für jeden Zeitraum das Feld „Jahrgang“ mit dem Wert „8“ oder „9“ angegeben werden. |
| Abschlussjahrgänge | Bitte legen Sie unter `Verzeichnisse > Abschlussjahrgänge` die Abschlussjahrgänge an. Es genügt dabei die Angabe des Kürzels, der Bezeichnung und der Kategorie \(Mittelstufe\). |
| Verordnungen | Richten Sie bitte unter `Verzeichnisse > Verordnungen` pro verwendeter Verordnung eine Zeile entsprechend der Anleitung pro Skript an. Wichtig hierbei ist das Feld "Jahrgang". **Für die Synchonisation muss der Jahrgang mit dem Wert "9" gefüllt werden.** |

!!! info "Hinweis"

     Beim Synchronisieren werden die Noten aus der Spalte „Endnote“ in der `Ansicht "Schüler" > Zeugnis > Leistungen` in das Menü `Mittelstufe` übernommen.

So synchronisieren Sie Schüler für die Abschlussberechnung:

Rufen Sie den Assistenten aus dem Menü `Mittelstufe` auf der Karte `Prüfung` über die Schaltfläche `Schüler synchronisieren` auf. Der Assistent bietet Ihnen alle Schüler zum Synchronisieren an, filtern Sie hier nach dem Jahrgang und markieren Sie die Schüler und klicken auf `Weiter`.  Auf der nächsten Karte wählen Sie bitte die `Prüfungsordnung` und den `Abschlussjahrgang` aus und klicken auf `Weiter` und `Fertigstellen`.

![Assistent zum Schüler synchronisieren](/assets/images/mittelstufe/ms_synch.png)

![Assistent zum Schüler synchronisieren / weitere Angaben ](/assets/images/mittelstufe/ms_sync1.png)

Wechseln Sie nach dem Synchronisieren in den Menüpunkt `Mittelstufe` auf die Registerkarte `Auswahl`. Es werden alle synchronisierten Schüler angezeigt.

Per Doppelklick auf den gewünschten Schüler oder über einen Klick auf die Registerkarte `Prüfung` wechseln Sie zur Abschlussberechnung. Auf dieser Registerkarte finden Sie die Fächer, Unterrichtsarten und Notenwerte der Klassen 8.2, 9.1 und 9.2 (KLasse 9) bzw. 9.2, 10.1  und 10.2 (Klasse 10), falls Sie diese Angaben bereits in MAGELLAN unter der Rubrik `Schüler` gemacht haben sollten.

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

Die Matrix ist in folgende Spaltenbereich aufgeteilt:

| Bereiche | Anmerkung |
| --- | --- |
| 8.2 | Hier sind die aufgrund der Synchronisation übertragenen Werte aus dem Halbjahr 8.2 enthalten. Sie stellen die Jahresnoten für den Jahrgang 8 dar|
| 9.1 | Hier sind die aufgrund der Synchronisation übertragenen Werte aus dem Halbjahr 9.1 enthalten. |
| 9.2 | Hier sind die aufgrund der Synchronisation übertragenen Werte aus dem Halbjahr 9.2 enthalten |
| 10.1 | Hier sind die aufgrund der Synchronisation übertragenen Werte aus dem Halbjahr 10.1 enthalten. |
| 10.2 | Hier sind die aufgrund der Synchronisation übertragenen Werte aus dem Halbjahr 10.2 enthalten |
| Vornote | Hier wird automatisch falls relevant die Vornote ausgegeben. |
| Prüfung | Hier wird werden die Punkte der Prüfung eingetragen. In der Spalte "Pflicht" wird die schriftliche Prüfung in Deutsch und Mathematik eingetragen. In der Spalte "Wahl" wird ein evtl. zusätzliche weitere mündliche Prüfung eingegeben. Entscheidend für die weitere Berechnung ist der Wert in der Spalte "Note". |
| Endnote | In den Spalten "Unterrichtsart" und "Note \(Niveau\)" stehen die berechneten Werte auf der zuletzt in 9.2 (Abschluss Klasse 9) bzw. 10.2 (Abschluss Klasse 10) unterrichteten Unterrichtsart für das Zeugnis. In der Spalten "Abschlussnote" und "Unterrichtsart \(Abschlussnote\)" stehen die für die Abschlussberechnung relevanten Werte. |

!!! info "Hinweis"

    Punkte mit weniger als 4 Punkte werden mit rot hinterlegt.

### Kriterien

Unter den Kriterien werden automatisch die jeweiligen Kriterien für den Hauptschulabschluss bzw. den erweiterten Hauptschulabschluss mit Bezug auf die Paragraphen der Verordnung gefüllt, wenn die Schaltfläche `Neu prüfen` angewählt wurde.

Erfolgt eine Änderung in den Matrix, wird rechts unten der Status mit "Abschluss nicht geprüft" ausgewiesen. Erst mit Drücken der Schaltfläche `Neu prüfen` wird der Status auf `"Abschluss geprüft"` gesetzt.

### Spalte Merkmal

In MAGELLAN finden Sie in der Ansicht `MITTELSTUFE` auf der Registerkarte `Prüfung` die Spalte „Merkmal“. Sie dient dazu, für ein Fach bestimmte Merkmale einzutragen, die für den Ausdruck und die Berechnung verwendet werden können. Folgende Einträge sind möglich: `*`, `**` oder `***`
Hierdurch wird als Zeugnisbemerkung automatisch einer der folgenden ministeriellen Texte  ausgewählt:

Eintrag|Text
---|---
`*` | Der Schüler wurde in den gekennzeichneten Fächern `*` nach einem individuellen Förderplan unterrichtet. Seine Leistungen wurden entsprechend diesem Förderplan bewertet.
`**` | Der Schüler wurde in den gekennzeichneten Fächern `**` im Rahmen seiner sonderpädagogischen Förderung im Bereich Lernen nach einem entsprechenden Förderplan unterrichtet.
`***`|Der Schüler wurde in den gekennzeichneten Fächern `***` im Rahmen seiner sonderpädagogischen Förderung im Bereich geistige Entwicklung nach einem entsprechenden Förderplan unterrichtet.
