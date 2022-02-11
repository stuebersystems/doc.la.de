# KV09b Masernschutz

[1]:/assets/images/berichte.schueler/KV09b_Masernschutz.png "KV09b_Masernschutz"

## Ausdruck

Der Bericht muss aus dem Menü `Schüler` gedruckt werden.

## Allgemein

Es werden im Berichtskopf die Schüler-/Sorgeberechtigtendaten aus den Einträgen in MAGELLAN ausgegeben. 

## Druckdatum und Ort

Das Druckdatum (Tagesdatum) und der Ort (`Mandanten > Daten > Ort`) werden automatisch eingefügt. Weitere Angaben im Bericht sind nach dem Druck manuell einzutragen.

## Volljährigkeit

Der Bericht prüft die Volljährigkeit des Schülers. Ist der Schüler ab dem Druckdatum volljährig, bleibt das Sorgeberechtigtenfeld leer, die Adressdaten (PLZ, Ort, Straße) und Kontaktdaten (E-Mail, Telefonnummer) des Schülers werden ausgegeben.

Ist der Schüler minderjährig, wird das Sorgeberechtigtenfeld gefüllt, es werden die Adressdaten (PLZ, Ort, Straße) und die Kontaktdaten (E-Mail, Telefonnummer) des Sorgeberechtigten ausgegeben.

!!! danger "Achtung"

    Aus der Liste unter `Schüler > Daten1 > Familie` werden (sortiert nach der Position) Sorgeberechtige ausgegeben, für die der Wert `Immer` im Feld `Benachrichtigung` eingetragen wurde.

[![KV09b_Masernschutztung][1]][1]
