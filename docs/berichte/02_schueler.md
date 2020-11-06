# Schülerberichte

Nachfolgend sind erforderliche Eintragungen für die Berichte unter `MAGELLAN > Schüler > Drucken > Berichte` beschrieben.

## Anmeldeschein (weiterführende Schulen).rpt

**(A0112H)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0332)** `Schüler > Laufbahn > Empfehlung`

Tragen Sie die Schulübergangsempfehlung im Menü Schüler > Laufbahn im Feld "Empfehlung" wie folgt ein:

Kürzel | Schlüssel | Bezeichnung
--|--|--
050 | 050 | Schulübergangsempfehlung der Grundschule für die Hauptschule
080 | 080 | Schulübergangsempfehlung der Grundschule für die Realschule
090 | 090 | Schulübergangsempfehlung der Grundschule für das Gymnasium
100 | 100 | Sonstige (einschl. I-Schüler)
110 | 110 |keine Schulübergangsempfehlung bei Wechsel in Gemeinschaftsschule aus dazugehöriger Grundschule

**(A0050)** `Schüler > Daten 1 > Familie`

Tragen Sie im aktuellen Zeitraum im Schüler > Daten 1 > Familie  die Sorgeberechtigten des Schülers ein. Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie einen
Sorgeberechtigten zuweisen, neu anlegen oder ändern. Grundlage bildet das Menü Sorgeberechtigte. Für den Zeugnisdruck sind nur die Sorgeberechtigten, die unter Schüler > Familie im Feld "Benachrichtigung"
"immer" enthalten, relevant.

## Ausländerliste (nach Staatsangehörigkeiten).rpt

## BBS-Schulbescheinigung.rpt

## Bescheinigung über den Schulbesuch zweifach mit 31 Wochenstunden.rpt

## Bescheinigung über den Schulbesuch zweifach(mit Wochenstunden).rpt

## Bescheinigung über den Schulbesuch zweifach.rpt

## Bescheinigung über Schulbesuch.rpt

**(A0085)** `Schüler > Merkmale > Bemerkung`

Um der Bescheinigung eine Bemerkung zuzuordnen, tragen Sie im Menü Schüler > Merkmale  im Feld "Bemerkung" den entsprechenden Text ein.

## Bescheinigung über Schülerübergabe.rpt

Sorgeberechtigte/r muss unter Benachrichtigung „immer“ haben

## Fachwahl-Kursliste.rpt

Die Liste kann nach Kursen gruppiert Schüler eines Kurshalbjahres aus dem Bereich Abitur > Fachwahl ausgeben (zu drucken über Berichte drucken)

**(A0804)** `Abitur > Drucken > Berichte drucken`

Der Bericht wird aus dem Menü Abitur heraus gedruckt.
Wechseln Sie in das Menü Abitur > Auswahl und markieren eine Gruppe von Schülern, für die Sie eine Kursliste für ein bestimmtes Kurshalbjahr (E1, E2, Q1, Q2, Q3 oder Q4)**ausgeben möchten.
Wählen Sie Drucken > Berichte > Fachwahl-Kursliste.rpt und rufen die Druckvorschau auf. Es erscheint ein Parameterfenster, wählen Sie das Kurshalbjahr (E1, E2, Q1, Q2, Q3 oder Q4)**aus!

Der Bericht fasst die gewählten Kurse nach Fach und Unterrichtsart der markierten Schüler zusammen und gibt jeweils Schüler, Klasse und Fachstatus aus.

## KV09b Masernschutz.rpt

Der Bericht muss aus dem Menü `Schüler` gedruckt werden.
Es werden im Berichtskopf die Schüler-/Sorgeberechtigtendaten aus den Einträgen in MAGELLAN ausgegeben. Das Druckdatum (Tagesdatum) und der Ort (`Mandanten > Daten > Ort`) werden automatisch eingefügt. Weitere Angaben im Bericht sind nach dem Druck manuell einzutragen.

**Volljährigkeit**

Der Bericht prüft die Volljährigkeit des Schülers. Ist der Schüler ab dem Druckdatum volljährig, bleibt das Sorgeberechtigtenfeld leer, die Adressdaten (PLZ, Ort, Straße) und Kontaktdaten (E-Mail, Telefonnummer) des Schülers werden ausgegeben.

Ist der Schüler minderjährig, wird das Sorgeberechtigtenfeld gefüllt, es werden die Adressdaten (PLZ, Ort, Straße) und die Kontaktdaten (E-Mail, Telefonnummer) des Sorgeberechtigten ausgegeben.

!!! danger "Achtung"

    Aus der Liste unter `Schüler > Daten1 > Familie` wird (sortiert nach der Position) der erste Sorgeberechtige ausgegeben, der den Wert `Immer` im Feld `Benachrichtigung` eingetragen hat.

## MVP-Schullastenausgleich-Teilzeit (nicht im Landkreis Mecklenburgische Seenplatte).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0336)** `Schüler > Daten 1 > Gemeinde`

Tragen Sie die Gemeinde des Schüler-Wohnortes im Menü Schüler > Daten 1 im Feld "Gemeinde" ein.


**(A0630)** `Klassen > Daten > Organisation`

Um zu differenzieren, ob es sich um einen Teilzeit- oder Vollzeitschüler handelt, gehen Sie wie folgt vor:
Tragen Sie die Vollzeit-  bzw. Teilzeitform im Menü Klassen > Daten im Feld „Organisation“ ein. Grundlage hierfür bildet das Schlüsselverzeichnis> Organisationen. Das Kürzel und der Schlüssel im Schlüsselverzeichnis sind frei wählbar (z.B. "VZ", "TZ"), die Bezeichnung muss entsprechend  "Vollzeit" oder  "Teillzeit" lauten.

Kürzel | Schlüssel | Bezeichnung
--|--|--
beliebig (VZ)**| leer | Vollzeit
beliebig (TZ)**| leer | Teilzeit

**(A0631)** `Schüler > Auswahl > Drucken > Berichte drucken > Mecklenburg Vorpommern`

Es werden nur die Schüler ausgegeben, die ungleich der ersten 5 Ziffern "13071" der Gemeindekennziffer sind. (siehe auch A0336)

## MVP-Schullastenausgleich-Vollzeit (nicht im Landkreis Mecklenburgische Seenplatte).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.


**(A0336)** `Schüler > Daten 1 > Gemeinde`

Tragen Sie die Gemeinde des Schüler-Wohnortes im Menü Schüler > Daten 1 im Feld "Gemeinde" ein.

**(A0630)** `Klassen > Daten > Organisation`

Um zu differenzieren, ob es sich um einen Teilzeit- oder Vollzeitschüler handelt, gehen Sie wie folgt vor:
Tragen Sie die Vollzeit-  bzw. Teilzeitform im Menü Klassen > Daten im Feld „Organisation“ ein. Grundlage hierfür bildet das Schlüsselverzeichnis> Organisationen. Das Kürzel und der Schlüssel im Schlüsselverzeichnis sind frei wählbar (z.B. "VZ", "TZ"), die Bezeichnung muss entsprechend  "Vollzeit" oder  "Teillzeit" lauten.

Kürzel | Schlüssel | Bezeichnung
--|--|--
beliebig (VZ)**| leer | Vollzeit
beliebig (TZ)**| leer | Teilzeit

**(A0631)** `Schüler > Auswahl > Drucken > Berichte drucken > Mecklenburg Vorpommern`

Es werden nur die Schüler ausgegeben, die ungleich der ersten 5 Ziffern "13071" der Gemeindekennziffer sind. (siehe auch A0336)

## NRW-Schülerstammblatt.rpt

**(A0021)** `Schüler > Zeugnis >Bemerkungen/Formulare > Merkmale`

Bei den Zeugnisbemerkungen müssen verschiedene Typen der Bemerkung unterschieden werden. Die Unterscheidung erfolgt durch den Eintrag in der Spalte "Merkmal" unter Schlüsselverzeichnis Zeugnisbemerkungen, falls
es sich um allgemeingültige Zeugnisbemerkungen handelt, oder beim Schüler, falls Sie diesem eine individuelle Zeugnisbemerkung zuweisen möchten. Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü Schüler > Zeugnis >Bemerkungen/Formulare. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung auswählen und zuweisen. Erfolgt keine Eingabe in der Spalte "Merkmal", so wird die Bemerkung unter "allgemeinen Bemerkungen" auf dem Zeugnisdruck ausgegeben.
Folgende Kürzel im Feld "Merkmal" dürfen für den Zeugnisdruck verwendet werden:

**(A0023)** S`chüler > Daten 3 > 1./2./3./4. Fremdsprache`

Tragen Sie im Menü Schüler > Daten 3 beim entsprechenden Schüler die Fremdsprache im aktuellen Zeitraum unter "Fremdsprachenfolge" ein. Damit Ihnen hier Fremdsprachen im Auswahlmenü
angeboten werden, müssen Sie unter Schlüsselverzeichnis > Fächer im Feld "Kategorie" aus dem Pull-Down-Menü "Fremdsprache" zugewiesen haben.

**(A0035)** `Klassen > Daten > Bildungsgang`

Weisen Sie unter `Klassen > Daten im Feld "Bildungsgang"` zu. Grundlage bildet das Schlüsselverzeichnis "Bildungsgänge".

**(A0036)** `Schüler > Ausbildung > Ausbildungbetriebe > Beruf`

Tragen Sie im Menü Schüler > Ausbildung im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Beruf" den Beruf ein. Grundlage bildet das Schlüsselverzeichnis Berufe. 

**(A0050)** `Schüler > Daten 1 > Familie`

Tragen Sie im aktuellen Zeitraum im Schüler > Daten 1 > Familie  die Sorgeberechtigten des Schülers ein. Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie einen
Sorgeberechtigten zuweisen, neu anlegen oder ändern. Grundlage bildet das Menü Sorgeberechtigte. Für den Zeugnisdruck sind nur die Sorgeberechtigten, die unter Schüler > Familie im Feld "Benachrichtigung"
"immer" enthalten, relevant.

**(A0080)** `Schüler > Daten 2 > Bereits besuchte Schulen`

Tragen Sie im Menü Schüler > Daten 2  im Bereich "Bereits besuchte Schulen" die jeweilige Schule ein.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0170)** `Klassen > Daten > Berufsfeld`

Die Fachrichtung weisen Sie im Menü Klassen > Daten im Feld "Berufsfeld" zu. Grundlage bildet das Schlüsselverzeichnis > Berufsfelder.

**(A0178)** `Klasse > Daten > Schulart`

Tragen Sie im aktuellen Zeitraum im Menü Klasse > Daten die Schulfart im Feld "Schulart" ein. Grundlage hierfür bildet das Schlüsselverzeichnis > Schularten.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0277)** `Schüler > Daten 1 > Staatsangeh. 1`

Tragen Sie die Staatsangehörigkeit des Schülers im Menü Schüler > Daten 1 im Feld "Staatsangeh. 1" ein.

**(A0434)** `Schüler > Ausbildung > Ausbildungsbetriebe`

Tragen Sie den Betrieb im Menü Schüler > Ausbildung unter Ausbildungsbetriebe ein.

**(A0435)** `Schüler > Ausbildung > Ausbildungsbetriebe > Ausbilderkontakt`

Tragen Sie den Ausbilder im Menü Schüler > Ausbildung beim zugewiesenen Ausbildungsbetrieb im Feld  "Ausbilderkontakt" ein.

**(A0439)** `Schüler > Daten 1 > Konfession`

Tragen Sie im Menü Schüler> Daten 1 im Feld "Konfession" die Konfession des Schülers ein. Grundlage bildet das Schlüsselverzeichnis > Konfessionen.

**(A0440)** `Schüler > Daten 1 > Aussiedler seit`

Tragen Sie im Menü "Schüler" beim entsprechenden Schüler den Status "Ausländer" unter der Registerkarte "Daten 1" im Feld "Aussiedler seit" ein.

**(A0441)** `Schüler > Daten 4 > Beförderung > Fahrkarte`

Falls der/die Schüler/in eine "Fahrkarte" erhält, tragen Sie die jeweilige Bemerkung im Menü Schüler > Daten 4 > Beförderung im Feld "Fahrkarte" ein.  Grundlage für das Zuweisen bildet das Schlüsselverzeichnis > Fahrkarten.

**(A0442)** `Schüler > Daten 4 > Finanzielle Förderung > erhält Bafög bis`

Falls der/die Schüler/in Bafög erhält, markieren Sie im Menü Schüler > Daten 4 im Bereich "Finanzielle Förderung" das Options-Feld "erhält Bafög bis".

**(A0443)** `Schüler > Daten 2 > bereits besuchte Schulen > Schulform`

Die "letzte Schulform" tragen Sie im Menü Schüler > Daten 2 im Bereich "bereits besuchte Schulen" bei der zugewiesenen Schule im Feld "Schulform" ein. Grundlage bildet das Schlüsselverzeichnis > Schulformen (Herkunft)“.

**(A0444)** `Schüler > Daten 2 > bereits besuchte Schulen > Abschluss`

Die "letzte schulische Qualif." tragen Sie im Menü Schüler > Daten 2 im Bereich "bereits besuchte Schulen" bei der zugewiesenen Schule im Feld "Abschluss"ein. Grundlage bildet das Schlüsselverzeichnis > Abschlüsse (extern).

**(A0445)** `Schüler > Daten 2 > bereits besuchte Schulen > letzte Klasse`

Die "Entlassklasse" tragen Sie im Menü Schüler > Daten 2 im Bereich "bereits besuchte Schulen" im Feld "letzte Klasse"ein.

**(A0446)** `Schüler > Daten 2 > Zugang > Zugang am`

Die "erste Einschulung" tragen Sie  im Menü Schüler > Daten 2 im Bereich "Zugang" im Feld „Zugang am“ ein.

## Rentenbescheid.rpt

Bescheid für Zwecke der gesetzlichen Rentenversicherung über Zeiten des Schul-Fachschul-Fachhochschul- oder Hochschulbesuchs -auszustellen durch SchuleFachschuleFachhochschuleoder Hachschule -

**(A0036)** `Schüler > Ausbildung > Ausbildungbetriebe > Beruf`

Tragen Sie im Menü Schüler > Ausbildung im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Beruf" den Beruf ein. Grundlage bildet das Schlüsselverzeichnis Berufe. 

**(A0045)** `Mandanten > Daten >Name 1`

Tragen Sie die Bezeichnung Ihrer Schule im Menü "Mandanten" auf der Registerkarte "Daten 1" im Feld "Name
1" ein.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken` (Strg + P) gedruckt werden.

## RLP-BBS (Bescheinigung Niveaustufen).rpt

**(A0035)** `Klassen > Daten > Bildungsgang`

Weisen Sie unter Klassen > Daten im Feld "Bildungsgang" zu. Grundlage bildet das Schlüsselverzeichnis "Bildungsgänge".

**(A0077)** `Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter `Mandanten > Daten1` im Feld "Schulleiter" eingetragen werden.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0588)** `Klassen > Merkmale > Merkmal A6`

`Schüler > Merkmale > Merkmal A6`

Angabe der Niveaustufe „Europäische Qualifikationsrahmen“:

1. **Ist die Angabe der Niveaustufe „Europäische Qualifikationsrahmen“ bei allen Schülern einer Klasse gleich, tragen Sie diese im Menü Klassen > Merkmale im Feld "Merkmal A6" ein. Grundlage bildet das Schlüsselverzeichnis > Merkmale (Klassen). Hier ist in der Spalte „Bereich“ der Wert  „Merkmal A6“ zuzuweisen. 

2. ** Ist die Angabe der Niveaustufe nicht bei allen Schülern einer Klasse gleich, weisen Sie dieses jedem einzelnen Schüler im Menü Schüler > Merkmale im Feld „Merkmal A6“ zu. Grundlage bildet das Schlüsselverzeichnis Merkmale (Schüler). Hier ist in der Spalte „Bereich“ zuzuweisen „Merkmal A6“.  Für den Zeugnisdruck ist nur der Wert in der Spalte „Bezeichnung“ des Merkmales relevant.

Tipp: Ist die Niveaustufe bei den meisten Schülern einer Klasse gleich, dann weisen Sie das Merkmal im Menü Klasse zu (siehe 1.)**und lassen das Merkmal bei diesen Schülern im Menü Schüler leer. Den restlichen Schülern mit einer abweichenden Niveaustufe weisen Sie das Merkmal im Menu Schüler zu (siehe 2.).

## Schulbescheinigung (Anmeldung weiterführende Schule).rpt

**(A0103)** `Schüler > Laufbahn > Allgemein > Empfehlung`

Tragen Sie im Menü "Schüler" im aktuellen Zeitraum auf der Registerkarte "Laufbahn" unter "Allgemein" im Feld "Empfehlung" die entsprechende Schulform ein.

**(A0050)** `Schüler > Daten 1 > Familie`

Tragen Sie im aktuellen Zeitraum im Schüler > Daten 1 > Familie  die Sorgeberechtigten des Schülers ein. Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie einen
Sorgeberechtigten zuweisen, neu anlegen oder ändern. Grundlage bildet das Menü Sorgeberechtigte. Für den Zeugnisdruck sind nur die Sorgeberechtigten, die unter Schüler > Familie im Feld "Benachrichtigung"
"immer" enthalten, relevant.

**(A0078)** `Klassen > Zeiträume > Zeitraum > Klassenleiter`

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü Klassen > Zeiträume bei der jeweiligen Klasse im Feld "Klassenleiter" eingetragen werden.

## Schulbescheinigung (Elternwunsch Schulform).rpt

**(A0103)** `Schüler > Laufbahn > Allgemein > Empfehlung`

Tragen Sie im Menü "Schüler" im aktuellen Zeitraum auf der Registerkarte "Laufbahn" unter "Allgemein" im Feld "Empfehlung" die entsprechende Schulform ein.

## Schulbescheinigung (Empfangsbestätigung).rpt

## Schulbescheinigung (mit Klasse und Ausbildungsdauer).rpt

**(A0018)** `Schueler >Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü Schüler > Daten 2 im Feld "Zugang am" bzw. "Abgang am" ein.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0684)** `Schüler > Ausbildung > Dauer`

Tragen Sie die Dauer der Ausbildung im Menü Schüler > Ausbildung im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Dauer" ein.

## Schulbescheinigung (mit Klasse und vorauss. Ende einfach).rpt

Schulbescheinigung Typ B 

**(A0018)** `Schueler > Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü Schüler > Daten 2 im Feld "Zugang am" bzw. "Abgang am" ein.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0284)** `Schüler > Daten 2 > Abgang > Voraus. Ende`

Tragen Sie im Menü `Schüler > Daten 2` im Bereich "Abgang" das Datum für das voraussichtliche Ende im Feld "Voraus. Ende" ein.

## Schulbescheinigung (mit Klasse und vorauss. Ende zweifach).rpt

Schulbescheinigung Typ A

## Schulbescheinigung (mit Klasse).rpt

Schulbescheinigung Typ C 

## Schulbescheinigung (Schullaufbahnempfehlung).rpt

**(A0103)** `Schüler > Laufbahn > Allgemein > Empfehlung`

Tragen Sie im Menü "Schüler" im aktuellen Zeitraum auf der Registerkarte "Laufbahn" unter "Allgemein" im Feld "Empfehlung" die entsprechende Schulform ein.

**(A0021)** `Schüler > Zeugnis >Bemerkungen/Formulare > Merkmale`

Bei den Zeugnisbemerkungen müssen verschiedene Typen der Bemerkung unterschieden werden. Die Unterscheidung erfolgt durch den Eintrag in der Spalte "Merkmal" unter Schlüsselverzeichnis Zeugnisbemerkungen, falls
es sich um allgemeingültige Zeugnisbemerkungen handelt, oder beim Schüler, falls Sie diesem eine individuelle Zeugnisbemerkung zuweisen möchten. Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü Schüler > Zeugnis >Bemerkungen/Formulare. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung auswählen und zuweisen. Erfolgt keine Eingabe in der Spalte "Merkmal", so wird die Bemerkung unter "allgemeinen Bemerkungen" auf dem Zeugnisdruck ausgegeben.
Folgende Kürzel im Feld "Merkmal" dürfen für den Zeugnisdruck verwendet werden:

**(A0021.25)** `Merkmal > Bedeutung`

Merkmal | Bedeutung
--|--
gut  | Gutachten

**(A0007)** `Extras > Schlüsselverzeichnisse > Zeiträume > Ausdruck 2`

Die Ausgabe des Schulhalbjahres erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN unter Extras > Schlüsselverzeichnisse > Zeiträume. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck2".

## Schulbescheinigung (SHL - in Word ausfüllbar).rpt

**(A0292)** `Sonstiges > Word`

Dieser Bericht enthält spezielle Textfelder, die Sie über Microsoft Word ausfüllen können. Gehen Sie dafür folgendermaßen vor:

1. Markieren Sie den zu druckenden Datensatz aus, gehen auf Drucken > Berichte drucken > Bericht auswählen > Vorschau. 
2. Wählen  Sie im folgenden Programmfenster die Schaltfläche „Bericht exportieren“
3. Wählen Sie  im Fenster „Format“ bitte  „MS Word“ und im Fenster „Ziel“ bitte „Anwendung“. Bestätigen Sie mit OK.
4. Der Bericht öffnet sich mit MS Word und Sie können die auszufüllenden Felder per Mausklick aktivieren und füllen.

**(A0284)** `Schüler > Daten 2 > Abgang > Voraus. Ende`

Tragen Sie im Menü Schüler > Daten 2 im Bereich "Abgang" das Datum für das voraussichtliche Ende im Feld "Voraus. Ende" ein.

**(A0274)** `Schlüsselverzeichnisse > Zeiträume > Ausdruck 1`

Die Ausgabe in der Spalte "Zeitraum" erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN im `Schlüsselverzeichnisse > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte „Ausdruck1“.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0054)** `Klassen > Daten > Schulform`

Tragen Sie im aktuellen Zeitraum im Menü Klassen > Daten die Schulform im Feld "Schulform" ein. Grundlage hierfür bildet das Schlüsselverzeichnis > Schulformen.

**(A0075)** `Klassen > Daten > Kürzel`

Im entsprechenden Zeitraum muss im Menü Klassen > Daten im Feld "Kürzel" die Klasse angeben.

**(A0084)** `Mandanten > Daten 1 > Name 3`

Um den Ort des Druckdatums anzuzeigen, tragen Sie den Ort Ihrer Schule im Menü `Mandanten > Daten 1 > Name 3` ein.

## Schulbescheinigung (SHL).rpt

**(A0284)** `Schüler > Daten 2 > Abgang > Voraus. Ende`

Tragen Sie im Menü Schüler > Daten 2 im Bereich "Abgang" das Datum für das voraussichtliche Ende im Feld "Voraus. Ende" ein.

**(A0274)** `Schlüsselverzeichnisse > Zeiträume > Ausdruck 1`

Die Ausgabe in der Spalte "Zeitraum" erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN im Schlüsselverzeichnisse > Zeiträume. Ausgegeben wird hierbei der Eintrag in der Spalte „Ausdruck1“.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0054)** `Klassen > Daten > Schulform`

Tragen Sie im aktuellen Zeitraum im Menü Klassen > Daten die Schulform im Feld "Schulform" ein. Grundlage hierfür bildet das Schlüsselverzeichnis > Schulformen.

**(A0075)** `Klassen > Daten > Kürzel`

Im entsprechenden Zeitraum muss im Menü Klassen > Daten im Feld "Kürzel" die Klasse angeben.

**(A0084)** `Mandanten > Daten 1 > Name 3`

Um den Ort des Druckdatums anzuzeigen, tragen Sie den Ort Ihrer Schule im Menü `Mandanten > Daten 1 > Name 3` ein.

## Schulbescheinigung (Standard).rpt

Schulbescheinigung Typ D (2 DIN A5 Bescheinigungen auf einer DIN A4 Seite)

## Schulbescheinigung (Vergangenheit mit Klasse).rpt

## Schulbescheinigung (Überweisung).rpt

**(A0103)** `Schüler > Laufbahn > Allgemein > Empfehlung`

Tragen Sie im Menü "Schüler" im aktuellen Zeitraum auf der Registerkarte "Laufbahn" unter "Allgemein" im Feld "Empfehlung" die entsprechende Schulform ein.

**(A0007)** `Extras > Schlüsselverzeichnisse > Zeiträume > Ausdruck 2`

Die Ausgabe des Schulhalbjahres erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN unter `Extras > Schlüsselverzeichnisse > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck2".

## Schulbescheinigung BBS (mit Zugang-Abgang der Klasse).rpt

Schulbescheinigung für Berufsbildende Schulen

## Schulbescheinigung für die Vergangenheit.rpt

## Schulbescheinigung zweifach.rpt

## Schullastenausgleich Teilzeit.rpt

Bei der Klasse muss die Organisation mit dem Schlüssel „2“ für Teilzeit eingetragen sein.

## Schullastenausgleich Vollzeit.rpt

Bei der Klasse muss die Organisation mit dem Schlüssel „1“ für Vollzeit eingetragen sein.

## Schullaufbahnempfehlung.rpt

**(A0103)** `Schüler > Laufbahn > Allgemein > Empfehlung`

Tragen Sie im Menü "Schüler" im aktuellen Zeitraum auf der Registerkarte "Laufbahn" unter "Allgemein" im Feld "Empfehlung" die entsprechende Schulform ein.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0150)** `Allgemein > Systemdatum`

Auf dem Zeugnis/Bericht wird das Systemdatum ausgegeben.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken` (Strg + P) gedruckt werden.

**(A0050)** `Schüler > Daten 1 > Familie`

Tragen Sie im aktuellen Zeitraum im Schüler > Daten 1 > Familie  die Sorgeberechtigten des Schülers ein. Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie einen
Sorgeberechtigten zuweisen, neu anlegen oder ändern. Grundlage bildet das Menü Sorgeberechtigte. Für den Zeugnisdruck sind nur die Sorgeberechtigten, die unter Schüler > Familie im Feld "Benachrichtigung"
"immer" enthalten, relevant.

**(A0077)** `Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter Mandanten > Daten1 im Feld "Schulleiter" eingetragen werden.

**(A0276)** `Schüler > Laufbahn > Allgemein > Empfehlung`

In MAGELLAN muss im Menü `Schüler > Laufbahn` im Bereich "Allgemein" im Feld "Empfehlung" HS, RS oder GY gewählt werden. Grundlage bildet das Schlüsselverzeichnis > Empfehlungen. Der Bericht setzt dann automatisch folgende Kreuzchen:

HS > HS, R+ und IGS
RS > RS, R+ und IGS
GY ---> GY und IGS

## Schulzeitenbescheinigung (in Word ausfüllbar).rpt

**(A0292)** `Sonstiges > Word`

Dieser Bericht enthält spezielle Textfelder, die Sie über Microsoft Word ausfüllen können. Gehen Sie dafür folgendermaßen vor: 

1. Markieren Sie den zu druckenden Datensatz aus, gehen auf `Drucken > Berichte drucken > Bericht auswählen > Vorschau`. 
2. Wählen  Sie im folgenden Programmfenster die Schaltfläche „Bericht exportieren“
3. Wählen Sie  im Fenster „Format“ bitte  „MS Word“ und im Fenster „Ziel“ bitte „Anwendung“. Bestätigen Sie mit OK.
4. Der Bericht öffnet sich mit MS Word und Sie können die auszufüllenden Felder per Mausklick aktivieren und füllen.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0150)** `Allgemein > Systemdatum`

Auf dem Zeugnis/Bericht wird das Systemdatum ausgegeben.

**(A0018)** `Schueler > Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü Schüler > Daten 2 im Feld "Zugang am" bzw. "Abgang am" ein.

**(A0183)** `Mandanten > Daten 1 > Ort`

Der Ort des Druckdatums ergibt sich aufgrund der Eintragung im Menü `Mandanten > Daten 1` im Feld "Ort".

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken` (Strg + P) gedruckt werden.

## Schulzeitenbescheinigung.rpt

**(A0150)** `Allgemein > Systemdatum`

Auf dem Zeugnis/Bericht wird das Systemdatum ausgegeben.

**(A0018)** `Schueler > Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü `Schüler > Daten 2` im Feld "Zugang am" bzw. "Abgang am" ein.

**(A0183)** `Mandanten > Daten 1 > Ort`

Der Ort des Druckdatums ergibt sich aufgrund der Eintragung im Menü `Mandanten > Daten 1` im Feld "Ort".

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken` (Strg + P) gedruckt werden.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

## Schüler (Anzahl Schüler je Herkunftsschulen).rpt

Aufsummierung der Schüler nach Herkunftsschule

**(A0080)** `Schüler > Daten 2 > Bereits besuchte Schulen`

Tragen Sie im Menü `Schüler > Daten 2`  im Bereich "Bereits besuchte Schulen" die jeweilige Schule ein.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken` (Strg + P) gedruckt werden.

**(A0299)** `Schüler > Daten 2 > Bereits besuchte Schulen > Herkunftsschule`

Tragen Sie im Menü Schüler > Daten 2  im Bereich "Bereits besuchte Schulen" die Herkunftsschule ein. Grundlage bilden die bereits erfassten Schulen im Menü Schulen.

## Schüler (Anzeige Schulpflichtverletzung).rpt

**(A0021)** `Schüler > Zeugnis > Bemerkungen/Formulare > Merkmale`

Bei den Zeugnisbemerkungen müssen verschiedene Typen der Bemerkung unterschieden werden. Die Unterscheidung erfolgt durch den Eintrag in der Spalte "Merkmal" unter Schlüsselverzeichnis Zeugnisbemerkungen, falls
es sich um allgemeingültige Zeugnisbemerkungen handelt, oder beim Schüler, falls Sie diesem eine individuelle Zeugnisbemerkung zuweisen möchten. Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Bemerkungen/Formulare`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung auswählen und zuweisen. Erfolgt keine Eingabe in der Spalte "Merkmal", so wird die Bemerkung unter "allgemeinen Bemerkungen" auf dem Zeugnisdruck ausgegeben.
Folgende Kürzel im Feld "Merkmal" dürfen für den Zeugnisdruck verwendet werden:

**(A0050)** `Schüler > Daten 1 > Familie`

Tragen Sie im aktuellen Zeitraum im `Schüler > Daten 1 > Familie`  die Sorgeberechtigten des Schülers ein. Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie einen
Sorgeberechtigten zuweisen, neu anlegen oder ändern. Grundlage bildet das Menü Sorgeberechtigte. Für den Zeugnisdruck sind nur die Sorgeberechtigten, die unter `Schüler > Daten1 > Familie` im Feld "Benachrichtigung"
"immer" enthalten, relevant.

**(A0077)** `Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter Mandanten > Daten1 im Feld "Schulleiter" eingetragen werden.

**(A0078)** `Klassen > Zeiträume > Zeitraum > Klassenleiter`

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü `Klassen > Zeiträume` bei der jeweiligen Klasse im Feld "Klassenleiter" eingetragen werden.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0690)** `Adressen > Daten > Kategorie (SVA)`
---
Die Adresse des Schulverwaltungsamt legen Sie im Menü Adressen > Daten an. Wichtig ist, dass Sie in dem Feld „Kategorie“ das Kürzel „SVA“ zuweisen. Grundlage hierfür bildet das Schlüsselverzeichnis > Kategorien (Adressen).

**(A021.58)** Merkmal Zeugnisbereich

Merkmal | Zeugnisbereich
--|--
SVA | Bemerkung für Schulpflichtverletzung

## Schüler (Bescheinigung-Laufbahn).rpt

**(A0018)** `Schueler > Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü `Schüler > Daten 2` im Feld "Zugang am" bzw. "Abgang am" ein.

**(A0054)**` Klassen > Daten > Schulform
`
Tragen Sie im aktuellen Zeitraum im Menü `Klassen > Daten` die Schulform im Feld "Schulform" ein. Grundlage hierfür bildet das `Schlüsselverzeichnis > Schulformen`.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0150)** `Allgemein > Systemdatum`

Auf dem Zeugnis/Bericht wird das Systemdatum ausgegeben.

**(A0216)** `Mandanten >Daten 1 > Ort`

Der Schulort (bzw. Ausstellungsort) ergibt sich aufgrund der Eintragung im Menü Mandanten >Daten 1 im Feld „Ort“.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0284)** `Schüler > Daten 2 > Abgang > Voraus. Ende`

Tragen Sie im Menü Schüler > Daten 2 im Bereich "Abgang" das Datum für das voraussichtliche Ende im Feld "Voraus. Ende" ein.

**(A0370)** `Schlüsselverzeichnis > Zeiträume > Ausdruck 2`

Die Ausgabe des Schuljahres erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN `Schlüsselverzeichnis > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck 2".

## Schüler (gruppiert nach Herkunftsschulen).rpt

**(A0080)** `Schüler > Daten 2 > Bereits besuchte Schulen`

Tragen Sie im Menü `Schüler > Daten 2 ` im Bereich "Bereits besuchte Schulen" die jeweilige Schule ein.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0299)** `Schüler > Daten 2 > Bereits besuchte Schulen > Herkunftsschule`

Tragen Sie im Menü `Schüler > Daten 2`  im Bereich "Bereits besuchte Schulen" die Herkunftsschule ein. Grundlage bilden die bereits erfassten Schulen im Menü Schulen.

**(A0445)** `Schüler > Daten 2 > bereits besuchte Schulen > letzte Klasse`

Die "Entlassklasse" tragen Sie im Menü `Schüler > Daten 2` im Bereich "bereits besuchte Schulen" im Feld "letzte Klasse"ein.

**(A0566)** `Schüler > Daten 2 > Bereits besuchte Schule > Klassenleiter(in)`

Den Klassenlehrer der "Entlassklasse" tragen Sie im Menü `Schüler > Daten 2`  im Bereich "Bereits besuchte Schule" Feld "Klassenleiter(in)" ein.
Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie die Eingabe im Feld "Klassenleiter(in)" vornehmen.

## Schüler (Nachmahnung).rpt

**(A0045)** `Mandanten > Daten > Name 1`

Tragen Sie die Bezeichnung Ihrer Schule im Menü "Mandanten" auf der Registerkarte "Daten 1" im Feld "Name
1" ein.

**(A0050)** `Schüler > Daten 1 > Familie`

Tragen Sie im aktuellen Zeitraum im `Schüler > Daten 1 > Familie`  die Sorgeberechtigten des Schülers ein. Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie einen
Sorgeberechtigten zuweisen, neu anlegen oder ändern. Grundlage bildet das Menü Sorgeberechtigte. Für den Zeugnisdruck sind nur die Sorgeberechtigten, die unter `Schüler > Daten1 > Familie` im Feld "Benachrichtigung"
"immer" enthalten, relevant.

***(A0077)** `Mandanten > Daten 1 > Schulleiter`

Der Schulleiter muss im entsprechenden Zeitraum unter `Mandanten > Daten1` im Feld "Schulleiter" eingetragen werden.

**(A0078)** `Klassen > Zeiträume > Zeitraum > Klassenleiter`

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü `Klassen > Zeiträume` bei der jeweiligen Klasse im Feld "Klassenleiter" eingetragen werden.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0150)** `Allgemein > Systemdatum`

Auf dem Zeugnis/Bericht wird das Systemdatum ausgegeben.

**(A0211)** `Lehrer > Daten 2 > Dienstbez.`

Die Dienstbezeichnung des Schulleiters / Lehrers tragen Sie im Menü Lehrer > Daten 2 im Feld "Dienstbez." ein. Grundlage für das Zuweisen einer Dienstbezeichnung bildet das Schlüsselverzeichnis > Dienstbezeichnungen.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0362)** `Lehrer > Daten 1 > Anrede`

Weisen Sie die Anrede des Lehrers im Menü `Lehrer > Daten 1` im Feld "Anrede" zu.

**(A0397)** `Schüler > Zeugnis > Leistungen > Mahnung (Nachmahnung)`

Die Fächer für die "Nachmahnung" weisen Sie dem jeweiligen Schüler im Menü `Schüler > Zeugnis > Fächer` zu. Im Menü `Schüler > Zeugnis > Leistungen` weisen Sie diesen Fächern aus dem Aufklappmenü im Feld "Mahnung" den Wert "Nachmahnung" zu.

## Schüler BBS(Zeitraumübergreifende Notenübersicht).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0115)** `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren,
die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung
"2" usw.

**(A0012)** `Klassen > Zeiträume > Zeitraum > Klassenstufe`

Im entsprechenden Zeitraum muss im Menü Klassen bei der Klasse des Schülers die Klassenstufe auf der Registerkarte `Zeiträume > Zeitraum` im Feld "Klassenstufe" eingetragen sein.

**(A0013)** `Schueler > Zeugnis > Details > Fehltage und/oder Fehlstunden`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern "Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

**(A0238)** `Schüler > Daten 2 > Höchster Abschluss > Abschluss`

Tragen Sie im Menü „Schüler“ im aktuellen Zeitraum auf der Registerkarte „Daten2“ unter „Höchster Abschluss ABS“ die Abschlussbezeichnung im Feld „Abschluss“ ein. Grundlage hierfür bildet das Schlüsselverzeichnis Abschlüsse (Extern).

**(A0239)** Ausdruck

Der Bericht muss aus dem Menu "Drucken" "Zeugnis Drucken" (Strg + Z)**gedruckt werden.

**(A0280)** `Schlüsselverzeichnisse > Zeiträume`

Die Ausgabe des Schulhalbjahrs erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN im `Schlüsselverzeichnis > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte „Bezeichnung“. Aus Platzgründen formatieren Sie die „Bezeichnung“ folgendermaßen:

1. kürzen Sie "Halbjahr" mit "HJ" ab
2. kürzen Sie das Jahr, z.B. "2009" mit "09" ab

Ihr Schulhalbjahr sollte dann in etwa so formatiert sein:  "1. HJ 08/09"

## Schüler mit Herkunftsschulen u. letzte Klasse.rpt

**(A0023)** `Schüler > Daten 3 > 1./2./3./4. Fremdsprache`

Tragen Sie im Menü `Schüler > Daten 3` beim entsprechenden Schüler die Fremdsprache im aktuellen Zeitraum unter "Fremdsprachenfolge" ein. Damit Ihnen hier Fremdsprachen im Auswahlmenü
angeboten werden, müssen Sie unter Schlüsselverzeichnis > Fächer im Feld "Kategorie" aus dem Pull-Down-Menü "Fremdsprache" zugewiesen haben.

**(A0063)** `Schüler > Daten 2 > Bereits besuchte Schule > letzte Klasse`

Tragen Sie im Menü Schüler > Daten 2 im Bereich "Bereits besuchte Schule" die zuletzt besuchte Klasse ein. Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie die Eingabe im Feld "Letzte Klasse" vornehmen.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0299)** `Schüler > Daten 2 > Bereits besuchte Schulen > Herkunftsschule`

Tragen Sie im Menü `Schüler > Daten 2`  im Bereich "Bereits besuchte Schulen" die Herkunftsschule ein. Grundlage bilden die bereits erfassten Schulen im Menü Schulen.

**(A0595)** `Schüler > Daten 2 > Zugang > externe Empfehlung`

Tragen Sie im die Empfehlung des Schülers im Menü `Schüler > Daten 2` im Bereich "Zugang" im Feld „externe Empfehlung“ ein. Grundlage bildet das Schlüsselverzeichnis > Empfehlungen.

## Schüler mit Herkunftsschulen.rpt

## Schüler-Abi (Antrag mündliche Prüfung).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

## Schüler-Abschlussbericht(Schulabgänger).rpt

**(A0018)** `Schueler > Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü `Schüler > Daten 2` im Feld "Zugang am" bzw. "Abgang am" ein.

**(A0023)** `Schüler > Daten 3 > 1./2./3./4. Fremdsprache`

Tragen Sie im Menü Schüler > Daten 3 beim entsprechenden Schüler die Fremdsprache im aktuellen Zeitraum unter "Fremdsprachenfolge" ein. Damit Ihnen hier Fremdsprachen im Auswahlmenü
angeboten werden, müssen Sie unter `Schlüsselverzeichnis > Fächer` im Feld "Kategorie" aus dem Pull-Down-Menü "Fremdsprache" zugewiesen haben.

**(A0028)** `Schüler > Zeugnis > Fächer > Position`

Für die Sortierung der Fächer auf den Zeugnissen muss im Menü `Schüler > Zeugnis > Fächer` pro Fach eine Position in der Spalte "Position" angegeben werden. Bei der Ausgabe der Fächer auf dem Zeugnis werden die geraden Positionen in der rechten Spalte und die ungeraden Positionen in der linken Spalte ausgegeben. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis der
Fachtafeln unter `Schlüsselvezeichnis > Fachtafeln` die Zeugnisposition zuweisen können. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Position nicht pro Schüler und pro Fach vornehmen.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0463)** `Schüler > Laufbahn > Abschluss > Abschluss 1`

Den Abschluss des Schülers tragen Sie im Menü Schüler > Laufbahn > Abschluss im Feld  „Abschluss1“ ein. Grundlage bildet das `Schlüsselverzeichnis > Abschlüsse (intern)`.

**(A0464)** `Schüler > Zeugnis > Fächer`

Der Abschlussbericht für Schulabgänger gibt aus dem Menü `Schüler > Zeugnis > Fächer` folgende Daten aus, die entsprechend in MAGELLAN eingetragen werden müssen:

* Klasse
* Schuljahr und Halbjahr
* Fachkürzel
* Kürzel Fachstatus
* Kürzel Unterrichtsart
* Note
* Lehrer

## Schülerausweis ABS (52 X 74).rpt

Schülerausweis - Format DIN A8 (52mm Höhe und 74mm Breite)**

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

## Schülerausweis ABS.rpt

## Schülerausweis BBS.rpt

## Schülerausweis ohne Photo.rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0723)** `Schüler > Daten 4 > Sonstige Daten > Schülerausweis > gültig bis`

Die Gültigkeit des Schülerausweises tragen Sie im Menü `Schüler > Daten 4 > Sonstige Daten` im Bereich "Schülerausweis" im Feld "gültig bis" ein.

## Schülerkarteikarte (DIN A5).rpt

**(A0018)** `Schueler >Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü Schüler > Daten 2 im Feld "Zugang am" bzw. "Abgang am" ein.

**(A0050)** `Schüler > Daten 1 > Familie`

Tragen Sie im aktuellen Zeitraum im `Schüler > Daten 1 > Familie`  die Sorgeberechtigten des Schülers ein. Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie einen
Sorgeberechtigten zuweisen, neu anlegen oder ändern. Grundlage bildet das Menü Sorgeberechtigte. Für den Zeugnisdruck sind nur die Sorgeberechtigten, die unter `Schüler > Familie` im Feld "Benachrichtigung"
"immer" enthalten, relevant.

**(A0075)** `Klassen > Daten > Kürzel`

Im entsprechenden Zeitraum muss im Menü Klassen > Daten im Feld "Kürzel" die Klasse angeben.

## Schülerkarteikarte.rpt

* Sorgeberechtigte/r  muss unter Benachrichtigung „immer“ haben. 
* Zug Nr. unter Merkmal A1 auf der Registerkarte Schüler in  Magellan eintragen.

**(A0050)** `Schüler > Daten 1 > Familie`

Tragen Sie im aktuellen Zeitraum im `Schüler > Daten 1 > Familie`  die Sorgeberechtigten des Schülers ein. Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie einen
Sorgeberechtigten zuweisen, neu anlegen oder ändern. Grundlage bildet das Menü Sorgeberechtigte. Für den Zeugnisdruck sind nur die Sorgeberechtigten, die unter `Schüler > Familie` im Feld "Benachrichtigung"
"immer" enthalten, relevant.

## Schülerliste ( Klasse, Geburtsdaten, Adresse, Telefon).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

## Schülerliste ( Klasse, Geburtsdaten, Konfession, Geschlecht).rpt

## Schülerliste ( Klasse, Tutor, Merkmal B1, B2, B3, B4).rpt

## Schülerliste (Anwesenheit Ags).rpt

**(A0006)** `Extras > Schlüsselverzeichnisse > Zeiträume > Ausdruck 1`

Die Ausgabe des Schulhalbjahres erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN unter `Extras > Schlüsselverzeichnisse > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte "Ausdruck1".

**(A0019)** `Extras > Schlüsselverzeichnisse > Unterrichtsarten`

Die korrekte Ausgabe der Zeugnisbereiche wird im Menü `Schüler > Zeugnis > Fächer` im Feld "Unterrichtsart" ausgewählt. Grundlage bildet das Schlüsselverzeichnis Unterrichtsarten. Für den Zeugnisdruck ist dabei nur der Schlüssel der Unterrichtsart relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis Fachtafeln die Unterrichtsart zuweisen können. Wenn Sie dann
den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe der Unterrichtsart nicht pro Schüler und pro Fach vornehmen.
Folgende Unterrichtsarten dürfen im Zeugnisdruck verwendet werden:

**(A0019.33)** Unterrichtsart Werte

Kürzel | Schlüssel | Zeugnisbereich
--|--|--
AG | AG | Arbeitsgemeinschaft

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

## Schülerliste (Bafög).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0442)** `Schüler > Daten 4 > Finanzielle Förderung > erhält Bafög bis`

Falls der/die Schüler/in Bafög erhält, markieren Sie im Menü Schüler > Daten 4 im Bereich "Finanzielle Förderung" das Options-Feld "erhält Bafög bis".

## Schülerliste (Einschulmerkmal1 sortiert nach Bewerber-Gesamtnote, Punkte, HF-Note).rpt

zeigt im Schülermenü BewerbernotePunkte und Hauptfachnote an

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0550)**Sonstiges

Der Bericht ermöglicht Ihnen für bereits als Schüler übernommene Bewerber nachträglich, zum Beispiel für die Verwaltung von Wartelistenplätzen, die Bewerbungsnoten anzuzeigen. Der Bericht gruppiert die markierten Schülerdatensätze nach dem Einschulmerkmal 1 und sortiert innerhalb des Einschulmerkmals1 als nach der Bewerbergesamtnote, anschließend nach den Bewerbungspunkten und als letztes nach der Hauptfachnote.

## Schülerliste (Fehlzeiten nach Klasse gruppiert).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0688)** `Schüler > Auswahl > Fehlzeiten`

Die Fehlzeiten des Schülers tragen Sie im Menü Schüler > Auswahl ein. Markieren Sie den gewünschten Schüler mit der Maus und betätigen die rechte Maustaste, wählen Sie hier „Fehlzeiten“ oder wahlweise Strg + F. Es öffnet sich ein Dialog, wo Sie die Fehlzeiten des Schülers zuordnen können. Grundlage für das Erfassen der Fehlgründe bildet das `Schlüsselverzeichnis > Fehlgründe (Schüler)`.

## Schülerliste (Fehlzeiten nach Schüler gruppiert).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0688)** `Schüler > Auswahl > Fehlzeiten`

Die Fehlzeiten des Schülers tragen Sie im Menü `Schüler > Auswahl` ein. Markieren Sie den gewünschten Schüler mit der Maus und betätigen die rechte Maustaste, wählen Sie hier „Fehlzeiten“ oder wahlweise Strg + F. Es öffnet sich ein Dialog, wo Sie die Fehlzeiten des Schülers zuordnen können. Grundlage für das Erfassen der Fehlgründe bildet das `Schlüsselverzeichnis > Fehlgründe (Schüler)`.

## Schülerliste (Förderung).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0702)** `Schüler > Daten 4 > Beeinträchtigung und Fördermaßnahmen`

Falls der/die Schüler/in eine Förderung erhält, tragen Sie im Menü `Schüler > Daten 4` im Bereich "Beeinträchtigung und Fördermaßnahmen" im Feld „Förderung“ die entsprechende Förderung ein. Grundlage bildet das `Schlüsselverzeichnis > Förderungen`.

## Schülerliste (gruppiert nach Berufen mit Wohnort).rpt

**(A0036)** `Schüler > Ausbildung > Ausbildungbetriebe > Beruf`

Tragen Sie im Menü `Schüler > Ausbildung` im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Beruf" den Beruf ein. Grundlage bildet das Schlüsselverzeichnis Berufe.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

## Schülerliste (gruppiert nach Berufen).rpt

**(A0036)** `Schüler > Ausbildung > Ausbildungbetriebe > Beruf`

Tragen Sie im Menü `Schüler > Ausbildung` im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Beruf" den Beruf ein. Grundlage bildet das Schlüsselverzeichnis Berufe.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

## Schülerliste (gruppiert nach Betrieben).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0434)** `Schüler > Ausbildung > Ausbildungsbetriebe`

Tragen Sie den Betrieb im Menü `Schüler > Ausbildung` unter Ausbildungsbetriebe ein.

## Schülerliste (gruppiert nach Bildungsgängen).rpt

**(A0037)** `Schüler > Ausbildung > Ausbildungbetriebe > Bildungsgang`

Tragen Sie im Menü `Schüler > Ausbildung` im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Bildungsgang" ein. Grundlage bildet das Schlüsselverzeichnis Bildungsgänge.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

## Schülerliste (Klasse, Geburtsdatum und Geburtsland).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0613)** `Schüler > Daten 1 > Geburtsland`

Weisen Sie dem Schüler im Menü `Schüler > Daten > Geburtsland` das Geburtsland zu. Grundlage bildet das `Schlüsselverzeichnis > Staatsangehörigkeiten`.

## Schülerliste (mit Betrieben und Geburtsdatum).rpt

**(A0036)** `Schüler > Ausbildung > Ausbildungbetriebe > Beruf`

Tragen Sie im Menü `Schüler > Ausbildung` im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Beruf" den Beruf ein. Grundlage bildet das Schlüsselverzeichnis Berufe. 

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0228)** `Schüler > Ausbildung > Ausbildungsbetriebe > Beruf `

Tragen Sie im Menü Schüler > Ausbildung > Beruf  im Feld "Ausbildung" den Beruf des Schülers ein.

**(A0434)** `Schüler > Ausbildung > Ausbildungsbetriebe`

Tragen Sie den Betrieb im Menü `Schüler > Ausbildung` unter Ausbildungsbetriebe ein.

**(A0435)** `Schüler > Ausbildung > Ausbildungsbetriebe > Ausbilderkontakt`

Tragen Sie den Ausbilder im Menü `Schüler > Ausbildung` beim zugewiesenen Ausbildungsbetrieb im Feld  "Ausbilderkontakt" ein.

## Schülerliste (mit Betrieben).rpt

Schüler mit ihren Betrieben 

**(A0036)** `Schüler > Ausbildung > Ausbildungbetriebe > Beruf`

Tragen Sie im Menü Schüler > Ausbildung im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Beruf" den Beruf ein. Grundlage bildet das Schlüsselverzeichnis Berufe. 

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0228)** `Schüler > Ausbildung > Ausbildungsbetriebe > Beruf`

Tragen Sie im Menü `Schüler > Ausbildung > Beruf` im Feld "Ausbildung" den Beruf des Schülers ein.

**(A0434)** `Schüler > Ausbildung > Ausbildungsbetriebe`

Tragen Sie den Betrieb im Menü `Schüler > Ausbildung` unter Ausbildungsbetriebe ein.

**(A0435)** `Schüler > Ausbildung > Ausbildungsbetriebe > Ausbilderkontakt`

Tragen Sie den Ausbilder im Menü `Schüler > Ausbildung` beim zugewiesenen Ausbildungsbetrieb im Feld  "Ausbilderkontakt" ein.

## Schülerliste (mit Praxisbetrieben und Geburtsdatum).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0525)** `Schüler > Ausbildung > Ausbildungsbetriebe > Praxisbetrieb`

Tragen Sie den Praxisbetrieb im Menü `Schüler > Ausbildung` im Bereich „Ausbildungsbetriebe“ ein. Wenn Sie die Schaltfläche "+" oder "Editieren" anklicken, können Sie einen Ausbildungsbetrieb zuweisen bzw. bearbeiten. Im Feld "Praxisbetrieb" hinterlegen Sie den Betrieb.

**(A0543)** `Schüler > Ausbildung > Ausbildungsbetriebe > Praxisbetrieb`

Tragen Sie den Betrieb des Praktikums im Menü `Schüler > Ausbildung` im Bereich „Ausbildungsbetriebe“ ein. Wenn Sie die Schaltfläche "+" oder "Editieren" anklicken, können Sie einen Ausbildungsbetrieb zuweisen bzw. bearbeiten. Im Feld "Praxisbetrieb" hinterlegen Sie den Betrieb. Erfassen Sie ebenso die "Praktikumsdauer", die "Praxis von" und die "Praxis bis" sowie den "Praxis Kontakt".

## Schülerliste (mit Prüfungsfächern inkl. Lehrer).rpt

**(A0015)** `Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das Schlüsselverzeichnis > Fachstatus. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.
Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

**(A0015.61)** Fachstatuswerte

Kürzel | Schlüssel | Zeugnisbereich
--|--|---
1PF | 1PF | 1. Prüfungsfach
2PF | 2PF | 2. Prüfungsfach
3PF | 3PF | 3. Prüfungsfach
4PF | 4PF | 4. Prüfungsfach
Pflicht | Pflicht | Pflichtunterricht
Projekt | Projekt | Projekt
WahlPF | WahlPF | Wahlpflichtunterricht
ZusatzK | ZusatzK | Zusatzunterricht

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

## Schülerliste (mit Sorgeberechtigten deutsch).rpt

**(A0542)** `Schüler > Daten 1 > Familie`

Tragen Sie im aktuellen Zeitraum im `Schüler > Daten 1 > Familie`  die Sorgeberechtigten des Schülers ein. Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie einen
Sorgeberechtigten zuweisen, neu anlegen oder ändern. Grundlage bildet das Menü Sorgeberechtigte. 

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0150)** `Allgemein > Systemdatum`

Auf dem Zeugnis/Bericht wird das Systemdatum ausgegeben.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

## Schülerliste (mit Sorgeberechtigten französisch).rpt

**(A0542)** `Schüler > Daten 1 > Familie`

Tragen Sie im aktuellen Zeitraum im `Schüler > Daten 1 > Familie`  die Sorgeberechtigten des Schülers ein. Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie einen
Sorgeberechtigten zuweisen, neu anlegen oder ändern. Grundlage bildet das Menü Sorgeberechtigte. 

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0150)** `Allgemein > Systemdatum`

Auf dem Zeugnis/Bericht wird das Systemdatum ausgegeben.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

## Schülerliste (mit Sorgeberechtigten).rpt

Menü `Schüler > Daten1 > Familie`

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0131)** `Schüler > Zeugnis > Details > Tutor`

Der Tutor muss im entsprechenden Zeitraum im Menü Schüler > Zeugnis > Details beim jeweiligen Schüler im Feld "Tutor" hinterlegt werden.

**(A0150)** `Allgemein > Systemdatum`

Auf dem Zeugnis/Bericht wird das Systemdatum ausgegeben.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0050)** `Schüler > Daten 1 > Familie`

Tragen Sie im aktuellen Zeitraum im `Schüler > Daten 1 > Familie`  die Sorgeberechtigten des Schülers ein. Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie einen
Sorgeberechtigten zuweisen, neu anlegen oder ändern. Grundlage bildet das Menü Sorgeberechtigte. Für den Zeugnisdruck sind nur die Sorgeberechtigten, die unter `Schüler > Daten1 > Familie` im Feld "Benachrichtigung"
"immer" enthalten, relevant.

## Schülerliste (Nachprüflinge).rpt

**(A0025)** `Schüler > Laufbahn > Abschluss`

Tragen Sie im Menü `Schüler > Laufbahn > Abschluss` im aktuellen Zeitraum das Abschlussdatum im Feld "Abschluss 1" ein. Entscheidend ist hierbei die Markierung des Zeitraumes im linken Zeitraumfenster.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0463)** `Schüler > Laufbahn > Abschluss > Abschluss 1`

Den Abschluss des Schülers tragen Sie im Menü `Schüler > Laufbahn > Abschluss` im Feld  „Abschluss1“ ein. Grundlage bildet das `Schlüsselverzeichnis > Abschlüsse (intern)`.

## Schülerliste (Tagebuch mit Betrieben).rpt

**(A0228)** `Schüler > Ausbildung > Ausbildungsbetriebe > Beruf`

Tragen Sie im Menü `Schüler > Ausbildung > Beruf` im Feld "Ausbildung" den Beruf des Schülers ein.

## Schülerliste (zeitraumübergreifende Fehlzeiten).rpt

**(A0013)** `Schueler > Zeugnis > Details > Fehltage und/oder Fehlstunden`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern "Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0156)** `Schüler > Zeugnis > Details > Versäumnisse`

Tragen Sie die "Verspätungen" im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` im Feld "Versäumnisse" ein.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

## Schülerliste mit Behinderungsarten.rpt

## Schülerliste mit Photos.rpt

## Schülerpersonalblatt (A5 - Laufbahn).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0322)** `Schüler > Daten 2 > Abgang > Abgangsart`

Tragen Sie die Abgangsart im Schüler > Daten 2 im Bereich "Abgang" im Feld "Abgangsart" ein. Grundlage für das Zuweisen einer  Abgangsart bildet das `Schlüsselverzeichnis > Abgangsarten (Schüler)`.

## Schülerpersonalblatt (mit Fremdsprachen)**A5.rpt

**(A0018)** `Schueler > Daten 2 > Zugang am und/oder Abgang am`

Tragen Sie das Zugangs- bzw. Abgangsdatum im aktuellen Zeitraum im Menü `Schüler > Daten 2` im Feld "Zugang am" bzw. "Abgang am" ein.

**(A0058)** `Schüler > Laufbahn > Abschluss > Abschluss 1`

Tragen Sie im aktuellen Zeitraum im Menü `Schüler > Laufbahn > Abschluss` die Abschlussbezeichnung unter "Abschluss 1" im Feld "Abschluss" ein. Grundlage hierfür bildet das `Schlüsselverzeichnis >  Abschlüsse (Intern)`.

## Schülerpersonalblatt (mit Fremdsprachenfolge).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0023)** `Schüler > Daten 3 > 1./2./3./4. Fremdsprache`

Tragen Sie im Menü Schüler > Daten 3 beim entsprechenden Schüler die Fremdsprache im aktuellen Zeitraum unter "Fremdsprachenfolge" ein. Damit Ihnen hier Fremdsprachen im Auswahlmenü
angeboten werden, müssen Sie unter `Schlüsselverzeichnis > Fächer` im Feld "Kategorie" aus dem Pull-Down-Menü "Fremdsprache" zugewiesen haben.

## Schülerpersonalblatt (mit Vorbildung und Herkunftsschule).rpt

**(A0050)** `Schüler > Daten 1 > Familie`

Tragen Sie im aktuellen Zeitraum im `Schüler > Daten 1 > Familie` die Sorgeberechtigten des Schülers ein. Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie einen
Sorgeberechtigten zuweisen, neu anlegen oder ändern. Grundlage bildet das Menü Sorgeberechtigte. Für den Zeugnisdruck sind nur die Sorgeberechtigten, die unter `Schüler > Familie` im Feld "Benachrichtigung"
"immer" enthalten, relevant.

**(A0054)** `Klassen > Daten > Schulform`

Tragen Sie im aktuellen Zeitraum im Menü `Klassen > Daten` die Schulform im Feld "Schulform" ein. Grundlage hierfür bildet das `Schlüsselverzeichnis > Schulformen`.

**(A0078)** `Klassen > Zeiträume > Zeitraum > Klassenleiter`

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü `Klassen > Zeiträume` bei der jeweiligen Klasse im Feld "Klassenleiter" eingetragen werden.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0211)** `Lehrer > Daten 2 > Dienstbez.`

Die Dienstbezeichnung des Schulleiters / Lehrers tragen Sie im Menü `Lehrer > Daten 2` im Feld "Dienstbez." ein. Grundlage für das Zuweisen einer Dienstbezeichnung bildet das `Schlüsselverzeichnis > Dienstbezeichnungen`.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0238)** `Schüler > Daten 2 > Höchster Abschluss > Abschluss`

Tragen Sie im Menü „Schüler“ im aktuellen Zeitraum auf der Registerkarte „Daten2“ unter „Höchster Abschluss ABS“ die Abschlussbezeichnung im Feld „Abschluss“ ein. Grundlage hierfür bildet das Schlüsselverzeichnis Abschlüsse (Extern).

**(A0277)** `Schüler > Daten 1 > Staatsangeh. 1`

Tragen Sie die Staatsangehörigkeit des Schülers im Menü `Schüler > Daten 1` im Feld "Staatsangeh. 1" ein.

**(A0299)** `Schüler > Daten 2 > Bereits besuchte Schulen > Herkunftsschule`

Tragen Sie im Menü `Schüler > Daten 2`  im Bereich "Bereits besuchte Schulen" die Herkunftsschule ein. Grundlage bilden die bereits erfassten Schulen im Menü Schulen.

**(A0443)** `Schüler > Daten 2 > bereits besuchte Schulen > Schulform`

Die "letzte Schulform" tragen Sie im Menü `Schüler > Daten 2` im Bereich "bereits besuchte Schulen" bei der zugewiesenen Schule im Feld "Schulform" ein. Grundlage bildet das `Schlüsselverzeichnis > Schulformen (Herkunft)`.

## Schülerpersonalblatt (mit Vorbildung).rpt

Schülerstammdaten Typ A 

## Schülerpersonalblatt (nur Eltern und Vorbildung).rpt

Schülerstammdaten Typ B 

## Schülerpersonalblatt (ohne Vorbildung)

DIN A5 Bescheinigungen auf 1 DIN A4 Seite 

## Schülerpersonalblatt incl. Schuleintritt (Betriebe -Querformat).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

## Schülerpersonalblatt incl. Schuleintritt (Betriebe).rpt

**(A0036)** `Schüler > Ausbildung > Ausbildungbetriebe > Beruf`

Tragen Sie im Menü `Schüler > Ausbildung` im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Beruf" den Beruf ein. Grundlage bildet das Schlüsselverzeichnis Berufe.

**(A0037)** `Schüler > Ausbildung > Ausbildungbetriebe > Bildungsgang`

Tragen Sie im Menü `Schüler > Ausbildung` im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Bildungsgang" ein. Grundlage bildet das Schlüsselverzeichnis Bildungsgänge.

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0434)** `Schüler > Ausbildung > Ausbildungsbetriebe`

Tragen Sie den Betrieb im Menü `Schüler > Ausbildung` unter Ausbildungsbetriebe ein.

**(A0525)** `Schüler > Ausbildung > Ausbildungsbetriebe > Praxisbetrieb`

Tragen Sie den Praxisbetrieb im Menü Schüler > Ausbildung im Bereich „Ausbildungsbetriebe“ ein. Wenn Sie die Schaltfläche "+" oder "Editieren" anklicken, können Sie einen Ausbildungsbetrieb zuweisen bzw. bearbeiten. Im Feld "Praxisbetrieb" hinterlegen Sie den Betrieb.

## Schülerpersonalblatt incl. Schuleintritt (mit Vorbildung).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

## Schülerpersonalblatt incl. Schuleintritt und -austritt (mit Vorbildung).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0273)** `Schlüsselverzeichnisse > Zeiträume`

Die Ausgabe des "von" - "bis" Datums des Zeitraumes ergibt sich aufgrund der Definition des aktuellen Zeitraums in MAGELLAN unter `Schlüsselverzeichnisse > Zeiträume`. Ausgegeben werden hierbei die Einträge in den Spalten „Von“ und "Bis".

**(A0274)** `Schlüsselverzeichnisse > Zeiträume > Ausdruck 1`

Die Ausgabe in der Spalte "Zeitraum" erfolgt aufgrund der Definition des aktuellen Zeitraums in MAGELLAN im `Schlüsselverzeichnisse > Zeiträume`. Ausgegeben wird hierbei der Eintrag in der Spalte „Ausdruck1“.

**(A0275)** `Schüler > Laufbahn > Allgemein > Zugang/Abgang`

Im entsprechenden Zeitraum muss im Menü `Schüler > Laufbahn` im Bereich "Allgemein" das Datum im Feld „Zugang“ und "Abgang" eingetragen sein.
Entscheidend ist hierbei die Markierung des Zeitraumes im linken Zeitraumfenster.

**(A0435)** `Schüler > Ausbildung > Ausbildungsbetriebe > Ausbilderkontakt`

Tragen Sie den Ausbilder im Menü `Schüler > Ausbildung` beim zugewiesenen Ausbildungsbetrieb im Feld  "Ausbilderkontakt" ein.

## Schülerstammblatt (Belegung der Arbeitsgemeinschaften).rpt

**(A0112)** Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü "Schüler" gedruckt werden.

**(A0015)** `Extras > Schlüsselverzeichnisse > Fachstatus`

Für die korrekte Ausgabe der Fächer in den entsprechenden Zeugnisbereichen müssen Sie im Menü `Schüler > Zeugnis > Fächer` den entsprechenden Fächern einen Fachstatus zuordnen. Für den Zeugnisdruck ist dabei nur der Schlüssel des Fachstatus relevant, das Kürzel kann beliebig gewählt werden. Bedenken Sie hierbei, dass Sie bereits im Schlüsselverzeichnis "Fachtafeln" den Fachstatus zuweisen können. Grundlage für das Zuweisen eines Fachstatus bildet das Schlüsselverzeichnis > Fachstatus. Wenn Sie dann den Schülern diese Fachtafeln zuweisen, müssen Sie die Angabe des Fachstatus nicht pro Schüler und pro Fach vornehmen.
Folgende Fachstati dürfen im Zeugnisdruck verwendet werden:

**(A0015.39)** Arbeitsgemeinschaften

Bitte legen Sie Ihre Arbeitsgemeinschaften unter `Schüsselverzeichnisse > Fächer` als Fachzeilen an. Verteilen Sie die Arbeitsgemeinschaften per Sammelzuweisung der Fachtafeln oder weisen sie direkt dem Schüler unter `Schüler > Zeugnis > Fächer` die entsprechenden Fächer der AGs zu. Weisen Sie die Fachzeilen bitte den Fachstatus AG. Legen Sie dazu den Fachstatus einmalig wie folgt an:

Kürzel | Schlüssel | Zeugnisbereich
--|--|---
AG | AG | Arbeitsgemeinschaft

## Schülerstammblatt BF 2seitig (mit Zensuren blanko).rpt

## Schülerstammblatt BGJ 2seitig (mit Zensuren blanko)rpt

## Schülerstammblatt BS 2seitig (mit Zensuren blanko).rpt

## Schülerstammblatt FO 2seitig (mit Zensuren blanko).rpt

## Schülerstammblatt FS 2seitig (mit Zensuren blanko).rpt

## Schülerstammblatt WG11 2seitig (mit Zensuren blanko).rpt

## Schülerstammblatt WG12-13 2seitig (mit Zensuren blanko).rpt

## Schülerüberweisung.rpt

## Unfallanzeige (in Word ausfüllbar).rpt

**(A0281)** `Mandanten > Daten 1 > Schulträger`

Tragen Sie im Menü `Mandanten > Daten 1` den Schulträger im Feld „Schulträger“ ein. Grundlage hierfür bildet das Schlüsselverzeichnis >Schulträger.

**(A0282)** `Adressen`

Um die Ausgabe des Empfängers zu gewährleisten, legen Sie die Adresse Ihrer Unfallkasse im Menü Adressen an. Weisen Sie der Unfallkasse das "Kürzel" "unfall" zu.

**(A0292)** `Sonstiges > Word`

Dieser Bericht enthält spezielle Textfelder, die Sie über Microsoft Word ausfüllen können. Gehen Sie dafür folgendermaßen vor:

1. Markieren Sie den zu druckenden Datensatz aus, gehen auf `Drucken > Berichte drucken > Bericht auswählen > Vorschau`. 
2. Wählen  Sie im folgenden Programmfenster die Schaltfläche „Bericht exportieren“
3. Wählen Sie  im Fenster „Format“ bitte  „MS Word“ und im Fenster „Ziel“ bitte „Anwendung“. Bestätigen Sie mit OK.
4. Der Bericht öffnet sich mit MS Word und Sie können die auszufüllenden Felder per Mausklick aktivieren und füllen.

## Unfallanzeige (mit Erläuterungen).rpt

**(A0050)** `Schüler > Daten 1 > Familie`

Tragen Sie im aktuellen Zeitraum im `Schüler > Daten 1 > Familie`  die Sorgeberechtigten des Schülers ein. Wenn Sie die Schaltfläche "Hinzufügen" oder "Editieren" anklicken, können Sie einen Sorgeberechtigten zuweisen, neu anlegen oder ändern. Grundlage bildet das Menü Sorgeberechtigte. Für den Zeugnisdruck sind nur die Sorgeberechtigten, die unter `Schüler > Familie` im Feld "Benachrichtigung" "immer" enthalten, relevant.

**(A0281)** `Mandanten > Daten 1 > Schulträger`

Tragen Sie im Menü `Mandanten > Daten 1` den Schulträger im Feld „Schulträger“ ein. Grundlage hierfür bildet das `Schlüsselverzeichnis > Schulträger`.

## Unfallanzeige.rpt

**(A0281)** `Mandanten > Daten 1 > Schulträger`

Tragen Sie im Menü Mandanten > Daten 1 den Schulträger im Feld „Schulträger“ ein. Grundlage hierfür bildet das `Schlüsselverzeichnis > Schulträger`.

**(A0282)** `Adressen`

Um die Ausgabe des Empfängers zu gewährleisten, legen Sie die Adresse Ihrer Unfallkasse im Menü Adressen an. Weisen Sie der Unfallkasse das "Kürzel" "unfall" zu.

## Unfallbericht.rpt

## Zeugnisliste nach Schülerfächern (Kopfnoten).rpt

**(A0009)** `Schueler > Zeugnis > Details > Zeugniskonferenz am`

Im entsprechenden Zeitraum muss das Datum der Zeugniskonferenz im Menü "Schüler" unter `Zeugnis > Details` im Feld "Zeugniskonferenz am" eingetragen sein.

**(A0013)** `Schueler > Zeugnis > Details > Fehltage und/oder Fehlstunden`

Die Angabe der Fehltage und/oder der Fehlstunden muss im entsprechenden Zeitraum im Menü `Schüler > Zeugnis > Details` in den Feldern "Fehltage", "davon unentschuldigt", "Fehlstunden" und "davon unentschuldigt" erfolgen.

**(A0014)** `Schueler > Zeugnis > Details > Verhalten und/oder Mitarbeit`

Die Noten für Mitarbeit und Verhalten tragen Sie im Menü `Schüler > Zeugnis > Details` in den Feldern "Mitarbeit" und "Verhalten" ein.

**(A0078)** `Klassen > Zeiträume > Zeitraum > Klassenleiter`

Der Klassenlehrer muss im entsprechenden Zeitraum im Menü `Klassen > Zeiträume` bei der jeweiligen Klasse im Feld "Klassenleiter" eingetragen werden.

**(A0100)** `Schüler > Zeugnis > Details > Zeugnisdatum`

Im entsprechenden Zeitraum muss das Zeugnisdatum im Menü `Schüler > Zeugnis > Details` im Feld "Zeugnisdatum" eingetragen sein.

**(A0188)** Ausdruck

Der Bericht muss aus dem Menü "Klassen" gedruckt werden.

**(A0224)** Ausdruck

Der Bericht muss aus über `Drucken > Bericht Drucken`(Strg + P) gedruckt werden.

**(A0346)** `Klassen > Zeiträume > Zeitraum > Klassenleiter 2`

Der stellv. Klassenlehrer muss im entsprechenden Zeitraum im Menü Menü `Klassen > Zeiträume` im Feld „Klassenleiter 2“ eingetragen werden.

**(A0634)** `Schüler > Auswahl > Zeugnisse drucken`

Die Fächer werden in der Kreuztabelle nach Position sortiert. Beachten Sie, dass die Fächer der Schüler einer Klasse im Menü Schüler > Zeugnis > Fächer im Feld "Posistion" alle die selbe Position haben müssen, da sonst die Fächer mehrfach ausgegeben werden.
