# Allgemeines

Allgemeine Formulare, die Zeugnisformulare und deren Anwendung werden im Modul `MAGELLAN-Berichte` beschrieben, das Sie nach der Installation unter `Start > Programme > STÜBER SYSTEMS` finden.

## DAVINCI Landesanpassungen

Als Teil der DAVINCI Landesanpassung werden folgende landesspezifische Funktionen bzw. Daten zur Verfügung gestellt bzw. installiert:
1.	Die Fachwahlüberprüfung für Ihr Bundesland Sie kann Teil von DAVINCI KURSPLAN sein.
2.	Die Lehrer-Soll-Berechnungsschlüssel, d.h. die Mehrarbeits- und Ermäßigungsgründe für die Lehrer. Sie werden als keys-Datei für Ihr Bundesland installiert.

## MAGELLAN Landesanpassungen

Als Teil der Landesanpassung werden in MAGELLAN folgende landesspezifische Funktionen bzw. Daten zur Verfügung gestellt bzw. installiert:
* Die Fachwahlüberprüfung unter `MAGELLAN > Abitur >Fachwahl` für Ihr Bundesland 
* Die Schlüsselverzeichnisse für Ihr Bundesland 
* Die Abiturqualifikationsberechnungen für Ihr Bundesland 
* Die Landesstatistik (siehe gesonderte Dokumentation)


# Schlüsselverzeichnisse

Schlüsselverzeichnisse spielen in MAGELLAN und DAVINCI eine zentrale Rolle. 
Jeder Eintrag in diesen Verzeichnissen besteht mindestens aus `Kürzel` und `Schlüssel`. 
Das Kürzel wird in MAGELLAN und DAVINCI zur Anzeige verwendet, der Schlüssel wird für Berichte, die Landesstatistik und für die Fachwahlüberprüfung bzw. die Abiturqualifikation verwendet.

> #### primary::Hinweis
>
> Viele Werte sind durch den Import der Schlüsselverzeichnisse bereits korrekt gefüllt, bitte prüfen Sie aber dennoch vorab, ob die pro Skript oder Bericht erwarteten Werte in Ihrem Verzeichnis enthalten sind oder ggfs. ergänzt werden müssen. Welche genau das sind, beschreiben wir im jeweiligen Unterpunkt pro Skript oder für Berichte im Modul MAGELLAN Berichte.

Beim Datenabgleich zwischen MAGELLAN und DAVINCI werden die Schlüsselverzeichnisse `Unterrichtsarten` und `Fachstatus` aus Sicherheitsgründen nicht mit abgeglichen.


# Lehrer-Soll-Berechnungsschlüssel

Die Lehrer-Soll-Berechnungsschlüssel werden in DAVINCI für das individuelle Soll-Berechnungsschema des einzelnen Lehrers benötigt. Mit ihnen geben Sie an, welche Ermäßigungs- und Mehrarbeitsstunden jeder Lehrer erhält. Die Lehrer-Soll-Berechnungsschlüssel geben Sie im DAVINCI-Basismodul im Stammdatenfenster auf der Registerkarte `Lehrer`  über `Arbeitszeitkonto bearbeiten` (rechte Maustaste auf Lehrerkürzel) ein.
Bei der Installation von DAVINCI werden alle verfügbaren Soll-Berechnungsschlüssel im Unterverzeichnis `Schlüssel` im DAVINCI-Verzeichnis installiert. Die Schlüsseldateien sind nach dem jeweiligen Bundesland benannt und haben die Endung .Keys“. 

# Abkürzungen

Nachfolgende werden folgende Abkürzungen erklärt:

* [Allgemeine Abkürzungen](abkurzungen_allgemeine_abkurzungen.md)  
* [Abkürzungen in Meldungen](abkurzungen_abkurzungen_in_meldungen.md)  
* [Abkürzungen für Bundesländer](abkurzungen_abkurzungen_der_bundeslander.md)  


# Allgemeine Abkürzungen

Folgende Abkürzungen werden in den nachfolgenden Kapiteln verwendet:


| Abkürzung   | Bezeichnung                  |
|-------------|------------------------------|
| ABS         | allgemeinbildende Schule     |
| ABI         | Abitur                       |
| AG          | Abendgymnasium               |
| APO         | Abiturprüfungsordnung        |
| AS          | Abschlusszeugnis             |
| AZ          | Abgangszeugnis               |
| BBS         | berufsbildende Schule        |
| BF          | Berufsfachschule             |
| BGJ         | Berufsgrundschuljahr         |
| BG          | Berufliches Gymnasium        |
| BKO         | Berufskolleg                 |
| BS          | Berufsschule                 |
| BV          | Berufsvorbereitende Maßnahme |
| BVJ         | Berufsvorbereitungsjahr      |
| FG          | Fachgymnasium                |
| FO oder FOS | Fachoberschule               |
| FSP         | Fremdsprache                 |
| FS          | Fachschule                   |
| GES         | Gesamtschule                 |
| GS          | Grundschule                  |
| GY          | Gymnasium                    |
| HA          | Handelsschule                |
| HBF         | Höhere Berufsfachschule      |
| HHA         | Höhere Handelsschule         |
| HJ          | Halbjahr                     |
| HJZ         | Halbjahreszeugnis            |
| HS          | Hauptschule                  |
| IGS         | Integrierte Gesamtschule     |
| JZ          | Jahreszeugnis                |
| KO          | Kolleg                       |
| MIT         | Mittelschule                 |
| REG         | Regionale Schule             |
| RGL         | Regelschule                  |
| RS          | Realschule                   |
| SEK         | Sekundarschule               |
| SO          | Sonderschule                 |
| ÜZ          | Übergangszeugnis             |
| WG          | Wirtschaftsgymnasium         |



# Abkürzungen in Meldungen

Als Ergebnis der Fachwahlüberprüfung in MAGELLAN und DAVINCI KURSPLAN werden ggf. Hinweise ausgegeben, z.B. „NW, FS nicht abgedeckt“. 

Die Bedeutung der Abkürzungen können Sie der nachfolgenden Tabelle entnehmen:


| Merkmal | Bedeutung                                |
|---------|------------------------------------------|
| D       | Deutsch                                  |
| FS      | Fremdsprachen                            |
| Ge      | Geschichte                               |
| Che     | Chemie                                   |
| M       | Mathematik                               |
| NW      | Naturwissenschaft                        |
| Sport   | Sport                                    |
| R/Eth   | Religion/Ethik                           |
| Phy     | Physik                                   |
| Bio     | Biologie                                 |
| Inf     | Informatik                               |
| GK      | Gemeinschaftskunde bzw. Gesellschaftskunde |
| Ku      | Kunst                                    |
| KF      | Künstlerisches Fach, d.h. Kunst bzw. Musik |
| Pol     | Politische Bildung bzw. Politik          |
| Spiel   | Darstellendes Spiel                      |
| LF      | Leistungsfach                            |
| Phi     | Philosophie                              |
| Bereich | Aufgabenbereich bzw. Aufgabenfeld        |
| Erd     | Erdkunde                                 |


# Abkürzungen der Bundesländer/Länder

Folgende Abkürzungen werden für die Bundesländer verwendet:


| Abkürzung | Bezeichnung                          |
|-----------|--------------------------------------|
| ALL       | Allgemein, d.h. bundeslandunabhängig |
| BAW       | Baden-Württemberg                    |
| BAY       | Bayern                               |
| BRA       | Brandenburg                          |
| BRE       | Bremen                               |
| HAM       | Hamburg                              |
| HES       | Hessen                               |
| MVP       | Mecklenburg-Vorpommern               |
| NIE       | Niedersachsen                        |
| NRW       | Nordrhein-Westfalen                  |
| RLP       | Rheinland-Pfalz                      |
| SAA       | Sachsen-Anhalt                       |
| SAR       | Saarland                             |
| SAC       | Sachsen                              |
| SHL       | Schleswig-Holstein                   |
| THÜ       | Thüringen                            |
| DAS       | Deutsche Auslandsschulen             |
