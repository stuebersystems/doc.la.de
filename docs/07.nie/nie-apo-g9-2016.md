# NIE-APO-G9-2016

## Quelle
Basierend auf der Verordnung über die gymnasiale Oberstufe (VO-GO)  [http://schure.de/; Vom 17.Februar 2005 (Nds.GVBl. Nr.4/2005 S.51; SVBl. 4/2005 S.171), geändert durch VO vom 12.4.2007 (Nds.GVBl. Nr.9/2007 S.137; SVBl. 5/2007 S.159), vom 13.6.2008 (Nds.GVBl. Nr.13/2008 S.217; SVBl. 7/2008 S.206), 17.5.2010 (Nds.GVBl. Nr.14/2010 S.224; SVBl. 7/2010 S.245), 16.12.2011 (Nds.GVBl. Nr.31/2011 S.505; 2012 S. 27) und vom 12.8.2016 (Nds.GVBl. Nr.10/2016 S.149) - VORIS 22410 -)

> #### warning::Wichtig!
>
>  Das Skript NIE-APO-G9-2016 berechnet das Abitur für den Jahrgang, der nach 13 Jahren Abitur macht und berücksichtigt für die Qualifikation die Halbjahre 12/1-13/2. Die entsprechenden Jahrgänge müssen in MAGELLAN als Oberstufenjahrgänge gekennzeichnet sein.
> Mit diese Skript kann auch die Fachhochschulreife berechnet werden. Bitte wählen Sie dazu unter `Menü > Abitur > Qualifikation > Status` den entsprechenden Status aus.



## Verzeichnis Verordnung

Bitte legen Sie unter ```Verzeichnisse > Verordnungen``` eine neue Zeile an und füllen Sie diese mit den nachstehenden Werten. Beim Synchronisieren der Schüler in das Abitur-Menü weisen Sie den Schülern die Verordnung zu.

|Spalte|Wert|
|--|--|
|Kürzel|beliebig|
|Bezeichnung|beliebig|
|Kategorie|Abitur|
|Typ|Beim Seminarfach muss je Schule ein Halbjahr eingegeben werden, dass unbedingt eingebracht werden muss. Bitte geben Sie im Verzeichnis Verordnungen in der Spalte "Typ" das entsprechende HJ an, z.B. "2" für 2. Halbjahr.|
|Ab Jahrgang|11|
|Skript|```...\Ihre Region\Ihr_Skript.dws``` (Pfad zur Skriptdatei auf Ihrem Server)|
|Notenart 11|Noten oder Punkte|
|Notenart 12|Punkte|
|Notenart 13|Punkte|
|Notenart 13|Punkte|
|Notenart BBS|leer|
|Gültig von |leer|
|Gültig bis|leer|


## Profil

Geben Sie den Schulzweig (Profil) beim jeweiligen Schüler auf der Registerkarte ```Daten3 > Verschiedenes > Profil``` ein. Beim Synchronisieren ins Menü „Abitur“ wird das Profil mit übernommen.
Bitte geben Sie im Schlüsselverzeichnis „Profile (Schüler)“ folgende Werte ein:

|Schlüssel	|Bedeutung|
|--|--|
|SPR	|Sprachlicher Schwerpunkt|
|MUK	|Musikalisch-Künstlerischer Schwerpunkt|
|GWI	|Gesellschaftswissenschaftlicher Schwerpunkt|
|NAT	|Naturwissenschaftlicher Schwerpunkt|
|SPO	|Sportlicher Schwerpunkt|

## Fachkategorien

Jedem Fach, dass Sie in der Oberstufe verwenden, müssen Sie eine Kategorie unter ```Verzeichnisse > Fächer > Kategorie``` zuweisen.
Folgende Fachkategorien werden durch das Abiturqualifikationsskript verwendet, bitte verwenden Sie nur die gekennzeichneten Fachkategorien.

|Fachkategorien|Wird vom Skript berücksichtigt|
|--|--|
|Fremdsprache|x|
|Religion/Ethik|x|
|Deutsch|x|
|Mathematik|x|
|Kunst|x|
|Musik|x|
|Sport|x|
|Informatik|x|
|Philosophie||
|Geschichte|x|
|Physik|x|
|Chemie|x|
|Biologie|x|
|Erdkunde||
|Sozialkunde||
|Wirtschaft||
|Politik||
|Darstellendes Spiel|x|
|Evangelische Religion||
|Katholische Religion||
|Technik||
|Pädagogik||
|Sporttheorie||
|BWL/RW||
|BWL/VWL||
|VWL||
|Seminar|x|
|Gesundheit||
|Psychologie||
|Recht||
|Literatur|||

## Aufgabenbereiche

Folgende Aufgabenbereiche stehen zur Verfügung und müssen unter ```Verzeichnisse > Fächer > Spalte Aufgabenbereich``` verwendet werden:

|Aufgabenbereich|
|--|
|sprachl.-lit.-künstlerisch|
|gesellschaftswiss.|
|mathem.-nat.-technisch|
|Religion|
|Sport|

## Seminarfach

Bitte benutzen Sie für das Seminarfach unter ```Verzeichnisse > Fächer``` in der Spalte "Kategorie" den Wert „Seminar“.
In Spalte ```Verordungen > Typ``` muss das Seminarfach-Halbjahr der Schule eingetragen werden, z.B. "2" für das 2. HJ.

  

## Unterrichtsart

Die Unterrichtsart muss unter ```Abitur > Qualifikation > Unterrichtsart``` zugeordnet sein. Sie kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Unterrichtsart``` übernommen werden. 
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Unterrichtsarten```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel|	Schlüssel	|Bedeutung|
|--|--|--|
|LK|LK|Leistungskurs|
|GK|GK|Grundkurs|

## Fachstatus

Der Fachstatus muss unter ```Abitur > Qualifikation > Fachstatus``` zugeordnet sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Fachstatus``` übernommen werden. 
Prüfen Sie bitte unter ```Verzeichnisse > weitere Schlüsselverzeichnisse > Fachstatus```,  dass in Ihrem Verzeichnis alle erwarteten Werte vorhanden sind oder legen Sie ggfs. an.

|Kürzel	|Schlüssel	|Bedeutung|
|--|--|--|
|1PF	|1PF	|1. Prüfungsfach|
|2PF	|2PF	|2. Prüfungsfach|
|3PF	|3PF	|3. Prüfungsfach|
|4PF	|4PF	|4. Prüfungsfach|
|5PF	|5PF	|5. Prüfungsfach|

## Merkmal

Das Merkmal muss unter ```Abitur > Qualifikation > Merkmal``` eingetragen sein. Er kann aber auch beim Synchronisieren der Schülerfachdaten bereits aus ```Schüler > Zeugnis > Fächer > Merkmal``` übernommen werden. 

|Merkmal	|Bedeutung|
|--|--|
|A|	Fremdsprache Anfänger|


 ## Sport-Praxis Sonderregelung
 
Ist Sport 1. Prüfungsfach, dann wird auf Prüfungsregisterkarte bei "Schriftliche Note" die Punktzahl SP (siehe unten) aus schriftlicher und mündlicher Note eingetragen und in der Spalte "mündliche Note" die Sport-Praxis-Note. Die mündliche Note erscheint nämlich nicht im Zeugnis.

Verordnungstext:

EB-AVO-GOFAK 16.3 Im Fach Sport sind die Prüfungsergebnisse in einfacher Wertung einzutragen. Ist Sport Schwerpunktfach, so wird das Ergebnis der sportpraktischen Prüfung in die Spalte „mündliche Prüfungsergebnisse” der Zeugnisformulare eingetragen. 

Wird die schriftliche Prüfung durch eine mündliche ergänzt, so wird das Ergebnis nach der Formel SP = (2 x s + m) ÷ 3 errechnet und in der Spalte „schriftliche Prüfung” eingetragen, wobei Bruchteile entfallen; dabei ist s = Punktzahl der schriftlichen Prüfung und m = Punktzahl der mündlichen Prüfung.

Sportberechnung laut AVO-GOFAK vom 13.6.2008 ist wie folgt:

Berechnungsformel 1 (ohne mündliche Prüfung): E = (p + s) x 2

E = Prüfungsergebnis

p = Punktzahl der sportpraktischen Prüfung

s = Punktzahl der schriftlichen Prüfung.


