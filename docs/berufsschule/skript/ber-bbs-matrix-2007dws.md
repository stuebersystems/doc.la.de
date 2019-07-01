# BER-BBS-Matrix-2007.dws

> #### warning::Wichtig!
>
> Weitere wichtige Informationen finden Sie in der MAGELLAN-Dokumentation im Abschnitt [`Regionales > Berlin`](https://doc.magellan6.stueber.de/regionales/berlin/bs.html)!



## Verordnung

Bei der Definition der Verordnung für das Skript „BER-BBS-Matrix-2007“ müssen Sie unter Typ „BER-BS“ angeben. 

## Fächer

Bei dem Skript „BER-BBS-Matrix-2007“ für das Bundesland Berlin sind die folgenden Angaben für das Fach Sport/Gesundheitsförderung und fakultative Fächer Voraussetzung.

## Sport/Gesundheitsförderung

Ob ein dem Schüler zugeordnetes Fach das Fach Sport/Gesundheitsförderung ist, richtet sich nach der Definition des Fachs im Verzeichnis der Fächer. 

|Kürzel	|Schlüssel	|Bedeutung|
|--|--|--|
|Spo|beliebig|Sport|

Kürzel (im abgebildeten Fall „Spo“ für Sport) und Schlüssel können dabei beliebig gewählt werden, entscheidend ist die Zuordnung des Fachs zur Kategorie „Sport“ im Verzeichnis der Fächer.

## Religion

Ob ein dem Schüler zugeordnetes Fach das Fach „Religion“ bzw. „Ethik“ ist, richtet sich nach der Definition des Fachs im Verzeichnis der Fächer. 

|Kürzel	|Schlüssel|	Bedeutung|
|--|--|--|
|Rel|beliebig|	Religion/Ethik|
|Eth|beliebig|	Religion/Ethik|

Kürzel (im abgebildeten Fall „Rel“ für Religion bzw. „Eth“ für Ethik) und Schlüssel können dabei beliebig gewählt werden, entscheidend ist die Zuordnung des Fachs zur Kategorie „Religion/Ethik“ im Verzeichnis der Fächer.

## Fakultative Fächer

Fakultative Fächer werden bei der Zuordnung der Fächer zum Schüler durch den Fachstatus „Wahlb“ gekennzeichnet, wie z.B.:

|Fach	|Fachstatus|
|--|--|
|Fra	|Wahlb|

Besitzt ein Fach die Kategorie „Religion/Ethik“ wird es automatisch als fakultatives Fach betrachtet. 
Das Fach Sport/Gesundheitsförderung und fakultative Fächer werden bei der Berechnung des Gesamt-notendurchschnitts in der Berufsschulmatrix nicht berücksichtigt.

## Wiederholer

Ob ein Schüler im jeweils letzten Zeitraum seiner Laufbahn die Klasse wiederholt, richtet sich nach dem Eintrag unter Ansicht „Schüler“/Laufbahn/Allgemein“ im Feld „Wiederholer“. Ist dieses markiert, wiederholt der Schüler die Klasse.

Für das Skript bedeutet dies, dass er kein Zeugnis zugewiesen bekommt. 

## Kammerprüfung

Ob ein Schüler bei Berufsschulabschluss die Kammerprüfung bestanden hat, richtet sich nach dem Eintrag unter Ansicht „Schüler/Laufbahn/Allgemein“ im Feld „Entscheidung“. Da dies ein Schlüsselfeld ist, müssen Sie unter „Verzeichnisse/Entscheidungen“ folgenden Eintrag definieren:

|Kürzel	|Schlüssel	|Bedeutung|
|--|--|--|
|J|beliebig|Kammerprüfung bestanden|

Bei keinem Eintrag im Feld „Entscheidung“ hat der Schüler die Kammerprüfung nicht bestanden.

## Höchster bisheriger Abschluss 

Für die Berechnung des zusätzlichen Abschlusses im obigen Abschnitt, muss für den Schüler festgehalten werden, ob er den Hauptschulabschluss besitzt. Dieser Abschluss wird pro Schüler unter der Ansicht ```Schüler > Daten 2 ```im Feld „Höchster Abschluss ABS/Abschluss“ bzw. „Höchster Abschluss BBS/Abschluss“ eingetragen. Für diese Felder muss unter ```Verzeichnisse > Abschlüsse (Extern)``` folgende Einträge definiert werden:

|Kürzel	|Schlüssel	|Bedeutung|
|--|--|--|
|HS	|HS	|Hauptschulabschluss|
|EHS|	EHS	|Erweiterter Hauptschulabschluss|
|MSA|	MSA	|Mittlerer Schulabschluss|
|BOS|	BOS	|Abschuss der Berufsoberschule|
|FH	|FH	|Abschluss Fachhochschulreife|
|ABI|	ABI	|Abschluss Abitur|

## Ausreichende Fremdsprachenkenntnisse

Ob ein Schüler bei Berufsschulabschluss ausreichende Fremdsprachenkenntnisse besitzt, richtet sich nach dem Eintrag unter Ansicht ```Schüler > Laufbahn > Allgemein``` im Feld „Empfehlung“. Da dies ein Schlüsselfeld ist, müssen Sie unter „Verzeichnisse/Empfehlungen“ folgenden Eintrag definieren:

|Kürzel	|Schlüssel	|Bedeutung|
|--|--|--|
|J|beliebig|Ausreichende Fremdsprachenkenntnisse|

Bei keinem Eintrag im Feld „Empfehlung“ hat der Schüler nicht ausreichende Fremdsprachenkenntnisse.

## Regelstundenzeit des Bildungsgangs

Ob ein Schüler bei Berufsschulabschluss die ausreichende Regelstundenzeit in seinem Bildungsgang besitzt, richtet sich nach den unter dem Bildungsgang des Schülers eingetragenen Regelstunden. Die Regelstunden eines Bildungsgangs definieren Sie unter „Verzeichnisse/Bildungsgänge“ im Feld „Statistik-ID“.

|Kürzel	|Schlüssel	|Bedeutung|Statistik-ID|
|--|--|--|--|
|beliebig|beliebig|beliebig|Anzahl der Regelstunden|

Einen Bildungsgang können Sie demnach beispielweise wie folgt definieren.

|Kürzel	|Schlüssel	|Bedeutung	|Statistik-ID|
|--|--|--|--|
|KFZ|KFZ|Feinmechatroniker|480|

Hat der Schüler weniger als 480 Stunden als Regelstundenzeit in seinem Bildungsgang, so muss er für das Erreichen des Mittleren Schulabschlusses den zusätzlichen allgemeinbildenden Unterricht mit Erfolg besucht haben. 

Ob ein Schüler den zusätzlichen  allgemeinbildenden Unterricht mit Erfolg besucht hat,  richtet sich nach dem Eintrag unter Ansicht „Schüler“/Merkmale im Feld „Merkmal A6“.

|Kürzel	|Schlüssel	|Bedeutung|
|--|--|--|
|J	|beliebig|Zusätzlicher Unterricht MSA erfolgreich besucht|

## Zeugnisformulare für Abschluss- und Abgangszeugnis

Da das Skript automatisch die jeweiligen Zeugnisformulare den Schülern zuordnet, müssen die Zeugnisformulare zuvor unter ```Verzeichnisse > Zeugnisformulare ```definiert werden. 

|Bezeichnung|	Typ|	Datei|
|--|--|--|
|BER-BS-AS|beliebig|beliebig|
|BER-BS-MSA|beliebig|beliebig|
|BER-BS-AZ|beliebig|beliebig|

> #### warning::Wichtig!
>
> Die Bezeichnungen BER-BS-AS für das Abschlusszeugnis, BER-BS-MSA für das Zusatzzeugnis Mittlerer Schulabschluss und BER-BS-AZ für das Abgangszeugnis sind fest vorgegeben.



