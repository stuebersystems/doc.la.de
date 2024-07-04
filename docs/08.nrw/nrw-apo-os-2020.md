# NRW-APO-OS-2020

Nachstehend beschreiben wir die vorausgesetzten Eintragungen in Magellan.

## Verordnung und Gültigkeit

Quelle:

```
Abiturqualifikationsberechnung Nordrhein-Westfalen
Oberstufen-Kolleg an der Universität Bielefeld 
Abiturprüfungsordnung vom 20. Juni 2002 in der letzten Änderung vom 01. Mai 2020 
```

## Skriptfunktionalität

Dieses Skript kann die Gesamtqualifikation und die Fachhochschulreife berechnen. Bitte verwenden Sie dabei beim Auslösen des Skriptes unter `Abitur > Qualifikation` im Feld `Status` die Unterpunkte `Gesamtqualifikation berechnen` oder `Fachhochschulreife berechnen`.

Für den Status `Fachhochschulreife` wählen Sie im Feld `HJ eingebracht` bitte den Zeitraum `Q1-Q2`, `Q2-Q3` oder `Q3-Q4` aus und markieren die gewünschten Kurse.

### Markieren und Berechnen

Um die Gesamtqualifikation und Fachhochschulreife zu berechnen, markieren Sie die gewünschten Kurse. Dafür aktivieren Sie bitte das Häkchen vor `Manuell Markieren` und klicken die gewünschten Kurse an. Die markierten Kurse werden gelb hinterlegt dargestellt.

![Markieren](\assets\images\nrw\04.png)

Klicken Sie auf die Schaltfläche `Berechnen` um Meldung zu erzeugen. Das Meldungsfenster zeigt die Ergebnisse der Prüfungen des Skriptes an, beispielsweise ob die ausreichend Sf-Kurse markiert wurden, ob die Aufgabenbereiche abgedeckt sind, ob genug weitere Kurse markiert wurden, ob mindestens die Hälfte der Leistungen schriftlich erbracht wurden uws.
Wenn Sie andere Kurse markieren möchten, müssten Sie bitte im Anschluss erneut auf die Schaltfläche `Berechnen` klicken, um eine erneute Prüfung auszulösen.

![Berechnen](\assets\images\nrw\05.png)

## Verzeichnis Verordnungen

Bitte legen Sie unter `Verzeichnisse > Verordnungen` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

|Spalte|Wert|
|--|--|
|Kürzel|beliebig|
|Bezeichnung|beliebig|
|Kategorie|Abitur|
|Typ|leer|
|Ab Jahrgang|leer|
|Skript|```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server)|
|Notenart 11|Noten oder Punkte|
|Notenart 12|Punkte|
|Notenart 13|Punkte|
|Notenart 13|Punkte|
|Notenart BBS|leer|
|Gültig von |leer|
|Gültig bis|leer|

![Beispiel für Eintrag im Verzeichnis Verordnungen](\assets\images\nrw\02.png)

## Fachkategorien

Berechnungsskripte erkennen relevante Fächer anhand der Eintragungen unter `Extras > Schlüsselverzeichnisse > Fächer > Fachkategorie`. 
Dabei müssen, je nach Verordnung, einige Fächer besonders berücksichtigt werden. Für diese Fächer sind die zu verwendenden Fachkategorien fest vorgeschrieben. Alle anderen Fächer können mit einer der übrigen Fachkategorie gekennzeichnet werden oder ohne Fachkategorie geführt werden.

|Fachkategorien|Muss genutzt werden|
|--|--|
|Fremdsprache|**Ja**|
|Religion/Ethik|**Ja**|
|Deutsch|**Ja**|
|Mathematik|**Ja**|
|Kunst|**Ja**|
|Musik|**Ja**|
|Sport|**Ja**|
|Informatik|**Ja**|
|Philosophie|**Ja**|
|Geschichte|**Ja**|
|Physik|**Ja**|
|Chemie|**Ja**|
|Biologie|**Ja**|
|Erdkunde|**Ja**|
|Sozialkunde|Nein|
|Wirtschaft|**Ja**|
|Politik|**Ja**|
|Darstellendes Spiel|Nein|
|Evangelische Religion|Nein|
|Katholische Religion|Nein|
|Technik|Nein|
|Pädagogik|**Ja**|
|Sporttheorie|Nein|
|BWL/RW|Nein|
|BWL/VWL|Nein|
|VWL|Nein|
|Seminar|**Ja**|
|Gesundheit|Nein|
|Psychologie|**Ja**|
|Recht|**Ja**|
|Literatur|**Ja**|

## Aufgabenbereiche

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter `Verzeichnisse > Fächer > Spalte Aufgabenbereich` verwendet werden:

|Aufgabenbereich|
|--|
|sprachl.-lit.-künstlerisch|
|gesellschaftswiss.|
|mathem.-nat.-technisch|
|Religion|
|Sport|

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel |Schlüssel |Bedeutung|
|--|--|--|
|1PF |1PF |1. Prüfungsfach|
|2PF |2PF |2. Prüfungsfach|
|3PF |3PF |3. Prüfungsfach|
|4PF |4PF |4. Prüfungsfach|
|5PF |5PF |5. Prüfungsfach|
|Pflicht|Pflicht|Pflichtbereich|

## Prüfungen

### 3. und 4. Prüfungsfach

Prüfungen können für die GH-Kurse des 3. Prüfungsfach und/oder 4. Prüfungsfach auch in mehreren Fächern des gleichen Aufgabenfeldes oder mit unterschiedlichen Aufgabenfeldern abgelegt werden. 
Beide Fächer müssen in Magellan auf der Qualifikationskarte erscheinen und auswertbar markiert werden, auf der Karte `Abitur > Prüfungen` und dem Abiturzeugnis soll aber nur eins der beiden Fächer erscheinen.

1. Beide Fachzeilen werden im Feld Status als Prüfungsfach markiert (Fachstatus `3PF` und `3PF` oder `4PF` und `4PF`).
2. In der Spalte `Merkmal` wird manuell erfasst (Varianten nachstehend), welche Kurse je Fachzeile als Prüfungsfachkurse zu werten sind.
3. Für eine der beiden Zeilen wird in der Spalte `Merkmal` hinter der Kennzeichnung der Kurshalbjahre mit einem `*` gekennzeichnet, dass dieses Fach auf dem Abiturzeugnis als Prüfungsfach ausgegeben werden soll.

![Darstellung](/assets/images/nrw.bielefeld/04.png)

Merkmal|Bedeutung|
-----|-----|
Q1 |Note aus Q1 wird für die Prüfung berücksichtigt.|
Q2 | Note aus Q3 wird für die Prüfung berücksichtigt.|
Q3 | Note aus Q3 wird für die Prüfung berücksichtigt.|
Q4 | Note aus Q4 wird für die Prüfung berücksichtigt.| 
Q1* | Note aus Q1* wird für die Prüfung berücksichtigt.<br/>(Übernahme des Fachs auf Prüfungskarte)|
Q2* | Note aus Q2* wird für die Prüfung berücksichtigt.<br/>(Übernahme des Fachs auf Prüfungskarte)|
Q3* | Note aus Q3* wird für die Prüfung berücksichtigt.<br/>(Übernahme des Fachs auf Prüfungskarte)|
Q4* | Note aus Q3* wird für die Prüfung berücksichtigt.<br/>(Übernahme des Fachs auf Prüfungskarte)|
Q1Q2| Noten aus Q1 und Q2 werden für die Prüfung berücksichtigt.|
Q2Q3| Noten aus Q2 und Q3 werden für die Prüfung berücksichtigt.|
Q3Q4 | Noten aus Q3 und Q4 werden für die Prüfung berücksichtigt.|
Q1Q2* | Noten aus Q1 und Q2 werden für die Prüfung berücksichtigt.<br/>(Übernahme des Fachs auf Prüfungskarte)|
Q2Q3* | Noten aus Q2 und Q3 werden für die Prüfung berücksichtigt.<br/>(Übernahme des Fachs auf Prüfungskarte)|
Q3Q4* | Noten aus Q3 und Q4 werden für die Prüfung berücksichtigt.<br/>(Übernahme des Fachs auf Prüfungskarte)|
Q1Q2Q3 | Noten aus Q1, Q2 und Q3 werden für die Prüfung berücksichtigt. |
Q2Q3Q4 | Noten aus Q2, Q3 und Q4 werden für die Prüfung berücksichtigt. |
Q1Q2Q3*|Noten aus Q1, Q2 und Q3 werden für die Prüfung berücksichtigt.<br/>(Übernahme des Fachs auf Prüfungskarte) |
Q2Q3Q4* | Noten aus Q2, Q3 und Q4 werden für die Prüfung berücksichtigt.<br/>(Übernahme des Fachs auf Prüfungskarte)|

!!! danger Achtung

    **`*`**:     Die Karte `Prüfung` stellt je Prüfungsfach ein Feld zur Darstellung des Prüfungsfachs bereit. Beim Auslösen der Berechnung werden die als Prüfungsfach anhand des Fachstatus erkannten Fächer auf die Prüfungkarte übergeben. Gibt es für das 3PF oder 4PF mehr als eine Fachzeile, wird das Feld `Merkmal` ausgewertet. 
    Das mit **`*`** markierte Fach (siehe obere Möglichkeiten), wird auf die Prüfungskarte übergeben und auf dem Zeugnis als Prüfungsfach gezeigt.

!!! tipp "Hinweis!"

    Alle drei Informationen (Fachstatus, Zeugnisfach und PF-Kurshalbjahre) können bereits aus `Schüler > Zeugnis > Fächer` synchronisiert werden. Durch den korrekten Eintrag im Feld `Merkmal` wird sichergestellt, dass bei der erneuten Auslösung des Skriptes nicht das verkehrte Fach auf die Prüfungskarte übernommen wird.

## Unterrichtsarten

Die Unterrichtsart muss unter ```Abitur > Qualifikation > Unterrichtsart``` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Unterrichtsart``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

Die Kürzel und Bezeichnungen sind frei wählbar, das Skript prüft die in der Spalte `Schlüssel` hinterlegten Werte, hier dürfen nur die nachstehenden Werte genutzt werden.

Kürzel|Schlüssel|Bezeichnung
--|--|--
Ba|**GK**|Basiskurs
Bü|**GK**|Brückenkurs
Ge|**GK**|Grundkurs der Eingangsphase
Gh|**GK**|Grundkurs der Hauptphase
GK|**GK**|Grundkus
Ges|**LK**|Studienfachbezogneer Grundkurs der Eingangsphase
Sf|**LK**|Studienfachkurs
Pr|**PR**|Projekt

## Merkmal (neu einsetzende Fremdsprache)

Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden.

|Merkmal|Bedeutung|
|--|--|
|**A**| Fremdsprache Anfänger|

## Füllkurse

Beim Starten der Vorschlagsautomatik oder der automatischen Berechnung werden in den Spalten `Q1Bestanden` bis `Q4Bestanden` die eingebrachten Füllkurse automatisch gelb markiert. Diese Darstellung ist manuell nicht änderbar, sondern kann Änderungen der Daten durch das Neuauslösen des Skriptes neu gesetzt werden.

## Leistungsarten

Für jedes Fach kann für jedes Kurshalbjahr eine Leistungsart zugewiesen werden. Die Leistungsart kann bereits unter `Schüler > Zeugnis > Leistungen` zugewiesen und auf die Karte `Abitur > Qualifikation` per Synchronisation übertragen werden. Alternativ können Sie die Angabe auch direkt auf der Karte `Abitur > Qualifikation` vornehmen.

Legen Sie in dem Verzeichnis Ihre gewünschten Leistungsarten an, vergeben Sie für jeden Eintrag bitte eine Eingabe in der Spalte `Leistungsart-Art`. Zur Auswahl stehen `mündlich`, `schriftlich` oder `praktisch`.

Zur Prüfung der Leistungsart "Klausur" wird das Kürzel `Klausur` und die Leistungsart-Art `schriftlich` vorausgesetzt.

Kürzel|Bezeichnung|Leistungsart
--|--|--
**KL**|Klausur|**schriftlich**
**FA**|Facharbeit|**schriftlich**
**PR**|Projekt|beliebig

![Beispiel für angelegte Leistungsarten](\assets\images\nrw\01.png)

## Projekt

Bitte legen Sie ein Fach "Projekt" (Kürzel, Bezeichnung) an, dass keine Fachkategorie und keinen Aufgabenbereich hat. Dieses Fach wird mit der Unterrichtsart "Pr" markiert und kann den Schülern unter `Schüler > Zeugnis > Fächer` im gewünschten Zeitraum zugewiesen und benotet. Dieses Fach wird beim Synchronisieren der Schülerdaten ins Menü Abitur übernommen. Es kann für die Abiturberechnung mit markiert werden und wird auch auf dem Abiturzeugnis mit ausgegeben.

Kürzel|Schlüssel|Bezeichnung
--|--|--
Pr|**PR**|Projekt

## Besondere Lernleistung

Im Menü `Abitur > Prüfung` tragen Sie unter „Lernleistung“ das Fach und Thema der Besonderen Lernleistung ein.
Die Endnote der besonderen Lernleistung weisen Sie im Menü `Abitur > Prüfung` unter „Lernleistung“ links im ersten "Punkte" Feld zu.

Das Skript vervierfacht die Note. Das Ergebnis der eingebrachten Lernleistung wird zur Gesamtsumme addiert.

Soll die Lernleistung vom Skript berücksichtigt werden, setzen Sie bitte das Häkchen vor `Lernleistung einbringen`.

![Beispiel für den Eintrag der besonderen Lernleistung](\assets\images\nrw\08.png)

## Benotung

`Extras > Schlüsselverzeichnisse > Noten` <br/>`Abitur > Qualifikation > Q1-Q4`<br/>`Abitur > Qualifikation > Q1Bestanden-Q4Bestanden`

Das Abiturzeugnis gibt für eingebrachte Kurse (gelbe Markierung auf der Qualifikationskarte) die erfasste Punktzahl aus. 
Wurde ein bestandener Kurs nicht bewertet, nutzen Sie bitte die Note "-".
Wurde ein nicht bestandener Kurs nicht bewertet, setzt das Skritp die Note "nb.", vorausgesetzt, sie ist wie in der untenstehenden Tabelle in der Datenbank angelegt. 

**Bestandene Kurse ohne Note**: <br/>Ist der Kurs bestanden, kennzeichnen Sie unter `Qualifikation > Q1Bestanden-Q4Bestanden` den Kurs mit "Bestanden (P)", diese Information wird für nicht eingebrachte Kurse als "X" ausgegeben.<br/>
**Nicht bestandene Kurse ohne Note**: <br/>Ist der Kurs nicht bestanden, kennzeichnen Sie unter `Qualifikation > Q1Bestanden-Q4Bestanden` den Kurs mit "Nicht bestanden (F)", diese Information in Kombination mit der Note "nb." nicht auf dem Zeugnis ausgegeben, aber in der Prüfung des Abiturskriptes erkannt.

Eintrag im Notenverzeichnis:

Kürzel|Bezeichnung|Wert|Notenart|Bedeutung
--|--|--|--|--
**-**|beliebig|leer|Füllwert| Ausgabe `-` auf dem Zeugnis
**nb.**|beliebig|leer|Füllwert| keine Ausgabe auf dem Zeugnis

## Prüfung Praktikumsbescheinigung

Im Skript „NRW-APO-OS-2020“ gibt es eine Prüfung: Wenn für den zu der Vorschlag oder die Berechnung für Schüler ausgelöst wird und unter `Schüler > Merkmale > MerkmalA10` kein Wert mit dem Kürzel „Ja“ hinterlegt ist, gibt die Meldung nach dem Auslösen des Vorschlags/Berechnens aus, dass der Schüler nicht zum Abitur zugelassen ist, weil die Praktikumsbescheinigung fehlt.

## Sammelaktion "Vorschlag zuweisen"

Um den Berechnungsvorschlag für eine Gruppe von Schülern ausführen zu lassen, gibt es ab der Version 11.0.5 eine Funktion, die wir nachstehend beschreiben.

!!! warning "Wichtig!"

    Die Sammelaktion "Vorschlag zuweisen" setzt die Nutzung der Regionaleinstellung "Nordrhein-Westfalen" und des  Abiturberechnungsskripts "NRW-APO-OS-2020.dws" voraus.

**Voraussetzungen:** <br/>
**Region:** Für die Verbindung von Magellan zu Ihrer Datenbank kann je Arbeitsplatz eine Region gewählt werden. Sie können diese Einstellung einsehen oder anpassen im Modul Magellan Administrator unter `Datenbankverbindungen > Doppelklick auf Ihre Verbindungszeile > Unterkarte Datenbank > Feld Region`. Hier muss der Wert "Nordrhein-Westfalen" gewählt sein. <br/>
**Skriptdatei**: Den Schülern muss das Berechnungsverordnungsskript "NRW-APO-OS-2020.dws" ab der Magellan-Version 11.0.5 zugewiesen sein, dieses Skript kann auf die Aktion reagieren und die Aktionen Initialisieren, Vorschlag und Berechnen für eine Gruppe von Schülern ausführen.

**So gehen Sie vor:**

1. Bitte markieren Sie die gewünschten Schüler in der Auswahlliste des Menüs `Abitur` und rufen den Assistenten am oberen Fensterrand unter `Abitur > Vorschlag zuweisen` auf. 
2. Klicken Sie auf `Weiter` und `Fertigstellen` um den Assistenten auszuführen.

Die Ergebnisse der Markierung und der Berechnung können Sie je Schüler auf der Karte `Qualifikation` einsehen. Wenn Sie das Meldungsfenster aufrufen, werden Ihnen die gespeicherten Meldungen des Vorschlags und der Berechnung gezeigt.
