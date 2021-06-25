# DE-MSA-2019.dws

[1]:/assets/images/6.5.33_04.png

Innerhalb eines Zeitraums kann mit Hilfe des Berechnungsskriptes _DE-MSA-2019.dws_ der Notendurchschnitt für Auslandsschulen gemäß Ordnung für den Abschluss der Sekundarstufe I an Deutschen Schulen im Ausland vom 16.03.2017 ermittelt werden.

## Vorbereitungen

Zur Berechnung des Notendurchschnittes gehen Sie bitte wie folgt vor:

1. Berechnungsverordnung definieren
2. Noten zur Berechnung eingeben
3. Berechnung ausführen

### 1. Berechnungsverordnung definieren

Bitte legen Sie unter `Schlüsselverzeichnis > Verordnungen` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten.

|Spalte|Wert|
|--|--|
|Kürzel|beliebig|
|Bezeichnung|beliebig|
|Kategorie|Versetzung|
|Typ|leer|
|Ab Jahrgang|leer|
|Skript|`...\Ihre Region\Ihr_Skript.dws` (Pfad zur Skriptdatei auf Ihrem Server) hier _DE-MSA-2019.dws_|
|Notenart 11|leer|
|Notenart 12|leer|
|Notenart 13|leer|
|Notenart BBS|leer|
|Gültig von |leer|
|Gültig bis|leer|

!!! warning "Wichtig"

    Das Skript DE-MSA-2019.dws wird im Menü `Schüler > Zeugnis > Leistungen` ausgeführt und muss im Schlüsselverzeichnis > Verordnungen mit der Kategorie „Versetzung“ angelegt werden.

#### 2. Noten zur Berechnung eingeben

Um die Berechnung durchführen zu können, müssen Sie zunächst die Noten der Schüler unter  `Schüler > Zeugnis > Leistungen` im Feld "Endnote" eintragen.

|Spalte |Bedeutung|
|--|--|
|Endnote |Jahrgangsnoten der Fächer|

[![Leistungen im Feld `Endnote` erfassen][1]][1]

#### 3. Berechnung ausführen

Markieren Sie für den Schüler unter `Schüler > Zeugnis > Leistungen` das Optionsfeld `Durchschnitt einblenden`. Auf der rechten Seite der Registerkarte erscheint nun eine zusätzliche Leiste.

Geben Sie unter Prüfungsordnung die gewünschte Prüfungsordnung (basierend auf dem Skript DE-MSA-2019.dws) zur Versetzung an. Klicken Sie auf ``Neu berechnen` berechnen, um die Daten automatisch durch das entsprechende Skript berechnen zu lassen.

Durch die Berechnung wird automatisch folgendes Feld befüllt:

* Notendurchschnitt wird in das Feld `Durchschnitt 1` eingetragen

Dieser Notendurchschnitt wird auf dem Zeugnis-Hauptschulabschluss (Anlage 8)(§23) und Zeugnis Realschule Mittlerer Schulabschluss (Anlage 9)(§23) ausgegeben. Bitte verwenden Sie die dafür vorgesehenen Berichte:

| Berichtsname                             | Anlagennummern der "Ordnung für den Abschluss der Sekundarstufe I an Deutschen Schulen im Ausland vom 16.03.2017" |
|------------------------------------------|------------------------------------------|
| DAS-HS-MSA-AS (Anlage 8 und 9)(§23).rpt  | Anlage 8 und 9 - Zeugnis Hauptschulabschluss & Zeugnis Realschule Mittlerer Schulabschluss gemäß |
| DAS-Zeugnis Gymnasium - Mittlerer Schulabschluss (Anlage 10)(§23).rpt | Anlage 10 - Zeugnis Gymnasium - Mittlerer Schulabschluss (Prüfung) |
