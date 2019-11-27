# NRW-AS-APO-BK-1999

## Abschlussberechnung für Berufskollegs in Nordrhein-Westfalen

!!! danger "Achtung"

    MAGELLAN bietet die Möglichkeit eigene Skripte oder Bericht (mitunter auf der Grundlage von Veröffentlichungen von STÜBER SYSTEMS) zu entwickeln und einzusetzen. **Diese selbst erstellten Skripte und Berichte werden von uns nicht gepflegt, sondern lediglich veröffentlicht.** 
    Federführender Autor des Skriptes, der Berichte und der Dokumentation ist Heinz Kersting vom Berufskolleg Mitte TÜV NORD College.

Für Berufskollegs in Nordrhein-Westfalen steht ein von Anwendern entwickeltes Skript zur Verfügung, das Notendurchschnitte für verschiedene Bildungsgänge berechnet und auch Abschlüsse zuordnen kann. Gleichzeitig können die sich daraus ergebenen Zeugnisberichte (ebenfalls von Anwendern entwickelt), u.a. auch Zeugnisbemerkungen, den Schüler hinterlegt werden. In den folgenden Abschnitten beschreiben wir die dafür notwendigen Einstellungen.

## Zeugnisse zur Anlage A der BASS 2012/2013: Bildungsgänge der Berufsschule

Für das Bundesland Nordrhein-Westfalen stellen wir folgende Berichte der Anlage A der BASS 2012/2013 zur Verfügung.

* NRW-BBS-AG-AS-JZ-HZ (A01-A04).rpt
* NRW-BBS-JZ-HJ-AG-AS (A05-A06).rpt
* NRW-BBS-JZ-HJ-AG-AS (A07).rpt
* NRW-BS-AS (A01).rpt

## Verzeichnisse vorbereiten

Für die Notenvergabe und den Zeugnisdruck sind vorbereitend Werte in den Schlüsselverzeichnissen anzulegen.

* Unterrichtsarten
* Fachtafeln
* Dienstbezeichnungen
* Noten
* Bildungsgänge
* Fachthemen
* Verordnungen
* Schülermerkmale
* Zeugnisformulare
* Zeugnisbemerkungen
* Berufsfelder

## Unterrichtsarten definieren

In MAGELLAN 6 müssen unter ```Verzeichnisse > Weitere Schlüsselverzeichnisse > Unterrichtsarten``` die Unterrichtsarten wie folgt definiert sein. Entscheidend ist der Eintrag in der Spalte Kürzel. Das Kürzel wird in den Zeugnissen abgefragt und ordnet die Fächer dem entsprechenden Zeugnisbereich zu. Der eingetragene Schlüssel kann dagegen frei gewählt werden.

Kürzel |Bezeichnung
--|--
AS |Arbeits-und Sozialverhalten
AV |Arbeitsverhalten
BL |Besondere Lernleistung
BU |Berufsbezogener Bereich
BÜ |Berufsübergreifender Bereich
BU-P |Berufsbezogene Praxis
BU-T |Berufsbezogene Theorie
BU-WP| Berufsbezogener Unterricht im Wahlpflichtbereich
DB |Differenzierungsbereich
FB |Fachrichtungsbezogener Lernbereich
FE |Fachschulexamen
FH-P |Fachhochschulprüfung Fachschule
FK |Fundamentalkurs
FP-GF |Fachpraxis Grundfach
FP-KF| Fachpraxis Kernfach
FÜ| Fachrichtungsübergreifender Lernbereich
GF |Grundfach
GK |Grundkurs
KF |Kernfach
Kurs |Kurs
PR|Projektarbeit

## Fachtafeleinträge überprüfen

Unter ```Verzeichnisse > Fachtafeln``` müssen den Fächern die entsprechenden Unterrichtsarten zugewiesen werden. Der Gewichtungsfaktor der Fächer zur Durchschnittsberechnung ist in der Spalte Faktor einzutragen. In der Spalte Position weisen Sie den Fächern eine Positionsnummer für die spätere Ausgabe der Fächer innerhalb der Bereiche (wie Berufsbezogener Lernbereich, Berufsübergreifender Lernbereich, Differenzierungsbereich etc.) zu.

![Hier tragen Sie die Positionen in der Fachtafel ein.](/assets/images/nrw/nrw_fachtafel.png)

!!! info "Hinweis"

    Fachtafeleinträge können von DAVINCI nach MAGELLAN abgeglichen werden.

## Dienstbezeichnungen definieren

Unter ```Verzeichnisse > Weitere Schlüsselverzeichnisse > Dienstbezeichnungen``` müssen die genauen Dienstbezeichnungen eingetragen werden. Verwenden Sie die Werte in MAGELLAN unter ```Lehrer > Daten2 > Dienstbez```.

![Dienstbezeichnungen ](/assets/images/nrw/nrw_dienstbez.png)

## Noten definieren

Unter ```Verzeichnisse > Noten``` legen Sie die Notenstufen 1-6 an. Dabei weisen Sie den Noten in der Spalte Notenart „Notenwert“ zu. Um ein Fach mit einem bestimmten Füllwert (z.B. „abgewählt“) auf dem Zeugnis auszugeben, müssen Sie in der Spalte Notenart „Füllwert“ hinterlegen.

![Hier legen Sie die Punkte, Noten und Füllwerte fest.](/assets/images/nrw/nrw_noten.png)

Diese Vorgaben haben beispielweise für den Religionsunterricht auf der Registerkarte Ansicht ```Schüler > Zeugnis > Leistungen``` folgende Bedeutungen:

Eintrag in Spalte „Fach“|Eintrag in Spalte „Endnote“|Fach auf dem Zeugnis|Note auf dem Zeugnis
------------------------|---------------------------|--------------------|--------------------
Religion             |gut                     |Religion            |gut
Religion             |1.                      |Religion            |leer
Religion             |ab                         |Religion            |leer
Religion             |kein Eintrag               |Fach wird auf dem Zeugnis ausgeblendet|leer

## Bildungsgänge definieren und den Klassen bzw. Schülern zuweisen

Stellen Sie sicher, dass unter ```Verzeichnisse > Bildungsgänge``` die Einträge in den Spalten „Bezeichnung“ (für Schüler) und „Bezeichnung2“ (für Schülerinnen) angepasst sind.

Den Klassen sind die Bildungsgänge unter Ansicht ```Klassen > Daten 1 > Bildungsgang``` zuzuordnen. Bei Mischklassen müssen Sie für Schüler, deren Bildungsgang von der Klasse abweicht (nur bei diesen Schülern), unter Ansicht ```Schüler > Ausbildung``` einen Bildungsgang zuordnen.

## Fachthemen definieren

Für die Ausgabe von Lernfeldern auf dem Zeugnis müssen Sie diese im ```Verzeichnisse > Fachthemen``` anlegen. Voraussetzung dabei ist, dass die ersten 3 Ziffern der Klassenbezeichnung den Ausbildungsberuf bestimmen. Wenn Sie an Ihrer Schule eine andere Systematik für Klassenbezeichnungen haben, müssen Sie die Zeugnisformulare und die Fachthemen anpassen.

![Fachthemen ](/assets/images/nrw/nrw_fachthemen.png)

Hier erklärt für das Beispiel „EB- für Elektroniker für Betriebstechnik einschließlich der Doppelqualifikation“

* In der Spalte Kürzel sind die ersten 3 Zeichen mit der zugehörigen Fachtafel des Berufes identisch (z.B. EB- für Elektroniker für Betriebstechnik einschließlich der Doppelqualifikation).
* Zeichen 4-7 bezeichnen das Kürzel des Lernfeldes (z.B. LF01 für Lernfeld 1, LF02 für Lernfeld 2 etc.)
* Die Spalte Bezeichnung bezieht sich auf die Bezeichnung des Lernfeldes.
* Die Spalte Fach steht für zugehöriges Fach (z.B. EAA - Errichten und Betreiben automatisierter Anlagen).
* Die Spalte Position steht für Reihenfolge des Lernfeldes auf dem Zeugnisausdruck.
* Die Spalte Statistik-ID steht für Ausbildungsjahre, bei mehreren durch Komma getrennt, in denen das Lernfeld erteilt wird.

## Berechnungskript ablegen

Unter ```Verzeichnisse > Verordnungen``` müssen die Berechnungsskript(e) für die Abschlussberechnung hinterlegt sein. Aktuell gibt es das Skript mit der Bezeichnung NRW-AS-APO-BK-1999.dws für die folgenden Zeugnisarten:

* HZ für Halbjahreszeugnisse
* JZ für Jahreszeugnisse
* VZ für Versetzungszeugnisse
* AG für Abgangszeugnisse nach vorzeitigem Abbruch der Ausbildung
* AS für Abschlusszeugnisse
* AW für Abgangszeugnis für Schulwechsler
* ZB für Zwischenbeurteilungen

Das Skript NRW-AS-APO-BK-1999.dws muss nur einmalig vorhanden und sollte im Unterordner: ```….\MAGELLAN 6\Skripte\Nordrhein-Westfalen``` abgelegt sein.

!!! info "Hinweis"

    Bitte beachten Sie, das zum Ausführen den Skriptes NRW-AS-APO-BK-1999.dws Schulleitungs-, Sekretariats- oder Administrationsrechte notwendig sind, damit dem Schüler Abschlüsse unter ```Schüler > Laufbahn > Abschluss``` zugewiesen werden können.

## Verordnungen definieren

Für die Abschlussberechnungen der verschiedenen Zeugnisarten müssen Sie jeweils eine Verordnung unter ```Verzeichnisse > Verordnungen``` anlegen.

![Verzeichnis > Verordnungen](/assets/images/nrw/nrw_verordnung.png)

Entscheidend sind folgende Eintragungen:

Spalte |möglicher Wert
-------|--------------
Kürzel |hier stehen die ersten 2 Zeichen für die Zeugnisart:JZ, HZ, VZ, AG, ZB, AW, AS
Bezeichnung| bezieht sich auf die Bezeichnung der Zeugnisart
Kategorie|wählen Sie den Wert Versetzung aus
Typ |geben Sie das Kürzel der Zeugnisart ein
Skript|Das Berechnungsskript gilt für alle Zeugnisarten. Deshalb kann unter der Spalte Skript das gleiche Skript für alle Zeugnisarten zugeordnet werden.

## Schülermerkmale definieren

Im Verzeichnis ```Verzeichnisse > Merkmale > Schülermerkmale``` müssen als Weiteres die Merkmale A4 (z.B. BA-P -> Berufsabschluss nachgewiesen) und A5 (z.B. FH-P -> Fachhochschulprüfung bestanden) definiert werden. Die entsprechenden Merkmale sind in den Schülerstammdaten unter Ansicht ```Schüler > Merkmale``` nach Bedarf zuzuweisen.

![Schülermerkmale ](/assets/images/nrw/nrw_merkmale.png)

## Noten- bzw. Punktwerte vergeben

Wenn Sie Noten- bzw. Punktwerte vergeben möchten, weisen Sie diese den entsprechenden Fächern des Schülers unter Ansicht ```Schüler > Leistungen > Spalte „Endnote“``` zu. Bitten achten Sie darauf, dass das Optionsfeld Durchschnitt einblenden markiert ist. Wählen Sie auf der rechten Seite im dem Feld Prüfungsordnung den Eintrag aus, der zuvor unter ```Verzeichnisse > Verordnungen``` in den definierten Verordnungen für Halbjahreszeugnisse, Jahreszeugnisse, Versetzungszeugnisse, Zeugnisse nach Abbruch des Bildungsganges oder Abschluss/Abgangszeugnisse hinlegt ist.

![Hier geben Sie die Noten- bzw. Punktwerte ein und ordnen die Prüfungsordnung zu.](/assets/images/nrw/nrw_zeugnis.png)

## Zeugnisformulare definieren und den Schülern zuweisen

Unter ```Verzeichnisse > Zeugnisformulare``` können Zeugnisformulare definiert werden, die man auf der Registerkarte Ansicht ```Schüler > Zeugnis > Zeugnisformulare``` den Schülern zuweisen kann. Über das Drucken von Zeugnisformularen (```Bearbeiten > Drucken > Zeugnisformluare``` drucken) können diese ausgedruckt werden.

![Zeugnisformulare](/assets/images/nrw/nrw_zeugnisformular.png)

Das Berechnungsskript NRW-AS-APO-BK-1999.dws kann eine richtige Zuweisung der Zeugnisformulare zu den Schülern aufgrund der eventuell berechneten Abschlüsse und Bildungsgänge nur dann korrekt vornehmen, wenn die nachfolgende beschriebene Systematik beim Ausfüllen der Spalte Bezeichnung unter Verzeichnis-se|Zeugnisformulare eingehalten wird.

Relevant sind bei der Bezeichnung nur die Zeichen bis zu ersten Klammer. Im einen Zeugnisformular „z-A0112300-0A (Bergmech. ohne Abschluss o. LF)“ wären dies beispielsweise die Zeichen
„z-A0112300-0A “.

Suchdurchlauf|geprüfte Zeichen|Prüfung
--------------------------------------------------------------------|------|------
Suchdurchlauf 1| |Es werden die ersten 11 Zeichen der Bezeichnung geprüft auf folgende Eigenschaften
|1-8|Schlüssel des Bildungsganges (entsprechend der Angaben unter ```Verzeichnisse > Bildungsgänge```)
|9|Bindestrich –
|10-11| JZ für Jahreszeugnis  
|10-11| HZ für Halbjahreszeugnis oder
|10-11| VZ für Versetzungszeugnis oder
|10-11| AG für Abgangszeugnis von Schülern, die die Ausbildung vorzeitig abgebrochen haben oder
|10-11| AW für Schulwechsler in den gleichen Bildungsgang einer anderen Schule oder das 2-stellige Zeichen für die Abschlussart (entsprechend der Angaben unter ```Verzeichnisse > Bildungsgänge```, z.B. 3A für den Berufsschulabschluss, 0A Abgangszeugnis usw.)
Suchdurchlauf 2 wenn kein Zeugnisformular in Suchdurchlauf 1 gefunden wurde||Es werden die ersten 6 Zeichen der Bezeichnung geprüft auf folgende Eigenschaften
|1-3|Schulform/Schulgliederung entsprechend dem Schlüsselverzeichnis aus der Landesstatistik. Sie sind identisch mit den ersten 3 Zeichen der Spalte Schlüssel unter ```Verzeichnisse > Bildungsgänge```
|4-6| Entsprechen der Prüfung der Zeichen 9-11 im Suchdurchlauf 1
Suchdurchlauf 3, wenn kein Zeugnisformular in Suchdurchlauf 2 gefunden wurde||Es werden die ersten 4 Zeichen der Bezeichnung geprüft auf folgende Eigenschaften
|1-3| Erstes Zeichen der Schulgliederung entsprechend dem Schlüsselverzeichnis aus der Landesstatistik. Sie sind identisch mit den ersten 3 Zeichen der Spalte Schlüssel unter ```Verzeichnisse > Bildungsgänge```
|2-4|Entsprechen der Prüfung der Zeichen 9-11 im Suchdurchlauf 1
Suchdurchlauf 4, wenn kein Zeugnisformular in Suchdurchlauf 3 gefunden wurde||Falls weiterhin kein passendes Zeugnisformular gefunden wird, erfolgt die Abfrage nach den ersten 2 Zeichen. Diese Zeichen stehen für die Zeugnisart bzw. Abschlussart (Prüfung entspricht den Zeichen 10 – 11 im Suchdurchlauf 1)

!!! info "Hinweis"

    Die aufgrund dieser Suchsystematik gefundenen Zeugnisformulare werden den Schülern dann automatisch unter der Registerkarte Ansicht ```Schüler > Zeugnis > Zeugnisformulare``` zugeordnet.

![Hier finden die zugeordneten Zeugnisformulare des Schülers.](/assets/images/nrw/nrw_zeugnis_zuordnen.png)

## Beispiel für die Suchsystematik des Skripts

Ein Schüler hat Bildungsgang für Bergmechaniker (Bildungsgang mit dem Schlüssel A01123000) und soll ein Jahreszeugnis bekommen. In den Zeugnisformularen ist ein Zeugnisformular A0112300-JZ (Bergmechaniker Jahresz.) definiert.

Das Skript versucht nun ein passendes Zeugnisformular zuzuordnen. Der Suchdurchlauf 1 prüft im Verzeichnis der Zeugnisformulare, ob es ein Formular gibt, welches

* in den ersten 8 Zeichen den Wert A0112300 hat,
* beim 9. Zeichen den Wert – hat und
* beim Zeichen 10-11 den Wert JZ hat.

Dabei wird das Zeugnisformular A0112300-JZ (Bergmechaniker Jahresz.) gefunden.
Die weiteren Suchdurchläufe 2-4 entfallen, da ja ein Zeugnisformular gefunden wurde.
Das Zeugnisformular A0112300-JZ (Bergmechaniker Jahresz.) wird dem Schüler unter Ansicht ```Schüler > Zeugnis > Zeugnisformulare``` zugeordnet.

Sie können die Zeugnisformulare, die in einem Schuljahr zum ersten Mal benutzt wurden, in einem Unterverzeichnis anzulegen. In diesem Beispiel ist das Zeugnisformular im Unterverzeichnis ```„2011\ A-JZ-Teilzeitberufschüler-DQ 2HJ.rpt```“ hinterlegt, da es zum ersten Mal im Schuljahr 2011 verwendet wird.

Mit dem Skript ist es möglich, einem Schüler bzw. Schülerin mehrere Zeugnisformulare zuzuordnen. Beispielweise bekommen Schüler der Berufsfachschule mit dem Abschluss 5J ein Fachhochschulreifezeugnis und ein Berufsabschlusszeugnis. Dazu definieren Sie bitte im Verzeichnis der Zeugnisformulare zwei Zeugnisformulare (eines für Fachhochschulreife bei Abschluss 5J und eines für Berufsabschlusszeugnis bei Abschluss 5J), bei denen die Zeichen der Zeugnisformularbezeichnung bis zur ersten Klammer identisch sind. In diesem Fall ordnet die Suchsystematik dann auch beide Zeugnisformulare dem Schüler zu.

## Zeugnisformulare drucken

Über ```Drucken > Zeugnisformulare``` drucken werden dem Schüler bzw. Schülerin zugewiesene Zeugnisse gedruckt.

![Hier können Sie die bei den Schülern zugewiesenen Zeugnisformulare drucken.](/assets/images/nrw/nrw_zeugnis_drucken.png)

## Vordefinieren von Bemerkungstexten

Unter ```Verzeichnisse > Zeugnisbemerkungen``` können Bemerkungen für Zeugnisse vordefiniert werden. Die Bemerkungstexte können Platzhalter enthalten, die beim Ausdruck durch bestimmte Inhalte dynamisch ersetzt werden.

!!! info "Hinweis"

    Die Platzhalter sind in doppelt spitze Klammer zu setzen, bitte sehen Sie sich die nachfolgende Abbildung an.

Folgende Platzhalter stehen zur Verfügung:

Platzhalter |Im Zeugnisausdruck
------------|-------------------
&lt;&lt;Vorname&gt;&gt;     |Vorname der Schülerin/des Schülers wird ausgegeben
&lt;&lt;Nachname&gt;&gt; |Nachname der Schülerin/des Schülers wir ausgegeben
&lt;&lt;Herr&gt;&gt;  |Herr oder Frau
&lt;&lt;Herrn&gt;&gt;  |Herrn oder Frau
&lt;&lt;Er&gt;&gt;   |Er oder Sie

![Hier können Sie die Zeugnisbemerkungen inkl. der zuvor beschriebenen Platzhalter definieren.](/assets/images/nrw/nrw_zeugnisbem.png)

!!! info "Hinweis"

    Falls im angewählten Zeugnisformular die Bemerkung mit einem Unterbericht in Crystal Reports ausgegeben wird, sollte dort auch die Tabelle „Schüler“ eingebunden werden, damit Vorname, Nachname und Anrede korrekt ausgegeben werden

## Schulgliederung und Fachklasse festlegen

Im ```Verzeichnisse > Weitere Schlüsselverzeichnisse > Berufsfelder``` wird die Schulgliederung für Berufskollegs hinterlegt. Die Eintragungen wie z.B. Fachklassen/Fachhochschulreife (BS/FHR; TZ) werden in diesem Verzeichnis eingetragen. Bei der Schulgliederung handelt es sich um das Statistikfeld für Berufskollegs bestehend aus einem 3-stelligem Schlüssel, z.B. A01 für Auszubildende.

Der Bildungsgang wird durch die Fachklasse festgelegt. Die Fachklasse besteht aus einem 5-stelligen Schlüssel, z.B. 27500 für Industriekaufmann. Im ```Verzeichnisse > Weitere Schlüsselverzeichnisse > Bildungsgang``` werden die Fachklassen erfasst.

Dazu können pro Fachklasse die Fachrichtung, der Schwerpunkt und das Berufsfeld (Schulgliederung) eingetragen werden. Dieses Verzeichnis wird um ein weiteres Feld „Bezeichnung2“ zur Abbildung der Unterscheidung männlicher und weiblicher Fachklassenbezeichnungen ergänzt. In Spalte „Bezeichnung“ und Spalte „Bezeichnung2“ wird der Beruf erfasst. Die Fachklasse geben Sie entweder unter ```Schüler > Ausbildung > Ausbildung``` bzw. unter ```Klassen > Daten > Bildungsgang``` ein.

![Hier tragen Sie den Bildungsgang der Klasse ein.](/assets/images/nrw/nrw_bildungsgang.png)

In der obigen Abbildung ist als Beispiel der Klasse IB-1R2 der Ausbildungsberuf (Bildungsgang) Industriemechaniker zugeordnet. Wenn nun in dieser Klasse ein Schüler oder eine Schülerin mit dem Ausbildungsberuf Teilezurichter beschult wird, muss dieses Merkmal dem Schüler zugeordnet werden, und zwar in MAGELLAN unter Ansicht ```Schüler > Ausbildung > Ausbildung```.

Bei homogenen Klassen (d.h. alle Schüler haben den gleichen Bildungsgang bzw. Ausbildungsberuf) sollte der Bildungsgang nur der Klasse in MAGELLAN unter Ansicht ```Klassen > Daten > Bildungsgang``` zugeordnet werden.

Grundsätzlich gilt, dass beim Zeugnisdruck und in der Landesstatistik für die Zuordnung des Bildungsgan-ges/Ausbildungsberufes zuerst der Eintrag unter Ansicht ```Schüler > Ausbildung``` geprüft wird. Falls dort kein Eintrag vorhanden ist, wird der Bildungsgang/Ausbildungsberuf genommen, der unter Ansicht ```Klassen > Daten``` zugeordnet ist.

## Zeugnisse zur Anlage E der BASS 2012/2013: Bildungsgänge der Fachschule

Für das Bundesland Nordrhein-Westfalen stellen wir folgende Zeugnisse der Anlage E zur Verfügung:
• NRW-E01-6A-J (Fachschulabschluss +- FHR).rpt

## Fächer kennzeichnen

Die Fächer, die in die Berechnung der Durchschnittsnote für die Fachhochschulreife eingehen, sind unter Merkmal mit *) zu kennzeichnen. Diese Systematik wird auch für das Berechnungsskript NRW-AS-APO-BK-1999.dws für die Schulabschlüsse verlangt.

![Fächer für die Fachhochschulreife mit Sternchen im Merkmal kennzeichnen](/assets/images/nrw/nrw_merkmal_mit_stern.png)

## Änderungen

Nachstehend finden Sie erfolgte Änderungen für das Skript NRW-AS-APO-BK-1999.

!!! info "Hinweis"

    Federführender Autor des Skriptes und der Dokumentation ist Heinz Kersting vom Berufskolleg Mitte TÜV NORD College. 

### Version vom 23.06.2017

Fehler in der Abschlussberechnung für die Bildungsgänge A12/A13 korrigiert. Ein 5 oder 6 in Mathematik (M) wird nicht berücksichtigt, wenn ein Ausgleich in Naturwissenschaften (NW) vorliegt.

### Version vom 16.06.2017

Skript wurde an die Magellan-Version 6.5.X angepasst.

### Version vom 16.02.2017

#### Anlage A: Berechnung des FHR-Durchschnittes Bildungsganges A02 (‚Doppelquali‘)

Wird in diesen Bildungsgängen die FHR-Prüfung nach 3 Jahren und die Berufsabschlussprüfung nach 3.5 Jahren abgelegt kann es vorkommen, dass Beurteilungen für den Berufsschulabschluss und den FHR-Abschluss in Fächern unterschiedlich ausfallen. In diesem Fall können abweichende FHR-Noten in die Spalte `Endnote(gesamt)` eingetragen werden, diese werden dann für die FHR-Abschlussnote berücksichtigt.

Wird in der Spalte `Endnote(gesamt)` keine Note eingetragen, so werden wie bisher für die FHR-Abschlussnoten die Werte aus der Spalte Endnote genommen.

#### Anlage E: Fehler bei der Berechnung der Abschlüsse in der Fachschule bereinigt

Die Abschlussberechnung wurde überarbeitet, die Ausgabe der Kommentare wurde optimiert.

### Version vom 15.12.2015

Änderungen der APO-BK ab dem 1.8.2015 wurden eingearbeitet

#### Anlage A

Bei einer Berufsschulabschlussnote von mind. 2,5 wird die FOR mit der Berechtigung zum Besuch der gymnasialen Oberstufe zugewiesen. Dieses gilt nur für Schüler die nach dem 1.8.2015 eingeschult wurden.
Damit der neue Abschluss eingetragen werden kann muss in den Verzeichnissen `Abgangsarten` (Schüler) und `Abschlüsse (Intern)` der Abschluss 3G definiert werden.

Für Auszubildende in den Helferberufen nach § 66 BBiG wird mit dem Berufsschulabschluss der Hauptschulabschluss erworben, Berechnung wurde hinzugefügt. Dabei wird davon ausgegangen, dass die Fachklassenbezeichnung bei diesen Schülern mit dem Zeichen 8 beginnt.

Die Berechnung für die Bildungsgänge A12 und A13 wurde hinzugefügt. Für die Zuerkennung des Hauptschulabschlusses dieser Bildungsgänge muss die notwendige Stundentafel erfüllt sein, in Magellan wird das durch unter `Schüler > MerkmalA4` mit dem Kürzel HS-M dokumentiert.

#### Anlage B

Die Abschlussberechnungen für die Schulgliederungen B06, B07, B08, B09 und B10 wurde hinzugeführt. Die zu vergebenen Abschlüsse in den Schulgliederungen B08, B09 und B10 hängen auch davon ab welche Kurse in Mathe und Englisch besucht wurden (§ 6 Absatz 1 Anlage B). Dieses muss bei den Schülern mit dem Merkmal A5 eingestellt werden (Kürzel GK und EK, siehe unten). In dem untenstehenden Bild sind nochmal alle relevanten Merkmale für die Abschlussberechnung zusammengestellt.

![Verzeichnisse > Merkmale > Schüler ](/assets/images/hr.kersting/Verzeichnis.Merkmale.png)

#### Anlage E

Die Änderungen der Bezeichnungen für die Unterrichtsarten (Fachrichtungsübergreifender (Kürzel FÜ) in Berufsübergreifender (Kürzel BÜ) und Fachrichtungsbezogener (Kürzel FB) in Berufsbezogener (Kürzel BU) wird bei der Abschlussberechnung berücksichtigt.
Der FHR – Abschluss wird nun auch bei den Schülern vergeben die diesen Abschluss bereits besitzen (siehe VV zu § 16 allgemeiner Teil).
Bitte beachten Sie, dass bei der Berechnung der Abschlüsse alle Fächer des Bildungsganges eine Unterrichtsart mit dem Schlüssel-Wert  FÜ oder FB oder PR oder DB oder BU oder BÜ haben müssen, das Kürzel ist frei wählbar.
Für die Noten des Fachschulexamens ist bei der Unterrichtsart der Schlüssel FE zu wählen, für die Fachhochschulreifeprüfung der Unterrichtsart-Schlüssel FH-P.

### Version vom 18.06.2015

#### Abschlussberechnung Anlage C01

Schüler dieses Bildungsganges, die bereits die Fachhochschulreife oder die Hochschulreife besitzen, wird der Abschluss 5A zugewiesen wenn sie die Berufsabschlussprüfung bestehen. Bei diesen Schülern muss unter `Schüler > Daten 2 > Höchster Abschluss` ABS der Wert J oder K zugewiesen werden.

#### Abschlussberechnung Anlage A06 (BGJ)

Für den Abschluss 2F und 2G sind besondere Leistungen in den Fächern M, D und E notwendig. Diese Abschlüsse werden grundsätzlich nicht vergeben, wenn in einem von diesen 3 Fächern keine Note eingetragen ist.

### Version vom 08.09.2014

#### Berufsabschluss nach Landesrecht Anlage C01

Bei Schülern dieser Anlage kann es vorkommen, dass die Noten in einigen Fächern auf dem Fachhochschulreifezeugnis und dem Berufsabschlusszeugnis unterschiedlich sind.

Auszug aus der APO-BK, Anlage C:
VV zu § 26
26.1 zu Abs. 1
26.11In Fächern, in denen im Rahmen der Berufsabschlussprüfung nicht geprüft wurde, werden die Vornoten als Endnoten festgestellt. Die Prüfungsleistungen zum Erwerb der Fachhochschulreife werden bei der Festlegung der Endnoten berücksichtigt, wenn sie zu einer Verbesserung der Vornote führen. Die Endnoten sind die Zeugnisnoten.

Deshalb setzt das Berechnungsskript davon aus, dass die Noten für den FHR-Abschluss in der Spalte `Endnote` und die Noten für den Berufsabschluss unter der Spalte `Endnote (Gesamt)` eingetragen werden (Siehe Darstellung unten)

![Beispiel für Einträge](/assets/images/hr.kersting/beispiel.01.jpg)

Die Zeugnisformulare müssen dann auf die unterschiedlichen Felder zugreifen.
In der Praxis dürften unterschiedlichen Noten im gleichem Fach selten vorkommen. Das Skript wurde jetzt so geändert, dass die Abschlüsse auch dann richtig berechnet werden, wenn nur die Noten in der Spalte Endnote eingetragen werden. Die Noten für den Berufsabschluss werden dann bei der Berechnung der Abschlüsse auch aus dieser Spalte genommen. Für Schulen die weiterhin die beiden Spalten nutzen ändert sich nichts.

### Version vom 29.06.2014

Folgendes Problem wurde bei der Abschlussberechnung für die Berufsfachschule (Anlage B) gelöst:

Hintergrund ist folgendes:
Im § 3 Absatz 3 in der APO-BK hieß es z.B. noch 2009:
(3) Mit der Zulassung zur Berufsabschlussprüfung wird der mittlere Schulabschluss (Fachoberschulreife) erworben, wenn die entsprechenden Kurse in Englisch und Mathematik gemäß § 7 Abs. 2 mit jeweils mindestens ausreichenden Leistungen abgeschlossen wurden. In allen anderen Fällen wird mit der Zulassung zur Berufsabschlussprüfung der Hauptschulabschluss nach Klasse 10 erworben.
Für Schüler der Berufsfachschule mit einem Berufsabschluss nach Landesrecht musste man also zum Erreichen der Fachoberschulreife unter anderem in Mathematik und Englisch mit mindestens ausreichenden Leistungen abgeschlossen haben.

Diese Einschränkung gibt es nicht mehr, das wurde im Skript entsprechend angepasst.

### Version vom 18.03.2014

Für die Anlage E01 und E02 (Fachschule für Technik) mussten bisher für die Fächer, die in die Berechnung der Durchschnittsnote für die Fachhochschulreife eingingen, unter Merkmal „*)“ eingetragen werden.

Fächer mit dem Unterrichtsartenschlüssel FB, DB, FH-P und Fächern mit dem Schlüssel „E“, „PK“ und „D“ werden bei der Durchschnittsberechnung auch ohne Eintragung des Merkmales „*)“ bei der Durchschnittszensurberechnung berücksichtigt. Das alte Verfahren gilt weiter.

* Änderung zulässiger Notenkürzel: statt ‚M‘ für vom Religionsunterricht abgemeldet die Zeichen ‚ab‘ (entsprechend der Zeugnisformulare)
* Kommentare für die Voreinstellungen (Schalter) erweitert
* Wenn Noten mit dem Wert 0 (z.B. ab für vom Religionsunterricht abgemeldet, K für keine Benotung) wurden unter bestimmtem Bedingungen die Durchschnittsnoten falsch berechnet. Der Fehler ist behoben. Grundsätzlich werden jetzt Noten mit dem Wert 0 (einzutragen im Verzeichnis Noten) bei der Durchschnittsberechnung nicht berücksichtigt.

### Version vom 07.11.2013

Es wurde ein zusätzlicher Merker eingeführt:

* Merker Note PP (Note der praktischen Prüfung Anlage C)
* Die Kommentare zur Abschlussberechnung wurden optimiert.

### Version vom 02.09.2013

* Vorgaben für bestimmte Fächer-Schlüssel
Für die Berechnung von Schulabschlüssen sind die Leistungen in einigen Fächern wichtig. Dafür werden folgende Fächer zwischengespeichert:
Merker Note M (Mathematik)
Merker Note D (Deutsch)
Merker Note E (Englisch)
Merker Note PK (Politik)
Merker Note NW (Naturwissenschaften)
Merker Note PH (Physik)
Merker Note BB (berufsbezogene Praxis insgesamt im Berufsorientierungsjahr)

Abgefragt werden die Schlüsselwerte der Fächer, als Kürzel können schulspezifische Abkürzungen verwendete werden, z.B für das Fach Deutsch ‚DEU‘ als Kürzel, als Schlüssel muss ‚D‘ im Verzeichnis Fächer eingetragen werden.

* Neuer Schalter AendLeistungsanforderung
Wenn der Wert auf true gesetzt wird, wird das Feld Leistungsanforderungen in der Tabelle SchuelerZeitraeume entsprechend der Leistungen gefüllt (in Magellan unter `Schüler > Zeugnis > Details > Leistungsanforderungen` einzutragen).

* Neuer Schalter AendVersetzung
wenn der Wert auf true gesetzt wird, wird die Versetzungsentscheidung in der Tabelle SchuelerKlassen im Feld Versetzungsart eingetragen:
* Bei Versetzungszeugnissen nach Vorgabe der Zeugnisart (Rollbalken Prüfungsverordnung) bei der Zensureneingabe
* Bei Schüler der in der dualen Ausbildung werden alle Schüler mit einem Jahreszeugnis versetzt

* Fehler bei der Entscheidung, ob die Leistungsanforderungen erfüllt sind:
Bei der Schülern Anlage C und Schülern mit der Schulgliederung A02 wurden bei der Entscheidung über die Erfüllung der Leistungsanforderungen die Fächer Religion und Sport nicht berücksichtigt. Der Fehler wurde korrigiert.

* FHR-Abschluss in der Anlage C
Bei Schülern der Anlage C braucht das Bestehen der FHR – Prüfung unter Merkmale nicht mehr angegeben werden. Das Bestehen der FHR – Prüfung ergibt sich aus den eingetragenen Endnoten.

* Keine Beurteilung aus Krankheitsgründen
Wenn in für die Abschlüsse relevanten Fächern ein K eingetragen wird (K steht für ‚wegen entschuldigter Fehlzeiten kann keine Beurteilung erstellt werden‘) werden keine Abschlüsse erteilt.

### Version vom 5.6.2013

* Abschlüsse werden auch für die Bildungsgänge B01, B02, B03, B04 berechnet

* Das Datenfeld Leistungsanforderungen in der Tabelle SchuelerZeitraeume wird entsprechend der Verwaltungsvorschriften aktualisiert. Dazu muss der Schalter ‚AendLeistungsanforderung‘ auf ‚true‘ gesetzt werden. Voraussetzung ist zusätzlich, dass der Schalter ‚AendSchuelerZeitraeume‘ auf true gesetzt wird.

* Es wird vom Skript eine neue Zeugnisart berücksichtigt: NV für Versetzungszeugnis, Schüler wird nicht versetzt.

Dazu muss im Verzeichnis Verordnungen der entsprechende Eintrag gemacht werden. Ausgewertet vom Skript werden die beiden ersten Zeichen der Spalte Kuerzel (es würden diese beiden Zeichen reichen, z.B AG für Vorzeitiger Abbruch der Ausbildung). Dadurch kann man Versetzungsentscheidungen unabhängig vom Notenbild eintragen. Die ersten beiden Zeichen im Datenfeld SchuelerZeitraeume.Verordnung geben dann Auskunft über die Versetzungsentscheidung und können für Zeugnisformulare für die Ausweisung der Versetzungsentscheidung ausgewertet werden.
