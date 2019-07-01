# DAVINCI: Daten mit WinLD austauschen

DAVINCI kann Daten für diverse Landesstatistiken exportieren bzw. importieren. Starten Sie dazu in DAVINCI über ```Plan > Importieren und Exportieren``` den Import und Export-Assistenten.

![Beschriftung](/assets/images/winld/winld.png)

## Allgemein
DAVINCI importiert Lehrer-, Klassen-, Fachstammdaten aus WinLD und exportiert Unterrichtsdaten nach WinLD. Bitte beachten Sie die Unterschiede beim Exportverfahren zwischen allgemeinbildenden und berufsbildenden Schulen.

#### Was Sie allgemein beachten sollten

Verwenden Sie in DAVINCI keine Blockungen mit unterschiedlichen Stundenzahlen. WinLD kann derartige Blockungen leider nicht verarbeiten. Splitten Sie stattdessen die Blockungen in DAVINCI.
Zur Übertragung der Unterrichtsart wird der Eintrag im Feld „Fachstatus“ herangezogen. Erfassen Sie die Fachstatus im Menü ```Extras > Schlüsselverzeichnisse > Fachstatus```. In der Spalte „Schlüssel“ muss der von WinLD vorgegebene Schlüssel eingetragen werden. Weisen Sie den einzelnen Fächern in der Unterrichtsverteilung den entsprechenden Fachstatus zu.

Kürzel	|Schlüssel
--------|--------
Pflicht1-4|	1
Pflicht5-6|	2
Pflicht7-9/7-10	|3
Pflicht10|	4
Pflicht11	|5
Kollegstufe	|6
	|7
	|8
	|9
Pflicht-BOS	|s
Pflicht-BOS	|t
Pflicht-BOS |v
Wahlunterr.	|w
Ergänz.unt.	|e
Förderunt.	|f
Förderunt.	|g
Arbeitsgem.	|a
Arbeitsgem. |N
Pluskurs	|P
Hausunterr. |K

## Hinweise für berufsbildende Schulen

Bitte beachten Sie, dass die im DAVINCI-Planfenster für einen Lehrer unter der Unterrichtsverteilung angezeigte "Ist"-Stundenzahl etwas von der in WinLD errechneten Stundensumme abweichen kann. Der Grund dafür ist, dass die in DAVINCI angezeigte Summe einen Mittelwert errechnet aus dem in DAVINCI angegebenen Wochenschema darstellt, die von DAVINCI nach WinLD exportierten Daten aber genauer sind, da hier zusätzlich der tatsächliche Planungszeitraum (Start-/Enddatum aus dem Zeitrahmen-Fenster) und die Kalendereinträge (Ferien-, Feiertage usw.) berücksichtigt werden. Etwaige Vertretungsplaninformationen werden NICHT berücksichtigt. 

Sollten Sie in den Kalender einen schulfreien Tag oder schulfreie Stunden eingetragen haben, werden diese Angaben beim Export ebenfalls berücksichtigt, d.h. nicht gezählt. In der aktuellen Schnittstellenbeschreibung zu WinLD ist derzeit nicht definiert, welche Tage für die Statistik erfasst werden sollen und welche nicht.

## Wiederholungsfaktor bei berufsbildenden Schulen

Bei berufsbildenden Schulen muss der Wiederholungsfaktor (die Anzahl der Wochen, in denen z.B. eine Stunde BWL montags stattfindet) an WinLD übergeben werden. DAVINCI errechnet den Wiederholungsfaktor automatisch aufgrund folgender Angaben:

* Planungszeitraum gemäß Extras > Zeitrahmen > Hauptzeitrahmen

* Kalender (Ansicht „Kalender“)

* Wochenangabe für die Veranstaltung (z.B. 14tägig, 1. Woche) 

* Tatsächlich verplanter Tag laut Stundenplan

Der Periodenfaktor wird beim WinLD-Export nicht beachtetet und auch nicht exportiert. Achten Sie unbedingt darauf, im DAVINCI-Kalender alle Ferientage und Feiertage einzutragen, andernfalls kann der Wiederholungsfaktor nicht korrekt berechnet werden. Für allgemeinbildende Schulen spielt der Wiederholungsfaktor keine Rolle.

## Importieren der Daten aus WinLD nach DAVINCI 

DAVINCI kann Daten der WinLD-Dateien STDFACH.TXT, STDLEHR.TXT und STDKLASS.TXT importieren. Sie müssen die Dateien nacheinander importieren. Bitte halten Sie beim Import folgende Reihenfolge ein, da z.B. die Klassendatei einen Verweis auf Klassenlehrer enthält, die bereits zuvor eingelesen worden sein müssen.
* Fach-Stammdaten (Datei “STDFACH.TXT”)
* Lehrer-Stammdaten (Datei “STDLEHR.TXT”)
* Klassen-Stammdaten (Datei “STDKLASS.TXT”)

![Assistent](/assets/images/winld/winld1.png)

So importieren Sie WinLD-Daten:
1. Klicken Sie dazu in DAVINCI auf ```Plan > Importieren und Exportieren```.
2. Klicken Sie auf ```Bayern WinLD Daten importieren```.
3. Geben Sie den Namen der Datei an, in die Sie importieren möchten (STDFACH.TXT, STDLEHR.TXT oder STDKLASS.TXT).
4. Klicken Sie auf ```OK```. Die Daten werden durch das Skript nach DAVINCI importiert. Wiederholen Sie die Schritte mit der nächsten Datei.

## Exportieren der Daten aus DAVINCI nach WinLD

DAVINCI kann Unterrichtsdaten für berufsbildende Schulen direkt nach WinLD exportieren. Je Veranstaltungszeile werden Klasse, Fach, Lehrer, Stunden, Blocknummer, Raum, Jahrgang und Lehrer-Ist nach WinLD exportiert.

![Assistent](/assets/images/winld/winld2.png)
So exportieren Sie WinLD-Daten:
1. Klicken Sie dazu in DAVINCI auf ```Plan > Importieren und Exportieren```.
2. Klicken Sie auf ```Statistk Bayern BBS (WinLD) importieren```.
3. Geben Sie den Namen der Datei an, in die Sie exportieren möchten.
4. Klicken Sie auf ```OK```. Die Daten werden in die angegebene Datei konvertiert.
5. Starten Sie WinLD und lesen Sie die Datei dort ein.


