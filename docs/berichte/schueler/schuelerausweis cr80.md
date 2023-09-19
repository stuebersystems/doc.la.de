# Schülerausweis (CR80)

[1]:/assets/images/schueler/cr80.png "Schülerausweis (CR80)"

[![Schülerausweis (CR80)][1]][1]

## Format

Der Bericht ist für Kartendrucker und den Kartentyp CR80 angepasst. **Bitte beachten Sie, dass Sie den Kartendrucker für die korrekte Ausgabe als Standarddrucker am Arbeitsplatz eingerichtet haben müssen.**

## Druck

Bitte markieren Sie die gewünschten Schüler im Menü `Schüler` und rufen den Bericht über `Drucken < Berichte` oder mit `STRG+P` auf.

## Schulname

`Mandant > Daten > Name1`<br/>`Mandant > Daten > Name2`<br/>`Mandant > Daten > Name2`<br/>

Für die Ausgabe des Schulnamens werden die drei Namensfelder aus dem Menü `Mandanten` verwendet.

## Logo

`Mandant > Daten2 > Logo`

Oben rechts kann ein Logo (1:1) aus dem Feld `Mandant > Daten > Logo` ausgegeben werden.

## Schülerfoto

`Schüler > Daten1 > Passfoto`

Das Schülerfoto wird aus dem Feld `Schüler > Daten1 > Passfoto` gelesen.

## Schülername

`Schüler > Daten1 > Vorname` <br/>`Schüler > Daten1 > 2.Vorname` <br/>`Schüler > Daten1 > Zusatz` <br/>`Schüler > Daten1 > Nachname` 

Das Namensfeld kann bei langen Namen zweizeilig ausgegeben werden. Die Namen werden je nach Angabe in MAGELLAN in folgender Reihenfolge ausgegeben: `Zusatz Nachname, Vorname 2.Vorname`.

## Weitere Schülerdaten

Ausgabe|Quelle
--|--
Geburtsdatum|`Schüler > Daten1 > Geburtsdatum`
Geburtsort|`Schüler > Daten1 > Geburtsort`
Gültig bis|`Schüler > Daten4 > Sonstige Daten > Gültig bis`
Gültig von|`Schüler > Daten4 > Sonstige Daten > Ausgestellt am`

!!! warning "Wichtig!"

    Bitte beachten Sie, dass die Felder `Gültig bis` und `Ausgestellt am` auch per Sammelzuweisung (`Menü Schüler > Reiter Schüler > Sammelzuweisung`) befüllt werden können.