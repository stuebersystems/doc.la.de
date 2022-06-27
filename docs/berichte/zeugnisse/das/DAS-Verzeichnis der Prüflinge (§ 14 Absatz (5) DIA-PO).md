# DAS-Verzeichnis der Prüflinge (§ 14 Absatz (5) DIA-PO)

[1]:/assets/images/das/das35.02.png "DDAS-Verzeichnis der Prüflinge (§ 14 Absatz (5) DIA-PO)"
[2]:/assets/images/das/das36.png "Prüfungsfächer und Unterrichtssprache"

## Ausdruck

`Schüler > Auswahl > Drucken > Ausland` <br/>
`Abitur > Auswahl > Drucken > Ausland`

Zum Drucken der Prüfungslisten gehen Sie wie folgt vor:

1) Im Menü `Schüler/Abitur > Auswahl` markieren Sie die gewünschten Schüler.
2) Wählen Sie über `Start > Drucken > Ausland` aus.

[![DAS-Verzeichnis der Prüflinge (§ 14 Absatz (5) DIA-PO)][1]

## Mandant

Bitte erfassten Sie Ihren Schulnamen unter `Mandant > Name 1`.

## Zeitraum

Als Schuljahr wird für das beim Druck verwendete Halbjahr der Eintrag aus `Extras > Zeiträume > Ausdruck 1` ausgegeben.

## Geburtsjahr

Erfassen Sie das Geburtsdatum unter `Schüler > Daten1 > Geburtsdatum`.

## Staatsangehörigkeit

Erfassen Sie die Staatsangehörigkeit unter `Schüler > Daten1 > Staatsangehörigkeit 1`, dem Feld liegt das Verzeichnis `Staatsangehörigkeiten` unter `Extras > Schlüsselverzeichnisse` zugrunde.

## Erstsprache

Erfassen Sie die Erstsprache unter `Schüler > Daten1 > Muttersprache`, dem Feld liegt das Verzeichnis `Muttersprachen` unter `Extras > Schlüsselverzeichnisse` zugrunde.

## Fach und Fachstatus

Im Feld `Fach` wird der Eintrag des Fachkürzels aus `Menü Abitur > Qualifikation` ausgegeben, dabei wird das Fachkürzel nur ausgegeben, wenn dem Fach im Feld `Fachstatus` einen Wert aus der nachfolgenden Tabelle zugewiesen wurde, genutzt wird hierbei das Kürzel des Fachstatus.

Das Fach wird durch den Eintrag des `Fachstatus` markiert.

Der Fachstatus muss unter `Abitur > Qualifikation > Fachstatus` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus `Schüler > Zeugnis > Fächer > Fachstatus` übernommen werden.  
Prüfen Sie bitte unter `Extras > Schlüsselverzeichnisse > Fachstatus`,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

| Kürzel | Schlüssel | Bedeutung       |
|--------|-----------|-----------------|
| **1PF**    | 1PF       | 1. Prüfungsfach |
| **2PF**    | 2PF       | 2. Prüfungsfach |
| **3PF**    | 3PF       | 3. Prüfungsfach |
| **4PF**    | 4PF       | 4. Prüfungsfach |
| **5PF**    | 5PF       | 5. Prüfungsfach |

## Unterrichtssprache

Ausgewertet werden die Kurssprachen (`Q1Bilingual`-`Q4Bilingual`) unter `Abitur > Qualifikation`, der als Prüfungsfächer markierten Fächer. Der Bericht versucht als erstes die Kurssprache des Q4-Zeitraums auszugeben, ist sie nicht gefüllt, die des Q3-Zeitraums auszugeben usw.

Für die Einträge müssen die Verzeichnisse `Fächer`, `Fachstatus` und `Kurssprachen` entsprechend Ihrer Verordnung vorbefüllt sein.

[![Prüfungsfächer und Unterrichtssprache][2]

## Teilqualifikation im Bereich A

Der Wert wird aus dem per Skript zu berechnenden Feld unter `Abitur > Prüfung > Bereich 3` gelesen.

## Teilqualifikation im Bereich Q

Der Wert wird aus dem per Skript zu berechnenden Feld unter `Abitur > Prüfung > Bereich 3` gelesen.
