## [2_Funktion und Aufbau von Bibliotheks- und Archivsystemen]()

##  2.1 Datenvisualisierung

Am Anfang der virtuellen Vorlesung am 03.04.2020 haben wir uns einige aktuelle Beispiele wie [Tagesspiegel](https://interaktiv.tagesspiegel.de/lab/die-globale-verbreitung-des-coronavirus-im-zeitverlauf/) und [John Hopkins](https://coronavirus.jhu.edu/map.html) im Hinblick auf die Datenvisualisierung angeschaut und kommentiert. Wie die Autorin "Cole Nussbaumer Knaflic" in ihrem Buch [Storytelling mit Daten](https://www.beck-elibrary.de/10.15358/9783800653751/storytelling-mit-daten) schreibt, sollten einige Vorüberlegungen gemacht werden, bevor die Daten visualisiert werden. Auf die W-Fragen wem, was, wie und wann sollte eingegangen werden. Wie kann die Aufmerksamkeit des Publikums gewonnen werden und welche Emotionen werden die Daten auslösen? Und wird der Kontext meiner Datenvisualisierung richtig vermittelt? Welche Diagrame oder Abbildungen sind für welche Fragestellungen geeignet? Und weitere Fragen müssen beantwortet werden, bevor es losgeht. Daten sollten so visualisiert und dargestelt werden, damit die Geschichten beim Publikum gut ankommen können.


##  2.2. Koha

Das Bibliotheksystem [Koha](https://koha-community.org) kannte ich vorher nicht, aber das ist ein weltweit bekanntes und skalierbares System, an dem vielen Akteure wie Bibliothekn und Unternehmen beiteiligt sind. In der Schweiz bekannt ist Aleph und da aufgrund des neuen Projektes [SLSP] (https://slsp.ch/de) das Programm ALMA eingesetzt wird, ist auch ALMA bekannt geworden. Durch die Einführung in der Vorlesung haben wir einen Überblick über den technischen Hintergrund des Programms erhalten. Jetzt kann ich besser nachvollziehen, wie man Statistiken erstellen oder gewisse Abläufe wie Mahnungen stornieren kann. Durch ein in Kategorien geteiltes Staff Interface erhält man einen guten Überlick über die Abläufe. Es gibt nützliche Information auf der [Koha-Webseite](https://koha-community.org) und auch ein Handbuch [Koha-Webseite](https://koha-community.org/manual/19.11/en/html/#) und [Tutorials](https://vimeo.com/channels/kohails. Ich denke, wenn man keine praktische Erfahrung mit der bibliothekarischen oder archivarischen Arbeit hat, wird es ein bisschen schwierig, das ganze System zu verstehen.


##  2.3. Metadatenstandards MARC21 und Dublin Core

Die Metadatenstandards sind für die Information und den Datenaustausch von Bedeutung, damit die verschiedenen Systeme doch miteinander arbeiten können. Das beschleunigt den Austausch und ermöglicht eine Strukturierung der Daten. Die [Liste](http://www.dcc.ac.uk/resources/metadata-standards/list) für die Metadatenstandrds ist lang. Aber nicht alle haben sich etabiliert oder grosse Massen erreicht.

Die beiden Metadatenstandards sind bekannt im Bereich Informationswissenschaft. Der Marc Standard ist im Biblothekswesen bekannt und ermöglicht, die Daten maschinell zu repräsentieren und auszutauschen. Die aktuellste Version davon ist Marc21. Dublin Core ist durch das Internet entstanden, um den Datenaustausch im Internet strukturieren und beschleunigen zu können. 

Gemäss DCMI wird Dublin Core wie folgt beschrieben:

"Der Dublin Core, ein Satz von fünfzehn generischen, weit verbreiteten Elementen - Schöpfer, Beitragender, Herausgeber, Titel, Datum, Sprache, Format, Thema, Beschreibung, Identifikator, Beziehung, Quelle, Typ, Umfang und Rechte - wurde erstmals bei einem Treffen 1995 in Dublin, Ohio, entworfen, um zunächst die Informationssuche in einem explosionsartig wachsenden Web durch die Einbettung einfacher, kartenkatalogartiger Metadaten in seine Seiten zu erleichtern. Eine vielfältige Gemeinschaft von Bibliothekaren, Technologen und Forschern schloss sich der in einer Reihe von lebhaften Workshops und Konferenzen verfolgten und verfeinerten Idee an, durch einen Kern gemeinsamer Semantik eine grobe Interoperabilität zwischen Sprachen und Disziplinen zu erreichen"

Für die Pflege und Entwicklung von Marc ist [NDMSO](http://www.loc.gov/marc/ndmso.html) zuständig und für Dublin Core ist [DCMI](https://dublincore.org/about/) zuständig.

Die Beipiele von Datensätzen sehen wie folgt aus:


Same record with MARC tags:

| Nummer|       Feld|    
| ------ |    ------ |    
| 020__$a  | 978-3-86764-560-7|       
| 100_1_$a  | Hahn, Oliver|        
| 245_10_$a | Digitale Öffentlichkeiten| 
| 250_$a    |1. Auflge|     
| 260_$a    | München|    
| 300_$a    | 300 Seiten|      
| 520_$a   | Zusammenfassung|   
| 650_$a   | Internet|          
| 900_$a   | 650.54 HAH| 


The Dublin Core Metadata Element Set:  

| Nummer| Feld|     Nummer|   Feld      |
| ------ | ------  |------ | ------     |
| 1   | Title|        9|     Format|
| 2   | Subject|     10|     Identifier|
| 3   | Description| 11|     Language|
| 4   | SCreator|    12|     Relation|
| 5   | Publisher|   13|     Coverage|
| 6   | Contributor| 14|     Rights||
| 7   | Date|        15|     Source|
| 8   | Type|


##  2.3. Marktüberblick Bibliothekssysteme

Unter einem Bibliothekssystem wird eine Datenbank verstanden, welche alle möglichen Geschäftsabläufe der bibliothekarischen Arbeit abbilden kann,verstanden. Bekannte Abläufe für Bibliotheken sind Erwerbung, Ausleihe, Katalogisieren, Rechnungen etc. Auch ist die Liste für die [Bibliothekssysteme](https://homepage.ruhr-uni-bochum.de/Joerg.Becker/bibliothekssysteme.htm ) sehr lang, aber nicht alle haben den gleichen Erfolg. In der Schweiz wird je nach Bibliothekystyp ein anderes System genutzt. Im Bereich Hochschul- und Zentralbibliotheken wird Aleph benutzt, aber bald wird dieses System von ALMA abgelöst. Beide Systeme gehören zur Firma [ExLibris](https://www.exlibrisgroup.com/de/). Im öffentlichen Bereich kommen andere Systeme zum Einsatz. Einige bekannte werden nachfolgend aufgelistet:[Winmedio Predata AG](https://www.predata.ch/de/Bibliothekssoftware/winMedionet), [Netbiblio ](http://www.alcoda.ch/index.php/de/), [Axiell Arena](https://www.axiell.com/solutions/library-software/), [Aleph](https://www.exlibrisgroup.com/de/products/aleph-integrated-library-system/), [SISIS-SunRise](https://www.oclc.org/de/sunrise.html), [ALMA](https://www.exlibrisgroup.com/de/produkte/alma-cloudgestuetzte-bibliotheksplattform/), [Koha](https://koha-community.org).


##  2.4. Funktion und Aufbau von Archivsystemen
 
 
Am Samstag 25.04.2020 hatte ich vor, Zeit mit meiner Familie zu verbringen, aber die Realität hat mich daran erinnert, dass ich trotz des Alters von 34 immer noch Student bin und deswegen musste ich meine schulischen Pflichten erfüllen. Na ja, es ist ok, aber am Samstag sollten wir doch frei haben oder nicht? Eben nicht. Im Kalender wurde eingetragen, dass ich heute doch eine Vorlesung vom Modul BAIN habe. Grund dafür ist unser neuer Lebenspartner "CORONA". Die Uhr zeigt 7:30 Uhr und ich bin noch im Bett mit Pyjama und spiele mit Aline (meine 5-monatige Tochter). Nach den Aktivitäten wie Wickeln von Aline, Füttern von Meerschweinchen und Frühstücken mit der Familie, setzte ich mich vor den PC und logge ich mich überall ein, um pünktlich bereit für die Vorlesung zu sein. Ausser, dass ich keine Schuhe anziehen muss, bin ich so bereit, als ob ich in der realen Vorlesung in Zürich wäre. Worum geht es heute eigentlich? Funktion und Aufbau von Archivsystemen. Genauer gesagt, werden wir archivische Metadatenstandards wie [ISAD(G)](https://de.wikipedia.org/wiki/ISAD(G)),[ArchivesSpace ](http://archivesspace.org/community/whos-using-archivesspace) und den Marktüberblick von Archivstystemen anschauen. Ich muss zuerst zugeben, dass archivarische Themen nicht auf meiner Wunschliste sind, obwohl die Archive wichtige Funktionen für den Staat, die Menschen etc. übernehmen. Wenn ich ans Archiv denke, denke ich an den staubigen Koffer meines Vaters, in dem seine behördlichen Akten lagerten, welche wir 8 Kinder alle jedes Mal alle durchgehen mussten, bis wir etwas gefunden haben. Obwohl sich die Welt der Archive durch neue Möglichkeiten wie Internet, Technik verändert hat, ist sie für mich immer noch staubig.
 
 
 
 # Metadatenstandard & ArchivesSpace & Marktüberblick
 
Es war mal Anfang von 2017 in Chur, als Herr Niklaus Stettler uns sein Wissen zu diesem Thema in einer Vorlesung im Modul WOR2 mitgegeben hat. Der Metadatenstandard ISAD(G) wurde mit anderen Standards wie ISAAR (Erschliessung der Akteure) und ISDF (Prozesserschliessung) thematisiert. Trotzdem war es eine Auffrischung, wieder Blick ins Thema einwerfen zu dürfen. 
 

| Pflichsfellder von ISAD(G): |                    |    
| ------                      |    ------          |    
| Signatur                    | Entstehungszeitraum|       
| Titel                       | Umfang             |        
| Provenienz                  |  Verzeichnungsstufe| 


Zusätzlich war es auch nützlich, die Archivkataloge ["Online Archivkatalog des Staatsarchivs
BS](https://query.staatsarchiv.bs.ch/query/suchinfo.aspx) und ["Hochschularchiv ETH Zürich2](http://archivdatenbank-online.ethz.ch/)in der Gruppenarbeit anzuschauen und unsere Anmerkungen im gemeinsamen Dokument erfassen zu können. Da ich aus dem Bibliotheksbereich komme, musste ich mich zuerst in diesen Katalogen zurechtfinden, weil sie anders aufgebaut sind als Biblothekskataloge oder andere Datenbanken. Zudem konnten wir einige Übungen mit einer Open-Source-Software "ArchivesSpace"  als Gruppe durchführen. Die Software war meiner Einschätzung nach benutzerfreundlich und anhand der Anleitungen konnte sie schnell bedient werden. Als Gruppe konnten wir einiges testen (repository, Collection, Datensatz ablegen, Export und Import).Siehe [Screenshot von der Übung](https://pad.gwdg.de/uploads/upload_e09d85052a9ec3423ad0517d2f788dc7.png).

Von den Archivinformationssystemen haben wir nur [ATOM](https://www.accesstomemory.org) kurz in der Vorlesung von Herrn Niklaus Stettler kennengelernt. Da wir damals nicht genügend Zeit hatten, konnten wir keine Übungen damit machen. Zusätzlich sind [scope.Archiv](http://www.scope.ch) und [CMISTAR](https://www.cmiag.ch/cmistar) von Bedeutung für den Markt.

 
