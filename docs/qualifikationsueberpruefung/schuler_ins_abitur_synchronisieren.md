# Schüler ins Abitur synchronisieren

Die Schüler können für die Fachwahl in MAGELLAN oder für die Abiturqualifikation synchronisiert werden.
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

!!! info "Hinweis"

    Beim Synchronisieren werden die Noten aus der Spalte „Endnote“ in das Menü „Abitur“ übernommen.

![Daten fürs Abitur synchronisieren](/assets/images/abi_sync.jpg)

So synchronisieren Sie Schüler für die Abiturberechnung oder die Fachwahl:

Rufen Sie den Assistenten aus dem Menü ```Abitur``` auf der Karte ```Qualifikation``` über die Schaltfläche ```Schüler synchronisieren``` auf. Der Assistent bietet Ihnen alle Schüler zum Synchronisieren an, die sich in einer Klasse mit der Klassenart ```Oberstufenjahrgang``` befinden. Markieren Sie die Schüler und klicken auf ```Weiter```.
Auf der nächsten Karte wählen Sie bitte die ```Prüfungsordnung``` und den ```Abschlussjahrgang``` aus und klicken auf ```Weiter``` und ```Fertigstellen```.

![Assistent zum Schüler synchronisieren](/assets/images/abi_sync2.png)

Wechseln Sie nach dem Synchronisieren in den Menüpunkt ```Abitur``` auf die Unterkarte ```Auswahl```. Es werden alle synchronisierten Schüler angezeigt.

Per Doppelklick auf den gewünschten Schüler oder über einen Klick auf die Registerkarte ```Qualifikation``` wechseln Sie zur Abiturzulassung. Auf dieser Registerkarte finden Sie die Fächer und Notenwerte der Oberstufenhalbjahre, falls Sie diese Angaben bereits in MAGELLAN unter der Rubrik ```Schüler``` gemacht haben sollten. Andernfalls können Sie Fächer und Notenwerte für die Oberstufenhalbjahre auch hier eingeben.

Sollte die 11 in Ihrem Bundesland nicht in Leistungs- und Grundkursen unterrichtet werden, erscheinen die Fächer der besseren Übersicht wegen trotzdem unterschieden nach den Leistungs- und Grundkursen der Jahrgangsstufen 12 und 13. Intern macht MAGELLAN für die Noten der 11 keine Unterscheidung in Leistungs- und Grundkurse.
