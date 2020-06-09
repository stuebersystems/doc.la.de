# BER-IBA-HJ-2020.dws

Mit Hilfe des Berechnungsskriptes _BER-IBA-HJ-2020.dws_ können Sie für den Bildungsgang **Integrierte Berufsausbildungsvorbereitung**  die Gesamtnote der Fachtheorie und Fachpraxis für das aktuelle Halbjahr für den Berufsfeldbezogenen Unterricht berechnen lassen.

Die Gesamtnote der Fachtheorie und Fachpraxis errechnet sich aus den gewichteten Halbjahresnotendurchschnitten der jeweiligen Lernfeldnoten gemäß der Verordnung über die Integrierte Berufsausbildungsvorbereitung Anlage 4 Abschnitt B.

Im folgenden Kapitel beschreiben wir Ihnen die Vorgehensweise.

## Vorbereitungen

Zur Berechnung der Gesamtnote innerhalb eines Zeitraums gehören folgende Aufgaben:

1. Berechnungsverordnung definieren
2. Fächer der Schüler für den gewünschten Zeitraum einer Zeugnisausgabe  eingeben.
3. Noten pro Fach der Schüler für den gewünschten Zeitraum zur Berechnung eingeben
4. Berechnung ausführen

### 1. Berechnungsverordnung definieren

Bitte legen Sie unter `Schlüsselverzeichnisse > Verordnungen` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten.

| Spalte | Wert|
|---|---|
| Kürzel| beliebig                                 |
| Bezeichnung  | beliebig                                 |
| Kategorie    | Versetzung                               |
| Typ          | leer                                     |
| Ab Jahrgang  | leer                                     |
| Skript       | `...\Ihre Region\Ihr_Skript.dws` (Pfad zur Skriptdatei auf Ihrem Server) hier _BER-IBA-HJ-2020.dws_ |
| Notenart 11  | leer                                     |
| Notenart 12  | leer                                     |
| Notenart 13  | leer                                     |
| Notenart BBS | leer                                     |
| Gültig von   | leer                                     |
| Gültig bis   | leer                                     |

!!! warning "Wichtig"

    Das Skript BER-IBA-HJ-2020.dws wird im Menü `Schüler > Zeugnis > Leistungen` ausgeführt und muss im `Schlüsselverzeichnis > Verordnung` mit der Kategorie „Versetzung“ angelegt werden.

![Geben Sie hier die Berechnungsverordnung mit der Kategorie „Versetzung“ ein.](..\assets\images\IBA\IBA01.png)

### 2. Fächer der Schüler eingeben

!!! warning "Wichtig"

    Für die Fächer sind folgenden Unterscheidungen zwingende Voraussetzung.

#### Berufsfeldübergreifender/berufsfeldbezogener Unterricht

Fächern des berufsfeldübergreifenden bzw. berufsfeldbezogenen Unterricht weisen Sie im Menü `Schüler > Zeugnis > Fächer` folgende Unterrichtsarten zu. Grundlage dafür bildet das `Schlüsselverzeichnis > Unterrichtsarten`. 

|Kürzel |Schlüssel|Bezeichnung|
|--|--|--|
|BÜ|BÜ |Berufs/Fachübergreifender Lernbereich|
|FachT| FachT |Berufsbezogener Lernbereich / Fachtheorie|
|FachP| FachP |Berufsbezogener Lernbereich / Fachpraxis|

#### Wahlunterricht

Fächer des Wahlunterrichtes weisen Sie im Menü `Schüler > Zeugnis > Fächer` im Feld "Fachstatus" den Eintrag "WahlB" zu. Prüfen Sie bitte unter `Schlüsselverzeichnisse > Fachstatus`, dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung       |
|--------|-----------|-----------------|
| WahlB  | WahlB     | Wahlbereich     |

#### Betriebliche Lernaufgaben

Neben dem Wahlunterricht und den berufsfeldübergreifenden bzw. berufsfeldbezogenern Unterricht muss auch die Betriebliche Lernaufgabe benotet werden. Gehen Sie dafür wie folgt vor:

Legen Sie im `Schlüsselverzeichnisse > Fächer` drei Fächer für die Betrieblichen Lernaufgaben an, entscheidend ist der Eintrag im Feld "Schlüssel", dieser muss wie folgt hinterlegt sein:

| Kürzel | Schlüssel | Bezeichnung       |
|--------|-----------|-----------------|
| LA1 (beliebig)| LA1 | Betriebliche Lernaufgabe 1 (beliebig) |
| LA2 (beliebig)| LA2 | Betriebliche Lernaufgabe 2 (beliebig)|
| LA3 (beliebig)| LA3 | Betriebliche Lernaufgabe 3 (beliebig)|

Weisen Sie diese Fächer ebenfalls im Menü `Schüler > Zeugnis > Fächer` dem Schüler zu.  

#### 3. Noten der Fächer eingeben

Die Halbjahresnoten der Fächer erfassen Sie im Menü `Schüler > Zeugnis > Leistungen` im Feld "Endnote".

Für die automatische Berechnung der Gesamtnote der Fachtheorie und Fachpraxis werden die Noten der Fächer mit der Unterrichtsart "FachT" und "FachP" im Menü `Schüler > Zeugnis > Leistungen` im Feld "Endnote" herangezogen.

![Schüler > Zeugnis > Leistungen](..\assets\images\IBA\IBA02.png)

### Gesamtnotenberechnung Fachtheorie und Fachpraxis durchführen

Aktivieren Sie für den Schüler unter `Schüler > Zeugnis > Leistungen` das Optionsfeld `Durchschnitt`. Auf der rechten Seite der Registerkarte erscheint nun eine zusätzliche Leiste.

Im Feld "Prüfungsverordnung" wählen Sie über das Drop Down Menü die vorab im `Schlüsselverzeichnisse > Verordnungen` definierte Prüfungsverordnung aus.(basierend auf dem Skript BER-IBA-HJ-2020.dws) 
 
Im Feld "Status" wählen Sie `Abschluss berechnen`. Die Berechnung gemäß Skript stoßen Sie über die Schaltfläche `Neu berechnen` an. 

Durch die Berechnung werden automatisch folgende Felder befüllt:

| Feld | Note für...     |
|--------|-----------
Durchschnitte 1 | Fachtheorie - gesamt|
Durchschnitte 2 | Fachtpraxis - gesamt|

Die nachfolgende Abbildung zeigt ein Berechnungsbeispiel für den IBA Bildungsgang für das 1. Halbjahr in Berlin.

![Berechnung](..\assets\images\IBA\IBA03.png)

## Sonstiges für den Zeugnisdruck

### Betriebspraktikum 1./2. oder 3. bestanden/nicht bestanden

Ob im Zeugnis das Betriebspraktikum 1./2. oder 3. als "bestanden" oder "nicht bestanden" ausgegeben wird, hängt vom Eintrag im Menü `Schüler > Zeugnis > Fächer`  im Feld "Merkmal" ab.

1. Legen Sie im `Schlüsselverzeichnisse > Fächer` drei Fächer für die Betrieblichen Lernaufgaben an, entscheidend ist der Eintrag im Feld "Schlüssel", dieser muss wie folgt hinterlegt sein:

 Kürzel | Schlüssel | Bezeichnung      
--------|-----------|-----------------
LA1 (beliebig)| LA1 | Betriebliche Lernaufgabe 1 (beliebig)
LA2 (beliebig)| LA2 | Betriebliche Lernaufgabe 2 (beliebig)
LA3 (beliebig)| LA3 | Betriebliche Lernaufgabe 3 (beliebig)
2. Weisen Sie diese Fächer im Menü `Schüler > Zeugnis > Fächer` dem Schüler zu.

3. Die Betriebliche Lernaufgabe 1,/2./3.  bezieht sich auf das jeweilige Praktikum 1./2./3. Ein Eintrag "N" im Feld "Merkmal" bei der entsprechenden Lernaufgabe steuert die Ausgabe "nicht bestanden". Bleibt das Feld "Merkmal" leer, wird das Praktikum als "bestanden" ausgegeben.

### Betriebspraktikum 1./2. oder 3. - erfolgt im 1. oder 2.HJ?

Tragen Sie den Betrieb des Praktikums im Menü `Schüler > Ausbildung` im Bereich „Praxibetrieb“ ein. Wenn Sie die Schaltfläche `+`oder `Editieren` anklicken, können Sie einen Praxisbetrieb zuweisen bzw. bearbeiten. Im Feld "Praxisbetrieb" hinterlegen Sie den Betrieb. 
Erfassen Sie weiterhin in den Feldern `Praxis von` und `bis` den Zeitraum des Praktikums und die `Vertragsnummer` wie folgt:

Eintrag für | Eingabe wie folgt
--|--
1. Praktikum | LA1HJ1 
2. Praktikum | LA2HJ1 oder LA2HJ2
3. Praktikum | LA3HJ2

Anhand der Vertragsnummer kann der Bericht die "Betriebliche Lernaufgabe", die auch benotet wird, dem 1./2./3 Betriebspraktikum zuordnen. Zudem wird ein Bezug des Betriebspraktikums zum 1. Halbjahr bzw. 2. Halbjahr hergestellt.

![Vertragsnummer des Betriebspraktikums](..\assets\images\IBA\IBA04.png)
