# MVP-GY-AZ (2013 2 Seiten)

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Abitur` gedruckt werden.

## Tutor

`Schüler > Zeugnis > Details > Tutor`

Der Tutor muss im entsprechenden Zeitraum im Menü Schüler > Zeugnis > Details beim jeweiligen Schüler im Feld "Tutor" hinterlegt werden.

## Schulhalbjahr

`Schlüsselverzeichnis > Zeiträume > Art`

Die Ausgabe des Schulhalbjahres ergibt sich aufgrund der Definition des aktuellen Zeitraums in MAGELLAN unter `Schlüsselverzeichnis > Zeiträume` im Feld "Art"

## Fachstatus

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis> Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.

Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel |  Schlüssel | Zeugnisbereich
--|--|--
Abgew | Abgew | Fächer die nicht auf Zeugnis gedruckt werden sollen

## Qualifikation

`Abitur > Qualifikation`

Auf dem Zeugnis wird unterschieden, zwischen Fächern die in Klasse 11 abgeschlossen wurden und weiter führenden Fächern. Das hat zur Folge, dass Fächer, die nur eine Benotung in den Zeiträumen E1 und/oder E2
haben, nicht im Wahl- oder Pflichtbereich angezeigt werden. Analog dazu, werden Fächer, die Noten in den Zeiträumen 11-13 aufweisen, nicht in dem Bereich "Ergebnisse der Fächer, die in Klasse 11 abgeschlossen wurden"
angezeigt.

## Aufgabenbereich

`Extras > Schlüsselverzeichnisse > Fächer > Aufgabenbereich`

Für die korrekte Ausgabe der Zeugnisbereiche wählen Sie unter `Schlüsselverzeichnis > Fächer` für jedes Fach einen Aufgabenbereich aus dem Drop-Down-Menü in der Spalte "Aufgabenbereich" aus. Diese Fächer müssen im Menü `Schüler > Zeugnis > Fächer` zugewiesen sein. Folgende Aufgabenbereiche dürfen im Zeugnisdruck verwendet werden:

Aufgabenbereich|  Zeugnisbereich
--|--
sprachl.-lit.-künstlerisch | Sprachlich-literarisch-künstlerisches Aufgabenfeld
gesellschaftswiss. | Gesellschaftswissenschaftliches Aufgabenfeld
mathem.-nat.-technisch | Mathem.-naturwissenschaftl.-techn. Aufgabenfeld

## Noten

`Schüler > Zeugnis > Leistungen > Noten`

Beachten Sie bitte, dass Sie Fächern, die in der Klasse 11 abgeschlossen wurden nur Noten in der Skala von 1 bis 6 zuweisen.

##  am / Abgang am

`Schueler > Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü `Schüler > Daten 2` im Feld "Zugang am" bzw. "Abgang am" ein.

## Unterrichtsarten

`Extras > Schlüsselverzeichnisse > Unterrichtsarten`

Die korrekte Ausgabe der Zeugnisbereiche wird im Menü `Schüler > Zeugnis > Fächer` im Feld "Unterrichtsart" ausgewählt. Grundlage bildet das `Schlüsselverzeichnis > Unterrichtsarten`. Für den Zeugnisdruck ist dabei nur der Schlüssel der Unterrichtsart relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis Fachtafeln die Unterrichtsart zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Unterrichtsart nicht pro Schüler und pro Fach vornehmen.

Folgende Unterrichtsarten dürfen im Zeugnisdruck verwendet werden:

In der Spalte "Unterrichtsart" sind die Werte "GF" für die Grundfächer und "HF" für die Hauptfächer zu verwenden,
die im Verzeichnis "Unterrichtsarten" wie folgt definiert sind:

Kürzel | Schlüssel | Zeugnisbereich
-----------
GF | GF | Grundfach
HF | HF | Hauptfach

## Abschlussnote der abgewählten bzw. abgeschlossenen Fächer

`Abitur > Qualifikation`

Die Abschlussnote der abgewählten bzw. abgeschlossenen Fächer tragen Sie im Menü `Abitur > Qualifikation` in dem Feld "E1" ein. Beachten Sie dabei, Noten anstatt Punkte zu vergeben ("03" wird dabei z.B. als "3" ausgegeben).

## Zeitraum "von" und "bis" der abgewählten bzw. abgeschlossenen Fächer

`Abitur > Qualifikation > Merkmal`

Den Zeitraum "von" und "bis" der abgewählten bzw. abgeschlossenen Fächer tragen Sie im Menü `Abitur > Qualifikation` im Feld "Merkmal" ein. Bitte beachten Sie dabei, nur die letzen beiden Ziffern des jeweiligen Kalenderjahres hintereinander einzutragen.

Beispiel:
von / bis | ausgegeben werden soll | Eintrag in MAGELLAN
--|--|--
"von" | 2003/2004 | 0304
"bis" | 2005/2006 | 0506

Der gesamte Term im Feld "Merkmal" lautet 03040506

## korrekte Ausgabe der Fächer, die keinem Aufgabenfeld zugeordnet sind

`Extras > Schlüsselverzeichnisse > Fächer > Aufgabenbereich`

Für die korrekte Ausgabe von Fächern "die keinem Aufgabenfeld zugeordnet sind" beachten Sie folgendes: Im `Schlüsselverzeichnis > Fächer` weisen Sie den Fächern keinen Aufgabenbereich zu, d.h. die Spalte "Aufgabenbereich" für das jeweilige Fach bleibt leer.

## SchulleiterIn

`Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter `Mandanten > Daten1` im Feld "Schulleiter" eingetragen werden. Bitte achten Sie darauf, das dem zugrunde liegenden Lehrereintrag ein Geschlecht unter `Lehrer > Daten1` zugewiesen wurde.

## Klassenjahrgang

`Klassen > Zeiträume > Zeitraum > Jahrgang`

Im entsprechenden Zeitraum muss im Menü `Klassen > Zeiträume` bei der Klasse des Schülers der Jahrgang im Feld "Jahrgang" eingetragen sein. eingetragen sein.

## Zeugnisbemerkungen

`Abitur > Zeugnis > Zeugnisbemerkungen > Position`

Zum Eintragen einer Zeugnisbemerkung muss im Abitur > Zeugnis > Zeugnisbemerkungen im Feld "Position" bei der jeweiligen Zeugnisbemerkung eine Positionsnummer angegeben werden. Z.B. für die erste Bemerkung
eine "1", für die zweite eine "2" usw.