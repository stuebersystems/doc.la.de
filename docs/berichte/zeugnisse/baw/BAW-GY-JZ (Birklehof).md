# BAW-GY-JZ (Birklehof).md





## Ausdruck

Dieser Bericht wird als Zeugnis gedruckt aus dem Menü `Schüler` gedruckt. Bitte markieren Sie die gewünschten Schüler und rufen den Druck mit `STRG+Z` oder über `Drucken  > Zeugnisse` auf.

## Seite 1

![Seite 1](/assets/images/baw/bh1.png)

### Zeugniskopf

#### Logo

`Mandanten > Daten2 > Logo1`
Bitte hinterlegen Sie die Logodatei unter `Mandanten > Daten2 > Logo1`. Der Bericht fragt die in diesem Feld hinterlegte Bilddatei ab und gibt sie im Zeugniskopf aus.

#### Schülername

`Schüler > Daten1 > Vorname` <br/>`Schüler > Daten1 > 2.Vorname` <br/>`Schüler > Daten1 > Zusatz` <br/>`Schüler > Daten1 > Nachname`

Der Bericht fügt die Daten aus Vorname, 2.Vorname, Zusatz und Nachnamen zusammen und gibt das Ergebnis aus.

#### Schuljahr

`Extras > Schlüsselverzeichnisse > Zeiträume > Ausdruck1`

Bitte erfassen Sie unter `Extras > Schlüsselverzeichnisse > Zeiträume > Ausdruck1` das Schuljahr in der gewünschten Form.

#### Verhalten und Mitarbeit

`Extras > Schlüsselverzeichnisse > Noten > Bezeichnung` <br/>`Schüler > Zeugnis > Details > Mitarbeit`<br/>`Schüler > Zeugnis > Details > Verhalten`

Bitte legen Sie im Schlüsselverzeichnis die gewünschten Noten mit der Notenart `Note` an, es wird der Eintrag aus dem Feld `Bezeichnung` ausgegeben. 
Weisen Sie den Schülern die individuelle Note unter `Schüler > Zeugnis > Details` in den Feldern `Verhalten` und `Mitarbeit` zu. Die Note kann hier manuell erfasst werden, per Sammelzuweisung vorbelegt werden oder aus MyMAGELLAN übernommen werden.

### Fachbereich

#### Positionen

`Extras > Schlüsselverzeichnisse > Fachtafeln > FachtafelFächer > Position` <br/>`Schüler > Zeugnis > Fächer > Position`

Dieser Zeugnisbericht gibt Fächer und Noten zweispaltig aus. Die Anordnung wird über die Fachposition gesteuert, Fächer mit einer ungeraden Position werden in der linken Spalte, Fächer mit einer geraden Position werden in der rechten Spalte ausgegeben. Die Fachpositionierung können Sie bereits in den Fachtafeln vorbereiten und so den Schülern mit den Fächern zuweisen.
Sollten bereits die Fächer ohne Position den Schülern zugeordnet worden sein, können Positionen manuell ergänzt oder auch nachträglich per Fachtafel zugewiesen werden, bitte beachten Sie hierfür folgenden Abschnitt der MAGELLAN Dokumentation: [https://doc.magellan.stueber.de/schulverwaltung/howto/zeugnisdaten1/#optionen-zum-verandern-bestehender-fachdaten](https://doc.magellan.stueber.de/schulverwaltung/howto/zeugnisdaten1/#optionen-zum-verandern-bestehender-fachdaten).

#### Fächer und Fachbezeichnungen

`Extras > Schlüsselverzeichnisse > Fächer > Bezeichnungen`<br/>`Extras > Schlüsselverzeichnisse > Fachtafeln`<br/>`Schüler > Zeugnis > Fächer`

Die auf dem Zeugnis ausgegebenen Fächer werden unter `Schüler > Zeugnis > Fächer` erwartet. Auf dem Zeugnis wird  die Bezeichnung des Fachs ausgegeben.
Die Zuweisung kann per Fachtafel erfolgen.

#### Benotung

`Extras > Schlüsselverzeichnisse > Noten` <br/>`Klassen > Daten > Beurteilung`<br/>`Schüler > Zeungis > Leistungen > Endnote` 

Erfassen Sie die Beurteilung bitte in der Spalte `Endnote`. Für das Zeugnis wird die der gewählten Noten im Schlüsselverzeichnis `Noten` hinterlegte Bezeichnung ausgegeben.

### Birklehof-Stunden

`Extras > Schlüsselverzeichnisse > Fachstatus`<br/>`Extras > Schlüsselverzeichnisse > Fächer > Bezeichnungen`<br/>`Schüler > Zeugnis > Fächer`<br/>`Schüler > Zeugnis > Position`

Legen Sie bitte unter `Extras > Schlüsselverzeichnisse > Fachstatus` bitte folgenden Wert an:

Kürzel|Schlüssel|Bezeichnung
--|--|--
**BHS**|BHS|Birklehof-Stunden

Legen Sie unter `Extras > Schlüsselverzeichnisse > Fächer` bitte alle möglichen Birklehof-Stunden als Fach an, das Zeugnis nutzt später für die Ausgabe den Eintrag im Feld `Bezeichnung.`
Weisen Sie den Schülern die belegten Fächer (Birklehof-Stunden) zu und vergeben bitte eine aufsteigende Position und den Fachstatus `BHS`.

### Bemerkungen

#### Positionierung

`Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`

Die Zuweisung von Zeugnisbemerkungen erfolgt im Menü `Schüler > Zeugnis > Formulare/Zeugnisbemerkungen`. Wenn Sie die Schaltfläche "Hinzufügen" anklicken, können Sie eine Zeugnisbemerkung definieren, die ausschließlich für den markierten Schüler gültig ist oder eine zuvor in den Verzeichnissen definiert allgemeingültige Zeugnisbemerkung auswählen und zuweisen.
Für die Ausgabe der Zeugnisbemerkungen muss über das Feld "Position" eine Reihenfolge (Nummerierung) vorgegeben werden. Z.B. für die Ausgabe der ersten Bemerkung "1", für die Ausgabe der zweiten Bemerkung "2" usw.

#### Platzhalter

`Schüler > Zeugnis > Bemerkungen/Formulare` 

Bemerkungen legen Sie im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` an.
Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren. 
Einen Platzhalter definieren Sie über „<<“ zum Beginn und „>>“ zum Ende Ihres Platzhalters, z.B. so:  ````<<hier steht Ihr Platzhalter>>````. 

Möglich sind:

Platzhalter in MAGELLAN | Anzeige im Bericht
--|--
``<<Vorname>>`` | Vorname
``<<VornameV>>`` | Vorname Vorname2
``<<Nachname>>`` | Nachname
``<<NachnameV>>`` | Namenszusatz Nachname
``<<Name>>`` | Vorname Vorname2 Namenszusatz Nachname
``<<Er_Sie>>`` | Er/Sie (je nach Geschlecht des Schülers)
``<<er_sie>>`` | er/sie (je nach Geschlecht des Schülers)
``<<Seine_Ihre>>`` | Seine/Ihre (je nach Geschlecht des Schülers)   
``<<seine_ihre>>`` | seine/ihre (je nach Geschlecht des Schülers) 
``<<Ihm_Ihr>>`` | Ihm/Ihr (je nach Geschlecht des Schülers) 
``<<ihm_ihr>>`` | ihm/ihr (je nach Geschlecht des Schülers) 
``<<Seinen_Ihren>>`` | Seinen/Ihnen (je nach Geschlecht des Schülers) 
``<<seinen_ihren>>`` | seinen/ihnen (je nach Geschlecht des Schülers) 
``<<DerSchueler_DieSchuelerin>>`` | Der Schüler/Die Schülerin je nach Geschlecht des Schülers)
``<<derSchueler_dieSchuelerin>> `` | der Schüler/die Schülerin (je nach Geschlecht des Schülers) 
``<<DemSchueler_DerSchuelerin>> `` | Dem Schüler/Der Schülerin (je nach Geschlecht des Schülers)

## Seite 2

![Seite 1](/assets/images/baw/bh1.png)

### Verbalbeurteilung

`Schüler > Zeugnis > Leistungen > Beurteilung`

Wenn eine zusätzliche Beurteilung für ein Fach gewünscht ist, erfassen Sie diese bitte je Fach unter `Schüler > Zeugnis > Leistungen > Beurteilung`. Das Fach muss nicht Teil der Beurteilung sein, wir geben das Fach bereits mit einem Doppelpunkt aus.

Beispiel:
* Mathematik: Text der verbalen Beurteilung

Der Aufzählungspunkt, das Fach "Mathematik" und der Doppelpunkt dahinter werden vom Bericht erzeugt.

### Weiteres Engagement

Erfassen Sie bitte für die Einträge unter "Weiteres Engagement" Bemerkungen unter `Schüler > Zeugnis > Bemerkungen/Formulare`. Jeder Bemerkung weisen Sie bitte eine Position zu, die sich nicht doppeln darf. Um die Bemerkung nicht im allgemeinen Bemerkungsbereich auszugeben, tragen Sie bitte im Zeugnismerkmal `VB` ein. 

#### Platzhalter

`Schüler > Zeugnis > Bemerkungen/Formulare` 

Bemerkungen legen Sie im Menü `Schüler > Zeugnis > Bemerkungen/Formulare` an.
Sie können Zeugnisbemerkungen über Platzhalter auch personalisieren. 
Einen Platzhalter definieren Sie über „<<“ zum Beginn und „>>“ zum Ende Ihres Platzhalters, z.B. so:  ````<<hier steht Ihr Platzhalter>>````. 

Möglich sind:

Platzhalter in MAGELLAN | Anzeige im Bericht
--|--
``<<Vorname>>`` | Vorname
``<<VornameV>>`` | Vorname Vorname2
``<<Nachname>>`` | Nachname
``<<NachnameV>>`` | Namenszusatz Nachname
``<<Name>>`` | Vorname Vorname2 Namenszusatz Nachname
``<<Er_Sie>>`` | Er/Sie (je nach Geschlecht des Schülers)
``<<er_sie>>`` | er/sie (je nach Geschlecht des Schülers)
``<<Seine_Ihre>>`` | Seine/Ihre (je nach Geschlecht des Schülers)   
``<<seine_ihre>>`` | seine/ihre (je nach Geschlecht des Schülers) 
``<<Ihm_Ihr>>`` | Ihm/Ihr (je nach Geschlecht des Schülers) 
``<<ihm_ihr>>`` | ihm/ihr (je nach Geschlecht des Schülers) 
``<<Seinen_Ihren>>`` | Seinen/Ihnen (je nach Geschlecht des Schülers) 
``<<seinen_ihren>>`` | seinen/ihnen (je nach Geschlecht des Schülers) 
``<<DerSchueler_DieSchuelerin>>`` | Der Schüler/Die Schülerin je nach Geschlecht des Schülers)
``<<derSchueler_dieSchuelerin>> `` | der Schüler/die Schülerin (je nach Geschlecht des Schülers) 
``<<DemSchueler_DerSchuelerin>> `` | Dem Schüler/Der Schülerin (je nach Geschlecht des Schülers)

### Zeugnisfuß Seite 2

Feld| Quelle
--|--
Versetzt nach| Der Wert wird aus `Klasse > Zeiträume > Jahrgang` gelesen und um 1 Jahr erhöht.
Ort|Der Ort wird in Magellan unter `Mandanten > Daten > Ort` ausgelesen.
Datum|Das Zeugnisdatum wird unter `Schüler > Zeugnis > Details > Zeugnisdatum` ausgelesen. Bitte nutzen Sie die Sammelzuweisung am oberen Fensterrand.
Klassenlehrer| Der Klassenlehrer wird unter `Klasse > Zeiträume > Klassenleiter1` erwartet. Bitte prüfen Sie, ob unter `Lehrer > Geschlecht` der korrekte Eintrag erfolgte.
Schulleiter|Der Schulleiter wird unter `Mandanten > Daten > Schulleiter` erwartet. Bitte prüfen Sie, ob unter `Lehrer > Geschlecht` der korrekte Eintrag erfolgte.