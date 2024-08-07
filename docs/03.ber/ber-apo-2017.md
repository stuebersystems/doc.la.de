
# BER-APO-2017

!!! info "Hinweis"

     Weitere wichtige Informationen finden Sie in der Magellan-Dokumentation im Abschnitt [Regionales > Berlin](https://doc.magellan7.stueber.de/schulverwaltung/regionales/berlin/berlin/)!

## Allgemein

In diesem Skript werden für die korrekte Berechnung unter `Abitur > Qualifikation` drei als Leistungskurse markierte Fachzeilen erwartet, die nicht als 1. oder 2.Prüfungsfach erfasst wurden (Unterrichtsart LK und nicht Fachstatus 1PF oder 2PF). Der 3. Leistungskurs wird in der Berechnung wie ein Grundkurs behandelt.

## Verzeichnis Verordnung

Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

|Spalte|Wert|
|--|--|
|Kürzel|beliebig|
|Bezeichnung|beliebig|
|Kategorie|Abitur|
|Typ|G8 oder G9|
|Ab Jahrgang|bitte tragen Sie vor der Synchronisation der Schüler ins Abiturmodul bei G8 eine 10, sonst eine 11 ein|
|Skript|```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server)|
|Notenart 11|Noten oder Punkte|
|Notenart 12|Punkte|
|Notenart 13|Punkte|
|Notenart BBS|leer|
|Gültig von |leer|
|Gültig bis|leer|

![Eintragung im Verzeichnis Verordnungen für Abiturberechnung und Fachwahl](/assets/images/Verordnung.typ.abJG.png)

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
|Sozialkunde|**Ja**|
|Wirtschaft|**Ja**|
|Politik|**Ja**|
|Darstellendes Spiel|**Ja**|
|Evangelische Religion|Nein|
|Katholische Religion|Nein|
|Technik|Nein|
|Pädagogik|Nein|
|Sporttheorie|**Ja**|
|BWL/RW|Nein|
|BWL/VWL|Nein|
|VWL|Nein|
|Seminar|**Ja**|
|Gesundheit|Nein|
|Psychologie|**Ja**|
|Recht|Nein|Nein|
|Literatur|Nein|




## Aufgabenbereiche

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter ```Verzeichnisse > Fächer > Spalte Aufgabenbereich``` verwendet werden:

|Aufgabenbereich|
|--|
|sprachl.-lit.-künstlerisch|
|gesellschaftswiss.|
|mathem.-nat.-technisch|
|Religion|
|Sport|

## Unterrichtsart

Die Unterrichtsart muss unter `Abitur > Qualifikation > Unterrichtsart` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Unterrichtsart``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel| Schlüssel |Bedeutung|
|--|--|--|
|LK|LK|Leistungskurs|
|GK|GK|Grundkurs|
|Z|Z|Zusatzkurs|
|ME|ME|Musik Ensemble|

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus`` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus `Schüler > Zeugnis > Fächer > Fachstatus` übernommen werden.
Prüfen Sie bitte unter `Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus`,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel |Schlüssel |Bedeutung|
|--|--|--|
|1PF|1PF|1. Prüfungsfach|
|2PF|2PF|2. Prüfungsfach|
|3PF|3PF|3. Prüfungsfach|
|4PF|4PF|4. Prüfungsfach|
|1PFBLL|1PFBLL|1. Prüfungsfach und besondere Lernleistung|
|2PFBLL|2PFBLL|2. Prüfungsfach und besondere Lernleistung|
|3PFBLL|3PFBLL|3. Prüfungsfach und besondere Lernleistung|
|4PFBLL|4PFBLL|4. Prüfungsfach und besondere Lernleistung|
|BLL|BLL|5. Prüfungskomponente besondere Lernleistung|
|PRS|PRS|5. Prüfungskomponente Präsentationsprüfung|

### 5. Prüfungskomponente

Bei der 5. Prüfungskomponente wird zwischen einer **Präsentationprüfung** und der **Besonderen Lernleistung** unterschieden. Gehen Sie jeweils wie folgt vor:

#### Präsentationprüfung

Bei der **Präsentationsprüfung** weisen Sie dem entsprechenden Fach im Menü `Abitur > Qualifikation > Fachstatus` den Wert „PRS“ zu und führen das entsprechende Skript aus.
Im Menü `Abitur` wird auf der Registerkarte `Prüfung` im Feld `5. PF` das jeweilige Fach automatisch eingetragen. Die Noten für die schriftl. Ausarbeitung, Präsentation und das Prüfungsgespräch der Präsenationsprüfung tragen Sie bitte unter ```Abitur > Prüfung`` wie folgt ein:

|Feld | Note|
|--|--|
|schriftliche Note|Note der **schriftliche Ausarbeitung**|
|mündliche Note|Note der **Präsentation**|
|2. mündl. Note| Note des **Prüfungsgespräches**|

![Noteneingabe der Präsentationsprüfung](/assets/images/Berlin/vogo02.png)

#### Besondere Lernleistung

Die **besondere Lernleistung** kann auch eines der ersten 4 Prüfungsfächer sein. In diesem Fall müssen Sie den Fachstatus auf der Registerkarte ``Qualifikation`` wie folgt modifizieren:

- statt "1PF" nutzen Sie "1PFBLL"
- statt „2PF" nutzen Sie "2PFBLL"
- statt "3PF" nutzen Sie "3PFBLL" oder
- statt "4PF" nutzen Sie "4PFBLL"

Falls die Besondere Lernleistung nicht eines der Prüfungsfächer 1.-4. ist, weisen Sie dem Fach den Fachstatus "BLL" zu und führen das entsprechende Skript aus. Im Menü ``Abitur`` wird auf der Registerkarte ``Prüfung`` im Feld ``5. PF`` das jeweilige Fach automatisch eingetragen. Die Noten für die schriftl. Ausarbeitung und das Prüfungsgespräch der Besonderen Lernleistung tragen Sie bitte unter ```Abitur > Prüfung`` wie folgt ein:

|Feld | Note|
|--|--|
|schriftliche Note|Note der **schriftliche Ausarbeitung**|
|2. mündl. Note| Note des **Prüfungsgespräches**|

![Noteneingabe der Besonderen Lernleistung](/assets/images/Berlin/Vogo_01.png)

## Merkmal

Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden.

|Merkmal |Bedeutung|
|--|--|
|A| Fremdsprache Anfänger|

## Sport als 4. Prüfungsfach

Der Schüler belegt die folgenden Fächer:

Fach | Fachkategorie | Aufgabenbereich | Fachstatus
--|--|--|--
Sport | Sport | Sport | 4.PF (siehe Beschreibung im Abschnitt Fachstatus)
Sport-Theorie|Sport-Theorie | Sport | -

Für die Berechnung des Ergebnisses berücksichtigt das Skript: 

* Für das Fach Sport-Theorie: das Ergebnis des letzten Halbjahres auf der Karte `Abitur > Qualifikation` 
* Für das Fach `Sport` die Eingabe unter `Abitur > Prüfungen > 4.PF` wahlweise in den Spalten `schriftliche Prüfung` oder `mündliche Prüfung`
