# BER-KO-ABI (Schul Z 323)

Schul Z 323

`Ausdruck`

Das Zeugnis/der Bericht muss aus dem Menü `Abitur` gedruckt werden.

## Zeugnisdatum

`Abitur > Prüfung > Zeugnisdatum`

Tragen Sie das Zeugnisdatum im Menü `Abitur > Prüfung` im Feld "Zeugnisdatum" ein.

## Schullaufbahn (KO, AbdGY)

1. Das Schuljahr wird unter `Extras > Schlüsselverzeichnisse > Zeiträume` im Feld “Ausdruck1“ hinterlegt.
2. Das Schulhalbjahr wird unter `Extras > Schlüsselverzeichnisse > Zeiträume` im Feld „Art“ hinterlegt
3. Die Ausgabe Vorkurs/E-Phase/Kurshalbjahr ergibt sich aufgrund der Definition des aktuellen Zeitraums in MAGELLAN im `Schlüsselverzeichnis > Zeiträume` im Feld "Art" und aufgrund der Eintragungen im Menü `Klassen > Zeiträume` im Feld „Jahrgang“
4. Im Menü `Klassen > Klassenart` muss in den entsprechenden Zeiträumen entweder "Oberstufenjahrgang (Nur Kurse)" (für Vorkurs / E-Phase)** bzw. "Oberstufenjahrgang (Grund- und Leistungskurse)" (für Kurshalbjahre)** hinterlegt sein.

Jahrgange/Halbjahr | Ausgabe im Bericht/Zeugnis
--|--
10/1 | Vorkurs
10/2 | Vorkurs
11/1 | E1
11/2 | E2
12/1 | 1. KS
12/2 | 2. KS
13/1 | 3. KS
13/2 | 4. KS

## Schriftart

Damit das Zeugnis/der Bericht korrekt ausgedruckt wird, muss die vom Senat für den Zeugnisdruck vorgegebene Schriftart SenBJS auf Ihrem Rechner installiert sein.

## Jahrgang Klasse

`Klassen > Zeiträume > Jahrgang`

Beim Abgang können 2 Abschlüsse erworben werden. Es wird unterschieden:

Varianten | Ausgabe | Eingaben in MAGELLAN
--|--|--
Varinate 1 | mittlere Reife | Jahrgang 11 (1. und 2. HJ); Jahrgang 12 (1. HJ)
Variante 2 | schulischer Teil der Fachhochschulreife | Jahrgang 12 (2.HJ); Jahrgang 13 (1. und 2 HJ)

Den Jahrgang tragen Sie im entsprechenden Zeitraum bei der Klasse des Schülers im Menü `Klassen > Zeiträume > Jahrgang` ein. Das jeweilige Halbjahr ergibt sich automatisch aus dem Druckzeitraum, entsprechend wird auf dem Zeugnis Variante 1 oder 2 ausgegeben. 

## Eintrittsjahr Einführungsphase

Zur Ermittlung des Eintrittsdatums in die Einführungsphase der gymnasialen Oberstufe ist es zwingend erforderlich, dass Sie im Menü „Klassen“ bei der Klasse des Schülers auf der Registerkarte „Daten“ im Feld „Klassenart“ „Oberstufenjahrgang (Nur Kurse)“ oder "Oberstufenjahrgang (Grund- und Leistungskurse)" zugewiesen haben.

## Zeugnisbemerkungen

`Abitur > Zeugnisbemerkungen`

Bei den Zeugnisbemerkungen müssen verschiedene Typen der Bemerkung unterschieden werden. Die Unterscheidung erfolgt durch den Eintrag in der Spalte "Merkmal" im `Schlüsselverzeichnis > Zeugnisbemerkungen`, falls es sich um allgemeingültige Zeugnisbemerkungen handelt, oder beim Schüler, falls Sie diesem eine individuelle Zeugnisbemerkung zuweisen möchten. Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü Abitur > Zeugnisbemerkungen. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung auswählen und zuweisen. Erfolgt keine Eingabe in der Spalte "Merkmal", so wird die Bemerkung unter "allgemeinen Bemerkungen" auf dem Zeugnisdruck ausgegeben.

Folgende Kürzel im Feld "Merkmal" müssen für den Zeugnisdruck verwendet werden:

Merkmal | Bedeutung
--| --
Freiw | Text für die Teilnahme an freiwilligen Arbeitsgemeinschaften

## Aufgabenbereich

`Extras > Schlüsselverzeichnisse > Fächer > Aufgabenbereich`

Für die korrekte Ausgabe der Zeugnisbereiche wählen Sie unter `Schlüsselverzeichnis > Fächer` für jedes Fach einen Aufgabenbereich aus dem Drop-Down-Menü in der Spalte "Aufgabenbereich" aus. Diese Fächer müssen im Menü `Schüler > Zeugnis > Fächer` zugewiesen sein. Folgende Aufgabenbereiche dürfen im Zeugnisdruck verwendet werden:

Aufgabenbereich| Zeugnisbereich
--|--
sprachl.-lit.-künstlerisch | 1. Aufgabenfeld
gesellschaftswiss. | 2. Aufgabenfeld
mathem.-nat.-technisch | 3. Aufgabenfeld

## Unterrichtsarten

`Extras > Schlüsselverzeichnisse > Unterrichtsarten`

Die korrekte Ausgabe der Zeugnisbereiche wird im Menü `Schüler > Zeugnis > Fächer` im Feld "Unterrichtsart" ausgewählt. Grundlage bildet das `Schlüsselverzeichnis > Unterrichtsarten`. Für den Zeugnisdruck ist dabei nur der Schlüssel der Unterrichtsart relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis Fachtafeln die Unterrichtsart zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Unterrichtsart nicht pro Schüler und pro Fach vornehmen.

Folgende Unterrichtsarten dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
LK | LK | Leistungskurs

## Fremdsprachenfolge

`Schüler > Daten 3 > Von/Bis`
 
Tragen Sie das Von/Bis (erwartet wird der Jahrgang) der belegten Fremdsprachen in den Feldern "von/bis" ein.

## Fremdsprachenfolge

`Schüler > Daten 3 > 1./2./3./4. Fremdsprache`

Tragen Sie im Menü `Schüler > Daten 3` beim entsprechenden Schüler die Fremdsprache im aktuellen Zeitraum unter "Fremdsprachenfolge" ein. Damit Ihnen hier Fremdsprachen im Auswahlmenü angeboten werden, müssen Sie unter `Schlüsselverzeichnis > Fächer` im Feld "Kategorie" aus dem Pull-Down-Menü "Fremdsprache" zugewiesen haben.

## Noten wie o.B., n.B. oder sonstiges

`Extras > Schlüsselverzeichnisse > Noten > Füllwerte`

Um ein Fach mit einem bestimmten Füllwert (z.B. "oB" (ohne Bewertung)) auf dem Zeugnis auszugeben, müssen Sie unter `Schlüsselverzeichnisse > Noten` die Noten wie folgt anlegen. Auf dem Zeugnis wird das "Kürzel" ausgegeben.

Kürzel | Bezeichnung | Notenart
--|--|--
beliebig | beliebig | Füllwerte
oB | ohne Bewertung | Füllwerte

## Noten

`Extras > Schlüsselverzeichnisse > Noten`

Die Kürzel der Punkte müssen zweistellig (einstellig und eine Führungsnull) sein. 
Beim Anlegen von Punkten im `Schlüsselverzeichnis > Noten` (Notenart: Punkte) mit einem Notenwert kleiner 10 (0-9) weisen Sie im Feld "Notenkürzel" dem Notenwert eine "0" voran (z.B. "00", "03" usw.).

## Fächerpositionierung

 `Schüler > Zeugnis > Fächer (Position)** bzw. Abitur > Qualifikation (Position)`

Für die Sortierung der Fächer auf den Zeugnissen muss im Menü "Schüler" bei jedem Schüler auf der Registerkarte `Zeugnis > Fächer` bzw. im Menü `Abitur` bei jedem Schüler auf der Registerkarte "Qualifikation" pro Fach eine Position in der Spalte "Position" angegeben werden.

## TutorIn

`Schüler > Zeugnis > Details > Tutor`

Der Tutor muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` beim jeweiligen Schüler im Feld "Tutor" hinterlegt werden.

## Fachstatus

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.

Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
Abgew | Abgew | Fächer die nicht auf Zeugnis gedruckt werden sollen

## Schulform der Klasse

`Klassen > Daten > Schulform`

Tragen Sie im aktuellen Zeitraum im Menü `Klassen > Daten` die Schulform im Feld "Schulform" ein. Grundlage hierfür bildet das `Schlüsselverzeichnis > Schulformen`.