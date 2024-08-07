# Grundlegende Einstellungen

[1]:/assets/images/Berufsschule/01_berufsschule.png
[2]:/assets/images/Berufsschule/02_berufsschule.png
[3]:/assets/images/Berufsschule/03_berufsschule.png
[4]:/assets/images/Berufsschule/04_berufsschule.png
[5]:/assets/images/Berufsschule/05_berufsschule.png

!!! info "Hinweis"

    Die nachstehenden Punkte sind eine kurze Zusammenfassung des Vorgehens, die ausführliche Dokumentation finden Sie in der [Magellan Dokumentation](https://doc.magellan.stueber.de/).

## Notenberechnung in der Berufsschule

In der Berufsschule in Deutschland besuchen die Schüler eine Klasse im Rahmen der Berufsausbildung über ein, zwei, drei oder vier Jahre. Entsprechend sind den Berufsschulklassen in Magellan zwei Zeiträume (einjährige Klassen), vier Zeiträume (zweijährige Klassen), sechs Zeiträume (dreijährige Klassen) bzw. acht Zeiträume (vierjährige Klassen) zugeordnet, wobei jeder Zeitraum einem Halbjahr entspricht.

Verlässt der Schüler die Klasse vorzeitig, so erhält er ein Abgangszeugnis. Verlässt er die Klasse erfolgreich zum Abschluss seiner Ausbildung, so erhält er ein Abschlusszeugnis.

Die Halbjahres-,  Zwischen- und Jahreszeugnisse des Schülers zum Ende eines Halbjahres beziehen sich fast ausschließlich auf die Noten des aktuellen Zeitraums. In diesem Fall greift ein Zeugnisbericht immer auf die Noten des aktuellen Zeitraums zu. Die Noten der Schüler werden dann in Magellan unter den Zeugnisdaten eingefügt.
Bei den meisten Abgangs- bzw. Abschlusszeugnissen werden die Noten auf der Basis der Noten der einzelnen Schuljahre festgelegt. Dies erfolgt durch ein vorgegebenes Berechnungsschema, bei denen Noten sowohl innerhalb eines Schuljahres als auch im Verhältnis der Schuljahre zueinander berechnet werden.

Ein typisches Beispiel ist hierbei die Note des berufsbezogenen Unterrichts. Pro Schuljahr wird die Note des berufsbezogenen Unterrichts aufgrund der Stundenfaktoren der berufsbezogenen Fächer berechnet. In den Abgangs- bzw. Abschlusszeugnissen werden sowohl die Gesamtnote im berufsbezogenen Unterricht als auch die Abschlussnoten der einzelnen Fächer in bestimmten Verhältnissen der Schuljahre berechnet. Z.B. kann das letzte Schuljahr einen höheren Einfluss auf die Endnoten haben, als die vorangegangenen Schuljahre.

Die jeweiligen Verordnungen für die Berechnungsvorschriften spiegeln sich über die Landesanpassung von Magellan in der Notenberechnung für die Berufsschule wieder.
Magellan stellt sehr ausgefeilte Funktionen für die gesamte Endnotenberechnung der Berufsschule zur Verfügung. Damit die Berechnungen korrekt durchgeführt werden können und Sie auch die Abschluss- bzw. Abgangszeugnisse mit Bezug auf mehrere Zeiträume richtig ausgedruckt bekommen, müssen Sie allerdings einige wenige aber wichtige Details beachten. Diese Details werden in diesem Kapitel erklärt. Lesen Sie es bitte sorgfältig.

!!! info "Hinweis"

    Die zeitraumübergreifenden Endnotenberechnungen basieren auf Magellan-Skripten, die Sie mit Hilfe des Magellan-Skripteditors bearbeiten können. 

## Allgemein

Zur zeitraumübergreifenden Endnotenberechnung der Berufsschule und dem anschließenden Zeugnisdruck gehören folgende Aufgaben:

* Berufsschulklassen und andere Stammdaten einrichten
* Fächer und Noten der Schüler pro Zeitraum einer Zeugnisausgabe eingeben
* Endnoten für Abgangs- bzw. Abschlusszeugnisse berechnen
* Zeugnisbemerkungen eingeben und Zeugnisse drucken

Alle Schritte werden in Magellan ausgeführt.  

## Berufsschulklassen einrichten

Eine Klasse in der Berufsschule besteht aus den Jahrgängen 1 (= Grundstufe), 2 (Fachstufe 1), 3 (Fachstufe 2) bzw. 4 (Fachstufe 3).

In Magellan werden die Daten halbjahresbezogen abgelegt. Sie definieren also eine Klasse mit je zwei Zeiträumen bzw. Halbjahren für die Grundstufe, Fachstufe 1 und evtl. Fachstufe 2 bzw. Fachstufe 3.
Eine 2-jährige Klasse besteht demnach aus 4 Halbjahren mit dem Jahrgang 1 für die ersten beiden Halbjahre und dem Jahrgang 2 für die letzten beiden Halbjahre.

Folgende Angaben sind bei der Eingabe der Berufsschulklasse neben den Halbjahren wichtig:

|Eingabefeld |Eingabe|
|--|--|
|Klassenart |Standard|
|Jahrgang |1, 2, 3 oder 4 (pro Zeitraum der Klasse notwendig)|
|Beurteilungsart |Benotung durch Noten|

## Unterrichtsarten, Fachstatus und Faktoren

Voraussetzung für die Abgangs- bzw. Abschlussnotenberechnung ist, dass Sie bei den Fächern des Schülers die entsprechende Unterrichtsart und den entsprechenden Fachstatus eingegeben haben. Zusätzlich müssen Sie evtl. auch den Stundenfaktor des Fachs angeben.

Generell verwenden Sie die gleichen Unterrichtsarten, Fachstatus und Faktoren, die Sie auch in den sonstigen Zeugnissen (z.B. Jahreszeugnis) nutzen.

Bei den einzelnen Berechnungsskripten werden bestimmte Unterscheidungen in den Unterrichtsarten bzw. Fachstatus vorausgesetzt d.h. die entsprechenden Schlüssel müssen vorhanden sein (die Kürzel werden nur zur Anzeige verwendet). Teilweise müssen Sie auch Angaben zum Stundenfaktor des Fachs machen. Diese Informationen werden nachfolgend aufgelistet.

## Endnotenberechnung vorbereiten

[![Berufsschulmatrix][1]][1]

### Berechnungsverordnung definieren

Je Schüler Abschlussjahrgang und Berechnungsverordnung angeben

Je Schüler die Fächer, Noten bzw. Faktoren synchronisieren oder manuell eingeben

In den nachfolgenden Abschnitten erfahren Sie mehr zu den einzelnen Punkten.

## Abschlussjahrgang definieren

[![Verzeichnis Abschlussjahrgänge][2]][2]

Sie können in Magellan unter `Extras > Schlüsselverzeichnisse > Abschlussjahrgänge` Abschlussjahrgänge definieren. Damit können Sie jedem Schüler in der Rubrik „Berufsschule“ den entsprechenden Abschlussjahrgang zuordnen.

Dieser Vermerk hat keinen Einfluss auf Abschlussnotenberechnungen, sondern dient dazu, später alle Schüler eines bestimmten Abschlussgangs z.B. für Ausdrucke herausfiltern zu können und die Art der zu synchronisierenden Noten festzulegen.

!!! "Wichtig!"

    Die Art der zu synchronisierenden Noten des Abschlussjahrsganges legen Sie über das Feld "Kategorie" fest:

Kategorie | Bedeutung
--|--
Berufsschule (Jahresnoten) | Beim Synchronisieren der Schüler werden nur die Noten des jeweils 2. Halbjahres in die Ansicht „Berufschule“ zu übertragen.
Berufsschule (Halbjahresnoten) | Beim Synchronisieren der Schüler werden die Noten des jeweils 1. und 2. Halbjahres in die Ansicht „Berufschule“ zu übertragen.

## Berechnungsverordnung nochmals definieren

[![Definieren der Berechnungsordnung][3]][3]

Sie müssen für jeden Schüler die Berechnungsverordnung angeben, die für ihn relevant ist. Dazu müssen Sie im Schlüsselverzeichnis „Verordnungen“ die jeweilige Berechnungsverordnung definieren. Klicken Sie dazu auf `Extras > Schlüsselverzeichnisse > Verordnungen` und geben dort die Verordnung wie folgt an:

|Spalte |Bedeutung|
|--|--|
|Kürzel |8-stellige Kurzbezeichnung der Verordnung|
|Bezeichnung |Bezeichnung der Verordnung|
|Kategorie |Wenn Sie hier „Berufsschule“ eingeben, wird die Verordnung bei den Schüler-Berufsschuldaten angezeigt|
|Typ |Bei einigen Verordnungen muss hier eine spezielles Kürzel angegeben werden.|
|Gültig von |Gültigkeitsdatum von, ohne Bedeutung für die Berechnungen|
|Gültig bis| Gültigkeitsdatum bis, ohne Bedeutung für die Berechnungen|
|Skript |Geben Sie hier den Namen des Skripts für diese Berechnungsverordnung ein. Alle verfügbaren Skripte befinden sich im Magellan-Verzeichnis SKRIPTE.|

## Berufsschuldaten synchronisieren

[![Synchronisation][4]][4]

Bevor Sie die Endnotenberechnung durchführen können, müssen Sie die Daten der Schüler synchronisieren, indem Sie in Magellan auf „Berufsschule“ klicken und dann auf die Schaltfläche „Synchronisieren“ oben im Magellan-Fenster klicken.

Beim Synchronisieren geschieht Folgendes: 

* Magellan extrahiert für die markierten Schüler die Fachdaten der Noten der Grundstufe, Fachstufe 1, Fachstufe 2 bzw. Fachstufe 3. 
* besitzt der ausgewählt Abschlussjahrgang die Kategorie „Berufschule (Jahresnoten)“, werden nur die Noten der jeweiligen 2. Halbjahre  (=Jahresnoten) extrahiert
* besitzt der ausgewählt Abschlussjahrgang die Kategorie „Berufschule (Halbjahresnoten)“, werden die Noten des 1. und 2. Halbjahres extrahiert

Dies ist die Voraussetzung dafür, dass die Abschlussberechnungen der Berufschule durchgeführt werden können. Auch wenn Sie zuvor keine Fächer bzw. Noten in den Halbjahren des Schülers angegeben haben, müssen Sie diese Synchronisation einmal ausführen.

Damit die Schüler mit allen Fächern, Noten und Faktoren aus den einzelnen Halbjahren korrekt übernommen werden können, sind folgende Angaben in Magellan notwendig.

|Feld |Wert|
|--|--|
|Zeiträume: |Im Verzeichnis der Zeiträume muss das Feld „Art“ mit dem Wert „1. Halbjahr“ bzw. „2. Halbjahr“ gefüllt sein.|
|Jahrgang: |Bei jeder Klasse der Berufschule muss auf der Registerkarte „Zeiträume“ für jeden Zeitraum  das Feld „Jahrgang“ mit dem Wert „1“ (= Grundstufe), „2“ (= Fachstufe 1), „3“ (= Fachstufe 2) oder „4“ (= Fachstufe 3) angegeben werden.|

Ohne diese Angaben werden nur die Schüler ohne Fächer und Noten übernommen.

Beim Synchronisieren sollten Sie für die markierten Schüler die Berechnungsverordnung und den Abschlussjahrgang eingeben.

Klicken Sie nach dem Synchronisieren auf die Schaltfläche „Berufsschule“ in der Symbolleiste links im Magellan-Fenster. Es werden alle synchronisierten Schüler auf der Registerkarte „Auswahl“ angezeigt.

Per Doppelklick auf den gewünschten Schüler oder über einen Klick auf die Registerkarte wechseln Sie zur Notenmatrix der Berufsschule. Auf dieser Registerkarte finden Sie die Fächer, Unterrichtsarten, Fachstatus inkl. Notenwerte und Faktoren der Schuljahre, falls Sie diese Angaben bereits in Magellan bei den Zeugnisdaten der Schüler gemacht haben sollten. Andernfalls können Sie diese Angaben für die einzelnen Schulhalbjahre 1, 2, 3 bzw. 4 auch hier eingeben.

## Spalte „Faktor“ auf der Registerkarte „Matrix“

Auf der Registerkarte „Matrix“ hat die Spalte „Faktor“ für einige Skripte eine besondere Bedeutung. Sie gibt im Rahmen der Berechnung der Gesamtnote (auch teilweise „Gesamtnotendurchschnitt“ genannt) an, mit welchen Faktoren die Endnoten untereinander verrechnet werden.

Allen Berufschulverordnungen gemeinsam ist die Tatsache, dass die Fächer für Sport, Religion/Ethik und fakultative Fächer nicht bei der Gesamtnote berücksichtigt werden. Entsprechend wird die Spalte „Faktor“ im Rahmen der Synchronisation mit dem Faktor „0“ vorbesetzt.
Wie evtl. die Fächer für Sport, Religion/Ethik und fakultative Fächer speziell zu kennzeichnen sind, ist bei den jeweiligen landesspezifischen Skripten.

## Fächer und Punkte eingeben

Sollten Sie die Fächer nicht schon unter `Zeugnis > Leistungen` eingegeben haben, so dass sie beim Synchronisieren übernommen wurden, können Sie das auch direkt auf der Registerkarte „Matrix“ machen. Mit der Einfg-Taste oder durch Klick auf das Einfügen-Symbol rechts oben erzeugen Sie eine neue Zeile. Geben Sie das Fach, Unterrichtsart, Fachstatus und die Noten mit dem jeweiligen Faktor für die einzelnen Schuljahre ein.

## Sammelzuweisung für Fächer, Faktoren, Positionen, Merkmale, Konferenz- und Zeugnisdaten

Unter `Berufsschule > Matrix` haben Sie die Möglichkeit, Fachdaten eines Schülers auch auf andere Schüler zu kopieren. 

Sie gehen dazu wie folgt vor:

Wählen Sie unter `Berufsschule > Auswahl` den Schüler aus, dessen Fächer Sie kopieren möchten und wechseln  Sie dann auf die Registerkarte „Matrix“.

Starten Sie den Assistenten über den Befehl „Sammelzuweisung“.
Markieren Sie die Schüler, denen die kopierten Angaben zugewiesen werden sollen.
Wählen Sie auf der folgenden Karte aus welche Daten übernommen werden sollen und ob bereits vorhandene Daten überschrieben werden sollen.

[![Sammelzuweisung][5]][5]

## Die Spalte „Position“

Die Position kann als Merkmal für die Reihenfolge der Fächer auf der Registerkarte „Notenmatrix“ und auf den Abschluss-/Abgangszeugnis verwendet werden, welche die Berufschulmatrix nutzen. Die in Magellan mitgelieferten Skripte und Zeugnisformulare für die Berufschulmatrix verwenden diese Positionsangaben.
Klicken Sie auf den Titel „Position“, um die Fächerliste entsprechend zu sortieren.

## Unterrichtsarten eingeben

Geben Sie in der Spalte „Unterrichtsart“ für  jedes Fach die Unterrichtsart ein. Sie ist vom verwendeten Skript abhängig.

## Fachstatus eingeben

Geben Sie in der Spalte „Fachstatus“ für  jedes Fach den Fachstatus ein. Er ist vom verwendeten Skript abhängig.

## Endnotenberechnung durchführen

Die Endnoten  für Abschlusszeugnisse kann in zwei Schritte unterteilt werden:

1. Automatische Berechnung der Endnoten.
2. Eventuelle manuelle Eingabe/Korrektur der Endnoten.

Die folgenden Abschnitte sagen Ihnen, wie Sie genau vorgehen müssen.

## Automatische Berechnung

Überprüfen Sie, ob für den Schüler die notwendigen Fächer inkl. der Faktoren für die einzelnen Jahresnoten auf der Registerkarte Notenmatrix eingetragen sind. Zudem muss unter Verordnung die korrekte Endnotenverordnung eingestellt ist bzw. wählen Sie die entsprechende aus.

Klicken Sie auf „Neu berechnen“, um die Endnoten automatisch durch das entsprechende Skript berechnen zu lassen. Durch die Berechnungen werden automatisch die Noten in die Spalte Endnote eingetragen. Je nach Skriptinhalt werden auch auf der rechten Seite die Felder „BU-Note“ (=Gesamtnote für den Berufsbezogener Unterricht) bzw. „Gesamtnote“ (=Gesamtnote des Abschluss) berechnet.

Im automatisch erzeugten Meldungsfenster werden zusätzliche Statusinformationen zur Berechnung angezeigt. Insbesondere wird hier eine Aussage über die erfolgreiche Durchführung der Berechnung und eventuell notwendige Zwischensummen angezeigt.

## Manuelle Eingabe/Korrektur der Endnoten

Alle Noten der Berufsschulnotenmatrix können neben der automatischen Berechnung auch manuell eingegeben werden. Sie können so die Berufschulmatrix nur zur Eingabe von bereits  festgelegten Endnoten nutzen.
Insbesondere können Sie die manuelle Eingabe aber im Sinne der Korrektur einer zuvor automatischen Berechnung der Endnoten nutzen. Hat beispielsweise die automatische Berechnung ergeben, dass der Schüler genau zwischen zwei Noten steht, so können aufgrund des pädagogischen Ermessens in solchen Fällen z.B. die Faktoren geändert werden. Nach der Änderung kann dann die automatische Berechnung nochmals durchgeführt werden.

## Wer hat Berufsschuldaten geändert

Abschluss- bzw. Abgangsdaten der Berufschule sind sensible Daten. Über die Benutzerverwaltung des Magellan-Administrators wird festgelegt, wer Zugang zu welchen Daten hat. Wie aber können Sie feststellen, dass Daten unter „Berufschule“ geändert worden sind und sei es versehentlich durch Sie selbst?

Bei Änderungen auf den Registerkarten des Menüs `Berufsschule` vermerkt Magellan automatisch das aktuelle Datum und die Kennung des aktuellen Benutzers.  Unter `Berufsschule > Auswahl` werden für jeden Schüler das Datum und die Kennung desjenigen angezeigt, der diese Angaben bestätigt hat. So ist überprüfbar, wer wann Daten im Menü `Berufsschule` eines Schülers geändert hat.

## Drucken

Sollten für Ihr Bundesland keine zeitraumübergreifenden Zeugnisse verfügbar sein, können Sie diese selbst mit Crystal Reports erstellen, indem Sie das Zeugnis eines anderen Bundeslandes als Vorlage nehmen oder Sie geben STÜBER SYSTEMS den Auftrag, das Zeugnis für Sie zu erstellen.

Alle zeitraumübergreifenden Zeugnisse der Berufsschule basieren auf den Eintragungen unter Berufschule.
Wechseln Sie in das Menü `Berufsschule > Zeugnis`, um Zeugnisbemerkungen anzugeben. Zusammen mit den Angaben auf der Registerkarte „Notenmatrix“ und den allgemeine Daten zum Schüler verfügen Sie dann über alle Daten, um das zeitraumübergreifende Abschluss- bzw. Abgangszeugnis auszudrucken.
