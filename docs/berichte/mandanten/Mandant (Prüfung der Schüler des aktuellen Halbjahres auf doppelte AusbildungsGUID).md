# Mandant (Prüfung der Schüler des aktuellen Halbjahres auf doppelte AusbildungsGUID)

[1]:/assets/images/mandanten/001.png "Kopf des Berichtes"
[2]:/assets/images/mandanten/001.png "doppelte ID gefunden"

## Ausdruck

Das Bericht muss aus dem Menü `Mandanten` gedruckt werden.

## Funktionsweise

Dieser Bericht ist speziell für sächsische Schulen gedacht. Der Bericht prüft über alle Schülerausbildungen des Mandanten für das ausgewählte Halbjahr ab, ob GUIDs der Ausbildungen gibt, die mehrfach vorkommen und unterschiedlichen Schülern zugewiesen wurden. Mehrfache GUIDs innerhalb der SchuelerAusbildungen sind kein Problem, solange die zugewiesenen Ausbildungen zum selben Schüler gehören. 
Der Bericht gibt alle SchuelerAusbildungen.GUIDs aus und zeigt die Anzahl an. Sollte der Fall auftauchen, dass eine GUID für SchuelerAusbildungen mehrerer Schüler verwendet wurde, werden für die betroffenen Schüler der Vorname, der Nachname und die Klasse ausgegeben. Für einen dieser Schüler ist dann bitte die Ausbildung neu anzulegen.
Ausgegeben werden Schüler für die keine Ausbildung erfasst wurde oder für die eine Ausbildung erfasst wurde, diese aber nicht als 

Keine Dopplungen gefunde: <br/> [![Bericht][1]][1]

Dopplung gefunden: <br/>[![doppelte ID gefunde][2]][2]
