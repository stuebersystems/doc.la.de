# BER-Schul II 799-3 - (Zeugnisliste Qualifikationsphase ISS-GemS-BG)(11.19)

[1]:/assets/images/Berlin/BER-Schul_II_799-3.png "Bericht"
[2]:/assets/images/Berlin/12.png "Berichtskopf"
[3]:/assets/images/Berlin/13.png "Mittelteil"
[4]:/assets/images/Berlin/14.png "Berichtsfuß"
[5]:/assets/images/Berlin/15.png "Fehlzeiten"

![Bericht][1]

## Ausdruck

Der Bericht kann aus dem Menü `Schüler` oder `Abitur` über `Drucken > Zeugnisse (STRG+Z)` ausgegeben werden.

## Berichtskopf

![Berichtskopf][2]

### Tutor

`Schüler > Zeugnis > Details > Tutor`<br/>`Lehrer > Daten1 > Anrede` <br/>`Lehrer > Daten1 > Nachname` <br/>`Lehrer > Daten1 > Geschlecht` 

Die Schüler-Tutor wird unter `Zeugnis > Details` eingegeben und kann je Halbjahr variieren. Für die Eingabe steht Ihnen eine Sammelzuweisung auf derselben Unterkarte zur Verfügung. Für die korrekte Ausgabe müssen für den Lehrerdatensatz der Nachname, die Anrede und das Geschlecht befüllt werden.

### Eintritt in die E-Phase

Dieses Jahr wird aus den Einträgen unter `Schüler > Laufbahn > Zugang` und der Angabe der Klassenart (wahlweise `Oberstufenjahrgang (nur Kurse)` oder `Oberstufenjahrgang (Leistungs- und Grundkurse)`). Es werden dabei vom ersten Zugangsdatum zu einer Oberstufenklasse die letzten vier Stellen, also das Jahr, ausgegeben.

### Schuljahr

`Extras > Schlüsselverzeichnisse > Zeiträume > Ausdruck2`

Für das Schuljahr wird die Eingabe aus dem Feld `Ausdruck2` des ausgewählten Zeitraums ausgegeben.

### Kurshalbjahr

`Extras > Schlüsselverzeichnisse > Zeiträume > Art` <br/> `Klassen > Zeiträume > Zeitraum > Jahrgang`

Dieser Wert wird aus dem Wert der Zeitraumart (1. oder 2. Halbjahr) und dem Klassenjahrgang errechnet und um den Begriff ".Semester" ergänzt.

## Mittelteil

![Mittelteil][3]

### Aufgabenbereiche

`Extras > Schlüsselverzeichnisse > Fächer > Aufgabenbereich`<br/> `Schüler > Zeugnis > Fächer/Leistungen`

Der Bericht sortiert die Fächer des Schülers je nach Eintrag des Aufgabenbereiches des Faches im Verzeichnis Fächer. Bitte überprüfen Sie in Ihrem Fächerverzeichnis die Zuordung der Aufgabenbereiche.

### Unterrichtsart "LF"

`Extras > Schlüsselverzeichnisse > Unterrichtsart`<br/> `Schüler > Zeugnis > Fächer > Unterrichtsart`

Die Unterrichtsart `LF` ergibt sich aus der Eingabe der Unterrichtsart `LK`.

Kürzel|Schlüssel|Bezeichnung
--|--|--
LK|LK|Leistungskurs

### Kursnummer It. V. Rahmenplan

`Extras > Schlüsselverzeichnisse > Fächer > Kürzel`<br/> `Schüler > Zeugnis > Fächer > Fach`<br/> `Schüler > Zeugnis > Fächer > Kursnummer`

Die Ausgabe wird aus dem Fachkürzel und dem Eintrag in der Spalte Kursnummer kombiniert.

### Lehrer(in)

`Lehrer > Daten1 > Kürzel`<br/> `Schüler > Zeugnis > Fächer > Lehrer`

Der unterrichtende Lehrer kann manuell oder per Fachtafel unter `Schüler > Zeugnis > Fächer > Lehrer` zugeordnet werden.

### Bemerkungen

Dieses Feld kann manuell nach dem Druck befüllt werden, es wird keine Eintrag aus Magellan ausgegeben.

### Zahl der Wochenstunden

Dieses Feld kann manuell nach dem Druck befüllt werden, es wird keine Eintrag aus Magellan ausgegeben.

## Berichtsfuß

![Berichtsfuß][4]

### Fehlzeiten

`Schüler > Zeugnis > Details`

Diese Angaben können je Schüler oder per Sammelzuweisung (Aufruf auf der Unterkarte `Details`) zugewiesen werden.

Bezeichnung<br/>im Bericht|Feld in<br/>Magellan
--|--
versäumte Tage| Fehltage
davon unentschuldigt|(Fehltage) davon unentschuldigt
versäumte Einzelstunde|Fehlstunden
davon unentschuldigt|(Fehlstunden) davon unentschuldigt
verspätet|Versäumnisse

![Fehlzeiten][5]

### Zeugnis erteilt am

`Schüler > Zeugnis > Details > Zeugnisdatum`

Diese Angaben können je Schüler oder per Sammelzuweisung (Aufruf auf der Unterkarte `Details`) zugewiesen werden.