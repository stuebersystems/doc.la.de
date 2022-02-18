# SAR-AZ-Verhaltenszeugnis

## Fehltage, Fehlstunden

`Schueler > Zeugnis > Details > Fehltage und/oder Fehlstunden`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern "Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

## Fachstatus

`Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis ""Fachtafeln"" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.
Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

Kürzel |  Schlüssel | Zeugnisbereich
--|--|--
VHZ | VHZ | Betragen, Mitarbeit, Arbeitshaltung, Teamfähigkeit

## Merkmale für Zeugnisbemerkungen

`Schüler > Zeugnis > Bemerkungen/Formulare > Merkmale`

Bei den Zeugnisbemerkungen müssen verschiedene Typen der Bemerkung unterschieden werden. 

Die Unterscheidung erfolgt durch den Eintrag in der Spalte "Merkmal". Sie können den Eintrag vorab im `Schlüsselverzeichnis > Zeugnisbemerkungen` für die Bemerkung vordefinieren oder individuell unter Schüler > Zeugnis > Bemerkungen/Formulare je Schülerbemerkung anpassen.
Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Bemerkungen/Formulare`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung auswählen und zuweisen. Erfolgt keine Eingabe in der Spalte "Merkmal", so wird die Bemerkung unter "allgemeinen Bemerkungen" auf dem Zeugnisdruck ausgegeben.

Folgende Kürzel im Feld "Merkmal" dürfen für den Zeugnisdruck verwendet werden:

Merkmal | Bedeutung
--|--
SchulA | Besondere schulische Aktivitäten

## SchulleiterIn 

`Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter `Mandanten > Daten1` im Feld "Schulleiter" eingetragen werden. Bitte achten Sie darauf, das dem zugrunde liegenden Lehrereintrag ein Geschlecht unter `Lehrer > Daten1` zugewiesen wurde.

## KlassenleiterIn 

`Klassen > Zeiträume > Zeitraum > Klassenleiter`

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü `Klassen > Zeiträume` bei der jeweiligen Klasse im Feld "Klassenleiter" eingetragen werden. Bitte achten Sie darauf, das dem zugrunde liegenden Lehrereintrag ein Geschlecht unter `Lehrer > Daten1` zugewiesen wurde.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Schüler` gedruckt werden.

## Datum 

`Allgemein > Systemdatum`

Auf dem Zeugnis/Bericht wird das Systemdatum ausgegeben.

## Ort des Druckdatums

`Mandanten > Daten 1 > Ort`

Der Ort des Druckdatums ergibt sich aufgrund der Eintragung im Menü `Mandanten > Daten 1` im Feld "Ort".

## Dienstbezeichnung der Lehrer

`Lehrer > Daten 2 > Dienstbez.`

Die Dienstbezeichnung des Schulleiters/Lehrers tragen Sie im Menü `Lehrer > Daten 2` im Feld "Dienstbez." ein. Grundlage für das Zuweisen einer Dienstbezeichnung bildet das `Schlüsselverzeichnis > Dienstbezeichnungen`.

## Ausdruck

Der Bericht muss aus dem Menu `Drucken > Zeugnis Drucken` (Strg + Z) gedruckt werden.

## Schulname

`Mandaten > Daten 1 > Name 1, Name 2, Name 3`

Tragen Sie die Bezeichnung, Schulform und Schulort Ihrer Schule im Menü `Mandanten > Daten 1`  in den Feldern „Name 1“, „Name 2“ und „Name 3“ ein.

## Logos der Schule

`Mandanten > Daten 2 > Logo 1, Logo 2`

Die Landeswappen und/oder Ihr Schullogo können individuell auf dem Zeugnis ausgegeben werden:  
Im Menü `Mandanten > Daten 2` können Sie ihre Landeswappen oder Ihre Schullogos im "jepg" Format hochladen. Damit es zu keiner Skalierung kommt beachten Sie dabei, dass Ihre Datei nach Möglichkeit 2,8 cm hoch wie breit sein sollte.

## Betragen, Mitarbeit, Arbeitshaltung und Teamfähigkeit 

`Schüler > Zeugnis > Fächer`
 
Betragen, Mitarbeit, Arbeitshaltung und Teamfähigkeit usw. legen Sie im `Schlüsselverzeichnis > Fächer` an. Weisen Sie diese dem Schüler im Menü `Schüler > Zeugnis > Fächer` zu. Zusätzlich erhalten die Fächer im Feld "Fachstatus" den Eintrag "VHZ" zu. Grundlage für das Zuweisen eines Fachstatus bildet das `Schlüsselverzeichnis > Fachstatus`.
Die Reihenfolge der Fächer auf dem Zeugnis richtet sich nach der Positionsnummer, die Sie dem jeweiligen Fach in der Spalte „Position“ im Menü `Schüler > Zeugnis > Fächer` vergeben haben. Die Noten der Fächer tragen Sie im Menü `Schüler > Zeugnis > Leistungen` in der Spalte „Endnote“ ein. Grundlage bildet das `Schlüsselverzeichnis > Noten`. Beachten Sie dabei, dass bei einer 4 nicht die Notenbezeichnung sondern die Bezeichnung "nicht befriedigend" ausgegeben wird.
Verwenden Sie dafür die folgenden Notenkürzel:

V1 = sehr gut 
V2 = gut
V3 = befriedigend
V4 = nicht befriedigend

