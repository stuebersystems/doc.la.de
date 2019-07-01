# SIP-Schnittstelle MVP

Das Schulberichtssystem (SBS) wurde durch das Schulinformations- und Planungssystem M-V (SIP) am 03.01.2013 abgelöst. Somit erfolgt für allgemein bildende und berufliche Schulen die Datenerhebung in einem System. STÜBER SYSTEMS bietet Ihnen die Möglichkeit, Daten für die SIP-Schnittstelle mit MAGELLAN zu exportieren. 

##Einführung
Das Kultusministerium fordert die elektronische Erfassung im XML-Dateiformat. Die Schuldaten können in diesem Format aus MAGELLAN heraus erzeugt werden. Das XML-Dateiformat ist eine Auszeichnungssprache zur Darstellung hierarchisch strukturierter Daten in Form von Textdateien.
Durch die Hierarchie können explizit Daten für Allgemeinbildende und Berufsbildende Schulen  getrennt werden und es ist somit nicht erforderlich unterschiedliche Dateien für die jeweiligen Schulformen zu erzeugen. 

Für Sie als Schule bedeutet dies: Sie müssen die folgende XML-Datei über das Webportal ```https://portal.schule-mv.de``` übertragen:

1.	xxxxx_[DATUM].xml 
Hierbei steht xxxxx für Ihre Schulnummer und [DATUM] für das aktuelle Datum.
Notwendige Schritte 
Folgende Schritte sind notwendig:
1. Schritt: Statistikschlüssel aktualisieren 
2. Schritt: Statistisch relevante Daten eingeben
3. Schritt: Statistikdaten erstellen

Diese Schritte werden nachfolgend ausführlich erklärt.
##Statistikschlüssel aktualisieren
Aufgrund sich ändernder Anforderungen kommen jährlich aktualisierte Schlüssel für die Schnittstelle heraus. STÜBER SYSTEMS stellt die aktualisierten Schlüssel über ein Serviceupdate für MAGELLAN zur Verfügung.
##Statistisch relevante Daten eingeben
Bei einem Großteil der statistisch relevanten Daten handelt es sich um Stammdaten, die bei der alltäglichen Arbeit bereits erfasst wurden. Einige Daten werden Sie nachtragen müssen. Alle für die Statistik erforderlichen Daten finden Sie nachfolgend im Anhang, in einer tabellarischen Übersicht. 
##Statistikdaten erstellen
Die Erstellung der Statistikdateien werden zuerst alle erforderlichen Daten aus MAGELLAN ausgelesen, dann wird eine Datenprüfung vorgenommen und danach die Daten in die XML-Datei gespeichert. 

> Das Einlesen der Daten aus MAGELLAN erfolgt bei jeder Art der Erstellung ohne Berücksichtigung der zu erstellenden Statistikdatei.
Diese Prüfung ist eine Plausibilitätsprüfung, die beim Erstellen des Exports die zu exportierenden Werte mit den erwarteten Werten der SIP-Statistikschlüssel vergleicht und Ihnen Rückmeldung in Form von Hinweisen gibt, wenn ein Exportwert nicht mit einem Wert im Bereich der erwarteten Schlüssel passt.

##Datenprüfung und Export starten
1. Starten Sie MAGELLAN.
2. Klicken Sie im Menü Extras auf ```Export > SIP…```
3. Es wird das in MAGELLAN aktuell eingestellte Schulhalbjahr als Erhebungszeitraum voreingetragen. Wenn vorhanden, wählen Sie das davorliegende Schulhalbjahr aus, damit ggf. aufgetretene Änderungen korrekt erfasst werden können.
4. Wählen Sie die Schulform Ihrer Schule, Allgemeinbildende Schule (ABS) oder Berufsbildende Schulen (BBS) aus. Dies ist wichtig für die korrekte Ausgabe und Prüfung Ihrer Daten.
5. Das Gültig ab und Gültig bis Datum werden durch den ausgewählten Erhebungszeitraum vorberechnet und können entsprechend verändert werden, um die Gültigkeit Ihrer Daten anzupassen.
6. Geben Sie im Feld Exportordner den Dateipfad in dem die Exportdatei abgelegt werden soll. Klicken Sie dann auf ```Weiter```.
7. Auf der nächsten Seite erhalten Sie noch einmal eine Übersicht zum Datenexport. Klicken Sie auf ```Weiter```.
8. Klicken Sie auf ```Start```, um die Datenprüfung und Export der Daten zu starten.

![Beschriftung](/assets/images/sip/sip.png)

> Sie können nur bedingt Daten aus der Vergangenheit für SIP exportieren, aus diesem Grunde werden Ihnen nur das aktuelle Schuljahr und das vorangegangene Schuljahr zur Auswahl gestellt.

##Ergebnis der Datenprüfung auswerten 
Die Ergebnisse der Datenprüfung werden unter Hinweise aufgelistet. Sind dort keine Hinweise enthalten, sind die Daten für die Abgabe an das Statistikamt korrekt eingegeben. Die Hinweise werden unterschieden nach Art der Datei, dem betroffenen Datensatz, Kontroll-Nr der Plausibilität und dem eigentlichen Meldungstext. Sie können die Hinweise gruppieren und/oder Filtern und über die Schaltfläche „Export nach Excel“ nach Excel exportieren.
Sie müssen nun die Meldungen in MAGELLAN bearbeiten und dann erneut eine Datenprüfung durchführen.

>Viele in der Prüfung abgefragte Werte werden nicht in den Statistikdateien ausgegeben, dienen aber als Voraussetzung für die Plausibilitätsprüfungen. Beispiel: Zur Prüfung von  korrekten Fremdsprachen bei allgemeinbildenden Schulen muss die Schulart angegeben sein. Wurde diese nicht oder fehlerhaft angegeben, gibt die Prüfung eine Fehlermeldung aufgrund dieser Bedingung aus.



