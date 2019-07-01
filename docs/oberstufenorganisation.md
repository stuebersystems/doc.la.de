

# Oberstufenorganisation



Die jeweiligen Verordnungen spiegeln sich über die Landesanpassung von MAGELLAN bzw. DAVINCI in der Fachwahlüberprüfung und der Abiturqualifikationsberechnung wider. 
Die Oberstufe stellt den schwierigsten Teil der Schulorganisation dar. MAGELLAN und DAVINCI stellen Funktionen für die gesamte Oberstufenorganisation zur Verfügung. Damit die Berechnungen korrekt durchgeführt werden können und Sie auch die Abiturzeugnisse richtig ausgedruckt bekommen, müssen Sie allerdings einige wenige aber wichtige Details beachten. Diese Details werden in diesem Kapitel erklärt. Lesen Sie es bitte sorgfältig.
Der Vollständigkeit halber sei an dieser Stelle erwähnt: Fachwahlüberprüfung und Abiturqualifikationsberechnung basieren auf offengelegten (Open Source) MAGELLAN-Skripten, die Sie mit Hilfe des MAGELLAN-Skripteditors bearbeiten können. 
>Eine Bearbeitung der mitgelieferten Skripte ist nicht notwendig und sollte von Ihnen auch nicht durchgeführt werden, da wir für veränderte Skripte keinen Support mehr leisten können.

Zur Oberstufenorganisation gehören folgende Aufgaben:
1.	Oberstufenjahrgänge und andere Stammdaten einrichten
2.	Schüler-Fachwahlen eingeben sowie Kursangebot und Kursblockungen erstellen
3.	Zulassung zur 12 überprüfen (nur in einigen Bundesländern)
4.	Qualifikation berechnen und Abiturzulassung überprüfen 
5.	Schriftliche Abiturnoten eingeben
6.	Mündliche Abiturnoten eingeben
7.	Gesamtqualifikation für Prüfungsbereich (Abiturnote) berechnen
8.	Fachhochschulreife berechnen
9.	Zeugnisbemerkungen eingeben und Zeugnisse drucken

Schritt 1 muss in DAVINCI und MAGELLAN durchgeführt werden. 

Schritt 2 wird in DAVINCI-Kursplan oder in MAGELLAN durchgeführt, alle weiteren Schritte ausschließlich in MAGELLAN. 

>Diese Dokumentation versteht sich als Ergänzung der landesspezifischen Besonderheiten zu den Standarddokumentationen für [**MAGELLAN**](http://doc.magellan6.stueber.de/) und [**DAVINCI**](http://doc.davinci6.stueber.de/), die ausführlich die Schritte beschreiben.


DAVINCI und MAGELLAN verfügen über sehr kompakte Funktionen für die gesamte Oberstufenorganisation und machen Ihnen so die Arbeit so leicht wie möglich. Es liegt leider in der Natur der Sache, dass zusätzlich von Ihrer Seite aus sehr gute Kenntnisse in der jeweiligen Oberstufenverordnung erforderlich sind.
In den folgenden Abschnitten werden die einzelnen Schritte in der Oberstufenorganisation mit DAVINCI und MAGELLAN erläutert.
Bevor wir mit der Fachwahlüberprüfung beginnen, müssen wir zunächst einige wichtige Bemerkungen zu Oberstufenjahrgängen, Fachkürzeln, Fachkategorien, Aufgabenbereichen, Unterrichtsarten und Fachstatus machen.

## Oberstufenjahrgänge einrichten



Die Oberstufe besteht in der Regel aus den Jahrgängen 11, 12 und 13 (für das G8 Abitur lesen Sie bitte den Abschnitt „G8 Abitur". In MAGELLAN und DAVINCI sind Klassen und Jahrgänge gleichbedeutend.
In MAGELLAN werden die Schüler einer Klassen bzw. einem Jahrgang zugeordnet, indem sie eingeschult werden. Für jeden Schüler werden in MAGELLAN die entsprechenden Fächer bzw. Kurse mit den Noten (Punkten) erfasst. 

Eine Ausnahme bildet in der Regel die Oberstufe: Es ist effektiver die Schüler-Fachwahlen der Oberstufenjahrgänge in DAVINCI-Kursplan einzugeben, da DAVINCI-Kursplan dafür speziell optimiert wurde. In DAVINCI-Kursplan können Sie über „Extras|Aktualisieren“ die Fachwahlen dann nach MAGELLAN übertragen.


## Oberstufenjahrgänge in DAVINCI


In DAVINCI definieren Sie in den DAVINCI-Stammdaten die Klassen. Sie können eine Jahrgangsstufe in Klassen aufteilen (11a, 11b usw) oder pro Klassenstufe nur eine Klasse eingeben - wichtig ist, dass über das Feld `Stufe` der Jahrgang zugeordnet wird. Damit sind klassenübergreifende Kurse innerhalb eines Jahrgangs und auch jahgangsüerbgreifende Kurse abbildbar.

![Einrichten der Klassen in DAVINCI](/assets/images/klassen_davinci.jpg)

##Oberstufenjahrgänge in MAGELLAN

In MAGELLAN werden die Daten halbjahresbezogen abgelegt. Sie definieren also drei Klassen 11, 12 und 13 mit je zwei Zeiträumen bzw. Halbjahren. 
Folgende Angaben sind bei der Eingabe der Oberstufenjahrgänge neben den Halbjahren wichtig:

|Eingabefeld|Eingabe|
|--|--|
|Klassenart	|Oberstufenjahrgang (Leistungs- und Grundkurse) oder Oberstufenjahrgang (nur Kurse)|
|Jahrgang	|11, 12 oder 13 (pro Zeitraum der Klasse unter Klasse > Zeiträume > Zeitraum > Jahrgang notwendig)|
|Beurteilungsart|Benotung durch Punkte|

## G8-Klassen


Beim neuen Abitur Ende 12 anstatt Ende 13, dem sog. G8 Abitur, das aktuell in verschiedenen Bundesländern eingeführt wird, beginnt die Orientierungsstufe ein Jahr früher, also in der Jahrgangsstufe 10. 

Die Oberstufenjahrgänge sind also (10), 11 und 12. In MAGELLAN besteht die Registerkarte „Qualifikation“ in der Ansicht „Abitur“ standardmäßig aus den Jahrgängen 11, 12 und 13. Damit das Abiturskript und Anzeige korrekt sind, sollten Sie auf Folgendes beachten: 
Stellen Sie in MAGELLAN in der Ansicht „Klassen“ auf der Registerkarte``` „Daten“``` bei ```„Klassenart“``` unbedingt „Oberstufenjahrgang“ bei den Klassen  „11“ und „12“ ein, damit die Noten beim Synchronisieren (in der Ansicht „Abitur“) auch in den Abiturbereich übernommen werden. 

Für die Klasse 10 können Sie optional die Klassenart ```"Standard mit Oberstufensynchronisation"``` wählen. Bei dieser Auswahl würden in der Klasse 10 die Schüler ohne Fach- und Notendaten in den Bereich ```Abitur``` synchronisiert werden, um die Fachwahl  für 11, 12 ggfs. 13 unter ```Abitur > Fachwahl``` vorbereiten zu können.

Klicken Sie in der MAGELLAN Ansicht „Abitur“ in der Registerkarte „Qualifikation“ auf „Layout anpassen“ und verändern Sie die Spaltenüberschriften z.B. in „1.“, „2.“, …, „6.“ 

>Damit die Fachdaten und Noten bei G8- oder G9-Schülern in die korrekten Spalten auf der Qualifikati-onskarte übernommen werden, muss unter MAGELLAN|Verzeichnisse|Verordnungen|Jahrgang eine 10 (für G8) oder eine 11 oder nichts (für G9) angegeben werden

## Grundlegende Einstellungen

 
In den nachfolgenden Punkten wird allgemein beschrieben, welche Einstellungen zuvor im Programm gewählt werden sollen. Da diese pro Verordnung abweichen können, finden Sie die genauen Werte für Ihre Verordnung in den Abschnitten pro Bundesland.


In einigen Bundesländern muss bei der Berechnung der Gesamtqualifikation der Kursinhalt bzw. die Sportart beachtet werden. Dazu können Sie in MAGELLAN unter „Abitur“ auf der Registerkarte „Qualifikation“ in der Spalte „Merkmal“ bei Sport durch entsprechende Kürzel für jedes Qualifikationshalbjahr angeben, um welche Sportart es sich handelt. 

>Damit Sportarten vom Skript korrekt erkannt werden können, muss die korrekte Fachkategorie (Sport) im MAGELLAN Schlüsselverzeichnis „Fächer“ eingegeben werden und Sie müssendie korrekten Sportartenkürzel unter „Merkmal“ auf der Registerkarte „Abitur|Qualifikation“ eingeben 



>In einigen Abiturverordnungen muss Sport in „Theorie“ und „Praxis“ unterschieden werden. Auch dies geschieht durch entsprechende Angaben in der Spalte „Merkmale“.

Welche Fachkürzel und welche Sportarten-Kürzel Sie genau pro Verordnung verwenden müssen, können Sie in den jeweiligen Abschnitten pro Skript nachlesen.

### Sport


In einigen Bundesländern muss bei der Berechnung der Gesamtqualifikation der Kursinhalt bzw. die Sportart beachtet werden. Dazu können Sie in MAGELLAN unter „Abitur“ auf der Registerkarte „Qualifikation“ in der Spalte „Merkmal“ bei Sport durch entsprechende Kürzel für jedes Qualifikationshalbjahr angeben, um welche Sportart es sich handelt. 

>Damit Sportarten vom Skript korrekt erkannt werden können, muss die korrekte Fachkategorie (Sport) im MAGELLAN Schlüsselverzeichnis „Fächer“ eingegeben werden und Sie müssendie korrekten Sportartenkürzel unter „Merkmal“ auf der Registerkarte „Abitur|Qualifikation“ eingeben 



>In einigen Abiturverordnungen muss Sport in „Theorie“ und „Praxis“ unterschieden werden. Auch dies geschieht durch entsprechende Angaben in der Spalte „Merkmale“.

Welche Fachkürzel und welche Sportarten-Kürzel Sie genau pro Verordnung verwenden müssen, können Sie in den jeweiligen Abschnitten pro Skript nachlesen.

 ### Fachkürzel
 
 
Das Fachkürzel dient in MAGELLAN und DAVINCI in der Regel nur der schulinternen Bezeichnung. Für jedes Fach können Sie unter „Schlüssel“ den für etwaige landesspezifische Statistiken relevanten Statistikschlüssel eintragen. 

>Die Fächerkürzel werden in der Regel weder von der Fachwahlüberprüfung noch von den Abiturskripten beachtet. Für die Abiturqualifikation sind ausschließlich die Angaben unter „Fachkategorie“ und „Aufgabenbereich“ entscheidend. Sie bestimmen die Semantik des Fachkürzels „DE“, d.h. legen mit der Fachkategorie „Deutsch“ fest, dass „DE“ das Fach „Deutsch“ bezeichnet und nicht das beispielsweise auch vorhandene Fach „D“, das „Darstellende Künste“ kennzeichnen soll.

### Fachkategorien

Erst durch den Eintrag einer Fachkategorie unter ```Verzeichnisse > Fächer > Kategorie``` erkennt das Verordnungsskript das jeweilige Fach. Ein Fach ohne Kategorie kann nicht verarbeitet werden. Stellen Sie fest, dass einem Fach keine Kategorie zugewiesen wurde oder eine verkehrte verwendet wurde, genügt es die Kategorie im Verzeichnis Fächer abzuändern und das Verordnungsskript neu auszulösen.
Die Menge der Fachkategorien ist fest vorgegeben und kann nicht von Ihnen erweitert werden. Mit welcher Kategorie Ihr Verordnungsskript arbeitet, erfahren Sie im Abschnitt zum einzelnen Verordnungsskript. 

Folgende Fachkategorien stehen grundsätzlich zur Verfügung:


|Fachkategorie|
|--|
|Fremdsprachen|
|Religion/Ethik|
|Deutsch|
|Mathematik|
|Kunst|
|Musik|
|Sport|
|Informatik|
|Philosophie|
|Geschichte|
|Physik|
|Chemie|
|Biologie|
|Erdkunde|
|Sozialkunde|
|Wirtschaft|
|Politik|
|Darstellendes Spiel|
|Religion (evang.)|
|Religion (kath.)|
|Technik|
|Pädagogik|
|Sport-Theorie|
|BWL/RW|
|BWL/VWL|
|VWL|


### Aufgabenbereiche

 
Die korrekte Belegung prüft das Verordnungsskript (ggfs. vorab schon das Fachwahlskript) anhand der Zuweisung den Aufgabenbereichs pro Fach. Weisen Sie bitte unter ``Verzeichnisse > Fächer > Aufgabenbereich``` den Aufgabenbereich pro Fach zu.

|Abkürzung	|Bedeutung|
|--|--|
|sprachl.-lit.-künstlerisch	|sprachlich-literarisch-künstlerisches Aufgabenfeld|
|gesellschaftswiss.	|gesellschaftswissenschaftliches Aufgabenfeld|
|mathem.-nat.-techn.|	mathematisch-naturwissenschaftlich-technisches Aufgabenfeld|
|Religion	|Religion|
|Sport	|Sport|

### Spalte Merkmal



In MAGELLAN finden Sie in der Ansicht „Abitur“ auf der Registerkarte „Qualifikation“ die Spalte „Merkmal“. Sie dient dazu, für ein Fach bestimmte Merkmale einzutragen, die für den Ausdruck und die Abiturqualifikation verwendet werden können. Die meisten Abiturskripte beachten die Angaben in dieser Spalte nicht. 
Bitte beachten Sie hierzu auch den Abschnitt ["Sport"](grundlegende_einstellungen_sport.md)  .

### Unterrichtsarten


In MAGELLAN bzw. DAVINCI werden standardmäßig folgende Unterrichtsarten mitgeliefert. Bitte beachten Sie, dass für Berichte, Fachwahlüberprüfungen oder Abiturqualifikationen die Groß- und Kleinschreibweise bei „Schlüssel“ beachtet wird.

>Es können Unterrichtsarten in den Standardverzeichnissen fehlen, bitte prüfen Sie anhand der Beschreibung zu den einzelnen Skripten, welche Werte benötigt werden und legen Sie ggfs. im Verzeichnis an.

So rufen Sie in DAVINCI das Schlüsselverzeichnis „Unterrichtsarten“ auf:
1. Starten Sie das DAVINCI-Basismodul.
2. Klicken Sie auf „Extras|Schlüsselverzeichnisse|Unterrichtsarten“.

So rufen Sie in MAGELLAN das Schlüsselverzeichnis „Unterrichtsarten“ auf:
1.	Starten Sie MAGELLAN.
2.	Klicken Sie auf „Verzeichnisse|Weitere Schlüsselverzeichnisse“.
3.	Wählen Sie im Auswahlfenster „Unterrichtsarten“ und klicken Sie auf Bearbeiten“.

####standardmäßig mitgelieferte Unterrichtsarten


|Kürzel | Schlüssel| Bedeutung |
| -- | -- | -- |
| GK | GK | Grundkurs |
|Kurs	|Kurs	|Standardwert, d.h. Kurs bzw. Fach
|AG|	AG|	Arbeitsgemeinschaft, -gruppe|
|BL|	BL|	Besondere Lernleistung|
|BU	|BU	|Berufsbezogener Unterricht|
|BU-P|	BU-P|	Berufsbezogener Unterricht im Pflichtbereich|
|BU-WP	|BU-WP	|Berufsbezogener Unterricht im Wahlpflichtbereich|
|BÜ	|BÜ	|Berufsfeldübergreifender Lernbereich|
|FK	|FK	|Fundamentalkurs|
|FA	|FA	|Facharbeit|
|FP	|FP	|Fachpraxis|
|FP-GF	|FP-GF	|Fachpraxis Grundfach|
|FP-KF	|FP-KF	|Fachpraxis Kernfach|
|GF	|GF	|Grundfach|
|KF	|KF	|Kernfach|
|KursA	|KursA	|Fachleistungskurs A|
|KursB	|KursB	|Fachleistungskurs B|
|KursC	|KursC	|Fachleistungskurs C|
|KursE	|KursE|	E-Kurs|
|KursG	|KursG	|G-Kurs|
|LF	|LF	|Lernfeld|
|LG|	LG	|Lerngruppe|
|LK	|LK	|Leistungskurs|
|Modul	|Modul	|Modul|
|Modul-FÜ	|Modul-FÜ	|Modul fachübergreifend|
|Modul-FB|	Modul-FB	|Modul fachbezogen|
|PK	|PK	|Profilkurs|
|Theorie	|Theorie	|Theorie|
|Walhb|	Wahlb|	Wahlbereich|
|WPU1|	WPU1|	Wahlpflichtunterricht 1|
|WPU2|	WPU2|	Wahlpflichtunterricht 2|
|WPU3	|WPU3|	Wahlpflichtunterricht 3|
|WPU4	|WPU4	|Wahlpflichtunterricht 4|
|2x	|2x	|2fach gewertetes Fach|
|2xM	|2xM	|2fach gewertetes und mündliches Prüfungsfach|
|S	|S	|Schriftliches Prüfungsfach|
|SM	|SM	|Schriftliches und mündliches Prüfungsfach|
|M	|M	|Mündliches Prüfungsfach|


 ### Fachstatus
 
In MAGELLAN bzw. DAVINCI werden standardmäßig folgende Fachstatus mitgeliefert. Bitte beachten Sie, dass für Berichte, Fachwahlüberprüfungen oder Abiturqualifikationen die Groß- und Kleinschreibweise bei „Schlüssel“ beachtet wird.

>Es können Fachstatus in den Standardverzeichnissen fehlen, bitte prüfen Sie anhand der Beschreibung zu den einzelnen Skripten, welche Werte benötigt werden und legen Sie ggfs. im Verzeichnis an.

So rufen Sie in DAVINCI das Schlüsselverzeichnis „Fachstatus“ auf:
1. Starten Sie das DAVINCI-Basismodul.
2. Klicken Sie auf „Extras|Schlüsselverzeichnisse|Fachstatus“.

So rufen Sie in MAGELLAN das Schlüsselverzeichnis „Fachstatus“ auf:
1.	Starten Sie MAGELLAN.
2.	Klicken Sie auf „Verzeichnisse|Weitere Schlüsselverzeichnisse“.
3.	Wählen Sie im Auswahlfenster „Fachstatus“ und klicken Sie auf Bearbeiten“.


####standardmäßig mitgelieferte Fachstatus


|Kürzel | Schlüssel| Bedeutung |
| -- | -- | -- |
|1PF |1PF |1. Prüfungsfach | 
|2PF |2PF |2. Prüfungsfach  |
|3PF |3PF |3. Prüfungsfach  |
|4PF |4PF |4. Prüfungsfach  |
|Abgew| Abgew| Abgewählt  |
|AufgstGK| AufgstGK| Aufgestockter Grundkurs  |
|AusglK |AusglK |Ausgleichskurs  |
|Befreit| Befreit |Befreit  |
|Belegt |Belegt |Belegt  |
|Ersatz |Ersatz| Ersatz  |
|FörderK |FörderK| Förderkurs|  
|Freiw |Freiw |Freiwillig  |
|Mündl |Mündl |Mündlich  |
|Pflicht| Pflicht| Pflichtfach  |
|P-Modul| P-Modul |Pflichtmodul  |
|Projekt| Projekt |Projekt  |
|Standard| Standard| Standard|  
|Wahlb |Wahlb |Wahlbereich  |
|WahlPF |WahlPF| Wahlpflicht | 
|WP-Modul| WP-Modul |Wahlpflichtmodul  |
|ZusatzK |ZusatzK |Zuatzkurs  |


### Fortgeführte Fremdsprache


Auf der Schülerregisterkarte ```Daten 3 ```in MAGELLAN können Sie die Fremdsprachenfolge des jeweiligen Schülers eingeben. Für jede Fremdsprache können Sie dabei unter ```von ```und ```bis``` die Jahrgangsstufen angeben, in denen die Fremdsprache belegt wurde. Aus der Differenz ergibt sich für die Abiturskripte, ob es sich um eine fortgeführte Fremdsprache handelt. Eine fortgeführte Fremdsprache muss mindestens drei Jahre belegt worden sein.

Folgende MAGELLAN-Skripte berechnen die fortgeführte Fremdsprache bzw. verwenden diese Angaben:

* RLP-APO-BGY-1999
* RLP-APO-WG-1999

>Beachten Sie in MAGELLAN die Eingabe der korrekten Fremdsprachendauer. Andernfalls kann die Qualifikationsberechnung nicht korrekt arbeiten. Die Skripte, die nicht aufgeführt werden, verwenden diese Angaben nicht.

In der Fachwahlüberprüfung wird die Abdeckung der Aufgabenbereiche bzw. die Einhaltung der Kombinationsbedingungen geprüft und ggf. in der Spalten Bemerkung bzw. Schlüssel des Schüler-Fensters oder im Fachwahl-Fenster entsprechende Hinweise angezeigt.

Voraussetzung dafür ist, dass auf der Registerkarte „Fächer“ des „Stammdatenfensters“ die korrekten Angaben bei „Kategorie“ und „Aufgabenbereich“ gemacht wurden und auf der Registerkarte „Klassen“ des Stammdatenfensters die Stufe (11, 12 oder 13) in der gleichnamigen Spalte angegeben wurde. 

>Bei der Fachwahlüberprüfung werden derzeit keine über den Abiturzeitraum hinausgehenden Zeiträume geprüft, d.h. ob z.B. eine Fremdsprachenwahl aufgrund der Fremdsprachenfolge korrekt ist, die der Schüler in der Sekundarstufe I hatte.

## Verzeichnis Abschlussjahrgänge



Sie können in MAGELLAN unter ```Verzeichnisse > Abschlussjahrgänge``` Abschlussjahrgänge definieren. In unserem Fall ist dies ein Abiturjahrgang. Damit können Sie jedem Schüler in der Rubrik „Abitur“ den entsprechenden Abiturjahrgang zuordnen. 
Dieser Vermerk hat keinen Einfluss auf Abschluss- oder Qualifikationsberechnungen, sondern dient dazu, später alle Schüler eines bestimmten Abiturjahrgangs z.B. für Ausdrucke herausfiltern zu können und ist eine der Voraussetzungen zum Synchronisieren der Schüler in den Bereich ```Abitur```.

>Geben Sie bei der Definition des Abiturjahrgangs im Fenster Verzeichnisse der Abschlussjahrgänge unter „Kategorie“ unbedingt „Abitur“ an.


![Verzeichnis Abschlussjahrgänge](/assets/images/abschlussjahrgaenge.png)

## Verzeichnis Verordnungen



MAGELLAN ist überregional einsetzbar, insofern sind die doch recht unterschiedlichen Teile wie Abiturverordnungen, Fachwahlen, Zeugnisvorlagen usw. nicht fest im Programm integriert, sondern der Benutzer wählt aus, welche Bereiche er nutzt.
Welche Verordnungen (Abiturverordnung, Fachwahl) Sie verwenden möchten, definieren Sie in MAGELLAN unter ```Verzeichnisse > Verordnungen```. 

![Verzeichnis Verordnungen](/assets/images/verzeichnis_verordnungen.png)

Sie müssen für jeden Schüler die Abiturordnung angeben, die für ihn relevant ist. Dazu müssen Sie im Schlüsselverzeichnis Verordnungen die jeweilige Verordnung definieren. Klicken Sie dazu auf „Verzeichnisse|Verordnungen“ und geben Sie dort Verordnung wie folgt an:

|Spalte	|Bedeutung|
|--|--|
|Kürzel|	8-stellige Kurzbezeichnung der Verordnung (bitte beachten Sie Besonderheiten bei einzelnen Skripten s.u.)|
|Bezeichnung	|Bezeichnung der Verordnung|
|Kategorie|	Mögliche Eingaben sind Fachwahl, Berufsschule oder Abitur.|
|Gültig von	|Gültigkeitsdatum von, ohne Bedeutung für die Berechnung|
|Gültig bis	|Gültigkeitsdatum bis, ohne Bedeutung für die Berechnung|
|Skript|	Geben Sie hier den Namen des Skripts für diese Abiturprüfungs- oder Fachwahlordnung ein. Abiturskripte enthalten auch die Berechnung der Fachhochschulreife. Alle verfügbaren Skripte befinden sich im MAGELLAN-Verzeichnis SKRIPTE.|
|Typ	|Über Einträge im Typ wird zum Beispiel zwischen G8 und G9 unterschieden. Oder ob Sie Ihr Gymnasium den Schwerpunkt Technik (TG) oder Wirtschaft (WG) hat.  Was für Ihr Skript genau als Eintrag erwartet wird, lesen Sie bitte im Abschnitt zum Skript nach.|
|Ab Jahrgang	|Für G8-Jahrgänge wird der Wert 10 erwartet, für G9 eine 11. Durch den Eintrag werden beim Synchronisieren die Schülerdaten aus der 12 oder 13 in die Spalten der Qualifikationsphase übernommen. Für Skripte ohne G8/G9-Unterscheidung bleibt diese Spalte leer.|



## Qualifikationsüberprüfungen vorbereiten

![Menü Abitur](/assets/images/abiturmenue.png)

Für die Qualifikationsüberprüfungen müssen Sie folgende Daten definieren und je Schüler eingeben:
1. Abiturjahrgang definieren
2. Prüfungsordnung definieren
3. Schüler ins Menü Abitur synchronisieren, dabei Abiturjahrgang und Prüfungsordnung angeben
5. Je Schüler die Noten eingeben
6. Je Schüler die eingebrachten Kurse markieren

## Schüler ins Abitur synchronisieren



Mit der Aktion  ```Abitur > Qualifikation > Schüler synchronisieren``` werden die in den Halbjahren erfassten Fach- und Notendaten in auf die Qualifikationskarte kopiert. Damit die Daten korrekt in die Spalten kopiert werden können, müssen die nachstehenden Daten korrekt erfasst sein.

>Wenn Sie G8- und G9-Jahrgänge an Ihrer Schule haben, müssen Sie im Verzeichnis Verordnungen getrennte Zeilen anlegen. Tragen Sie in der Spalte "Ab Jahrgang" bitte 10 (für G8) oder 11 (für G9) ein. Synchronisieren Sie die Schüler bitte getrennt und weisen jeweils die Verordnungszeile zu. 


Die Schüler können für die **Fachwahl** in MAGELLAN oder für die **Abiturqualifikation** synchronisiert werden.
Bevor Sie die Fachwahl anlegen oder später die Abiturqualifikationen überprüfen können, müssen Sie die Daten der Schüler synchronisieren. Beim Synchronisieren geschieht Folgendes: 

MAGELLAN extrahiert für die markierten Schüler die Fachdaten der Halbjahre 11/1 bis 13/2. Dies ist die Voraussetzung dafür, dass die Qualifikations- und Abschlussberechnungen der Oberstufe durchgeführt werden können. Auch wenn Sie zuvor keine Fächer bzw. Punkte in den Oberstufenhalbjahren angegeben haben, müssen Sie diese Synchronisation einmal ausführen um die Schüler in das Abiturmenü zu übertragen.


Damit die Synchronisation klappt sind die folgenden Einstellungen wichtig:

|Voraussetzung | Anmerkung |
|--|--|
|Zeitraumart | Im Verzeichnis der Zeiträume muss das Feld „Art“ mit dem Wert „1. Halbjahr“ bzw. “2. Halbjahr“ gefüllt sein. |
 |Klassenart| Unter ```Klasse > Daten``` muss im Feld „Klassenart“ die Auswahl **Oberstufenjahrgang (Leistungs- und Grundkurse)** oder **Oberstufenjahrgang (nur Kurse) **getroffen sein. |
 ||Sie können auch die Art **Standardklasse mit Oberstufensynchronisation** wählen, hierbei werden aber lediglich die Schüler für den Punkt ```Abitur > Fachwahl``` übertragen, also keine Schülerfachdaten oder Leistungsdaten.|
|Jahrgang | Bei jeder Klasse/Jahrgang muss auf der Registerkarte „Zeiträume“ für jeden Zeitraum das Feld „Jahrgang“ mit dem Wert „11“, „12“ oder „13“ angegeben werden.| 
|Abschlussjahrgänge | Bitte legen Sie unter ```Verzeichnisse > Abschlussjahrgaenge..``` die Abschlussjahrgänge an. Es genügt dabei die Angabe des Kürzels, der Bezeichnung und der Kategorie (Abitur). |
 |Verordnungen | Richten Sie bitte unter ```Verzeichnisse > Verordnungen``` pro verwendeter Abiturverordnung oder Fachwahl eine Zeile entsprechend der Anleitung pro Skript an. Wichtig hierbei sind die Felder Typ und Jahrgang. **Für die Synchonisation von G8-Klassen muss der Jahrgang mit dem Wert "10" gefüllt werden.**|
 
 
 > Beim Synchronisieren werden die Noten aus der Spalte „Endnote“ in das Menü „Abitur“ übernommen.
 

![Daten fürs Abitur synchronisieren](/assets/images/abi_sync.jpg)

So synchronisieren Sie Schüler für die Abiturberechnung oder die Fachwahl:

Rufen Sie den Assistenten aus dem Menü ```Abitur``` auf der Karte ```Qualifikation``` über die Schaltfläche ```Schüler synchronisieren``` auf. Der Assistent bietet Ihnen alle Schüler zum Synchronisieren an, die sich in einer Klasse mit der Klassenart ```Oberstufenjahrgang``` befinden. Markieren Sie die Schüler und klicken auf ```Weiter```.
Auf der nächsten Karte wählen Sie bitte die ```Prüfungsordnung``` und den ```Abschlussjahrgang``` aus und klicken auf ```Weiter``` und ```Fertigstellen```.

![Assistent zum Schüler synchronisieren](/assets/images/abi_sync2.png)

Wechseln Sie nach dem Synchronisieren in den Menüpunkt ```Abitur``` auf die Unterkarte ```Auswahl```. Es werden alle synchronisierten Schüler angezeigt.

Per Doppelklick auf den gewünschten Schüler oder über einen Klick auf die Registerkarte ```Qualifikation``` wechseln Sie zur Abiturzulassung. Auf dieser Registerkarte finden Sie die Fächer und Notenwerte der Oberstufenhalbjahre, falls Sie diese Angaben bereits in MAGELLAN unter der Rubrik ```Schüler``` gemacht haben sollten. Andernfalls können Sie Fächer und Notenwerte für die Oberstufenhalbjahre auch hier eingeben.

Sollte die 11 in Ihrem Bundesland nicht in Leistungs- und Grundkursen unterrichtet werden, erscheinen die Fächer der besseren Übersicht wegen trotzdem unterschieden nach den Leistungs- und Grundkursen der Jahrgangsstufen 12 und 13. Intern macht MAGELLAN für die Noten der 11 keine Unterscheidung in Leistungs- und Grundkurse.


## Abitur nach G8 oder G9


Im Menü Abitur auf der Unterkarte Qualifikation werden je nach Verordnung die Spalten E1, E2, Q1-Q4 ausgewertet. 
Entscheidend ist bei der Synchronisation der Daten, dass die Halbjahresergebnisse der Schüler in die korrekte Spalte synchronisiert wird. Ausschlaggebend dafür ist der Eintrag unter ```Verzeichnisse > Verordnungen > Jahrgang```  beim Synchronisieren der Schüler. 

>Soll die Daten als G8-Daten erkannt werden, tragen Sie ```Verzeichnisse > Verordnungen > Jahrgang``` bitte eine 10 ein, für die Synchronisation als G9-Daten tragen Sie bitte ein 11 ein. Nach diesem Eintrag werden die Schülerergebnisse in unterschiedliche Spalten übertragen.

|Spalte auf der Karte ```Qualifikation``` |Synchronisation für G8|Synchronisation für G9|
|--|--|--|
|E1|eventuell 10.1 oder leer|11.1|
|E2|eventuell 10.2 oder leer|11.2|
|Q1|11.1|12.1|
|Q2|11.2|12.2|
|Q3|12.1|13.1|
|Q4|12.2|13.2|


>Haben Sie Schüler nach G8- und nach G9-System, legen Sie Ihre Verordnungszeile bitte doppelt an, tragen einmal 10 und einmal 11 in der Spalte ```Jahrgang``` ein und Synchronisieren Ihre Schüler getrennt und geben im Assistenten ```Synchronisiere Schüler ```die jeweils korrekte Verordnungszeile an.


![Beispiel für G8 und G9](/assets/images/g8_verordnung.jpg)








