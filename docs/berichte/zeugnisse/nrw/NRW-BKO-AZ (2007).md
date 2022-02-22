# NRW-BKO-AZ (2007)

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Abitur` gedruckt werden.

## Fehltage, Fehlstunden

`Schueler > Zeugnis > Details > Fehltage und/oder Fehlstunden`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern "Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

## Aufgabenbereich

`Extras > Schlüsselverzeichnisse > Fächer > Aufgabenbereich`

Für die korrekte Ausgabe der Zeugnisbereiche wählen Sie unter `Schlüsselverzeichnis > Fächer` für jedes Fach einen Aufgabenbereich aus dem Drop-Down-Menü in der Spalte "Aufgabenbereich" aus. Diese Fächer müssen im Menü `Schüler > Zeugnis > Fächer` zugewiesen sein. Folgende Aufgabenbereiche dürfen im Zeugnisdruck verwendet werden:

Aufgabenbereich|  Zeugnisbereich
--|--
sprachl.-lit.-künstlerisch > 1. Aufgabenfeld
gesellschaftswiss. > 2. Aufgabenfeld
mathem.-nat.-technisch > 3. Aufgabenfeld

## Arbeits- und Sozialverhalten

`Schlüsselverzeichnisse > Fächer` 

Bei der Ausgabe der Noten für Arbeits- und Sozialverhalten beachten Sie bitte folgendes:

1) Legen Sie im `Schlüsselverzeichnis > Fächer` Leistungsbereitschaft, Zuverlässigkeit, Selbstständigkeit, Verantwortungsbereitschaft, Konfliktverhalten und Kooperationsfähigkeit als Fächer an. Als Schlüssel weisen Sie dem Fach jeweils die ersten 3 Buchstaben zu ("Lei" für Leistungsbereitschaft, "Zuv" für Zuverlässigkeit, "Sel" für "Selbstständigkeit, "Ver" für Verantwortungsbereitschaft, "Kon" für Konfliktverhalten und "Koo" für Kooperationsfähigkeit)

Kürzel | Schlüssel | Bezeichnung
--|--|--
beliebig | Lei |  Leistungsbereitschaft
beliebig | Zuv | Zuverlässigkeit
beliebig | Ver | Verantwortungsbereitschaft
beliebig | Kon | Konfliktverhalten
beliebig | Koo | Kooperationsfähigkeit

2) Im Menü `Abitur > Qualifikation` weisen Sie dem Schüler diese Fächer zu.
3) Zusätzlich erhalten diese Fächer im Menü `Abitur > Qualifikation` im Feld "Fachstatus" den Wert "Kopf" zu (siehe A15.50).
4)##  Im Menü `Abitur > Qualifikation` tragen Sie in Spalte "Q4" dem jeweiligen Fach eine Note zwischen 1-4 zu.

## Zugang am / Abgang am

`Schueler > Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü `Schüler > Daten 2` im Feld "Zugang am" bzw. "Abgang am" ein.

## Unterrichtsarten

`Extras > Schlüsselverzeichnisse > Unterrichtsarten`

Die korrekte Ausgabe der Zeugnisbereiche wird im Menü `Schüler > Zeugnis > Fächer` im Feld "Unterrichtsart" ausgewählt. Grundlage bildet das `Schlüsselverzeichnis > Unterrichtsarten`. Für den Zeugnisdruck ist dabei nur der Schlüssel der Unterrichtsart relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis Fachtafeln die Unterrichtsart zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Unterrichtsart nicht pro Schüler und pro Fach vornehmen.

Folgende Unterrichtsarten dürfen im Zeugnisdruck verwendet werden:

Kürzel |  Schlüssel | Zeugnisbereich
--|--|--
Theorie | Theorie | Berufsbezogener theoretischer Lernbereich
FP | FP | Berufsbezogener praktischer Lernbereich
LK | LK | Leistungskurse
GK | GK | Grundkurse

## SchulleiterIn

`Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter `Mandanten > Daten1` im Feld "Schulleiter" eingetragen werden. Bitte achten Sie darauf, das dem zugrunde liegenden Lehrereintrag ein Geschlecht unter `Lehrer > Daten1` zugewiesen wurde.

## KlassenleiterIn

`Klassen > Zeiträume > Zeitraum > Klassenleiter`

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü `Klassen > Zeiträume` bei der jeweiligen Klasse im Feld "Klassenleiter" eingetragen werden. Bitte achten Sie darauf, das dem zugrunde liegenden Lehrereintrag ein Geschlecht unter `Lehrer > Daten1` zugewiesen wurde.

## Jahrgang Klasse

`Klassen > Zeiträume > Zeitraum > Jahrgang`

Im entsprechenden Zeitraum muss im Menü `Klassen > Zeiträume` bei der Klasse des Schülers der Jahrgang im Feld "Jahrgang" eingetragen sein.

## Positionierung der Zeugnisbemerkungen

`Abitur > Zeugnis > Zeugnisbemerkungen > Position`

Zum Eintragen einer Zeugnisbemerkung muss im Bereich `Abitur > Zeugnis > Zeugnisbemerkungen` im Feld "Position" bei der jeweiligen Zeugnisbemerkung eine Positionsnummer angegeben werden. Z.B. für die erste Bemerkung
eine "1", für die zweite eine "2" usw.

## Zeugnisbemerkungen

`Abitur > Zeugnisbemerkungen`

`Schüler > Zeugnis > Bemerkungen/Formulare`

Bemerkungen Legen Sie im MenüSchüler > Zeugnis > Bemerkungen/Formulare oder im Menü Abitur > Zeugnisbemerkungen an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren.  
Einen Platzhalter definieren Sie über „``<<“ zum Beginn und „>>``“ zum Ende Ihres Platzhalters, z.B.  So ``<<hier steht Ihr Platzhalter>>``.  

Möglich sind:

Platzhalter | Ausgabe im Bericht
--|--
``<<Name>>`` | Vorname, Vorname2, Namenszusatz und Nachname des Schülers
``<<Nachname>>`` | Nachname des Schülers
``<<Vorname>>`` | Vorname, Vorname2 und Namenszusatz des Schülers
``<<Anrede1>>`` | Er/Sie (je nach Geschlecht des Schülers)
``<<Anrede2>>`` | er/sie (je nach Geschlecht des Schülers)
``<<Anrede3>>`` | seine/ihre (je nach Geschlecht des Schülers)
``<<Anrede4>>`` |  ihm/ihr (je nach Geschlecht des Schülers)
``<<Anrede5>>`` | seinen/ihren (je nach Geschlecht des Schülers)