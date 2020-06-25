# BAW-APO-BGY-2016-G9

## Verzeichnis Verordnung

Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

| Spalte       | Wert                                     |
|--------------|------------------------------------------|
| Kürzel       | beliebig                                 |
| Bezeichnung  | beliebig                                 |
| Kategorie    | Abitur                                   |
| Typ          | Der Typ in Magellan unter ```Verzeichnisse > Verordnungen > Typ``` kennzeichnet die Schulform: <br/> AG  = Berufliches GymnasiumAgrarwissenschaft <br/>BTG = Berufliches Gymnasium Biotechnologie <br/> EG  = Berufliches Gymnasium Ernährungswissenschaft <br/> SG  = Berufliches Gymnasium Sozialpädagogik <br/> TG  = Berufliches Gymnasium Technik <br/> WG  = Berufliches Gymnasium Wirtschaftswissenschaften |
| Ab Jahrgang  | leer                                     |
| Skript       | ```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server) |
| Notenart 11  | Noten oder Punkte                        |
| Notenart 12  | Punkte                                   |
| Notenart 13  | Punkte                                   |
| Notenart 13  | Punkte                                   |
| Notenart BBS | leer                                     |
| Gültig von   | leer                                     |
| Gültig bis   | leer                                     |

## Fachkategorien

Berechnungsskripte erkennen relevante Fächer anhand der Eintragungen unter `Extras > Schlüsselverzeichnisse > Fächer > Fachkategorie`. 
Dabei müssen, je nach Verordnung, einige Fächer besonders berücksichtigt werden. Für diese Fächer sind die zu verwendenden Fachkategorien fest vorgeschrieben. Alle anderen Fächer können mit einer der übrigen Fachkategorie gekennzeichnet werden oder ohne Fachkategorie geführt werden.

|Fachkategorien|Muss genutzt werden|
|--|--|
| Fremdsprache |**Ja**|
| Religion/Ethik |**Ja**|
| Deutsch |**Ja**|
| Mathematik |**Ja**|
| Kunst |**Ja**|
| Musik |**Ja**|
| Sport |**Ja**|
| Informatik |**Ja**|
| Philosophie |Nein|
| Geschichte |**Ja**|
| Physik |**Ja**|
| Chemie |**Ja**|
| Biologie |**Ja**|
| Erdkunde |**Ja**|
| Sozialkunde |**Ja**|
| Wirtschaft |**Ja**|
| Politik |Nein|
| Darstellendes Spiel |Nein|
| Evangelische Religion |Nein|
| Katholische Religion |Nein|
| Technik |Nein|
| Pädagogik |Nein|
| Sporttheorie |Nein|
| Seminar |Nein|
| BWL/RW |Nein|
| BWL/VWL |Nein|
| VWL |Nein|
| Seminar |Nein|
| Gesundheit |Nein|
| Psychologie |Nein|
| Recht |Nein|
| Literatur |Nein|

## Aufgabenbereiche

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter ```Verzeichnisse > Fächer > Spalte Aufgabenbereich``` verwendet werden:

| Aufgabenbereich            |
|----------------------------|
| sprachl.-lit.-künstlerisch |
| gesellschaftswiss.         |
| mathem.-nat.-technisch     |
| Religion                   |
| Sport                      |

## Unterrichtsart

Die Unterrichtsart muss unter ```Abitur > Qualifikation > Unterrichtsart``` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Unterrichtsart``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung              |
|--------|-----------|------------------------|
| Kurs   | Kurs      | Kurs                   |
| FA     | FA        | Facharbeit             |
| BL     | BL        | Besondere Lernleistung |
| NF     | NF        | Neigungsfach           |
| PF     | PF        | Profilfach             |

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel   | Schlüssel | Bedeutung                                |
|----------|-----------|------------------------------------------|
| 1PF      | 1PF       | 1. Prüfungsfach                          |
| 2PF      | 2PF       | 2. Prüfungsfach                          |
| 3PF      | 3PF       | 3. Prüfungsfach                          |
| 4PF      | 4PF       | 4. Prüfungsfach                          |
| 4PFWahlb | 4PFWahlb  | 4. Prüfungsfach Wahlbereich              |
| 5PF      | 5PF       | 5. Prüfungsfach (nur mündlich) Pflichtbereich |
| 5PFWahlb | 5PFWahlb  | 5. Prüfungsfach (nur mündlich) Wahlbereich |

## Merkmal

Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden.

| Merkmal | Bedeutung                |
|---------|--------------------------|
| B       | 2. Fremdsprache Anfänger |
