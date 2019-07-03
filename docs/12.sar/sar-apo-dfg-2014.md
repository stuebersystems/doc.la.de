# SAR-APO-DFG-2014

Dieses Skript beinhaltet die Abiturqualifikationsberechnung für das Deutsch-Französische Gymnasium Saarbrücken.

## Trimester

Das Skript arbeitet mit Trimestern. Dazu müssen Sie unter `Extras > Optionen > Einstellungen > Zeiträume` den Standardwert von Halbjahren auf Trimester ändern.

!!! info "Hinweis"
    Sollten Sie bisher in MAGELLAN mit Halbjahre gearbeitet haben, benötigen STÜBER SYSTEMS Ihre Datenbank, um die vorhandenen Zeiträume pauschal auf Trimester umzustellen.

Nach der Änderung auf Trimester müssen Sie MAGELLAN schließen und neu starten, damit die Einstellung aktiv wird. Sie können dann unter Verzeichnisse \| Zeiträume nur noch Zeiträume der Art 1. Trimester, 2. Trimester bzw. 3. Trimester anlegen.

## Notenverzeichnis

Im Notenverzeichnis sind die Eintragungen für die Beurteilung der Oberstufenschüler wie folgt einzutragen:

| Spalte   | Wert       |
| -------- | ---------- |
| Wert     | 1 bis 10   |
| Notenart | Punktewert |

## Eintragungen für Klassen

Folgende Eintragungen sind für die Klassen Voraussetzung:

| Feld| Wert  |
| - | -- |
| ``Klassen > Daten > Beurteilungsart``| Beurteilung nach Punkten  |
| `Klassen > Daten > Klassenart`| Oberstufenjahrgang \(nur Kurse\) oder Oberstufenjahrgang \(Grund- und Leistungskurse\) |
| `Klassen > Zeiträume > Zeitraum > Jahrgang` | Für jeden Klassenzeitraum ist der Jahrgang \(11,12\) zu erfassen|

## Synchronisation der Schüler in das Menü Abitur

Die Schüler werden mit Ihren Fächern und Punkten in das Menü Abitur über den Aufruf „Schüler synchronisieren“ übertragen. Damit diese Synchronisation klappt, sind folgende Punkte zu beachten:

| Voraussetzung| Anmerkung|
| - |- |
| Zeitraumart| Im Verzeichnis der Zeiträume muss das Feld „Art“ mit dem Wert „1. Trimester“, „2.Trimester“ bzw. “3. Trimester“ gefüllt sein.|
| Klassenart| Unter `Klasse > Daten` muss im Feld „Klassenart“ die Auswahl „Oberstufenjahrgang \(Leistungs- und Grundkurse\)“ oder „Oberstufenjahrgang \(nur Kurse\)“ getroffen sein.|
| Jahrgang| Bei jeder Klasse/Jahrgang muss auf der Registerkarte „Zeiträume“ für jeden Zeitraum das Feld „Jahrgang“ mit dem Wert „11“oder „12“ angegeben werden.|
| Abschlussjahrgänge | Bitte legen Sie unter `Verzeichnisse > Verordnungen` die Abschlussjahrgänge an.|
| Verordnungen| Richten Sie bitte unter `Verzeichnisse > Verordnungen` pro verwendeter Abiturverord-nung oder Fachwahl eine Zeile ein. Beachten Sie bitte dazu den nachfolgenden Abschnitt „Verzeichnis der Verordnungen“. |

!!!info "Hinweis"
    Die Synchronisation geht von 5 Trimestern aus, also 11.1...11.3 und 12.1...12.2. Bitte schreiben Sie Ihre Schüler nicht in das 3. Semester der Klasse 12 fort.

## Verzeichnis Verordnung

Bitte legen Sie unter `Verzeichnisse > Verordnungen` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

Spalte| Wert| Anmerkung
-| -| - |
| Kürzel| beliebig| Dient der Anzeige im Abitur|
| Bezeichnung| beliebig| Dient der Anzeige im Abitur|
| Kategorie    | Abitur          ||
| Typ          | DFG             | "DFG" für "Deutsch-Französisches Gymnasium Saarbrücken"|
| Ab Jahrgang  | 11              ||
| Skript       | Pfad zum Skript | `...\Ihre Region\Ihr_Skript.dws` \(Pfad zur Skriptdatei auf Ihrem Server\) |
| Notenart 11  | Punkte          ||
| Notenart 12  | Punkte          ||
| Notenart 13  | Punkte          ||
| Notenart 13  | Punkte          ||
| Notenart BBS | leer            ||
| Gültig von   | leer            ||
| Gültig bis   | leer            ||

## Profile

Die 4 Zweige der Abiturprüfung müssen als Profile unter `Verzeichnisse > Weitere Schlüsselverzeichnisse > Profile (Schüler)` eingetragen werden.

| Kürzel | Schlüssel | Bedeutung |
| ------ | --------- | --------- |
| ES     | ES        | Zweig ES  |
| L      | L         | Zweig L   |
| SBC    | SBC       | Zweig SBC |
| SMP    | SMP       | Zweig SMP |

Jedem Schüler der Oberstufe muss unter Ansicht `Schüler > Daten 3 > Profile` eines dieser Profile eingetragen werden.

## Fachkategorien

Jedem Fach, dass Sie in der Oberstufe verwenden, müssen Sie eine Kategorie unter `Verzeichnisse > Fächer > Kategorie` zuweisen.  
Folgende Fachkategorien werden durch das Abiturqualifikationsskript verwendet:

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
|Politik| Nein|
|Darstellendes Spiel| Nein |
|Evangelische Religion| Nein |
|Katholische Religion| Nein |
|Technik| Nein |
|Pädagogik| Nein |
|Sporttheorie| Nein |
|BWL/RW| Nein |
|BWL/VWL| Nein |
|VWL| Nein |
|Seminar| Nein |
|Gesundheit| Nein |
|Psychologie| Nein |
|Recht| Nein |
|Literatur| Nein |

## Aufgabenbereiche

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter `Verzeichnisse > Fächer > Spalte Aufgabenbereich` verwendet werden:

| Aufgabenbereich |
| --- |
| sprachl.-lit.-künstlerisch |
| gesellschaftswiss. |
| mathem.-nat.-technisch |
| Religion |
| Sport |

## Fach „Gesellschaftswissenschaften"

Das Fach „Gesellschaftswissenschaften“ muss im Verzeichnis der Fächer mit dem Kürzel „GW“ definiert sein.

| Kürzel | Schlüssel | Bezeichnung                 |
| ------ | --------- | --------------------------- |
| GW     | GW        | Gesellschaftswissenschaften |

Das Fach „Gesellschaftswissenschaften“ wird unter Ansicht `Abitur > Qualifikation` automatisch eingefügt, wenn man die Schaltfläche `Initialisieren` wählt.

## Unterrichtsart

Die Unterrichtsart muss unter `Abitur > Qualifikation > Unterrichtsart` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus `Schüler > Zeugnis > Fächer > Unterrichtsart` übernommen werden.  
Prüfen Sie bitte unter `Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten`,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung                                           |
| ------ | --------- | --------------------------------------------------- |
| TPE    | TPE       | beliebig \(entspricht der besonderen Lernleistung\) |

## Fachstatus

Der Fachstatus muss unter `Abitur > Qualifikation > Fachstatus` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus `Schüler > Zeugnis > Fächer > Fachstatus` übernommen werden.  
Prüfen Sie bitte unter `Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus`,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung        |
| ------ | --------- | ---------------- |
| 1PF    | 1PF       | 1. Prüfungsfach  |
| 2PF    | 2PF       | 2. Prüfungsfach  |
| 3PF    | 3PF       | 3. Prüfungsfach  |
| 4PF    | 4PF       | 4. Prüfungsfach  |
| 5PF    | 5PF       | 5. Prüfungsfach  |
| 6PF    | 6PF       | 6. Prüfungsfach  |
| 7PF    | 7PF       | 7. Prüfungsfach  |
| 8PF    | 8PF       | 8. Prüfungsfach  |
| 9PF    | 9PF       | 9. Prüfungsfach  |
| 10PF   | 10PF      | 10. Prüfungsfach |

Dabei beinhalten die Fächer mit dem Fachstatus 1PF – 4 PF die Fächer der Gruppe I, die Fächer mit dem Fachstatus 5PF - 7PF die Fächer der Gruppe II und die Fächer mit dem Fachstatus 8PF - 10PF die Fächer der Gruppe III.

Die Muttersprache muss grundsätzlich den Fachstatus 1PF und die Partnersprache muss grundsätzlich den Fachstatus 2PF erhalten.

Die Werte 1PF – 4PF und 6PF – 10PF müssen den Fächern auf unter Ansicht `Abitur > Qualifikation` zugwiesen sein.

Das Fach „Gesellschaftswissenschaften“ wird unter Ansicht `Abitur > Qualifikation` automatisch eingefügt, wenn man die Schaltfläche `Initialisieren` wählt und erhält automatisch den Fachstatus 5PF.

## Registerkarte „Qualifikation“

Unter Ansicht `Abitur > Qualifikation` sollten Sie das Layout der Spalten wie folgt anpassen, indem Sie die Schaltfläche Layout anpassen wählen:

| Spalte | Spaltenüberschrift |
| ------ | ------------------ |
| E1     | 11/1               |
| E2     | 11/2               |
| Q1     | 11/3               |
| Q2     | 12/1               |
| Q3     | 12/2               |
| Q4     | TPE                |
| Summe2 | Schnitt            |
| Summe  | Vornote            |

Wenn man die Schaltfläche `Initialisieren` wählt, wird das Fach „Gesellschaftswissenschaften“ automatisch als zusätzlicher Eintrag eingefügt und erhält automatisch den Fachstatus 5PF.

Bei der Einstellung`Gesamtqualifikation berechnen` im Feld `Status` und Wahl der Schaltfläche `Neu berechnen` werden die Vornoten soweit möglich automatisch berechnet.
Die Vornote für das Fach „Gesellschaftswissenschaften“ muss manuell eingetragen werden.

Wird im Fall einer TPE ebenfalls ein Durchschnitt errechnet, der die Festlegung durch den Fachlehrer erfordert, muss dies ebenfalls manuell in der Spalte Vornote erfolgen. In beiden Fällen erfolgt ein entsprechender Hinweis im Meldungsfenster.

Die Berechnung der Gesamtqualifikation erfolgt auf dieser Registerkarte nur bis Abschluss der Phase 2, d.h. dem Ende des 2. Trimesters der Klassenstufe 12.

## Registerkarte „Prüfungen“

Unter Ansicht `Abitur > Prüfungen` können die eigentlichen Prüfungen erfasst werden.  
Die schriftlichen Prüfungen für das 1.PF bis 4. PF werden in der Spalte `Schriftliche Note` erfasst. Die mündliche Pflichtprüfung in der Partnersprache wird für das 2.PF in der Spalte `Pflichtprüfung` eingetragen.

![Registerkarte „Prüfungen“ in der Ansicht „Abitur“ für das Deutsch-Französische Gymnasium Saarbrücken](/assets/images/dfg_pruefung.png)

Die Aufbesserungsprüfungen werden in der Spalte `Aufbesser.-prüfung` eingetragen. Die Abiturprüfungen in Sport und den fakultativen Fächern \(8.PF – 10.PF\) werden in der Spalte `Pflichtprüfung` eingegeben.
