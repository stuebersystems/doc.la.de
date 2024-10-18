# Schülerliste (für CSV-Export) mit Elterndaten.rpt


[01]:/assets/images/schueler/griechisch/012.png "Bericht"
[02]:/assets/images/schueler/griechisch/005.png "Vorschau"
[03]:/assets/images/schueler/griechisch/006.png "Speichern"
[04]:/assets/images/schueler/griechisch/007.png "4"
[05]:/assets/images/schueler/griechisch/008.png "5"
[06]:/assets/images/schueler/griechisch/009.png "6"
[07]:/assets/images/schueler/griechisch/010.png "7"
[08]:/assets/images/schueler/griechisch/011.png "8"


[![Bericht][01]][01]

Der Bericht ist nicht für den Druck gedacht, sondern dient dazu, die aus Magellan gelesenen Daten aus der Berichtsvorschau heraus als Excel-Datei (Nur Daten *.xls) zu exportieren..

## Aufruf

Der Bericht kann aus dem Menü `Schüler` heraus in der Vorschau aufgerufen werden. Markieren Sie die gewünschten Schüler, klicken `STRG+P` oder wählen `Start > Drucken > Berichte drucken` und wählen dann die `Vorschau` (`STRG+V`).

## Ausgabe

Der Bericht erzeugt eine Kopfzeile und je markierten Schüler eine Datenzeile. 
Sollten in Textfeldern Anführungszeichen oder Semikola enthalten sein (Beispielsweise als Vorname ist "Klaus ; Gregor "; Bertram"), werden diese vom Bericht verdoppelt, damit Excel sie korrekt als Inhalt interpretiert und nicht als Trennzeichen für neue Spalten.
Der Bericht gibt für die ersten beiden für den Schüler unter `Schüler > Daten1 > Familie` erfassten Datensätze die Felder Vorname, Nachname, Mobilnummer und E-Mailadresse aus.

## Aufbau

Kopfzeile: `"Aριθμός ατομικού φακέλου /Aριθμός προσωρινής προστασίας";"ΟΝΟΜΑ ΜΑΘΗΤΗ";"ΕΠΩΝΥΜΟ ΜΑΘΗΤΗ";...`

Datenzeile: `"leer";"Vorname des Schülers";"Nachname des Schülers";...`


Kopfspalte| Inhalte
---|---
Aριθμός ατομικού φακέλου /Aριθμός προσωρινής προστασίας|leer
ΟΝΟΜΑ ΜΑΘΗΤΗ|Vorname des Schülers
ΕΠΩΝΥΜΟ ΜΑΘΗΤΗ|Nachname des Schülers
ΟΝΟΜΑ ΠΑΤΕΡΑ|Vorname des Schülerkontakt1
ΕΠΩΝΥΜΟ ΠΑΤΕΡΑ|Nachname des Schülerkontakt1
ΟΝΟΜΑ ΜΗΤΕΡΑΣ|Vorname des Schülerkontakt2
ΟΝΟΜΑ ΚΗΔΕΜΟΝΑ|leer
ΕΠΩΝΥΜΟ ΚΗΔΕΜΟΝΑ|leer
ΓΕΝΟΣ ΜΗΤΕΡΑΣ|Nachname des Schülerkontakt2
ΦΥΛΟ|Α für männlich und Θ für weiblich
ΗΜΕΡΟΜΗΝΙΑ ΓΕΝΝΗΣΗΣ (Μορφή ΗΗ/ΜΜ/ΕΕΕΕ, π.χ. 14/10/2002 ή 3/6/2007)|Geburtsdatum des Schülers 
ΤΙΤΛΟΣ ΕΙΣΟΔΟΥ (για το τρέχον Σχ. Έτος)|leer
ΤΑΞΗ ΕΓΓΡΑΦΗΣ Klasse|Klassenkürzel
ΟΜΑΔΑ ΠΡΟΣΑΝΑΤΟΛΙΣΜΟΥ/ΚΑΤΕΥΘΥΝΣΗ ΓΕΛ ή ΚΥΚΛΟΣ/ΤΟΜΕΑΣ/ΕΙΔΙΚΟΤΗΤΑ ΕΠΑΛ (ΜΟΝΟ ΓΙΑ ΓΕΛ ή ΕΠΑΛ, διαφορετικά κενό) |leer
ΚΩΔ. ΥΠΑΙΘ ΣΧ. ΜΟΝΑΔΑΣ ΠΡΟΕΛΕΥΣΗΣ|leer
ΑΡΙΘΜΟΣ ΒΙΒΛΙΟΥ ΜΗΤΡΩΩΝ (ο αριθμός του Βιβλίου στο οποίο είναι γραμμένοι οι Μαθητές)|leer
ΑΡΙΘΜΟΣ ΜΗΤΡΩΟΥ ΜΑΘΗΤΗ (ΟΧΙ Αρ. Δημοτολογίου)|Magellan SchuelerID
ΔΙΕΥΘΥΝΣΗ |Schueler.Strasse
ΤΚ|Schueler.PLZ
ΠΕΡΙΟΧΗ|Schueler.Ort
ΔΗΜΟΤΙΚΗ ΕΝΟΤΗΤΑ|leer
ΤΗΛΕΦΩΝΟ|Schueler.Telefon
ΤΗΛΕΦΩΝΟ ΚΗΔΕΜΟΝΑ (1)|Mobil Schuelerkontakt1
Αριθμός Δημοτολογίου|leer
Δημοτική Ενότητα Δημοτολογίου|leer
Αριθμός Μητρώου Αρρένων|leer
Δημοτική Ενότητα Μητρώου Αρρένων|leer
Επάγγελμα Πατέρα (αν είναι γνωστό)|leer
Σχέση Κηδεμόνα (π.χ. Πατέρας, Μητέρα, Παππούς κ.λπ.) |leer
Διεύθυνση (Πόλη εξωτερικού) (Εάν υπάρχει διεύθυνση Μαθητή στο εξωτερικό) |leer
Διεύθυνση (Χώρα) (Η Χώρα της διεύθυνσης του Μαθητή στο εξωτερικό) |leer
Τηλέφωνο Κηδεμόνα (2)|Mobil Schuelerkontakt2
Κινητό|leer
Ηλεκτρονική Διεύθυνση (email)|E-Mail Schuelerkontakt2
Διεύθυνση|leer
Περιοχή|leer
ΤΚ|leer
Τηλέφωνο|leer
Κινητό|leer
Φαξ|leer
Ηλεκτρονική Διεύθυνση (email)|E-Mail Schuelerkontakt1
Διεύθυνση|leer
Περιοχή|leer
ΤΚ|leer
Τηλέφωνο (1)|leer
Τηλέφωνο (2)|leer
Φαξ|leer
Ηλεκτρονική Διεύθυνση (email)|leer
Εκδούσα Αρχή (Τίτλου Εισόδου)|leer
Πρωτόκολλο Τίτλου Εγγραφής (αν είναι διαθέσιμο)|leer
Ημ/νία Εγγραφής (Μαθητή για το τρέχον Σχ. Έτος)|leer
Ημ/νία Διακοπής Φοίτησης|leer
Αιτία Διακοπής Φοίτησης|leer
Κωδικός Υποψηφίου|leer
ΟΝΟΜΑ ΜΑΘΗΤΗ|leer
ΕΠΩΝΥΜΟ ΜΑΘΗΤΗ|leer
ΟΝΟΜΑ ΠΑΤΕΡΑ|leer
ΕΠΩΝΥΜΟ ΠΑΤΕΡΑ|leer
ΟΝΟΜΑ ΜΗΤΕΡΑΣ|leer
ΟΝΟΜΑ ΚΗΔΕΜΟΝΑ|leer
ΕΠΩΝΥΜΟ ΚΗΔΕΜΟΝΑ|leer
ΓΕΝΟΣ ΜΗΤΕΡΑΣ|leer

!!! Tipp "Hinweis!"    
    Nachstehend beschreiben wir Ihnen an einem allgemeinen Beispiel eine mögliche Weiterverarbeitung der Inhalte. Die Bilder sind beispielhaft und beziehen sich ggfs. nicht auf diesen Bericht.

## Weiterverarbeitung

Rufen Sie die Berichtsvorschau auf:

[![Vorschau][02]][02]

Speichern Sie die Daten aus der Berichtsvorschau heraus als "Microsoft Excel - Nur Daten (*.xlsx)"!

[![Speichern][03]][03]

Starten Sie Excel und laden die Datei. Markieren Sie die erste Spalte und rufen Sie den Punkt `Daten > Datentools > Text in Spalten` auf.

[![Speichern][04]][04]

Wählen Sie "getrennt" und klicken auf "Weiter"!

[![Speichern][05]][05]

Aktivieren Sie nur die Auswahl "Semikolon" und klicken auf "Fertigstellen"! 

[![Speichern][06]][06]

Als Ergebnis werden die Daten jetzt spaltenweise dargestellt. Rufen Sie `Datei > Speichern unter` auf und achten bitte darauf, dass Sie als Dateityp wählen "CSV (Trennzeichen-getrennt) (*.csv)"

[![Speichern][07]][07]

So sieht die fertige Datei aus, wenn Sie sie beispielsweise im Texteditor aufrufen: 

[![Speichern][08]][08]
