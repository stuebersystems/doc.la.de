# BER-Schul Z 104 – Zeugnis der Jahrgangsstufen 3 und 4 – (04.23).rpt

Schul Z 104 – Zeugnis der Jahrgangsstufen 3 und 4 – (04.23).rpt

## Abbildung

[01]:/assets/images/Berlin/_schule.eins/Z104_schuleeins00.png "Vorderseite"

[![Vorderseite][01]][01]

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" mit STRG+Z oder Drucken > Zeugnis gedruckt werden.

## Zeiträume

`Extras > Schlüsselverzeichnisse > Zeiträume > Ausdruck 1`

Die Ausgabe des Schulhalbjahres erfolgt aufgrund der Definition des aktuellen Zeitraums in Magellan unter `Schlüsselverzeichnisse > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck1".

## Logo

Das Wappen ist eine feste Ausgabe, das Logo auf der rechten Seite im Zeugniskopf kann aus einer unter `Mandanten > Daten2 > Logo` hinterlegten JPG-Datei ausgegeben werden.

## Versetzung

`Schueler > Laufbahn > Allgemein > Versetzt`<br/>`Extras > Schlüsselverzeichnisse > Zeiträume > Art`<br/>`Klassen > Zeiträume > Jahrgang`

Die Ausgabe wird immer entsprechend der erfassten Zeitraumart, des aktellen Klassenjahrgangs und dem Eintrag in Feld "Versetzt" gebildet.

## Fehltage und/oder Fehlstunden

`Schueler > Zeugnis > Details > Fehltage und/oder Fehlstunden`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern "Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

Mögliche Ausgaben sind:

Ausgabe|Voraussetzungen
--|--
`Vorname` besucht die Jahrgangsstufe `Klassenjahrgang`.| 1.Halbjahr
`Vorname` rückt im kommenden Schuljahr auf in die Jahrgangsstufe `Klassenjahrgang`.|2.Halbjahr, versetzt
`Vorname` wiederholt im kommenden Schuljahr die Jahrgangsstufe `Klassenjahrgang`.|2.Halbjahr, nicht versetzt


## Fächer

`Extras > Schlüsselverzeichnisse > Fächer` <br/>`Schüler > Zeugnisse > Fächer` <br/>`Extras > Schlüsselverzeichnisse > Unterrichtsarten`

Fächer werden an bestimmten Eigenschaften erkannt und ausgegeben.

Fach|Spalte|Voraussetzung
--|--|--
Deutsch|links|Fachbezeichnung "Deutsch", Unterrichtsart nicht "WahlPF" oder "FachT"
Sprechen und Zuhören|links|Fachbezeichnung "Sprechen und Zuhören"
Schreiben - Texte verfassen|links|Fachbezeichnung "Schreiben - Texte verfassen"
Schreiben - Rechtschreibung|links|Fachbezeichnung "Schreiben - Rechtschreibung"
Sprachwissen - Sprachbewussheit|links|Fachbezeichnung "Sprachwissen - Sprachbewussheit"
Lesen - Mit Texten und Medien umgehen|links|Fachbezeichnung "Lesen - Mit Texten und Medien umgehen"
Fremdsprache|links|Fach muss unter `Schüler > Zeugnisse > Fächer` und unter `Schüler > Daten 3 > FS1` erfasst sein
Mathematik|rechts|Fachbezeichnung "Mathematik"
Naturwissenschaften|rechts|Fachbezeichnung "Naturwissenschaften"
Gesellschaftswissenschaften|rechts|Fachbezeichnung "Gesellschaftswissenschaften"
Kunst|rechts|Fachbezeichnung "Kunst"
Musik|rechts|Fachbezeichnung "Musik"
Sport|rechts|Fachbezeichnung "Sport"
erste freie Zeile|rechts|beliebiges Fach, Position 100|rechts|
zweite freie Zeile|rechts|beliebiges Fach, Position 101|rechts|

## Noten

`Schüler > Zeugnis > Leistungen`<br/>`Extras > Schlüsselverzeichnisse > Noten`

Die Noten werden für die Fächer aus dem Feld `Endnote` unter `Schüler > Zeugnis > Leistungen` gelesen, es wird das Notenkürzel ausgegeben.


## Benotung

`Schüler > Zeugnis > Leistungen > Endnote`

Die Noten der Fächer tragen Sie im Menü `Schüler > Zeugnis > Leistungen` in der Spalte "Endnote" ein. Grundlage bildet das `Schlüsselverzeichnis > Noten`.

## Versäumnisse, Fehlzeiten

`Schüler > Zeugnis > Details`

Tragen Sie die "Verspätungen" im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` ein.

## Zeugnisbemerkungen

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

### ASV, Beiblatt

Der Bericht gibt an verschiedenen Stellen Zeugnisbemerkungen oder auch vordefinierte Texte aus, dabei wird das Feld `Merkmal` ausgewertet. Folgende Merkmale sind möglich:

Merkmal|Bereich|Position|Ergebnis
--|--|--|--
leer| Rückseite, "Weitere Bemerkungen:"|muss aufsteigend gefüllt sein| Text der Bemerkungen wird ausgegeben
Beiblatt|Vorderseite, "Bemerkungen:"|leer|vordefinierte Bemerkungen wird ausgegeben ("Ein Beiblatt (Schul Z 620) ist Bestandteil dieses Zeugnisses" oder "Ein Beiblatt (Schul Z 620) ist nicht Bestandteil dieses Zeugnisses")
ASV|Vorderseite, "Bemerkungen:"|leer|vordefinierte Bemerkungen wird ausgegeben ("Entsprechend dem Beschluss der Schulkonferenz wird das Arbeits- und Sozialverhalten in der Anlage zu diesem Zeugnis beurteilt" oder "Entsprechend dem Beschluss der Schulkonferenz wird das Arbeits- und Sozialverhalten in der Anlage zu diesem Zeugnis nicht beurteilt")

### individuelle Bemerkungen

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

### Platzhalter

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
