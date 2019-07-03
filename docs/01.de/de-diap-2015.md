# DE-DIAP-2015

Abiturqualifikationsberechnung für Deutsche Auslandsschulen  nach der Ordnung der Deutschen Internationalen Abiturprüfung an deutschen Auslandsschulen nach Beschluss der Kultusministerkonferenz vom 11.06.2015.

## Verzeichnis Verordnung

Bitte legen Sie unter `Verzeichnisse > Verordnungen` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

| Spalte       | Wert                                     |
|--------------|------------------------------------------|
| Kürzel       | beliebig                                 |
| Bezeichnung  | beliebig                                 |
| Kategorie    | Abitur                                   |
| Typ          | bitte leer lassen                        |
| Ab Jahrgang  | 10 oder 11                               |
| Skript       | `...\Auslandsschulen\DE-DIAP-2015.dws` (Pfad zur Skriptdatei DE-DIAP-2015.dws auf Ihrem Server) |
| Notenart 11  | Noten oder Punkte                        |
| Notenart 12  | Punkte                                   |
| Notenart 13  | Punkte                                   |
| Notenart 13  | Punkte                                   |
| Notenart BBS | leer                                     |
| Gültig von   | leer                                     |
| Gültig bis   | leer                                     |

Nachfolgend Beispiele für Verordnungszeilen für G8 der G9:

![Anlegen der Verordnung für G8 und G9](/assets/images/DAS/Verordnung.dia.2015.png)

## Fachkategorien

Jedem Fach, dass Sie in der Oberstufe verwenden, müssen Sie eine Kategorie unter `Verzeichnisse > Fächer > Kategorie` zuweisen.  
Folgende Fachkategorien werden durch das Abiturqualifikationsskript verwendet, bitte verwenden Sie nur die gekennzeichneten Fachkategorien.

| Fachkategorien          | Wird vom Skript berücksichtigt |
|-------------------------|--------------------------------|
| **Fremdsprache**        | JA                             |
| **Religion/Ethik**      | JA                             |
| **Deutsch**             | JA                             |
| **Mathematik**          | JA                             |
| **Kunst**               | JA                             |
| **Musik**               | JA                             |
| **Sport**               | JA                             |
| **Informatik**          | JA                             |
| **Philosophie**         | JA                             |
| **Geschichte**          | JA                             |
| **Physik**              | JA                             |
| **Chemie**              | JA                             |
| **Biologie**            | JA                             |
| **Erdkunde**            | JA                             |
| **Sozialkunde**         | JA                             |
| **Wirtschaft**          | JA                             |
| **Politik**             | JA                             |
| **Darstellendes Spiel** | JA                             |
| **Religion**            | JA                             |
| **Sporttheorie**        | JA                             |
| **Seminar**             | JA                             |

## Aufgabenbereiche

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter `Verzeichnisse > Fächer > Spalte Aufgabenbereich` verwendet werden:

| Aufgabenbereich            |
|----------------------------|
| sprachl.-lit.-künstlerisch |
| gesellschaftswiss.         |
| mathem.-nat.-technisch     |
| Religion                   |
| Sport                      |

## Fachmerkmale

Bitte tragen Sie im Verzeichnis `Fächer` in der Spalte `Merkmal` für die Fächer Deutsch, Englisch, Mathematik und die Landessprache die nachstehenden Kürzel ein. Aus diesen Kürzeln ergeben sich später für verschiedene DAS-Berichte das **E** für die vierstündig unterrichteten Fächer (auf erhöhtem Anforderungsniveau).

* `DAS-Prüfungsbogen (Anlage 7 zu DIA-PO)(2018).rpt` (Ausgabe **E** für die vierstündig unterrichtete)
* `DAS-GY-ABI (Anlage 7).rpt`(Ausgabe **E** für die vierstündig unterrichtete Fächer)
* `DAS-ZZ (Q-Phase)(Anlage 1) (RiLi 1.6)` (Untergliederung der Fächeranzeige auf dem Zeugnis nach Fächer auf erhöhtem/grundlegendem Anforderungsniveau)

| Fach          | Merkmal |
|---------------|---------|
| Deutsch       | D       |
| Mathematik    | M       |
| Englisch      | E       |
| Landessprache | LS      |

Nachstehend ein Beispiel für die Eintragung mit der Landessprache Portugiesisch:

![Fachmerkmale festlegen](/assets/images/DAS/verordnung.dia.2015.fachmerkmale.png)

## Fachstatus

Der Fachstatus muss unter `Abitur > Qualifikation > Fachstatus` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus `Schüler > Zeugnis > Fächer > Fachstatus` übernommen werden.  
Prüfen Sie bitte unter `Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus`,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung       |
|--------|-----------|-----------------|
| 1PF    | 1PF       | 1. Prüfungsfach |
| 2PF    | 2PF       | 2. Prüfungsfach |
| 3PF    | 3PF       | 3. Prüfungsfach |
| 4PF    | 4PF       | 4. Prüfungsfach |
| 5PF    | 5PF       | 5. Prüfungsfach |

## Besondere Lernleistung

Zur Ausgabe der besonderen Lernleistung müssen Sie im Menü „Abitur“ unter der Registerkarte ``Prüfung > Lernleistung`` das entsprechende Fach zuweisen und das Optionsfeld ``Lernleistung einbringen`` markieren. Das Thema der besonderen Lernleistung weisen Sie analog dem entsprechenden Feld im Feld ``Thema`` zu.

``Abitur > Prüfung > Lernleistung``

## Merkmal

Das Merkmal muss unter `Abitur > Qualifikation > Merkmal` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus `Schüler > Zeugnis > Fächer > Merkmal` übernommen werden.

| Merkmal | Bedeutung                                |
|---------|------------------------------------------|
| A       | Fremdsprache Anfänger (2 Kurse müssen eingebracht werden) |

## Sonstiges

Das Berechnungsskript **DE-DIAP-2015** berücksichtigt auch folgendes:

* Ermittlung einer Schnittverbesserung durch mögliche Einbringung einer mdl. Note in einem Prüfungsfach unter dem Menü ``Abitur > Prüfung`` im Feld "mdl. Note"
* Ermittlung der Abiturzulassung am Ende der Q3, wenn unter dem Menü ``Abitur > Qualifikation`` in den Feldern ``Q4`` keine Punktwerte eingetragen sind
