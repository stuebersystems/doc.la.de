# BER-Schul Z 502 (09.19).rpt

Schul Z 502 – Zeugnis der Berufsschule über den mittleren Schulabschluss – (2 Seiten) – (09.19)

## Beruf Schüler

`Schüler > Ausbildung > Ausbildungbetriebe > Beruf`

Tragen Sie im Menü `Schüler > Ausbildung` im aktuellen Zeitraum über das Hinzufügen oder Bearbeiten eines Ausbildungsbetriebes im Feld "Beruf" den Beruf ein. Grundlage bildet das Schlüsselverzeichnis Berufe.

## Schulname

`Mandanten > Daten > Name 1`

Tragen Sie die Bezeichnung Ihrer Schule im Menü `Mandanten > Daten 1` im Feld "Name 1" ein.

## Gesamtnote Berufsschulmatrix

`Berufsschule > Matrix > Gesamtnote`

Tragen Sie die Durchschnittsnote des jeweiligen Schülers im Menü `Berufsschule > Matrix` im Feld "Gesamtnote" ein. Diese wird auch automatisch durch das Berufsschulskript berechnet und entsprechend hinterlegt.

## Ausdruck

Das Zeugnis/der Bericht muss aus dem Menü `Berufsschule` gedruckt werden.

## Zeugnisbemerkungen Bereich Berufsschule

`Berufsschule > Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Berufsschule > Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

## Schulname

`Mandanten > Daten 1 > Name 3`

Tragen Sie den Bezirk Ihrer Schule im Menü `Mandanten > Daten 1` im Feld "Name 3" ein.

## Konferenzdatum Berufsschule

 `Berufsschule > Matrix > Konferenzdatum`

Tragen Sie das Datum des Abschlusszeugnisses im Menü `Berufsschule > Matrix` im Feld "Konferenzdatum" ein.

## Zeugnisdatum Berufsschule

`Berufsschule > Matrix > Zeugnisdatum`

Tragen Sie das Datum des Abschlusszeugnisses im Menü `Berufsschule > Matrix` im Feld "Zeugnisdatum" ein.

## Zugang am/Abgang am bzw. 2. Zugang am/2. Abgang am

`Schüler > Daten 2 > Zugang am/Abgang am bzw. 2. Zugang am/2. Abgang am`

Ist das Feld "2. Zugang am" im Menü `Schüler > Daten 2` gefüllt, wird auf dem Zeugnis "2. Zugang am" und "2. Abgang am" ausgegeben, ansonsten "Zugang am" und "Abgang am".

## Schulname

`Mandanten > Daten > Name 2`

Tragen Sie die Namenszusätze Ihrer Schule im Menü `Mandanten > Daten 1` im Feld "Name 2" ein.

## Platzhalter in Zeugnisbemerkungen

`Schüler > Zeugnis > Bemerkungen/Formulare`und `Abitur > Abitur > Zeugnis > Zeugnisbemerkungen` und `Berufsschule > Zeugnisbemerkungen`

Bemerkungen legen Sie entweder im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` ODER im Menü `Abitur > Zeugnis > Zeugnisbemerkungen` ODER `Abitur > Zeugnis > Zeugnisbemerkungen` an. Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren. 
Einen Platzhalter definieren Sie über „<<“ zum Beginn und „>>“ zum Ende Ihres Platzhalters, z.B. So <<hier steht Ihr Platzhalter>>. 

Möglich sind:

Platzhalter in Magellan | Anzeige im Bericht
--|--
``<<Vorname>>`` | Vorname Vorname2
``<<Nachname>>`` | Nachname
``<<NachnameV>>`` | Namenszusatz Nachname
``<<Name>>`` | Vorname Vorname2 Namenszusatz Nachname
``<<Name>>`` | Vorname, Vorname2, Namenszusatz und Nachname des Schülers
``<<Nachname>>`` | Nachname des Schülers
``<<Vorname>>`` | Vorname, Vorname2 und Namenszusatz des Schülers
``<<Er_Sie>>`` | Er/Sie (je nach Geschlecht des Schülers)
``<<Seine_Ihre>>`` | Seine/Ihre (je nach Geschlecht des Schülers)   
``<<seine_ihre>>`` | seine/ihre (je nach Geschlecht des Schülers) 
``<<Ihm_Ihr>>`` | Ihm/Ihr (je nach Geschlecht des Schülers) 
``<<ihm_ihr>>`` | ihm/ihr (je nach Geschlecht des Schülers) 
``<<Seinen_Ihren>>`` | Seinen/Ihnen (je nach Geschlecht des Schülers) 
``<<seinen_ihren>>`` | seinen/ihnen (je nach Geschlecht des Schülers) 
``<<DerSchueler_DieSchuelerin>>`` | Der Schüler/Die Schülerin je nach Geschlecht des Schülers) ``
``<<derSchueler_dieSchuelerin>> `` | der Schüler/die Schülerin (je nach Geschlecht des Schülers) 
``<<DemSchueler_DerSchuelerin>> `` | Dem Schüler/Der Schülerin (je nach Geschlecht des Schülers)

## Ausreichende Fremdsprachenkenntnisse

`Schüler > Laufbahn > Allgemein`

Ausreichende Fremdsprachenkenntnisse: Ob ein Schüler bei Berufsschulabschluss ausreichende Fremdsprachenkenntnisse besitzt, richtet sich nach dem Eintrag unter Ansicht `Schüler > Laufbahn > Allgemein` im Feld „Empfehlung“. Da dies ein Schlüsselfeld ist, müssen Sie unter `Schlüsselverzeichnisse > Empfehlungen` folgenden Eintrag definieren:

Kürzel | Schlüssel | Bedeutung
--|--|--
J | beliebig | Ausreichende Fremdsprachenkenntnisse

Bei keinem Eintrag im Feld „Empfehlung“ hat der Schüler nicht ausreichende Fremdsprachenkenntnisse.

## Berechnungsskript

`BER-BBS-Matrix-2016.dws`

Um eine zeitraumübergreifenden Endnotenberechnung der Berufsschule in Magellan auszuführen, lesen Sie bitte unsere Onlinedokumentation:

[https://doc.la.stueber.de/berufsschule/](https://doc.la.stueber.de/berufsschule/)
[https://doc.la.stueber.de/03.ber/ber-bbs-matrix-2016dws/](https://doc.la.stueber.de/03.ber/ber-bbs-matrix-2016dws/)

## Zeugnisdatum

`Berufsschule > Matrix > Zeugnisdatum`

Das BIS-Datum für den Besuch des Schülers an der Schule wird aus dem Feld "Zeugnisdatum" im Menü `Berufsschule > Matrix` gezogen.