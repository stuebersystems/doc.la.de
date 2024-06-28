# MVP-FG-AZ (Qualifikationsphase)(2024)

## Abbildungen

[01]:/assets/images/MVP/001.png "S.1"
[02]:/assets/images/MVP/002.png "S.2"
[03]:/assets/images/MVP/003.png "S.3"

[![Seite 1][01]][01]
[![Seite 2][02]][02]
[![Seite 3][03]][03]

## Seite 1

### Zeugniskopf

Der Zeugniskopf gibt die Einträge aus `Menü Mandanten > Daten1 ` aus den Felder `Name1` und `Ort` aus.

### Wappen

Der Bericht gibt kein Wappen aus, sondern ist dafür gedacht, auf Papier mit Wappen gedruckt zu werden.

### Schülerdaten

Was|Wo
--|--
Vorname, Name| Wird aus den Feldern (`Schüler > Daten1`) Vorname, 2.Vorname, Zusatz und Nachname zusammegesetzt.
geb.am,in| Geburtsort und Geburtsdatum von `Schüler > Daten1`
von| `Schüler > Daten2 > Zugang am`
bis| `Schüler > Daten2 > Abgang am`
Schulhalbjahr| `Extras > Schlüsselverzeichnisse > Zeitraum > Art`
Jahrgangsstufe| `Klassen > Zeiträume > Zeitraum > Jahrgang`
erworben, nicht erworben| `Abitur > Qualifikation > Status` <br/>Fachhochschulreife erreicht<br/>Fachhochschulreife nicht erreicht<br/>oder Meldung `+++ PPRÜFUNGSSTATUS VERKEHRT +++`

## Seite 2

### Ausgabe der Fächer und Reihenfolge

Die Ausgabe basiert auf der Angabe der Fächer unter `Abitur > Qualifikation`. Die Fächer können hier natürlich auch aus `Schüler > Zeugnis > Fächer` synchronisiert werden. Die Reihenfolge ergibt sich aus den `Aufgabenbereichen` der vewendeten Fächer (siehe `Extras > Schlüsselverzeichnisse > Fächer > Aufgabenbereiche`), der den Fächer zugewiesenen `Position`.
Für die beiden Leistungskurse muss die Unterrichtsart `HF`. Kürzel und Schlüssel bitte unter `Extras > Unterrichtsart > Unterrichtsarten` = `HF` sein). 
Für das berufliche Schwerpunktfach erfassen Sie bitte zusätzlich unter `Extras > Schlüsselverzeichnisse > Fächer > Zeugnismerkmal` den Wert `BSF`.

### Facharbeit

Fach |Thema|Note
--|--|--
Fach|`Abitur > Prüfung > Projekt > Fach`
Thema|`Abitur > Prüfung > Projekt > Thema`
Note|`Abitur > Prüfung > Projekt > Punkte` (ganz links)

### Besondere Lernleistung

Fach |Thema|Note
--|--|--
Fach|`Abitur > Prüfung > Lernleistung > Fach`
Thema|`Abitur > Prüfung > Lernleistung > Thema`
Note|`Abitur > Prüfung > Lernleistung > Punkte` (ganz links)

## Seite 3

### Fremdsprachen

Die Fremdsprachen erfassen Sie bitte je Schüler unter `Schüler > Daten3 > Fremdsprachen` und vergeben hier bitte auch das `von` und `bis`. Diese Eintragungen können auch per Sammelzuweisung vorgenommen werden. Die "in der Einführungsphase neu beginnende Fremdsprache" wird ggfs. aus Ihren Angaben berechnet.

### Herkunftssprache

Wenn dem Schüler unter `Schüler > Daten1 > Muttersprache` ein Wert zugewiesen wurde und diese Muttersprache den identischen Wert im Feld Bezeichnung im jeweiligen Schlüsselverzeichnis (Fächer und Muttersprachen) für Fremdsprache1 oder Fremdsprache2 hat, dann wird die Bemerkung ausgegeben und mit dem Datum aus `Schüler > Merkmale > MerkmalD4` ergänzt.

### Nachweis

Hier kann ein flexibler Satz ausgegeben werden, der das Geschlecht des Schülers berücksichtigt und auch prüft, ob eins der Felder für Latinum, Gr.Latinum, Mittleres Latinum, Graecum unter `Abitur > Prüfungen` aktiviert wurde.

## Merkmale für Zeugnisbemerkungen

`Schüler > Zeugnis > Bemerkungen/Formulare > Merkmale`

Bei den Zeugnisbemerkungen müssen verschiedene Typen der Bemerkung unterschieden werden. 

Die Unterscheidung erfolgt durch den Eintrag in der Spalte "Merkmal". Sie können den Eintrag vorab im `Schlüsselverzeichnis > Zeugnisbemerkungen` für die Bemerkung vordefinieren oder individuell unter Schüler > Zeugnis > Bemerkungen/Formulare je Schülerbemerkung anpassen.
Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Bemerkungen/Formulare`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung auswählen und zuweisen. Erfolgt keine Eingabe in der Spalte "Merkmal", so wird die Bemerkung unter "allgemeinen Bemerkungen" auf dem Zeugnisdruck ausgegeben.

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

## Berechnungsgrundlage

[Landesanpassungen](https://doc.la.stueber.de)

Für den Zeugnisdruck des Abiturs lesen Sie bitte die Anleitung zu Ihrem Bundesland in unserer Online Dokumentation, die bildet die Grundlage. 