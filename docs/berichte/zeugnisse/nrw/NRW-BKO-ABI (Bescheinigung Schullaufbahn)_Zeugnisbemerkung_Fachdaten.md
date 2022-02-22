# NRW-BKO-ABI (Bescheinigung Schullaufbahn)_Zeugnisbemerkung_Fachdaten
## NRW-BKO-ABI (Bescheinigung Schullaufbahn)_Zeugnisbemerkung_Fachdaten.rpt

Dieser Bericht gibt die Zeugnisbemerkungen aus dem Bereich `Schüler > Zeugnis > Zeugnis > Zeugnisbemerkungen` für das beim Druck gewählte Halbjahr aus.

## Ausgabe Schulhalbjahr 

`Extras > Schlüsselverzeichnisse > Zeiträume > Ausdruck 1`

Die Ausgabe des Schulhalbjahres erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN unter `Schlüsselverzeichnisse > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck1".

## Jahrgang Klasse

`Klassen > Zeiträume > Zeitraum > Jahrgang`

Im entsprechenden Zeitraum muss im Menü `Klassen > Zeiträume` bei der Klasse des Schülers der Jahrgang im Feld "Jahrgang" eingetragen sein.

## Fehltage, Fehlstunden

`Schueler > Zeugnis > Details > Fehltage und/oder Fehlstunden`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern "Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

## Fachstatus 

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis> Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.

Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel |  Schlüssel | Bezeichnung	
--|--|--
1 PF | 1 PF | 1. Prüfungsfach
2 PF  | 2 PF  | 2. Prüfungsfach
3 PF  | 3 PF  | 3. Prüfungsfach
4 PF  | 4 PF  | 4. Prüfungsfach
BerufS2 | BerufS2 | 2. Berufsbezogener Lernbereich

## Aufgabenbereich 

`Extras > Schlüsselverzeichnisse > Fächer > Aufgabenbereich`

Für die korrekte Ausgabe der Zeugnisbereiche wählen Sie unter `Schlüsselverzeichnis > Fächer` für jedes Fach einen Aufgabenbereich aus dem Drop-Down-Menü in der Spalte "Aufgabenbereich" aus. Diese Fächer müssen im Menü `Schüler > Zeugnis > Fächer` zugewiesen sein. Folgende Aufgabenbereiche dürfen im Zeugnisdruck verwendet werden:

Aufgabenbereich|  Zeugnisbereich
--|--
sprachl.-lit.-künstlerisch > 1. Aufgabenfeld
gesellschaftswiss. > 2. Aufgabenfeld
mathem.-nat.-technisch > 3. Aufgabenfeld

## Ausdruck

Das Zeugnis wird in DIN A3 Format und doppelseitig ausgegeben.

## Bildungsgang der Klasse

`Klassen > Daten > Bildungsgang`

Weisen Sie unter `Klassen > Daten` im Feld "Bildungsgang" zu. Grundlage bildet das `Schlüsselverzeichnis > Bildungsgänge`.

## SchulleiterIn

`Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter `Mandanten > Daten1` im Feld "Schulleiter" eingetragen werden. Bitte achten Sie darauf, das dem zugrunde liegenden Lehrereintrag ein Geschlecht unter `Lehrer > Daten1` zugewiesen wurde.

## KlassenleiterIn

`Klassen > Zeiträume > Zeitraum > Klassenleiter`

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü `Klassen > Zeiträume` bei der jeweiligen Klasse im Feld "Klassenleiter" eingetragen werden. Bitte achten Sie darauf, das dem zugrunde liegenden Lehrereintrag ein Geschlecht unter `Lehrer > Daten1` zugewiesen wurde.

## Konferenzdatum

`Abitur > Prüfung > Konferenzdatum`

Tragen Sie das Zeugnisdatum im Menü `Abitur > Prüfung` im Feld "Konferenzdatum" ein.

## Fächerpositionierung

`Schüler > Zeugnis > Fächer > Position``

Die Reihenfolge der Fächer auf dem Zeugnis richtet sich nach der Positionsnummer, die Sie dem jeweiligen Fach in der Spalte "Position" vergeben haben.

## Zeugnisbemerkungen

`Schlüsselverzeichnisse > Zeugnisbemerkungen`

Zeugnisbemerkungen können im `Schlüsselverzeichnis > Zeugnisbemerkungen` vordefiniert werden oder beim Schüler individuell formuliert werden.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld „Position“ eine Reihenfolge (Nummerierung)##  vorgegeben werden - für die Ausgabe der ersten Bemerkung „1“, für die Ausgabe der zweiten Bemerkung „2“ usw.

+++Wichtiger Hinweis+++
Bei Halbjahres- und Jahreszeugnissen sowie bei Abgangszeugnissen kann der Eintrag in der Spalte "Merkmal" freigelassen oder der Eintrag „zb“ verwendet werden.
Bei den Verhaltenszeugnisbemerkungen muss das Merkmal „SchulA“ verwendet werden.

Sie können Zeugnisbemerkungen über Platzhalter personalisieren. Möglich sind:

Platzhalter | Ausgabe im Bericht
--|--
``<<Vorname>>`` | Vorname des Schülers
``<<Nachname> | Nachname des Schülers
``<<Frau>>`` | Frau
``<<Sie>>`` | Sie
``<<Herr>>`` | Herr
``<<Herrn>>`` | Herrn
``<<Er>>`` | Er

## Zeugnisbemerkungen 

`Schüler > Zeugnis > Bemerkungen/Formulare`
`Abitur > Abitur > Zeugnis > Zeugnisbemerkungen`
`Berufsschule > Zeugnisbemerkungen`

Bemerkungen legen Sie entweder im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` ODER im Menü `Abitur > Zeugnis > Zeugnisbemerkungen` ODER `Abitur > Zeugnis > Zeugnisbemerkungen` an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren.  
Einen Platzhalter definieren Sie über „``<<“ zum Beginn und „>>``“ zum Ende Ihres Platzhalters, z.B.  So ``<<hier steht Ihr Platzhalter>>``.  

Möglich sind:

Platzhalter in MAGELLAN | Anzeige im Bericht
--|--
``<<VornameV>>`` | Vorname Vorname2
``<<Nachname>>`` | Nachname
``<<NachnameV>>`` | Namenszusatz Nachname
``<<Name>>`` | Vorname Vorname2 Namenszusatz Nachname
``<<Name>>`` | Vorname, Vorname2, Namenszusatz und Nachname des Schülers
``<<Nachname>>``  |  Nachname des Schülers
``<<Vorname>>`` |  Vorname, Vorname2 und Namenszusatz des Schülers
``<<Er_Sie>>`` |  Er/Sie (je nach Geschlecht des Schülers)
``<<Seine_Ihre>>`` | Seine/Ihre (je nach Geschlecht des Schülers)##      
``<<seine_ihre>>`` |  seine/ihre (je nach Geschlecht des Schülers)##  
``<<Ihm_Ihr>>`` |  Ihm/Ihr (je nach Geschlecht des Schülers)##  
``<<ihm_ihr>>`` |  ihm/ihr (je nach Geschlecht des Schülers)##  
``<<Seinen_Ihren>>`` |  Seinen/Ihnen (je nach Geschlecht des Schülers)##  
``<<seinen_ihren>>`` |  seinen/ihnen (je nach Geschlecht des Schülers)##  
``<<DerSchueler_DieSchuelerin>>`` |  Der Schüler/Die Schülerin je nach Geschlecht des Schülers)##  
``<<derSchueler_dieSchuelerin>>``  | der Schüler/die Schülerin  (je nach Geschlecht des Schülers)##  
``<<DemSchueler_DerSchuelerin>>``  |  Dem Schüler/Der Schülerin (je nach Geschlecht des Schülers)

## Zeugnisbemerkungen

`Schüler > Zeugnis > Bemerkungen/Formulare`

Für diesen Bericht werden die Zeugnisbemerkungen aus dem Menü `Schüler > Zeugnis > Bemerkungen/Formulare` aus dem beim Druck aufgerufenen Halbjahr abgefragt. Bitte weisen Sie Ihren Bemerkungen im Feld „Position“  eine Positionsnummer zu. Z.B. für die erste Bemerkung eine „1“, für die zweite eine „2“ usw.

## Ausdruck `Ausdruck > Abitur`

Das Zeugnis/der Bericht muss aus dem Menü `Abitur` gedruckt werden. Fach und Noten werden aus dem Bereich `Abitur` erwartet, die Zeugnisbemerkung aus dem Menü `Schüler`.