# DE-DIAP-2024

[1]:/assets/images/DAS/Verordnung.dia.2018.png
[2]:/assets/images/DAS/verordnung.dia.2015.fachmerkmale01.png
[3]:/assets/images/DAS/das.bll2018.png
[4]:/assets/images/DAS/5.pf.png

Abiturqualifikationsberechnung für Deutsche Auslandsschulen nach der Ordnung der Deutschen Internationalen Abiturprüfung an deutschen Auslandsschulen nach Beschluss der Kultusministerkonferenz vom 11.06.2015 i. d. F. vom 08.02.2024

## Welcher Status wird im Skript berücksichtigt

Unter `Abitur > Qualifikation > Status` stehen mehrere Status zur Auswahl, wovon nur einige je Skript berücksichtigt werden. Für dieses Skript können folgende Auswahlen eingestellt werden:

* Gesamtqualifikation berechnen
* Fachhochschulreife berechnen

## Verzeichnis Verordnung

Bitte legen Sie unter `Verzeichnisse > Verordnungen` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

| Spalte       | Wert                                     |
|--------------|------------------------------------------|
| Kürzel       | beliebig                                 |
| Bezeichnung  | beliebig                                 |
| Kategorie    | Abitur                                   |
| Typ          | bitte leer lassen                        |
| Ab Jahrgang  | 10 oder 11                               |
| Skript       | `...\Auslandsschulen\DE-DIAP-2024.dws` (Pfad zur Skriptdatei DE-DIAP-2018.dws auf Ihrem Server) |
| Notenart 11  | Noten oder Punkte                        |
| Notenart 12  | Punkte                                   |
| Notenart 13  | Punkte                                   |
| Notenart 13  | Punkte                                   |
| Notenart BBS | leer                                     |
| Gültig von   | leer                                     |
| Gültig bis   | leer                                     |

Nachfolgend Beispiele für Verordnungszeilen für G8 der G9:

[![Anlegen der Verordnung für G8 und G9][1]][1]

## Fachkategorien

Berechnungsskripte erkennen relevante Fächer anhand der Eintragungen unter `Extras > Schlüsselverzeichnisse > Fächer > Fachkategorie`. 
Dabei müssen, je nach Verordnung, einige Fächer besonders berücksichtigt werden. Für diese Fächer sind die zu verwendenden Fachkategorien fest vorgeschrieben. Alle anderen Fächer können mit einer der übrigen Fachkategorie gekennzeichnet werden oder ohne Fachkategorie geführt werden.

|Fachkategorien|Muss genutzt werden|
|--|--|
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

### Das Fach "Ciencias Sociales"

Das an spanischen Auslandsschulen unterrichtete Fach "Ciencias Sociales" ist für die Qualifikation notwendig, kann aber kein Prüfungsfach sein. Bitte legen Sie das Fach im Schlüsselverzeichnis `Fächer` an, wählen die `Fachkategorie` "Sozialkunde" und in der Spalte `Aufgabenbereich` den Wert "gesellschaftswiss." aus.

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

Bitte tragen Sie im Schlüsselverzeichnis `Fächer` in der Spalte `Zeugnismerkmal` für die Fächer Deutsch, Englisch, Mathematik und die Landessprache die nachstehenden Kürzel ein. Aus diesen Kürzeln ergeben sich später für verschiedene DAS-Berichte das **E** für die vierstündig unterrichteten Fächer (auf erhöhtem Anforderungsniveau).

* `DAS-Prüfungsbogen (Anlage 7 zu DIA-PO)(2018).rpt` (Ausgabe **E** für die vierstündig unterrichtete)
* `DAS-GY-ABI (Anlage 7).rpt`(Ausgabe **E** für die vierstündig unterrichtete Fächer)
* `DAS-ZZ (Q-Phase)(Anlage 1) (RiLi 1.6)` (Untergliederung der Fächeranzeige auf dem Zeugnis nach Fächer auf erhöhtem/grundlegendem Anforderungsniveau)

| Fach          | Merkmal |
|---------------|---------|
| Deutsch       | D       |
| Mathematik    | M       |
| Englisch      | E       |
| Landessprache | LS      |

Nachstehend ein Beispiel für die Eintragung mit der Landessprache Italienisch:

[![Fachmerkmale festlegen][2]][2]

## Fachstatus

Der Fachstatus muss unter `Abitur > Qualifikation > Fachstatus` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus `Schüler > Zeugnis > Fächer > Fachstatus` übernommen werden.  
Prüfen Sie bitte unter `Extras > Schlüsselverzeichnisse > Fachstatus`,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung       |
|--------|-----------|-----------------|
| 1PF    | 1PF       | 1. Prüfungsfach |
| 2PF    | 2PF       | 2. Prüfungsfach |
| 3PF    | 3PF       | 3. Prüfungsfach |
| 4PF    | 4PF       | 4. Prüfungsfach |
| 5PF    | 5PF       | 5. Prüfungsfach |

## Besondere Lernleistung

Zur Ausgabe der besonderen Lernleistung müssen Sie im Menü „Abitur“ unter der Registerkarte `Prüfung > Lernleistung` das entsprechende Fach zuweisen und das Optionsfeld `Lernleistung einbringen` markieren. Das Thema der besonderen Lernleistung weisen Sie analog dem entsprechenden Feld im Feld `Thema` zu. 

Ergebnisse tragen Sie bitte im darüberliegenden Bereich `Prüfungen` für das 5.PF ein.

[![`Abitur > Prüfung > Lernleistung`][3]][3]

## Präsentation oder Streitgespräch

Das jeweilige Ergebnis ist bitte als mündliche Note des 5. Prüfungsfachs auf der Karte `Prüfung` zu erfassen. 
Bitte verwenden Sie hierfür **nicht** die Unterkarte "Präsentation".

[![Note erfassen][4]][4]

## Merkmal

Das Merkmal muss unter `Abitur > Qualifikation > Merkmal` eingetragen werden.

!!! info "Hinweis"

    Alternativ besteht auch die Möglichkeit das `Merkmal` ggfs. in einer Fachtafel vorzubelegen, den Schülern gemeinsamt mit den Fächern zuzuweisen und es dann beim Synchronisieren der Schülerfachdaten in den Bereich Abitur zu übernehmen.

| Merkmal | Bedeutung                                |
|---------|------------------------------------------|
| `A `      | Fremdsprache Anfänger (2 Kurse müssen eingebracht werden) |
|`von-bis`  | Tragen Sie als `von` bitte den Startjahrgang ein, als `bis` bitte den Endjahrgang für Fächer, die vor der Qualifikationsphase abgeschlossen wurden. Fächer, die vor der Klassenstufe 10 abgeschlossen wurden, werden nicht erfasst oder ausgewertet.<br/>  <br/>Ein Beispiel: <br/> Biologie wurde von Klassenstufe 5 bis Klassenstufe 10 belegt, dann tragen Sie im Feld Merkmal bitte `5-10` ein. Dieser Wert wird für Zeugnisberichte ausgewertet.

## Sonstiges

Das Berechnungsskript **DE-DIAP-2024** berücksichtigt auch folgendes:

* Ermittlung einer Schnittverbesserung durch mögliche Einbringung einer mdl. Note in einem Prüfungsfach unter dem Menü `Abitur > Prüfung` im Feld "mdl. Note"
  
![`Abitur > Prüfung > "Neu berechnen`](/assets/images/DAS/ds.schnittverbessernd2018.png)
* Ermittlung der Abiturzulassung am Ende der Q3, wenn unter dem Menü `Abitur > Qualifikation` in den Feldern `Q4` keine Punktwerte eingetragen sind
