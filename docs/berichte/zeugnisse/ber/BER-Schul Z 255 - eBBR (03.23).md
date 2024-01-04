# BER-Schul Z 255 - eBBR (03.23)

Schul Z 255 – Zeugnis des Gymnasiums über die erweiterte Berufsbildungsreife

[2]:/assets/images/Berlin/256.000.png
[3]:/assets/images/Berlin/256.001.png
[4]:/assets/images/Berlin/256.002.png
[5]:/assets/images/Berlin/256.003.png

## Versetzung

`Schueler > Laufbahn > Allgemein > Versetzt`

Im entsprechenden Zeitraum muss der Versetzungsvermerk im Menü `Schüler > Laufbahn > Allgemein` im Feld "Versetzt" eingetragen sein. Entscheidend ist hierbei die Markierung des Zeitraumes im linken Zeitraumfenster.

`Schüler > Laufbahn > Allgemein > Versetzt`

Ob der Schüler für die gymnasiale Oberstufe zugelassen wird oder nicht regeln Sie über das Feld „Versetzt“ im Menü `Schüler > Laufbahn > Allgemein`. Nehmen Sie keinen Eintrag vor oder weisen Sie den Status „Schüler wurde versetzt“ zu, wird auf dem Zeugnis „Das Zeugnis berechtigt zum Übergang in die gymnasiale Oberstufe“ markiert. Weisen Sie hingegen den Status „Schüler wurde NICHT versetzt“ zu, wird wird auf dem Zeugnis „Das Zeugnis berechtigt nicht zum Übergang in die gymnasiale Oberstufe“ markiert.

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

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.
Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
WahlPF | WahlPF | Wahlpflichtbereich

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

## Zeugnisbemerkungen

`Schüler > Zeugnis > Bemerkungen/Formulare > Merkmale`

Bei den Zeugnisbemerkungen müssen verschiedene Typen der Bemerkung unterschieden werden. Die Unterscheidung erfolgt durch den Eintrag in der Spalte "Merkmal" unter `Schlüsselverzeichnis > Zeugnisbemerkungen`, falls es sich um allgemeingültige Zeugnisbemerkungen handelt, oder beim Schüler, falls Sie diesem eine individuelle Zeugnisbemerkung zuweisen möchten. Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Bemerkungen/Formulare`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung auswählen und zuweisen. Erfolgt keine Eingabe in der Spalte "Merkmal", so wird die Bemerkung unter "allgemeinen Bemerkungen" auf dem Zeugnisdruck ausgegeben.
Folgende Kürzel im Feld "Merkmal" dürfen für den Zeugnisdruck verwendet werden:

Merkmal | Bedeutung
--|--
AG | Teilnahme an ergänzenden Angeboten
Beiblatt | Beiblatt ist Bestandteil des Zeugnisses

Die Ausgabe des Bemerkungstext: *Ein Beiblatt (Schul Z 620) ist Bestandteil dieses Zeugnisses:   ☐ ja   ☐ nein1).* wird wie folgt gesteuert:

Liegt eine Zeugnisbemerkung mit dem Merkmal "Beiblatt" beim Schüler vor, kommt der Text in der Bemerkung: *Ein Beiblatt (Schul Z 620) ist Bestandteil dieses Zeugnisses.*
Liegt dieses Merkmal nicht vor, kommt der Text in der Bemerkung: “Ein Beiblatt (Schul Z 620) ist nicht Bestandteil dieses Zeugnisses.

`Schüler > Zeugnis > Bemerkungen/Formulare`

Die Bemerkung "Entsprechend dem Beschluss der Schulkonferenz gemäß § 58 (7) SchulG wird das Arbeits- und Sozialverhalten - in der Anlage zu diesem Zeugnis berurteilt - nicht berurteilt-." wird vom Bericht automatisch eingetragen.

`Schüler > Zeugnis > Bemerkungen/Formulare > Merkmal (ASV1, ASV2, ASV12)`

Um die korrekte Bemerkung über das Arbeits- und Sozialverhalten zu generieren, legen Sie, falls das Arbeits- und Sozialverhalten beurteilt werden soll, im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` eine Zeugnisbemerkung mit dem Merkmal „ASV1“, „ASV2“ oder „ASV12“ an. Damit wird die entsprechende Bemerkung generiert und ermittelt um welches Schuljahr es sich handelt worauf sich Ihre Informationen über das „Arbeits- und Sozialverhalten“ beziehen, was für andere Zeugnisse relevant sein kann. Beachten Sie dabei: 

 Zeugnismerkmal|Schulhalbjahr
--|--
ASV1 | 1. HJ
ASV2 | 2. HJ
ASV12 | 1. und 2. HJ

Wird das Arbeits- und Sozialverhalten des Schülers nicht beurteilt, weisen Sie dem Schüler keine Bemerkung mit dem Merkmal „ASV1“, „ASV2“ oder „ASV12“ zu. Der entsprechende Vermerk wird auch dann ausgegeben.

`Schüler > Zeugnis > Bemerkungen/Formulare > Merkmal (LAT)`

Die Ausgabe "Dieses Zeugnis schließt den Nachweis des Latinums gemäß der „Vereinbarung über das Latinum und das Graecum“ (Beschluss der KMK vom 22.09.2005) ein / nicht ein."" erfolgt nur dann: 
Wenn Sie eine Zeugnisbemerkung mit dem Merkmal "LAT" angelegt haben, wenn es den Nachweis gibt. Die Zeugnisbemerkung muss dann genau so definiert werden, wie es auf dem Zeugnis ausgegeben werden soll. (D.h. Dieses Zeugnis schließt den Nachweis des Latinums gemäß der „Vereinbarung über das Latinum und das Graecum“ (Beschluss der KMK vom 22.09.2005) ein). 

Ist eine solche Zeugnisbemerkung mit diesem Merkmal "LAT" beim Schüler nicht eingetragen, wird der andere Fall als Standard ausgegeben. D.h. folgender Satz wird ausgegeben: "Dieses Zeugnis schließt den Nachweis des Latinums gemäß der „Vereinbarung über das Latinum und das Graecum“ (Beschluss der KMK vom 22.09.2005) nicht ein.

`Schüler > Zeugnis > Bemerkungen/Formulare > Merkmal (PRV)`

Für die Ausgabe von Bemerkungen zu Prüfungsversuchen legen Sie eine Zeugnisbemerkung mit dem Merkmal "PRV" an.

## Fremdsprachen

`Schüler > Daten 3 > 1./2./3./4. Fremdsprache`

Tragen Sie im Menü `Schüler > Daten 3` beim entsprechenden Schüler die Fremdsprache im aktuellen Zeitraum unter "Fremdsprachenfolge" ein. Damit Ihnen hier Fremdsprachen im Auswahlmenü
angeboten werden, müssen Sie unter `Schlüsselverzeichnis > Fächer` im Feld "Kategorie" aus dem Pull-Down-Menü "Fremdsprache" zugewiesen haben.

`Schüler > Daten 3 > Fremdsprachenfolge > Sprachreferenzen`

Bitte tragen Sie im Menü `Schüler > Daten 3 > Fremdsprachefolge` im Feld "Referenz" das Referenzniveau der Fremdsprache ein. Grundlage bildet das `Schlüsselverzeichnis > Sprachreferenzen`.

Vom Bericht wird das Kürzel abgefragt."

## Schulname

`Mandanten > Daten > Name 1`

Tragen Sie die Bezeichnung Ihrer Schule im Menü `Mandanten > Daten 1` im Feld "Name 1" ein.

`Mandanten > Daten > Name 2`

Tragen Sie die Namenszusätze Ihrer Schule im Menü `Mandanten > Daten 1` im Feld "Name 2" ein.

`Mandanten > Daten 1 > Name 3`

Tragen Sie den Bezirk Ihrer Schule im Menü `Mandanten > Daten 1` im Feld "Name 3" ein.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Schüler` gedruckt werden.

`Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein.

## vorgegeben Positionierung der Fächer

`Schüler > Zeugnis > Fächer > Position`

Um Noten den jeweiligen Fächer zuzuordnen, verwenden Sie für die Fächer folgende Positionen:

Fach | Position
--|--
Deutsch | 1
1. Fremdsprache | 2
2. Fremdsprache | 3
Lernbereich Gesellschaftswissenschaften | 4
Ethik | 5
Geografie | 6
Geschichte | 7
Politische Bildung | 8
Mathematik | 9
Lernbereich Naturwissenschaften | 10
Biologie | 11
Chemie | 12
Physik | 13
Kunst | 14
Musik | 15
Sport | 16
Informationstechnischen Grundkurs| 30
Wahlpflichtfach | 33
Wahlpflichtfach | 31
Wahlpflichtfach | 32
Wahlpflichtfach | 34
