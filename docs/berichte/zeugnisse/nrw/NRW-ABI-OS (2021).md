# NRW-ABI-OS (2021)

## Gültigkeit
Für die Verwendung am Oberstufenkolleg Bielefeld. 

Bitte beachten Sie ergänzend die Voraussetzungen für **Unterrichtsarten, Fachstatus, Fachkategorien und Aufgabenbereiche** für das dazugehörige Berechnungsskript unter [https://doc.la.stueber.de/08.nrw/nrw-apo-os-2020/](https://doc.la.stueber.de/08.nrw/nrw-apo-os-2020/).

## Druck

Bitte markieren Sie die Schüler im Menü `Abitur` und rufen den Bericht über STRG+Z im Unterverzeichnis `Nordrhein-Westfalen` auf.

## Mandanten

Bitte erfassen Sie im Menü `Mandanten` den `Ort` und den `Schulleiter`. Achten Sie bitte darauf, dass dem Lehrer, der als Schulleiter erfasst wird im Menü `Lehrer > Daten1` ein Eintrag im Feld `Geschlecht` zugewiesen wurde.

## Zeugnisdatum

`Abitur > Prüfung > Zeugnisdatum`

Tragen Sie das Zeugnisdatum im Menü `Abitur > Prüfung` im Feld "Zeugnisdatum" ein. Hierfür steht Ihnen auch auf der selben Karte der Aufruf für eine Sammelzuweisung zur Verfügung.

## Fremdsprachen, Sprachreferenz, Latinum

### Fremdsprachenfolge

`Schüler > Daten 3 > Von/Bis`

Tragen Sie das Von/Bis-Datum der belegten Fremdsprachen in den Feldern "von/bis" ein.

`Schüler > Daten 3 > 1./2./3./4. Fremdsprache`

Tragen Sie im Menü `Schüler > Daten 3` beim entsprechenden Schüler die Fremdsprache im aktuellen Zeitraum unter "Fremdsprachenfolge" ein. Damit Ihnen hier Fremdsprachen im Auswahlmenü angeboten werden, müssen Sie unter `Schlüsselverzeichnis > Fächer` im Feld "Kategorie" aus dem Pull-Down-Menü "Fremdsprache" zugewiesen haben.

### Sprachreferenzen

`Extras > Schlüsselverzeichnisse > Sprachreferenzen`

Bitte tragen Sie in unter im Menü `Schüler > Daten 3 > Fremdsprachenfolge` im Feld "Referenz" das Referenzniveau der Fremdsprache ein. Grundlage bildet das `Schlüsselverzeichnis > Sprachreferenzen`.

Mögliche Werte sind aktuell:

Kürzel | Schlüssel | Bezeichnung
--|--|--
A1 | A1 | Anfänger
A2 | A2 | Grundlegende Kenntnisse
B1 | B1 | Fortgeschrittene Sprachverwendung
B2 | B2 | Selbständige Sprachverwendung
C1 | C1 | Fachkundige Sprachkenntnisse
C2 | C2 | Annähernd muttersprachliche Kenntnisse

Vom Bericht fragt den Eintrag aus dem Feld "Kürzel" ab. Für das Zuweisen der `Sprachreferenzen` kann auch die Sammelzuweisung unter `Schüler > Schüler > Sammelzuweisung` verwendet werden.

### Latinum, Graecum, Hebraicum

Um die Bemerkung auf dem Bericht auszugeben, aktivieren Sie bitte das gewünschte Häkchen vor dem Feld unter `Abitur > Prüfung > Sprachkenntnisse.`

Häkchen<br/>aktiviert|Ausgabe
--|--
kleines Latinum|Das Zeugnis schließt Lateinkenntnisse im Umfang eines Kleinen Latinums (BASS 13 - 32 Nr. 3.2) ein.
großes Latinum|Dieses Zeugnis schließt das Latinum gemäß „Vereinbarung über das Latinum und das Graecum“ (Beschluss der Kultusministerkonferenz vom 22.09.2005) ein.
Graecum|Dieses Zeugnis schließt das Graecum gemäß „Vereinbarung über das Latinum und das Graecum“ (Beschluss der Kultusministerkonferenz vom 22.09.2005) ein.
großes Latinum und Graecum|Dieses Zeugnis schließt das Latinum und das Graecum gemäß „Vereinbarung über das Latinum und das Graecum“ (Beschluss der Kultusministerkonferenz vom 22.09.2005) ein.
Hebraicum|Dieses Zeugnis schließt das Hebraicum gemäß „Vereinbarung über das Latinum und das Graecum“ (Beschluss der Kultusministerkonferenz vom 22.09.2005) ein.

## Fachpositionen

Der Bericht verwendet für die Anzeigereihenfolge Postionsnummern. Bitte erfassen Sie die Positionsnummern im Abitur unter `Abitur > Qualifikation > Position`. Sie können dieses Feld auch per `Schüler synchronisieren` aus dem Bereich `Schüler > Zeugnis > Fächer` übertragen. Sollte ein Fach mehrfach für einen Schüler vergeben werden, sollten die Positionsnummern aufeinanderfolgend sein.
Positionsnummern dürfen nicht mehrfach vergeben werden und sollen aufsteigend sein, wobei das aber nicht bedeutet, dass es 1,2,3.. sein muss, auch 17,23,31 ist möglich.
Fachpositionen können bereits bei der Fachwahl per Fachwahltafel oder per Fachtafel zugewiesen werden.

## Prüfungen

Prüfungen können für die GH-Kurse des 3. Prüfungsfach und/oder 4. Prüfungsfach auch in mehreren Fächern des gleichen Aufgabenfeldes abgelegt werden. Beide Fächer müssen in MAGELLAN auf der Qualifikationskarte erscheinen und auswertbar markiert werden, da jeweils nur eine Teil der Kurse der jeweiligen Fachzeile als Prüfungsfächer berücksichtigt werden sollen, auf dem Abiturzeugnis aber nur eins der beiden Fächer erscheinen soll.

1. Beide Fachzeilen werden im Feld Status als Prüfungsfach markiert (Fachstatus `3PF` oder `4PF` ).
2. In der Spalte `Merkmal` wird manuell erfasst (Eintragung `Q1Q2` oder `Q3Q4`), welche Kurse je Fachzeile als Prüfungsfachkurse zu werten sind.
3. Für eine der beiden Zeilen wird in der Spalte `Merkmal` hinter der Kennzeichnung der Kurshalbjahre (`Q1Q2` oder `Q3Q4`) mit einem `*` gekennzeichnet, dass dieses Fach auf dem Abiturzeugnis als Prüfungsfach ausgegeben werden soll.

![Darstellung](/assets/images/nrw.bielefeld/04.png)


Merkmal|Bedeutung|
-----|-----|
Q1Q2 | Q1 und Q2 werden für die Prüfung eingebracht, das Fach selbst wird aber für die Prüfung nicht angezeigt|
Q3Q4 | Q3 und Q4 werden für die Prüfung eingebracht, das Fach selbst wird aber für die Prüfung nicht angezeigt|
Q1Q2* | Q1 und Q2 werden für die Prüfung eingebracht, das Fach selbst wird für die Prüfung angezeigt|
Q3Q4* | Q3 und Q4 werden für die Prüfung eingebracht, das Fach selbst wird für die Prüfung angezeigt|

!!! tipp "Hinweis!"

    Alle drei Informationen (Fachstatus, Zeugnisfach und PF-Kurshalbjahre) können bereits aus `Schüler > Zeugnis > Fächer` synchronisiert werden. Durch den korrekten Eintrag im Feld `Merkmal` wird sichergestellt, dass bei der erneuten Auslösung des Skriptes nicht das verkehrte Fach auf die Prüfungskarte übernommen wird.

## Zeugnisbemerkungen

`Abitur > Zeugnisbemerkungen`

Legen Sie im Menü `Abitur > Zeugnisbemerkungen` oder unter `Extras > Schlüsselverzeichnisse > Zeugnisbemerkungen` Bemerkungen an.
 
Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren. Platzhalter werden in der Berichtsvorschau für Sie sichtbar mit den Eingaben aus der Datenbank gefüllt. 
Einen Platzhalter definieren Sie über „``<<“ zum Beginn und „>>``“ zum Ende Ihres Platzhalters, z.B.  So ``<<hier steht Ihr Platzhalter>>``.  

Beispiele für den Einsatz der Platzhalter:

Platzhalter|Ausgabe|Felder in MAGELLAN
--|--|--
Vorname   | Hans|Vorname
VornameV  |Hans Peter  |Vorname + 2.Vorname
Nachname  | Müller |Nachname
NachnameV | von Müller |Zusatz + Nachname
Name| Hans Peter von Müller|Vorname + 2.Vorname + Zusatz + Nachname

Nachstehend eine Übersicht der Platzhalter, die dieser Bericht erkennt.

Platzhalter|Inhalt
--|--
`<<Vorname>>`| Vorname
`<<VornameV>>`| Vorname + 2.Vorname
`<<Nachname>>`| Nachname
`<<NachnameV>>`| Zusatz + Nachname
`<<Name>>`| Vorname + 2.Vorname + Zusatz + Nachname
`<<Er_Sie>>`|"Er"
`<<er_sie>>`|"er"
`<<Seine_Ihre>>`|"Seine"
`<<seine_ihre>>`|"seine"
`<<Ihm_Ihr>>`|"Ihm"
`<<ihm_ihr>>`|"ihm"
`<<Seinen_Ihren>>`|"Seinen"
`<<seinen_ihren>>`|"seinen"
`<<DerSchueler_DieSchuelerin>>`|"Der Schüler"
`<<derSchueler_dieSchuelerin>>`|"der Schüler"
`<<DemSchueler_DerSchuelerin>>`|"Dem Schüler"
`<<demSchueler_derSchuelerin>>`|"dem Schüler"
`<<Er_Sie>>`|"Sie"
`<<er_sie>>`|"sie"
`<<Seine_Ihre>>`|"Ihre"
`<<seine_ihre>>`|"ihre"
`<<Ihm_Ihr>>`|"Ihr"
`<<ihm_ihr>>`|"ihr"
`<<Seinen_Ihren>>`|"Ihren"
`<<seinen_ihren>>`|"ihren"
`<<DerSchueler_DieSchuelerin>>`|"Die Schülerin"
`<<derSchueler_dieSchuelerin>>`|"die Schülerin"
`<<DemSchueler_DerSchuelerin>>`|"Der Schülerin"
`<<demSchueler_derSchuelerin>>`|"der Schülerin"
