# BER-APO-FOS-2006

!!! info "Hinweis"

    Weitere wichtige Informationen finden Sie in der MAGELLAN-Dokumentation im Abschnitt [Regionales > Berlin](https://doc.magellan7.stueber.de/schulverwaltung/regionales/berlin/berlin/)!

## Verzeichnis Verordnung

Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

|Spalte|Wert|
|--|--|
|Kürzel|beliebig|
|Bezeichnung|beliebig|
|Kategorie|Abitur|
|Typ|dieser Eintrag unter ```Magellan > Verzeichnisse > Verordnungen > Typ``` unterscheidet zwischen der einjährigen und zweijährigen Fachoberschule:<br/>FOS2J = Verordnung zweijährige Fachoberschule<br/>FOS1J = Verordnung einjährige Fachoberschule|
|Ab Jahrgang|leer|
|Skript|```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server)|
|Notenart 11|Noten oder Punkte|
|Notenart 12|Punkte|
|Notenart 13|Punkte|
|Notenart 13|Punkte|
|Notenart BBS|leer|
|Gültig von |leer|
|Gültig bis|leer|

![Eintragungsbeispiele für die einjährige oder zweijährige Variante](/assets/images/ber-fos-verordnungen.png)

## Fachkategorien

Dieses Skript wertet die Einträge unter `Verzeichnisse > Fächer > Fachkategorie` nur für das Fach `Sport` (Kategorie Sport) aus.

## Aufgabenbereiche

Dieses Skript wertet die Einträge unter `Verzeichnisse > Fächer > Aufgabenbereich` nicht aus.

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden.
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel |Schlüssel |Bedeutung|
|--|--|--|
|1PF|1PF|1. Prüfungsfach|
|2PF|2PF|2. Prüfungsfach|
|3PF|3PF|3. Prüfungsfach|
|4PF|4PF|4. Prüfungsfach|
|5PF|5PF|5. Prüfungsfach|
|6PF|6PF|6. Prüfungsfach|
|7PF|7PF|7. Prüfungsfach|
|8PF|8PF|8. Prüfungsfach|
|9PF|9PF|9. Prüfungsfach|
|10PF|10PF|10. Prüfungsfach|
|11PF|11PF|11. Prüfungsfach|

## Merkmal

Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden.

|Merkmal |Bedeutung|
|--|--|
|2FS|2. Fremdsprache|
