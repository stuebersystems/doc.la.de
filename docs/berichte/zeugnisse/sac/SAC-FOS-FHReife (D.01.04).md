# SAC-FOS-FHReife (D.01.04)

D.01.04 Zeugnis über die Zuerkennung der Fachhochschulreife

## Ausgabe Schulhalbjahr 

`Extras > Schlüsselverzeichnisse > Zeiträume > Ausdruck 1`

Die Ausgabe des Schulhalbjahres erfolgt aufgrund der Definition des aktuellen Zeitraums in Magellan unter `Extras > Schlüsselverzeichnisse > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck1".

## Fachstatus 

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.
Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Bezeichnung
--|--|--
FA | FA | Facharbeit
FachP | FachP | Fachpraxis im Berufsfeld
Pflicht | Pflicht | Pflichtfach

## Zugang am / Abgang am 

`Schueler > Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü Schüler > Daten 2 im Feld "Zugang am" bzw. "Abgang am" ein.

## Fachrichtung

`Extras > Schlüsselverzeichnis > Bildungsgänge`<br/>
`Extras > Schlüsselverzeichnisse > Berufsfelder`

Die Fachrichtung entspricht dem Berufsfeld des Bildungsganges des Schülers bzw. der Klasse.

1. Bitte definieren Sie die Berufsfelder unter `Extras > Schlüsselverzeichnisse > Berufsfelder`. Die Bezeichnung der Berufsfelder wird später auf dem Bericht gezeigt.
2. Weisen Sie im zweiten Schritt die Berufsfelder den Bildungsgängen unter `Extras > Schlüsselverzeichnis > Bildungsgänge` zu. 
3. Tragen Sie den Schülern bitte den Bildungsgang unter `Schüler  > Ausbildung` ein, hierfür steht Ihnen eine Sammelzuweisung zur Verfügung oder unter oder unter `Klasse > Daten`.

## Schulname 

`Mandanten > Daten > Name 1`

Tragen Sie die Bezeichnung Ihrer Schule im Menü "Mandanten" auf der Registerkarte "Daten 1" im Feld "Name
1" ein.

## Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Schüler` gedruckt werden.

## Zeugnisbemerkungen Positionierung

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

## Notendurchschnitt

`Schüler > Zeugnis > Leistungen > Durchschnitt einblenden`

Der Gesamtdurchschnitt wird wie folgt ermittelt.

1) Bleibt das Feld "Durchschnitt 1" leer (Menü `Schüler > Zeugnis > Leistungen` Feld "Durchschnitt 1"), so wird der Durchschnitt gemäß Prüfungsvorschrift automatisch im Bericht berechnet.
2) Bleibt das Feld "Durchschnitt 1" nicht leer (Menü `Schüler > Zeugnis > Leistungen` Feld "Durchschnitt 1"), so wird der eingetragene Durchschnitt ausgegeben.

## Mandanten / Ort

`Mandanten > Daten 1 > Ort`

Der Schulort (bzw. Ausstellungsort) ergibt sich aufgrund der Eintragung im Menü `Mandanten > Daten 1` im Feld „Ort“.

## Organisation der Klasse

`Klassen > Daten > Organisation`

Tragen Sie die Vollzeit- bzw. Teilzeitform unter `Klassen > Daten > Organisation` ein. Grundlage bildet das `Schlüsselverzeichnis > Organisiationen`.

## automatischen Berechnung der Durchschnittsnote 

`Schlüsselverzeichnisse > Fächer > Aufgabenbereich`

Da bei der automatischen Berechnung der Durchschnittsnote die Fächer Religion, Ethik und Sport nicht mit einfliessen, ist es zwingend erforderlich den jeweiligen Fächern im `Schlüsselverzeichnis > Fächer` im Feld "Aufgabenbereich" die Werte "Religion" oder "Sport" zuzuweisen.

## Schulform Klasse 

Die Schulform entspricht der Schulform des Schülers bzw. der Klasse.
`Extras > Schlüsselverzeichnis > Schulformen`
Grundlage für die Ausgabe "EINJÄHRIGEN / ZWEIJÄHRIGEN" Bildungsgang bildet das `Schlüsselverzeichnis > Schulformen`. Tragen Sie die Schulform im Menü `Klassen > Daten` im Feld „Schulform“ ein oder unter `Schüler > Ausbildung` im Feld „Schulform“ ein. Abgefragt wird der Schlüssel!

Bsp.:

Kürzel | Schlüssel | Bezeichnung
--|--|--
FOS 12L(v) | 14 | Fachoberschule 12L
FOS 12L(t)| 15 | Fachoberschule 12L
FOS/FOS | 140 | Fachoberschule

## Berechnung Durchschnittsnote FHR 

Die Durchschnittsnote, die im Zeugnis der Fachhochschulreife ausgewiesen wird, wird automatisch berechnet. Sie ist das arithmetische Mittel sämtlicher Noten dieses Zeugnisses. Sie wird auf eine Dezimalstelle ohne Rundung berechnet. Die Note für die Facharbeit (Fachstatus "FA") und die Note im Fach Sport (Verzeichnis "Fächer", Aufgabenbereich "Sport) bleiben bei der Berechnung der Durchschnittsnote unberücksichtigt.

## Fachpraktischen Teil der Ausbildung bestanden/nicht bestanden

`Schlüsselverzeichnisse > Fächer > Fachpraktischer Teil der Ausbildung`

Um den " Fachpraktischen Teil der Ausbildung" als bestanden oder nicht bestanden auszugeben, legen Sie im `Schlüsselverzeichnis > Fächer` ein Fach mit der Fachbezeichnung "Fachpraktischer Teil der Ausbildung" an. Weisen Sie dieses Fach dem Schüler im Menü `Schüler > Fächer` zu, zusätzlich tragen Sie im Feld "Fachstatus" den Wert "FachP" ein. Grundlage bildet das `Schlüsselverzeichnis > Fachstatus`. Die Benotung erfolgt im Feld "Note".

## Füllwerte für Benotung

`Extras > Schlüsselverzeichnisse > Noten > Füllwerte`

Um ein Fach mit einem bestimmten Füllwert (z.B.bestanden, nicht bestanden) auf dem Zeugnis auszugeben, müssen Sie unter `Schlüsselverzeichnisse > Noten` die Noten wie folgt anlegen. Auf dem Zeugnis wird die Bezeichnung ausgegeben.

Kürzel | Bezeichnung | Notenart
--|--|--
nb | nicht bestanden | Füllwerte
oB | ohne Bewertung | Füllwerte
b | bestanden | Füllwerte

## Ausgaben Facharbeit

`Extras > Schlüsselverzeichnisse > Fächer`

Für die Ausgabe der Facharbeit legen Sie im `Schlüsselverzeichnis > Fächer` ein Fach mit der Fachbezeichnung "Facharbeit" an. 

Kürzel | Schlüssel | Bezeichnung
--|--|--
FA | FA | Facharbeit

Weisen Sie dieses Fach dem Schüler im Menü `Schüler > Fächer` zu, zusätzlich tragen Sie im Feld "Fachstatus" den Wert FA" ein. Grundlage bildet das `Schlüsselverzeichnis >  Fachstatus`. 

Kürzel | Schlüssel | Bezeichnung
--|--|--
FA | FA | Facharbeit

Das Thema der Facharbeit tragen Sie im Menü `Schüler > Leistungem` im Feld "Beurteilung" an. Die Note der Facharbeit erfolgt im Feld "Endnote".

