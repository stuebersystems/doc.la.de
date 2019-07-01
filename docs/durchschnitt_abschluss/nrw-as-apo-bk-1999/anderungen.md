# Änderungen

Nachstehend finden Sie erfolgte Änderungen für das Skript NRW-AS-APO-BK-1999. 

>Federführender Autor des Skriptes und der Dokumentation ist Heinz Kersting vom Berufskolleg Mitte TÜV NORD College. 

## Version vom 23.06.2017

Fehler in der Abschlussberechnung für die Bildungsgänge A12/A13 korrigiert. Ein 5 oder 6 in Mathematik (M) wird nicht berücksichtigt, wenn ein Ausgleich in Naturwissenschaften (NW) vorliegt.


## Version vom 16.06.2017

Skript wurde an die Magellan-Version 6.5.X angepasst.

## Version vom 16.02.2017

### Anlage A: Berechnung des FHR-Durchschnittes Bildungsganges A02 (‚Doppelquali‘)

Wird in diesen Bildungsgängen die FHR-Prüfung nach 3 Jahren und die Berufsabschlussprüfung nach 3.5 Jahren abgelegt kann es vorkommen, dass Beurteilungen für den Berufsschulabschluss und den FHR-Abschluss in Fächern unterschiedlich ausfallen. In diesem Fall können abweichende FHR-Noten in die Spalte `Endnote(gesamt)` eingetragen werden, diese werden dann für die FHR-Abschlussnote berücksichtigt.

Wird in der Spalte `Endnote(gesamt)` keine Note eingetragen, so werden wie bisher für die FHR-Abschlussnoten die Werte aus der Spalte Endnote genommen.

### Anlage E: Fehler bei der Berechnung der Abschlüsse in der Fachschule bereinigt 
Die Abschlussberechnung wurde überarbeitet, die Ausgabe der Kommentare wurde optimiert.

## Version vom 15.12.2015

Änderungen der APO-BK ab dem 1.8.2015 wurden eingearbeitet

### Anlage A


Bei einer Berufsschulabschlussnote von mind. 2,5 wird die FOR mit der Berechtigung zum Besuch der gymnasialen Oberstufe zugewiesen. Dieses gilt nur für Schüler die nach dem 1.8.2015 eingeschult wurden.
Damit der neue Abschluss eingetragen werden kann muss in den Verzeichnissen `Abgangsarten `(Schüler) und `Abschlüsse (Intern)` der Abschluss 3G definiert werden.

Für Auszubildende in den Helferberufen nach § 66 BBiG wird mit dem Berufsschulabschluss der Hauptschulabschluss erworben, Berechnung wurde hinzugefügt. Dabei wird davon ausgegangen, dass die Fachklassenbezeichnung bei diesen Schülern mit dem Zeichen 8 beginnt.

Die Berechnung für die Bildungsgänge A12 und A13 wurde hinzugefügt. Für die Zuerkennung des Hauptschulabschlusses dieser Bildungsgänge muss die notwendige Stundentafel erfüllt sein, in Magellan wird das durch unter `Schüler > MerkmalA4` mit dem Kürzel HS-M dokumentiert.

### Anlage B

Die Abschlussberechnungen für die Schulgliederungen B06, B07, B08, B09 und B10 wurde hinzugeführt. Die zu vergebenen Abschlüsse in den Schulgliederungen B08, B09 und B10 hängen auch davon ab welche Kurse in Mathe und Englisch besucht wurden (§ 6 Absatz 1 Anlage B). Dieses muss bei den Schülern mit dem Merkmal A5 eingestellt werden (Kürzel GK und EK, siehe unten). In dem untenstehenden Bild sind nochmal alle relevanten Merkmale für die Abschlussberechnung zusammengestellt.
 

![Verzeichnisse > Merkmale > Schüler ](/images/hr.kersting/Verzeichnis.Merkmale.png)

### Anlage E

Die Änderungen der Bezeichnungen für die Unterrichtsarten (Fachrichtungsübergreifender (Kürzel FÜ) in Berufsübergreifender (Kürzel BÜ) und Fachrichtungsbezogener (Kürzel FB) in Berufsbezogener (Kürzel BU) wird bei der Abschlussberechnung berücksichtigt.
Der FHR – Abschluss wird nun auch bei den Schülern vergeben die diesen Abschluss bereits besitzen (siehe VV zu § 16 allgemeiner Teil).
Bitte beachten Sie, dass bei der Berechnung der Abschlüsse alle Fächer des Bildungsganges eine Unterrichtsart mit dem Schlüssel-Wert  FÜ oder FB oder PR oder DB oder BU oder BÜ haben müssen, das Kürzel ist frei wählbar. 
Für die Noten des Fachschulexamens ist bei der Unterrichtsart der Schlüssel FE zu wählen, für die Fachhochschulreifeprüfung der Unterrichtsart-Schlüssel FH-P.

## Version vom 18.06.2015

### Abschlussberechnung Anlage C01

Schüler dieses Bildungsganges, die bereits die Fachhochschulreife oder die Hochschulreife besitzen, wird der Abschluss 5A zugewiesen wenn sie die Berufsabschlussprüfung bestehen. Bei diesen Schülern muss unter `Schüler > Daten 2 > Höchster Abschluss` ABS der Wert J oder K zugewiesen werden.

### Abschlussberechnung Anlage A06 (BGJ)

Für den Abschluss 2F und 2G sind besondere Leistungen in den Fächern M, D und E notwendig. Diese Abschlüsse werden grundsätzlich nicht vergeben, wenn in einem von diesen 3 Fächern keine Note eingetragen ist.

## Version vom 08.09.2014

### Berufsabschluss nach Landesrecht Anlage C01

Bei Schülern dieser Anlage kann es vorkommen, dass die Noten in einigen Fächern auf dem Fachhochschulreifezeugnis und dem Berufsabschlusszeugnis unterschiedlich sind. 

Auszug aus der APO-BK, Anlage C:
VV zu § 26 
26.1 zu Abs. 1
26.11In Fächern, in denen im Rahmen der Berufsabschlussprüfung nicht geprüft wurde, werden die Vornoten als Endnoten festgestellt. Die Prüfungsleistungen zum Erwerb der Fachhochschulreife werden bei der Festlegung der Endnoten berücksichtigt, wenn sie zu einer Verbesserung der Vornote führen. Die Endnoten sind die Zeugnisnoten.

Deshalb setzt das Berechnungsskript davon aus, dass die Noten für den FHR-Abschluss in der Spalte `Endnote `und die Noten für den Berufsabschluss unter der Spalte `Endnote (Gesamt)` eingetragen werden (Siehe Darstellung unten)
 
 ![Beispiel für Einträge](/images/hr.kersting/beispiel.01.jpg)
 
Die Zeugnisformulare müssen dann auf die unterschiedlichen Felder zugreifen.
In der Praxis dürften unterschiedlichen Noten im gleichem Fach selten vorkommen. Das Skript wurde jetzt so geändert, dass die Abschlüsse auch dann richtig berechnet werden, wenn nur die Noten in der Spalte Endnote eingetragen werden. Die Noten für den Berufsabschluss werden dann bei der Berechnung der Abschlüsse auch aus dieser Spalte genommen. Für Schulen die weiterhin die beiden Spalten nutzen ändert sich nichts.

## Version vom 29.06.2014
Folgendes Problem wurde bei der Abschlussberechnung für die Berufsfachschule (Anlage B) gelöst:

Hintergrund ist folgendes:
Im § 3 Absatz 3 in der APO-BK hieß es z.B. noch 2009: 
(3) Mit der Zulassung zur Berufsabschlussprüfung wird der mittlere Schulabschluss (Fachoberschulreife) erworben, wenn die entsprechenden Kurse in Englisch und Mathematik gemäß § 7 Abs. 2 mit jeweils mindestens ausreichenden Leistungen abgeschlossen wurden. In allen anderen Fällen wird mit der Zulassung zur Berufsabschlussprüfung der Hauptschulabschluss nach Klasse 10 erworben. 
Für Schüler der Berufsfachschule mit einem Berufsabschluss nach Landesrecht musste man also zum Erreichen der Fachoberschulreife unter anderem in Mathematik und Englisch mit mindestens ausreichenden Leistungen abgeschlossen haben. 

Diese Einschränkung gibt es nicht mehr, das wurde im Skript entsprechend angepasst.

## Version vom 18.03.2014

Für die Anlage E01 und E02 (Fachschule für Technik) mussten bisher für die Fächer, die in die Berechnung der Durchschnittsnote für die Fachhochschulreife eingingen, unter Merkmal „*)“ eingetragen werden. 

Fächer mit dem Unterrichtsartenschlüssel FB, DB, FH-P und Fächern mit dem Schlüssel „E“, „PK“ und „D“ werden bei der Durchschnittsberechnung auch ohne Eintragung des Merkmales „*)“ bei der Durchschnittszensurberechnung berücksichtigt. Das alte Verfahren gilt weiter.

## Version vom 18.03.2014

-	Änderung zulässiger Notenkürzel: statt ‚M‘ für vom Religionsunterricht abgemeldet die Zeichen ‚ab‘ (entsprechend der Zeugnisformulare)
-	Kommentare für die Voreinstellungen (Schalter) erweitert
-	Wenn Noten mit dem Wert 0 (z.B. ab für vom Religionsunterricht abgemeldet, K für keine Benotung) wurden unter bestimmtem Bedingungen die Durchschnittsnoten falsch berechnet. Der Fehler ist behoben. Grundsätzlich werden jetzt Noten mit dem Wert 0 (einzutragen im Verzeichnis Noten) bei der Durchschnittsberechnung nicht berücksichtigt.

## Version vom 07.11.2013

Es wurde ein zusätzlicher Merker eingeführt:
-	Merker Note PP (Note der praktischen Prüfung Anlage C)
-	Die Kommentare zur Abschlussberechnung wurden optimiert.


## Version vom 02.09.2013

-	Vorgaben für bestimmte Fächer-Schlüssel
Für die Berechnung von Schulabschlüssen sind die Leistungen in einigen Fächern wichtig. Dafür werden folgende Fächer zwischengespeichert:
Merker Note M (Mathematik)
Merker Note D (Deutsch)
Merker Note E (Englisch)
Merker Note PK (Politik)
Merker Note NW (Naturwissenschaften)
Merker Note PH (Physik)
Merker Note BB (berufsbezogene Praxis insgesamt im Berufsorientierungsjahr)

Abgefragt werden die Schlüsselwerte der Fächer, als Kürzel können schulspezifische Abkürzungen verwendete werden, z.B für das Fach Deutsch ‚DEU‘ als Kürzel, als Schlüssel muss ‚D‘ im Verzeichnis Fächer eingetragen werden.

-	Neuer Schalter AendLeistungsanforderung
Wenn der Wert auf true gesetzt wird, wird das Feld Leistungsanforderungen in der Tabelle SchuelerZeitraeume entsprechend der Leistungen gefüllt (in Magellan unter `Schüler > Zeugnis > Details > Leistungsanforderungen` einzutragen).

-	Neuer Schalter AendVersetzung
wenn der Wert auf true gesetzt wird, wird die Versetzungsentscheidung in der Tabelle SchuelerKlassen im Feld Versetzungsart eingetragen:
o	Bei Versetzungszeugnissen nach Vorgabe der Zeugnisart (Rollbalken Prüfungsverordnung) bei der Zensureneingabe
o	Bei Schüler der in der dualen Ausbildung werden alle Schüler mit einem Jahreszeugnis versetzt

-	Fehler bei der Entscheidung, ob die Leistungsanforderungen erfüllt sind:
Bei der Schülern Anlage C und Schülern mit der Schulgliederung A02 wurden bei der Entscheidung über die Erfüllung der Leistungsanforderungen die Fächer Religion und Sport nicht berücksichtigt. Der Fehler wurde korrigiert. 

-	FHR-Abschluss in der Anlage C
Bei Schülern der Anlage C braucht das Bestehen der FHR – Prüfung unter Merkmale nicht mehr angegeben werden. Das Bestehen der FHR – Prüfung ergibt sich aus den eingetragenen Endnoten.

-	Keine Beurteilung aus Krankheitsgründen
Wenn in für die Abschlüsse relevanten Fächern ein K eingetragen wird (K steht für ‚wegen entschuldigter Fehlzeiten kann keine Beurteilung erstellt werden‘) werden keine Abschlüsse erteilt.

## Version vom 5.6.2013

-	Abschlüsse werden auch für die Bildungsgänge B01, B02, B03, B04 berechnet

-	Das Datenfeld Leistungsanforderungen in der Tabelle SchuelerZeitraeume wird entsprechend der Verwaltungsvorschriften aktualisiert. Dazu muss der Schalter ‚AendLeistungsanforderung‘ auf ‚true‘ gesetzt werden. Voraussetzung ist zusätzlich, dass der Schalter ‚AendSchuelerZeitraeume‘ auf true gesetzt wird.

-	Es wird vom Skript eine neue Zeugnisart berücksichtigt: NV für Versetzungszeugnis, Schüler wird nicht versetzt. 
 
Dazu muss im Verzeichnis Verordnungen der entsprechende Eintrag gemacht werden. Ausgewertet vom Skript werden die beiden ersten Zeichen der Spalte Kuerzel (es würden diese beiden Zeichen reichen, z.B AG für Vorzeitiger Abbruch der Ausbildung). Dadurch kann man Versetzungsentscheidungen unabhängig vom Notenbild eintragen. Die ersten beiden Zeichen im Datenfeld SchuelerZeitraeume.Verordnung geben dann Auskunft über die Versetzungsentscheidung und können für Zeugnisformulare für die Ausweisung der Versetzungsentscheidung ausgewertet werden.
