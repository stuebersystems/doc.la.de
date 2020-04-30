# BER-IBA-MSA-2019.dws

Innerhalb eines Zeitraums können mit Hilfe des Berechnungsskriptes _BER-IBA-MSA-2019.dws_
Durchschnittsnoten für den Schulversuch "Integrierte Berufsausbildungsvorbereitung" ermittelt werden.

## Vorbereitungen

Zur Berechnung des MSA Durchschnittes und der Gesamtnoten für das 1.-3. sowie 4. Prüfungsfach gehen Sie bitte wie folgt vor:

1. Berechnungsverordnung definieren
2. Fächer (Unterrichtsart und Fachstatus) definieren
3. Noten zur Berechnung eingeben
4. Berechnung ausführen

### Berechnungsverordnung definieren

Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten.

| Spalte | Wert|
|---|---|
| Kürzel| beliebig                                 |
| Bezeichnung  | beliebig                                 |
| Kategorie    | Versetzung                               |
| Typ          | leer                                     |
| Ab Jahrgang  | leer                                     |
| Skript       | ```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server) hier _BER-IBA-MSA-2019.dws_ |
| Notenart 11  | leer                                     |
| Notenart 12  | leer                                     |
| Notenart 13  | leer                                     |
| Notenart BBS | leer                                     |
| Gültig von   | leer                                     |
| Gültig bis   | leer                                     |

!!! warning "Wichtig"

    Das Skript BER-IBA-MSA-2019.dws wird im Menü `Schüler > Zeugnis > Leistungen` ausgeführt und muss im `Schlüsselverzeichnis > Verordnung` mit der Kategorie „Versetzung“ angelegt werden.

![Verzeichnis Verordnungen](/assets/images/Durchschnitt/MSA.IBA.png)

### Fächer (Unterrichtsart und Fachstatus) definieren

!!! warning "Wichtig"

    Für die Fächer sind folgenden Unterscheidungen zwingende Voraussetzung.

### Unterrichtsart

Jedem Fach pro Schüler müssen eine der folgenden Unterrichtsarten auf der Registerkarte ``Schüler > Zeugnis > Fächer`` zugewiesen werden:

|Kürzel |Schlüssel|Bezeichnung|
|--|--|--|
|BÜ|BÜ |Berufs/Fachübergreifender Lernbereich|
|FachT| FachT |Berufsbezogener Lernbereich / Fachtheorie|
|FachP| FachP |Berufsbezogener Lernbereich / Fachpraxis|

### Fachstatus

Der Fachstatus muss unter ``Schüler > Zeugnis > Fachstatus`` zugeordnet sein.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung       |
|--------|-----------|-----------------|
| 1PF    | 1PF       | 1. Prüfungsfach |
| 2PF    | 2PF       | 2. Prüfungsfach |
| 3PF    | 3PF       | 3. Prüfungsfach |
| 4PF    | 4PF       | 4. Prüfungsfach |
| WahlB  | WahlB     | Wahlbereich     |

![JPrüfungsfächer festlegen](/assets/images/MSA.IBA.Prüfungsfächer.png)

### Noten zur Berechnung eingeben

Um die Berechnung durchzuführen, müssen Sie zunächst die Noten der Schüler eintragen.

### Erfassung der Prüfungsnoten in den Prüfungsfächern (1.-4.PF)

Für die automatische Berechnung des Gesamtnote im 1.-3. Prüfungsfach sind die Noten unter  ``Schüler > Zeugnis > Leistungen`` wie folgt einzugeben:

#### 1.-3. Prüfungsfach

| Spalte           | Bedeutung                       |
|------------------|---------------------------------|
| Schriftl. Note 1 | schriftliche Note 1PF, 2PF, 3PF |
| Mdl. Note        | schriftliche Note 1PF, 2PF, 3PF |

![Prüfungsergebnisse erfassen](/assets/images/MSA.IBA.Prüfungsfächer.Schrift.Mdl.png)

#### 4. Prüfungsfach

| Spalte           | Bedeutung                                |
|------------------|------------------------------------------|
| Endnote (Gesamt) | Gesamtnote des 4. Prüfungsfaches         |
| Beurteilung      | Thema der Präsentationsprüfung/Facharbeit |

![Eintragungen für 4.PF](/assets/images/MSA.IBA.4.PF.png)

### Erfassung der Jahrgangsnoten und Jahresstunden pro Fach

| Spalte           | Bedeutung                                |
|------------------|------------------------------------------|
| Endnote (Gesamt) | Gesamtnote des 4. Prüfungsfaches         |
| Beurteilung      | Thema der Präsentationsprüfung/Facharbeit |

![Note und Jahrgangsstunden](/assets/images/MSA.IBA.Jahresnoten.png)

### Berechnung ausführen

Markieren Sie für den Schüler unter ``Schüler > Zeugnis > Leistungen`` das Optionsfeld Durchschnitt einblenden. Auf der rechten Seite der Registerkarte erscheint nun eine zusätzliche Leiste.

### Automatische Berechnung

Geben Sie unter Prüfungsordnung die gewünschte Prüfungsordnung (basierend auf dem Skript BER-IBA-MSA-2019.dws) zur Versetzung an. Klicken Sie auf ``Neu`` berechnen, um die Daten automatisch durch das entsprechende Skript berechnen zu lassen.

Durch die Berechnung werden automatisch folgende Felder befüllt:

* **MSA Abschluss** wird in das Feld "**Durchschnitte 1**" eingetragen
* **Gesamtnoten für das 1.-3. Prüfungsfach** werden in das Feld "**Merkmal**" mathematisch gerundet pro Fach eingetragen.

![Berechnung](/assets/images/MSA.IBA.Durchschnitt.png)
