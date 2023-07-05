# BER-Schul Z 256 (03.23)

[1]:/assets/images/Berlin/ber-schul-z-256.png "Zugang, Abgang"
[2]:/assets/images/Berlin/256.000.png
[3]:/assets/images/Berlin/256.001.png
[4]:/assets/images/Berlin/256.002.png
[5]:/assets/images/Berlin/256.003.png

Schul Z 256 – Zeugnis des Gymnasiums über den mittleren Schulabschluss 

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Schüler` gedruckt werden.

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld Zeugnisdatum eingetragen sein.

## Schülerlaufbahn

`Schueler > Laufbahn > Allgemein > Versetzt`

Im entsprechenden Zeitraum muss der Versetzungsvermerk im Menü `Schüler > Laufbahn > Allgemein` im Feld `Versetzt` eingetragen sein. Entscheidend ist hierbei die Markierung des Zeitraumes im linken Zeitraumfenster.

## Kurshalbjahr Seite 1

`Extras > Schlüsselverzeichnisse > Zeiträume > Art` <br/>`Extras > Schlüsselverzeichnisse > Merkmale(Klassen)`<br/>`Klassen > Merkmale > MerkmalS4`

Das Kurshalbjahr wird berechnet aus den Eingaben unter `Extras > Schlüsselverzeichnisse > Zeiträume > Art` und dem Eintrag unter `Klasse > Merkmal S4`.

Bitte erfassen Sie im Schlüsselverzeichnis `Merkmale(Klassen)` den folgenden Wert und tragen ihn für G8-Klassen unter `Klassen > Merkmale > MerkmalS4` ein.

Kürzel|Schlüssel|Bezeichnung|Bereich
--|--|--|--
**G8**|G8|G8|**MerkmalS4**

## Zugang und Abgang

Bitte erfassen Sie Datumswerte für den Zugang und Abgang auf Seite 1 unter `Daten2 > ZugangAm und AbgangAm`. Dafür können Sie auch die Sammelzuweisung unter `Schüler > Schüler > Sammelzuweisung` verwenden.

![Zugang, Abgang][1]

## Ausgabe Versetzungstext Oberstufe

`Schüler > Laufbahn > Versetzungsart`

Den Versetzungstext in Bezug auf die Berechtigung zum Übergang an die gymnasiale Oberstufe, tragen Sie im Menu Schüler > Laufbahn > Versetzungsart ein. Grundlage bildet das `Schlüsselverzeichnis > Versetzungsarten`.

Kürzel | Schlüssel | Bedeutung
--|--|--
leer | leer | Wird nicht versetzt in Oberstufe
E | E | Versetzung in Einführungsphase
Q  | Q  | Versetzung in Qualifikationsphase

Hier wird der "Versetzungsart.Schlüssel" ausgewertet.

Ob der Schüler für die gymnasiale Oberstufe zugelassen wird oder nicht regeln Sie über das Feld „Versetzt“ im Menü `Schüler > Laufbahn > Allgemein`. Nehmen Sie keinen Eintrag vor oder weisen Sie den Status „Schüler wurde versetzt“ zu, wird auf dem Zeugnis „Das Zeugnis berechtigt zum Übergang in die gymnasiale Oberstufe“ markiert. Weisen Sie hingegen den Status „Schüler wurde NICHT versetzt“ zu, wird auf dem Zeugnis „Das Zeugnis berechtigt nicht zum Übergang in die gymnasiale Oberstufe“ markiert.

## Fachstatus

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis Fachtafeln den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.
Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
WahlPF | WahlPF | Wahlpflichtbereich
1PF | 1PF | 1. Prüfungsfach (Deutsch)
2PF | 2PF | 2. Prüfungsfach (Mathematik)
3PF | 3PF | 3. Prüfungsfach (1.Fremdsprache)
4PF | 4PF | 4. Prüfungsfach (Präsentationsprüfung)

## Zeugnisbemerkungen

`Schüler > Zeugnis > Bemerkungen/Formulare > Merkmale`

Bei den Zeugnisbemerkungen müssen verschiedene Typen der Bemerkung unterschieden werden. Die Unterscheidung erfolgt durch den Eintrag in der Spalte Merkmal unter `Schlüsselverzeichnis > Zeugnisbemerkungen`, falls es sich um allgemeingültige Zeugnisbemerkungen handelt, oder beim Schüler, falls Sie diesem eine individuelle Zeugnisbemerkung zuweisen möchten. Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Bemerkungen/Formulare`. Wenn Sie die Schaltfläche Hinzufügen anklicken, können Sie eine Zeugnisbemerkung auswählen und zuweisen. Erfolgt keine Eingabe in der Spalte Merkmal, so wird die Bemerkung unter allgemeinen Bemerkungen auf dem Zeugnisdruck ausgegeben.
Bitte beachten Sie, dass Sie für die Zeugnisbemerkungen aufsteigende Positionen erfassen, die die Reihenfolge beim Anzeigen steuern.

Folgende Kürzel im Feld Merkmal dürfen für den Zeugnisdruck verwendet werden:

Merkmal | Bedeutung
--|--
`AG` | Teilnahme an ergänzenden Angeboten
`Beiblatt` | Beiblatt ist Bestandteil des Zeugnisses
`ASV1` | 1. HJ
`ASV2` | 2. HJ
`ASV12` | 1. und 2. HJ
`LAT`| siehe Latinum, Graecum
leer|Die Bemerkung wird auf Seite 4 unter `V. Bemerkungen:` ausgegeben.

### Beiblatt

Die Ausgabe des Bemerkungstext: Ein Beiblatt (Schul Z 620) ist Bestandteil dieses Zeugnisses:  
☐ ja   ☐ nein 1). wird wie folgt gesteuert:

Liegt eine Zeugnisbemerkung mit dem Merkmal Beiblatt beim Schüler vor, kommt der Text in der Bemerkung: “Ein Beiblatt (Schul Z 620) ist Bestandteil dieses Zeugnisses.”
Liegt dieses Merkmal nicht vor, kommt der Text in der Bemerkung: “Ein Beiblatt (Schul Z 620) ist nicht Bestandteil dieses Zeugnisses.”

### Arbeits- uns Sozialverhalten

`Schüler > Zeugnis > Bemerkungen/Formulare > Merkmal (ASV1, ASV2, ASV12)`

Um die korrekte Bemerkung über das Arbeits- und Sozialverhalten zu generieren, legen Sie, falls das Arbeits- und Sozialverhalten beurteilt werden soll, im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` eine Zeugnisbemerkung mit dem Merkmal „ASV1“, „ASV2“ oder „ASV12“ an. Damit wird die entsprechende Bemerkung generiert und ermittelt um welches Schuljahr es sich handelt worauf sich Ihre Informationen über das „Arbeits- und Sozialverhalten“ beziehen, was für andere Zeugnisse relevant sein kann. Beachten Sie dabei: 

Wird das Arbeits- und Sozialverhalten des Schülers nicht beurteilt, weisen Sie dem Schüler keine Bemerkung mit dem Merkmal „ASV1“, „ASV2“ oder „ASV12“ zu. Der entsprechende Vermerk wird auch dann ausgegeben.

Die Bemerkung Entsprechend dem Beschluss der Schulkonferenz gemäß § 58 (7) SchulG wird das Arbeits- und Sozialverhalten - in der Anlage zu diesem Zeugnis berurteilt - nicht berurteilt-. wird vom Bericht automatisch eingetragen.

### Latinum, Graecum

`Schüler > Zeugnis > Bemerkungen/Formulare > Merkmal (LAT)`

Die Ausgabe Dieses Zeugnis schließt den Nachweis des Latinums gemäß der „Vereinbarung über das Latinum und das Graecum“ (Beschluss der KMK vom 22.09.2005) ein / nicht ein. erfolgt nur dann: 
Wenn Sie eine Zeugnisbemerkung mit dem Merkmal `LAT` angelegt haben, wenn es den Nachweis gibt. Die Zeugnisbemerkung muss dann genau so definiert werden, wie es auf dem Zeugnis ausgegeben werden soll. (D.h. Dieses Zeugnis schließt den Nachweis des Latinums gemäß der „Vereinbarung über das Latinum und das Graecum“ (Beschluss der KMK vom 22.09.2005) ein). 

Ist eine solche Zeugnisbemerkung mit diesem Merkmal LAT beim Schüler nicht eingetragen, wird der andere Fall als Standard ausgegeben. D.h. folgender Satz wird ausgegeben: Dieses Zeugnis schließt den Nachweis des Latinums gemäß der „Vereinbarung über das Latinum und das Graecum“ (Beschluss der KMK vom 22.09.2005) nicht ein.

## Fremdsprachen

`Schüler > Daten 3 > 1./2./3./4. Fremdsprache`

Tragen Sie im Menü `Schüler > Daten 3` beim entsprechenden Schüler die Fremdsprache im aktuellen Zeitraum unter Fremdsprachenfolge ein. Damit Ihnen hier Fremdsprachen im Auswahlmenü
angeboten werden, müssen Sie unter `Schlüsselverzeichnis > Fächer` im Feld Kategorie aus dem Pull-Down-Menü Fremdsprache zugewiesen haben.

`Schüler > Daten 3 > Fremdsprachenfolge > Sprachreferenzen`

Bitte tragen Sie im Menü `Schüler > Daten 3 > Fremdsprachefolge` im Feld Referenz das Referenzniveau der Fremdsprache ein. Grundlage bildet das `Schlüsselverzeichnis > Sprachreferenzen`.

Vom Bericht wird das Kürzel abgefragt.

## Schulname

`Mandanten > Daten > Name 1`

Tragen Sie die Bezeichnung Ihrer Schule im Menü `Mandanten > Daten 1` im Feld Name 1 ein.

`Mandanten > Daten 1 > Name 3`

Tragen Sie den Bezirk Ihrer Schule im Menü `Mandanten > Daten 1` im Feld Name 3 ein.

`Mandanten > Daten > Name 2`

Tragen Sie die Namenszusätze Ihrer Schule im Menü `Mandanten > Daten 1` im Feld Name 2 ein.

## II. Leistungen im Prüfungsteil (Seite 3)

Für die Ausgabe der Fächer und Noten im Menü `Schüler > Zeugnis > Fächer` im Feld "Fachstatus" die folgenden Einträge. Grundlage bildet das `Schlüsselverzeichnis > Fachstatus`.

Kürzel | Schlüssel | Bedeutung
--|--|--
1PF | 1PF | 1. Prüfungsfach (Deutsch)
2PF | 2PF | 2. Prüfungsfach (Mathematik)
3PF | 3PF | 3. Prüfungsfach (1.Fremdsprache)
4PF | 4PF | 4. Prüfungsfach (Präsentationsprüfung)

Die Noten der Prüfungsfächer erfassen Sie im Menü `Schüler > Zeugnis > Leistungen` in folgenden Feldern:

Spalte | Note für..
--|--
**Endnote (Gesamt)** | Gesamtnote
**Schriftl. Note 1**| schriftlich
**mdl. Note**| mündlich

[![Zugang, Abgang][2]][2]
[![Zugang, Abgang][4]][4]

## Benotung im Fach Deutsch

`Schüler > Zeugnis > Leistungen > Deutsch`

Deutsch erhält eine Note für den "allgemeinen Teil", "schriftliche Leistungen" und eine "Gesamtnote". Tragen Sie daher im Menü `Schüler > Zeugnis > Leistungen` für das Fach "Deutsch" die Noten in folgende Felder: 

Note | Spalte
--|--
**Endnote**|Gesamtnote
**schriftl. Note 3**|allgemeiner Teil 
**schriftl. Note 4**|schriftliche Leistungen

[![Zugang, Abgang][3]][3]
[![Zugang, Abgang][5]][5]

## vorgegeben Positionierung der Fächer

`Schüler > Zeugnis > Fächer > Position`

Um Noten den jeweiligen Fächer zuzuordnen, verwenden Sie für die Fächer folgende Positionen:

* Deutsch: 1
* 1. Fremdsprache: 2
* 2. Fremdsprache: 3
* Lernbereich Gesellschaftswissenschaften : 4
* Geografie: 5
* Geschichte: 7
* Politische Bildung: 8
* Ethik: 9
* Mathe: 10
* Lernbereich Naturwissenschaften: 11
* Biologie: 12
* Chemie: 13
* Physik: 14
* Kunst: 15
* Musik: 16
* Sport: 17
* Informationstechnischer Grundkurs: 18
* Wahlpflichtfach eins: 30
* Wahlpflichtfach zwei: 31
* Wahlpflichtfach drei: 32
* Wahlpflichtfach vier: 33