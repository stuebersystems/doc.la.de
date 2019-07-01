
# Die Fachwahl{#Die Fachwahl}

## Fachwahl in daVinci{#Fachwahl in daVinci}

Die Fachwahlen der Oberstufenschüler werden in der Ansicht ```Kursplan > Fachwahlen``` erfasst und ggf. auch entsprechend der Fachwahlüberprüfung geprüft. Die Fachwahlüberprüfung erfolgt aufgrund des Fachwahlskriptes, das Sie bei jeder Klasse in der Ansicht ```Stammdaten > Klassen``` in der Spalte „Skript“ eingeben können. 

## Fachwahlskript wählen{#Fachwahlskript wählen}

![Auswahl des Fachwahlskriptes](/assets/images/dav_fachwahlskript_waehlen.jpg)

DAVINCI wird mit Fachwahlskripten für verschiedene Bundesländer und Schularten ausgeliefert. Ein Fachwahlskript hat die Dateiendung „.js“ (für DAVINCI 5 ".dws"). Technisch gesehen ist ein Fachwahlskript eine Javascript-Datei. Die ersten drei Buchstaben kennzeichnen das Bundesland, die Jahreszahl informiert über die Ausgabe des Skripts bzw. die zugrundeliegende Verordnung. Welche Skripte aktuell zum Prüfen zur Verfügung stehen, können Sie im Abschnitt ["Alle Skripte im Überblick"](oberstufenorga_alle_skripte_im_uberblick.md) nachlesen.

Sie können die Schüler von MAGELLAN importieren, die Fachwahlen eingeben und die Fachwahlen der Schüler dann wieder nach MAGELLAN exportieren.

!!! info "Hinweis"

    Die Fachwahleingabe ist auch in MAGELLAN möglich, allerdings ohne Stundenzahlen. Die Fachwahlen aus MAGELLAN können per Import nach DAVINCI übernommen werden. MAGELLAN verwendet zur Fachwahlüberprüfung das gleiche Fachwahlskript wie DAVINCI.

## Schüler eingeben{#Schüler eingeben}

In der Ansicht ```Stammdaten > Schüler``` werden alle Schüler des Oberstufenjahrgangs angezeigt.

![Ansicht "Kursplan | Schüler" mit vollständiger Blockung und Verteilung](/assets/images/kp_schueler.jpg)

Sie können die Schüler (der Oberstufenjahrgänge) in den Ansichten ```Stammdaten > Schüler``` oder ```Kursplan > Schüler``` über den Befehl Neu eingeben. 

In der Ansicht ```Kursplan > Schüler``` wird der Schüler automatisch den eingestellten Jahrgang zugeordnet. Wenn Sie mit MAGELLAN arbeiten, können Sie die Schüler über ```Plan > Importieren und Exportieren > Von MAGELLAN importieren```. 

In der Ansicht ```Stammdaten > Schüler``` muss jeder Schüler in der Spalte „Klasse“ einem Jahrgang zugeordnet werden. Jahrgang und Klasse ist in diesem Fall gleichbedeutend.

Falls Sie MAGELLAN einsetzen, können Sie über den Befehl ```Plan > Importieren und Exportieren``` die Schüler aus Ihrer Schulverwaltung übernehmen. 

Tabelle 2: Bedeutung der Zellen Hintergrundfarben in der Ansicht ```Kursplan > Schüler```

|Hintergrundfarbe| Bemerkung|
|--|--|
|Keine Farbe | Reine Fachwahl, d.h. es wurde noch kein Kurs zugeordnet|
|Grün |Eine Fachwahl, der ein Kurs zugeordnet wurde|
|Rot |Bei einem oder mehreren Schüler liegt ein Konflikt vor, weil zwei Kurse eines oder mehrerer Schüler im gleichen Block sind.|
|Grau |Kurs mit zu geringer Teilnehmerzahl, siehe Spalte „Min. Schüler“ in der Ansicht ```Kursplan > Kurse```.|
|Gelb| Kurs mit zu hoher Teilnehmerzahl, siehe Spalte „Min. Schüler“ in der Ansicht ```Kursplan > Kurse```.|

![Von MAGELLAN importieren](/assets/images/fw_mag_importieren.jpg)

## Fachwahlen eingeben

In der Ansicht ```Kursplan > Fachwahlen``` können Sie für jeden Schüler nun dessen Fachwahl bestimmen. Wenn Sie bei der betreffenden Klasse des Schülers unter ```Stammdaten > Klassen``` in der Spalte „Skript“ das betreffende Fachwahlskript angegeben haben, wird die Eingabe entsprechend der durch das Skript geprüften Oberstufenverordnung überprüft. Der Name des jeweilige Skripts wird rechts oben in der Ansicht angezeigt. Ggf. werden Fehlermeldungen oben in der Ansicht angezeigt. Geben Sie die gewünschten Fächer ein und machen Sie die entsprechenden Angaben in den Spalten „Unterrichtsart“, „Fachstatus“ und „Stunden“.

![Die Ansicht "Kursplan > Fachwahlen](/assets/images/dav_ansicht_fw.jpg)

Mit den „Markieren“ Schaltflächen können Sie alle Halbjahre eines Fachs markieren (weiß) oder demarkieren (grau). Indem Sie eine Halbjahreszelle in der Tabelle anklicken, können Sie einzelne Halbjahre markieren bzw. demarkieren.

|Spalte |Bemerkung|
|--|--|
|Fach| Gewähltes Fach, das mit der Angabe von Unterrichtsart und „Fachstatus“  näher spezifiziert werden muss. |
|Unterrichtsart |Unterrichtsart, z.B. „LK“ oder „GK“ oder „Kurs“, abhängig von Fachwahlskript.  Geben Sie die Unterrichtsarten ggf. über ```Schlüsselverzeichnisse > Unterrichtsarten``` ein. Ausschlaggebend sind dort die Angaben in der Spalte „Schlüssel“. Diese Angabe wird von der Blockungsautomatik mit der Vorgabe „Unterrichtsart“ in der Ansicht ```Kursplan > Blöcke``` abgeglichen.|
|Fachstatus |Prüfungsfach z.B. „1PF“, „2PF“, „3PF“, „4PF“ oder „5PF“, abhängig von Fachwahlskript. Geben Sie die Fachstatus ggf. über ```Schlüsselverzeichnisse > Fachstatus``` ein. Ausschlaggebend sind dort die Angaben in der Spalte „Schlüssel“.|
|Stunden| Geben Sie hier die Stundenzahl ein. Sie wird automatisch auf die Halbjahre 1 bis 6 übertragen. Diese Angabe wird von der Blockungsautomatik mit der Vorgabe „Min. Std“ und „Max. Std“ in der Ansicht ```Kursplan > Blöcke``` abgeglichen. Sie können diese Angabe auch leer lassen.|
|1…6 |Die Halbjahre der Oberstufe mit der jeweiligen Stundenanzahl, die sich aus der Spalte „Stunden“ ergibt. Sie können mit einem Mausklick in die betreffende Zelle Halbjahre für ein Fach markieren (weiß) oder demarkieren (grau). Wenn Sie unter „Stunden“ keine Stundenanzahl eingegeben haben, bleiben die Zellen der Tabelle leer.|

## Fachwahlen nach MAGELLAN übertragen

Wenn Sie die Fachwahl für alle Schüler eingegeben haben, können Sie mit der Kurserstellung und Blockung fortfahren. Über ```Plan > Importieren und Exportieren > Nach MAGELLAN exportieren``` können Sie die Schülerfachwahlen wieder nach MAGELLAN übertragen.

![Nach MAGELLAN exportieren](/assets/images/fw_nach_mag_ex.jpg)

## Fachwahl aus einer Stundentafel erzeugen


Sie können sich viel Eingabearbeit ersparen, indem Sie mit Stundentafeln als Vorlagen arbeiten. Mit der Schaltfläche Fachwahl erzeugen können Sie für den aktuell markierten Schüler bzw. mehrere markierte Schüler oder alle Schüler des Jahrgangs die Fachwahl aufgrund einer Stundentafel, die als Vorlage dient, erzeugen.

![Dialog "Fachwahl erzeugen](/assets/images/dav_fw.erzeugen.jpg)

Standardmäßig ist die Stundentafel des Jahrgangs eingestellt, Sie können aber auch eine andere wählen, wenn z.B. die Schüler nur aus einer von wenigen Fachkombinationen wählen können, weil an Ihre Schule nur diese Kombinationen angeboten werden.

## Fachwahlen löschen{#Fachwahlen löschen}


![Dialog "Schülerdaten löschen"So können Sie die Fachwahl eines Schülers löschen](/assets/images/dav_fw_loeschen.jpg)

*  Wechseln Sie in die Ansicht ```Kursplan > Fachwahlen ```und klicken Sie den gewünschten Schüler in der Detailansicht „Schüler“ an.

*  Markieren Sie eine oder mehrere Zeilen in seiner Fachwahltabelle. Sie können mit Strg+Mausklick und Shift+Mausklick mehrere Zeilen in der Tabelle markieren.

*  Klicken Sie oben im Menü auf Löschen, um die entsprechenden Zeilen zu löschen.

So können Sie die Fachwahl mehrerer Schüler gleichzeitig löschen:

*  Wechseln Sie in die Ansicht ```Kursplan > Schüler``` und klicken Sie den gewünschten Schüler in der Detailansicht „Schüler“ an.

*  Markieren Sie eine oder mehrere Schüler in der Schüler-Tabelle. Sie können mit Strg+Mausklick und Shift+Mausklick mehrere Zeilen in der Tabelle markieren.

*  Klicken Sie oben im Menü auf Löschen, um die entsprechenden Zeilen zu löschen. Das Dialogfenster „Schüler löschen“ gibt Ihnen die Option die Schüler oder nur die Fachwahlen der markierten Schüler zu löschen. Wählen Sie dort „Nur Fachwahlen löschen“.

>Wenn Sie eine Stundentafel allen Schülern des Jahrgangs zugwiesen haben, um anschließend die Fachwahlen einzugeben, sind je Schüler unbenutzte Fächer als graue Zeilen in der Ansicht Schüler | Fachwahlen übrig geblieben. Das Dialogfenster „Schüler löschen“ gibt Ihnen die Option, nur die Fachwahlen ohne Belegung der markierten Schüler zu löschen. Wählen Sie dort „Nur Fachwahlen ohne Belegung löschen“.

## Stundentafeln als Fachwahlvorlagen anlegen{#Stundentafeln als Fachwahlvorlagen anlegen}

![Die Ansicht ```Stammdaten > Stundentafel```](/assets/images/dav_stammdaten_stundentafel.jpg)

Stundentafeln geben Sie in der Ansicht ```Stammdaten > Stundentafeln``` ein. Klicken Sie auf die Schaltfläche in der Spalte „Fächer“, um die Fächer der Stundentafel einzugeben.

![Fächerliste der Stundentafel](/assets/images/dav_stundentafel.jpg)

|Spalte |Bemerkung|
|--|--|
|Fach |Gewähltes Fach, das mit der Angabe von Unterrichtsart und „Fachstatus“  näher spezifiziert werden muss. |
|Unterrichtsart| Unterrichtsart, z.B. „LK“ oder „GK“ oder „Kurs“, wird in die gleichnamige Spalte der Fachwahl übernommen.  Geben Sie hier z.B. als Standardvorgabe „GK“ oder „Kurs“ ein, das erspart Ihnen die Eingabe in der Ansicht „Fachwahl“.. Für die Leistungskurse können Sie dann in der Fachwahl anstatt „GK“ die Angabe „LK“ machen. Geben Sie die Unterrichtsar-ten ggf. über ```Schlüsselverzeichnisse > Unterrichtsarten``` ein. Ausschlaggebend sind dort die Angaben in der Spalte „Schlüssel“.|
|Soll |Sollstundenzahl, die in die Spalte „Stunden“ der Fachwahl übernommen wird
|Pflichtkurse| Anzahl der zu belegenden Kurse über die 4 oder 6 Halbjahre der Oberstufe


## Fachwahl in Magellan{#Fachwahl in Magellan}


Nachdem Sie die Schüler in die Ansicht „Abitur“ synchronisiert haben, können Sie für jeden Schüler dessen Fachwahlen auf der Registerkarte Ansicht „Abitur“ > Fachwahl eintragen und gleichzeitig auf Korrektheit prüfen. Alternativ können Sie an dieser Stelle auch die Daten nach DAVINCI übertragen und dort die Fachwahl durchführen. Anschließend können die Fachwahlen wieder nach MAGELLAN zurücksynchronisiert werden.

![Registerkarte „Fachwahl“ zur Eingabe der Schüler-Fachwahlen](/assets/images/mag_fw.jpg)

Grundsätzlich wird hier:

* die Fachwahl des Schülers eingetragen,

* die Fachwahl auf Basis einer Fachwahlverordnung auf Gültigkeit überprüft

* die gültige Fachwahl abschließend zu den Fächern des Schülers übernommen 

>Die Fachwahleingabe kann auch in DAVINCI KURSPLAN erfolgen. Dort ist die Fachwahleingabe etwas ausführlicher und komfortabler: Es können zusätzlich die Stundenzahlen der einzelnen Halbjahre eingegeben werden. Das zugrundeliegende Skript, d.h. das Regelwerk, ist in beiden Fällen das gleiche: MAGELLAN verwendet für die Fachwahlüberprüfung das DAVINCI Fachwahl-Skript.

## Fachwahl eintragen {#Fachwahl eintragen}

 
Das Eintragen der Fächer für die Fachwahl kann sowohl rein manuell pro Fach erfolgen oder wesentlich komfortabler per Zuordnung von Fachwahltafeln. Wir beschreiben nachstehend allgemein die notwendigen Schritte für die Fachwahlerfassung und die Prüfung der Fachwahlen.  

##Fachwahltafeln zuordnen



Durch die Verwendung von Fachwahltafeln können Sie Kopiervorlagen definieren, die Sie über den Assistenten für die Zuweisung Fachwahltafel ein oder mehreren Schüler gleichzeitig zuweisen können.

So definieren Sie eine Fachwahltafel:

* Wählen über ```Verzeichnisse > Fachtafeln``` das Verzeichnis der Fachtafeln aus.

* Legen Sie auf der Registerkarte Fachtafeln über ```Neue Zeile``` eine neue Fachwahltafel an. Achten Sie dabei auf den Eintrag „Fachwahltafel“ in der Spalte Art.

* Tragen Sie für die Fachwahltafel auf der Registerkarte Fachwahltafel – Fächer“ die Fächer der Fachwahltafel mit deren Eigenschaften ein.

![Hier tragen Sie die Fächer der Fachwahltafel ein](/assets/images/mag_verzeichnis_fachtafeln.jpg)

So weisen Sie eine Fachwahltafel Schülern in der Ansicht „Abitur“ zu:

* Wechseln Sie in der Ansicht „Abitur“ auf die Registerkarte Fachwahl.

* Klicken Sie im oberen Bereich auf die Schaltfläche ```Fachwahltafel zuweisen```.

![Hier können Sie Schülern Fachwahltafeln zuweisen](/assets/images/mag_ft_zuweisen.jpg)

* Markieren Sie die Schüler, denen Sie eine Fachwahltafel zuweisen wollen und klicken Sie dann auf ```Weiter```. 

* Markieren Sie die gewünschte Fachwahltafel und ordnen Sie optional im unteren Bereich den Halb-jahren die entsprechende Zeiträume zu. Sollen bei der Zuweisung der Fachwahltafeln die eventuell bereits bestehenden Fachwahlen der markierten Schüler nicht zuvor gelöscht werden, so müssen Sie das Kontrollkästchen ```Vorhandene Fachwahlen der Schüler nicht löschen``` markieren. Klicken Sie auf ```Weiter```.

* Geben Sie optional den zuzuordnenden Abiturjahrgang und die Fachwahlverordnung an und klicken Sie dann auf ```Weiter```.

* Klicken Sie auf ```Fertigstellen```, um die Fachwahltafel den markierten Schülern zuzuordnen.

## Fächer manuell zuordnen{#Fächer manuell zuordnen}


Die Fächer der Fachwahl können auch ohne die Kopiervorlage der Fachwahltafeln dem Schüler zugeordnet werden. Dazu gehen Sie pro Fach wie folgt vor:

* Wechseln Sie in der Ansicht „Abitur“ auf die Registerkarte Fachwahl.

* Klicken Sie im oberen Bereich auf das rote Plus für eine neue Zeile.

* Tragen Sie jetzt das Fach und optional die Unterrichtsart und den Fachstatus ein.

>Wird ein Fach manuell zugeordnet, sind in der dadurch erzeugten neuen Zeile die Spalten „1. HJ“ bis „6. HJ“ automatisch markiert.

Wenn Sie die Fachwahl manuell pro Fach auf diese Weise zuordnen, müssen Sie im Unterschied zur Zuweisung per Fachwahltafel auch 

* pro Fach die Pflichtkursanzahl optional eintragen,

* pro Fach die Unterrichtsart und optional den Fachstatus eintragen,

* pro Fach festlegen, in welchen Halbjahren das Fach belegt wird sowie

* die Fachwahlverordnung und Zuordnung der Halbjahre zu den die Zeiträume pro Schüler manuell vornehmen.


## Abgleich der Karte Qualifikation/Karte Fachwahl{#Abgleich der Karte Qualifikation/Karte Fachwahl}


Unter Extras > Optionen > Einstellungen kann die Option ```Abgleich Qualifikation/Fachwahl im Abitur``` gewählt werden. 

Folgende Aktionen werden durch diese Option beeinflusst:

|Aktion|Auswirkung|
|--|--|
|Synchronisieren von Schülern ins Menü Abitur|Gibt es für die synchronisierten Schüler bereits Fachdaten im Menü ```Schüler > Zeugnis > Fächer```, werden diese auf die Karten Qualifikation und Fachwahl übernommen.|
|Ein Fach wird ergänzt|Wird ein Fach auf der Karte Qualifikation oder auf der Karte Fachwahl neu angelegt, wird das Fach automatisch auf der anderen Karte ergänzt. Das gilt auch durch das Ergänzen per Fachwahltafel auf der Karte Fachwahl oder durch erneutes Synchronisieren der Schüler in das Abiturmenü.|
|Ein Fach wird gelöscht|Wird ein Fach auf der Karte Qualifikation oder auf der Karte Fachwahl gelöscht, wird das Fach automatisch auf der anderen Karte entfernt. |
|Unterrichtsart, Fachstatus o.ä. wird verändert|Ist ein Fach durch den Abgleich auf beiden Karten angelegt worden und es wird eine der zusätzlich zur Verfügung stehenden Eigenschaften geändert, wird die Änderung auch auf der anderen Karte mit abgebildet. |

> Bereits bestehende Fächer auf der Karte Fachwahl und Qualifikation werden durch das Setzen der Option ``Abgleich Qualifikation/Fachwahl``` im Abitur nicht automatisch abgeglichen. Die Option wirkt sich auf neu angelegte oder neu synchronisierte Fächer aus.


## Fachwahl prüfen {#Fachwahl prüfen}


Sobald Sie dem Schüler eine Fachwahlverordnung zugeordnet haben, wird die Schaltfläche ```Neu prüfen``` zur Überprüfung der Fachwahl aktiv. Auf Basis der eingetragenen Fachwahl können Sie durch Wahl der Schaltfläche ```Neu prüfen``` diese prüfen. Das Ergebnis der Prüfung wird im oberen Bereich der Registerkarte Fachwahl angezeigt. Ist die Anzeige rot unterlegt, handelt es sich um eine (noch) nicht gültige Fachwahl. 

![Diese Fachwahl ist noch fehlerhaft](/assets/images/mag_fw_verkehrt.png)

Bei einer gültigen Fachwahl ist der obere Hinweistext grün hinterlegt mit dem Hinweis „Fachwahl ist gültig“.

![Diese Fachwahl ist gültig](/assets/images/mag_fw_ok.png)

Mit Wahl der Schaltfläche ```Neu prüfen ```wird oberhalb dieser Schaltfläche der Status Fachwahl geprüft angezeigt. Verändert man die Fachwahl des Schülers, wechselt der Status automatisch auf ```Fachwahl nicht geprüft```.

![Dies ist die Anzeige des Prüfstatus „Fachwahl nicht geprüft“ bzw. „Fachwahl geprüft“](/assets/images/mag_fw.png)

> Ist für ein eingetragenes Fach keine der Spalten „1. HJ“ bis „6. HJ“ markiert, wird dieses Fach bei der Fachwahlprüfung als nicht gewählt betrachtet.

> Die Zuordnung der Zeiträume zu den Halbjahren 1 bis 6 auf der rechten Seite haben keinen Einfluss auf die Fachwahlprüfung. Sie dienen nur der späteren Zuweisung der Fachwahlen eines Halbjahres zu den Fächern des Schülers (siehe nachfolgender Abschnitt)


 ## Fachwahl zu den Fächern des Schülers übernehmen{#Fachwahl zu den Fächern des Schülers übernehmen}

 

Die unter Ansicht ```Abitur > Fachwahl ```erstellten Fachwahlen der Schüler können nun zu Fächern der Schüler auf der Registerkarte Ansicht ```Schüler > Zeugnis > Fächer``` übernommen werden. Diese Zuweisung erfolgt immer zum aktuell eingestellten Zeitraum.

Bei der Übernahme der Fachwahl eines Schülers werden nur die Fächer übernommen, die in einem der sechs Halbjahre auf der rechten Seite den aktuellen Zeitraum von MAGELLAN zugewiesen haben und die in diesem Halbjahr das Kontrollkästchen markiert haben.

Beispiel: 

In MAGELLAN ist der aktuelle Zeitraum das „1. Halbjahr 2011/2012“. Der Schüler hat die nachfolgende Fachwahl:

![Beispiel für die Fachwahl eines Schülers](/assets/images/mag_fw_rueck1.png)

Die Spalte 1. HJ entspricht dem Zeitraum „1. Halbjahr 2011/2012“. Übernimmt man nun die Fachwahl im aktuellen Zeitraum, so werden alle Fächer der Fachwahl übernommen bis auf das Fach „Fr“, da dieses in der Spalte 1. HJ nicht markiert ist.

Auf Basis dieser Zuordnung kann nun die Zuweisung der Fachwahlen zu den Fächern der Schüler wie folgt durchgeführt werden:

* Wechseln Sie in der Ansicht „Abitur“ auf die Registerkarte Fachwahl.

* Klicken Sie im oberen Bereich auf die Schaltfläche ```Fachwahl übernehmen```.

* Markieren Sie die Schüler, deren Fachwahl Sie übernehmen wollen. Sollen bei der Übernahme die eventuell bereits bestehenden Fächer der markierten Schüler nicht zuvor gelöscht werden, so müssen Sie das Kontrollkästchen ```Vorhandene Fächer der Schüler nicht löschen``` markieren. Klicken Sie dann auf ```Weiter```. 

* Klicken Sie auf ```Fertigstellen```, um die Fachwahlübernahme zu starten.

Die übernommen Fächer finden Sie nun auf der Registerkarte Ansicht ```Schüler“ > Zeugnis > Fächer```.





