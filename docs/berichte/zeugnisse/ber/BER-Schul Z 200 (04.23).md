# BER-Schul Z 200 (04.23)

Schul Z 200 – Zeugnis der ISS und der Gemeinschaftsschule, Jahrgangsstufen 7 bis 10, Noten und Punkte (04.23)

[01]:/assets/images/Berlin/_schule.eins/Z200_schuleeins00.png "Vorderseite"
[02]:/assets/images/Berlin/_schule.eins/Z200_schuleeins01.png "Rückseite"
[03]:/assets/images/Berlin/_schule.eins/Z200_schuleeins02.png "Notenumrechnung"

## Abbildungen

[![Vorderseite][01]][01]

[![Rückseite][02]][02]

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

## Ausgabe Fächer

`Extras > Schlüsselverzeichnisse > Fächer`

Fächer werden an bestimmten Merkmalen erkannt und als Ergebnis wird die Note an der korrekten Stelle ausgeben.

Fach|Voraussetzung
--|--
Deutsch|nicht Fachstatus "WahlPF" und Fachbezeichnung "Deutsch"
1.Fremdsprache|nicht Fachstatus "WahlPF" und Fach ist unter `Schüler > Daten3 > 1FS` und auch unter `Schüler > Zeugnis > Fächer` erfasst
Lernbereich Gesellschaftswissenschaften| nicht Fachstatus "WahlPF" und Faecher.Schluessel = "LBG" oder Faecher.Bezeichnung = "Gesellschaftswissenschaften" oder "Lernbereich Gesellschaftswissenschaften"
Ethik|nicht Fachstatus "WahlPF" und Fachbezeichnung "Ethik"
Geografie|nicht Fachstatus "WahlPF" und Fachbezeichnung "Geografie"
Geschichte|Ausgegeben wird die Note des Fachs (`Schüler > Zeugnis > Fächer`), das eine der folgenden Fachbezeichnungen hat: "Geschichte", "Geschichte/Sozialkunde", "Sozialkunde" 
Politische Bildung|nicht Fachstatus "WahlPF" und Fachbezeichnung "Politische Bildung"
Wirtschaft-Arbeit-Technik|nicht Fachstatus "WahlPF" und Fachbezeichnung "Wirtschaft-Arbeit-Technik"
Wahlpflichtfach <br/>linke Seite| Fachstatus "WahlPF" und Position 8
Wahlpflichtfach <br/>linke Seite| Fachstatus "WahlPF" und Position 20
Mathematik|nicht Fachstatus "WahlPF" und Fachbezeichnung "Mathe" oder "Mathematik"
Lernbereich Naturwissenschaften|nicht Fachstatus "WahlPF" und Fachbezeichnung "Lernbereich Naturwissenschaften", "Naturwissenschaften"
Biologie|nicht Fachstatus "WahlPF" und Fachbezeichnung "Biologie"
Chemie|nicht Fachnicht Fachstatus "WahlPF" und Fachbezeichnung "Chemie"
Physik|nicht Fachnicht Fachstatus "WahlPF" und Fachbezeichnung "Physik"
Kunst|nicht Fachnicht Fachstatus "WahlPF" und Fachbezeichnung "Kunst" oder "Bildende Kunst"
Musik|nicht Fachnicht Fachstatus "WahlPF" und Fachbezeichnung "Musik"
Sport|nicht Fachnicht Fachstatus "WahlPF" und Fachbezeichnung "Sport"
ITG <br/>rechte Seite|Fachbezeichnung "Informationstechnischer Grundkurs"
Wahlpflichtfach <br/>rechte Seite| Fachstatus "WahlPF" und Position 21
Wahlpflichtfach <br/>rechte Seite| Fachstatus "WahlPF" und Position 22

## Logo

Das Wappen ist eine feste Ausgabe, das Logo auf der rechten Seite im Zeugniskopf kann aus einer unter `Mandanten > Daten2 > Logo` hinterlegten JPG-Datei ausgegeben werden.

## Zeugnisdatum

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein. Das Zeugnisdatum kann auch per Sammelzuweisung zugewiesen werden, den Aufruf für die Sammelzuweisung finden Sie am oberen Rand der Karte `Details`.

## Fehltage und/oder Fehlstunden

`Schueler > Zeugnis > Details > Fehltage und/oder Fehlstunden`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern "Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

## Versäumnisse

`Schüler > Zeugnis > Details > Versäumnisse`

Tragen Sie die "Verspätungen" im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` im Feld "Versäumnisse" ein.

## Fachstatus

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.

Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Bezeichnung 
--|--|--
WahlPF | WahlPF | Wahlpflichtfach


## Benotung

`Klassen > Daten > Beurteilungsart`<br/>`Extras >  Schlüsselverzeichnisse > Noten` <br/> `Schüler > Zeugnis > Leistungen`

Im Menü "Klassen" muss bei der Klasse des Schülers auf der Registerkarte Daten im Feld "Beurteilungsart" "Benotung durch Punkte" angegeben sein.

Spalte | Eingabe
--|--
GR|**Berechnung** aus der Punkteingabe im Feld Endnote
ER|**Berechnung** aus der Punkteingabe im Feld Endnote
Punkte|Schüler > Zeugnis > Leistungen > **Endnote** <br/>(Werte werden aus der Eingabe unter Endnote (Noten-Wert aus dem Verzeichnis) umgerechnet)
mündliche Note| Schüler > Zeugnis > Leistungen > **Mündl. Note**
Schriftliche Note| Schüler > Zeugnis > Leistungen > **Schriftliche Note 4**

Die Eingabe der Punkte wird für ER und GR entsprechend der Vorgaben umgerechnet:

[![Notenumrechnung][03]][03]

### mdl./schriftl. Note/Gesamtnote Fächer

`Schüler > Zeugnis > Leistungen`

Manche Fächer werden mit einer Note für mündliche Leistungen, einer Note für schriftliche Leistungen und einer Gesamtnote versehen. Tragen Sie daher im Menü `Schüler > Zeugnis > Leistungen` die Noten wie folgt ein:

Note | Feld in Magellan
--|--
mündliche Note | Mündl. Note 
schriftliche Note | Schriftl. Note 4
Gesamtnote | Endnote

### Ausgabe "n.e."

`Klassen > Zeiträume > Jahrgang`

Wird der Klassenjahrgang 8 erkannt, werden für Physik folgende Ergebnisse ausgegeben:
GR= `--`
ER= `n.e.`
Punkte= `--`

Wird der Klassenjahrgang 7 erkannt, werden für Chemie folgende Ergebnisse ausgegeben:
GR= `--`
ER= `n.e.`
Punkte= `--`

## Fremdsprachenfolge

`Schüler > Daten 3 > 1./2./3./4. Fremdsprache`

Tragen Sie im Menü `Schüler > Daten 3` beim entsprechenden Schüler die Fremdsprache im aktuellen Zeitraum unter "Fremdsprachenfolge" ein. Damit Ihnen hier Fremdsprachen im Auswahlmenü angeboten werden, müssen Sie unter `Schlüsselverzeichnis > Fächer` im Feld "Kategorie" aus dem Pull-Down-Menü "Fremdsprache" zugewiesen haben.

## Schulname

`Mandanten > Daten > Name 1` <br/> `Mandanten > Daten > Name 2`<br/>`Mandanten > Daten > Name 3`

Tragen Sie die Bezeichnung Ihrer Schule im Menü "Mandanten" auf der Registerkarte "Daten 1" im Feld "Name
1" ein. Ergänzen Sie im Feld "Name2" die Schulart und im Feld "Name 3" Stadt und Bezirk.

## SchulleiterIn

`Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter `Mandanten > Daten1` im Feld "Schulleiter" eingetragen werden. Bitte achten Sie darauf, das dem zugrunde liegenden Lehrereintrag ein Geschlecht unter `Lehrer > Daten1` zugewiesen wurde.

## Jahrgang Klasse

`Klassen > Zeiträume > Zeitraum > Jahrgang`

Im entsprechenden Zeitraum muss im Menü `Klassen` bei der Klasse des Schülers der Jahrgang auf der Registerkarte `Zeiträume` im Feld "Jahrgang" eingetragen sein.

## Zeiträume

`Extras > Schlüsselverzeichnis > Zeiträume > Ausdruck 1`

Die Ausgabe des Schuljahres erfolgt aufgrund der Definition des aktuellen Zeitraums in Magellan `Schlüsselverzeichnis > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck1".

## Versetzung

`Schüler > Laufbahn > Allgemein > Versetzt` <br/> `Extras > Schlüsselverzeichnisse > Zeitraum > Art` <br/> `Klasse > Zeiträume > Jahrgang`

Der Vermerk wird nur ausgeben, wenn die Art des Zeitraum 1.Halbjahr ist. Im entsprechenden Zeitraum muss der Versetzungsvermerk im Menü `Schüler > Laufbahn > Allgemein` im Feld "Versetzt" oder "Nicht versetzt" eingetragen sein und der Klassenjahrgang muss erfasst sein.
Beim Druck aus dem 2. Halbjahr wird einer der beiden Sätze ausgegeben:

* `Vorname` rückt im kommenden Schuljahr auf in die Jahrgangsstufe `aktueller Klassenjahrgang +1`
* `Vorname` rückt im kommenden Schuljahr nicht auf.

## Zeugnisbemerkungen

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

### ASV, Beiblatt, ergänzende Angebote

Der Bericht gibt an verschiedenen Stellen Zeugnisbemerkungen oder auch vordefinierte Texte aus, dabei wird das Feld `Merkmal` ausgewertet. Folgende Merkmale sind möglich:

Merkmal|Bereich|Position|Ergebnis
--|--|--|--
leer| Rückseite, "Weitere Bemerkungen:"|muss aufsteigend gefüllt sein| Text der Bemerkungen wird ausgegeben
AG|Vorderseite, "ergänzende Angebote:"|leer|Text der Bemerkungen wird ausgegeben
Beiblatt|Vorderseite, "Bemerkungen:"|leer|vordefinierte Bemerkungen wird ausgegeben ("Ein Beiblatt (Schul Z 620) ist Bestandteil dieses Zeugnisses" oder "Ein Beiblatt (Schul Z 620) ist nicht Bestandteil dieses Zeugnisses")
ASV|Vorderseite, "Bemerkungen:"|leer|vordefinierte Bemerkungen wird ausgegeben ("Entsprechend dem Beschluss der Schulkonferenz wird das Arbeits- und Sozialverhalten in der Anlage zu diesem Zeugnis beurteilt" oder "Entsprechend dem Beschluss der Schulkonferenz wird das Arbeits- und Sozialverhalten in der Anlage zu diesem Zeugnis nicht beurteilt")

### Personalisierung

`Abitur > Zeugnisbemerkungen` oder `Schüler > Zeugnis > Bemerkungen/Formulare`

Bemerkungen Legen Sie im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` oder im Menü `Abitur > Zeugnisbemerkungen` an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren. 
Einen Platzhalter definieren Sie über „`<<“ zum Beginn und „>>`“ zum Ende Ihres Platzhalters, z.B. So `<<hier steht Ihr Platzhalter>>`. 

Möglich sind:

Platzhalter | Ausgabe im Bericht
--|--
`<<Name>>` | Vorname, Vorname2, Namenszusatz und Nachname des Schülers
`<<Nachname>>` | Nachname des Schülers
`<<Vorname>>` | Vorname, Vorname2 und Namenszusatz des Schülers
`<<Anrede1>>` | Er/Sie (je nach Geschlecht des Schülers)
`<<Anrede2>>` | er/sie (je nach Geschlecht des Schülers)
`<<Anrede3>>` | seine/ihre (je nach Geschlecht des Schülers)
`<<Anrede4>>` | ihm/ihr (je nach Geschlecht des Schülers)
`<<Anrede5>>` | seinen/ihren (je nach Geschlecht des Schülers)
