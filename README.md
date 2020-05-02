 - Title: Modulblog BAIN
 - Author: Ibrahim Akoezel
 - E-Mail: ibrahim.akoezel@stud.fhgr.ch
 - Description: Einblick in Bibliotheken und Archiven eingesetzten Softwares und Technologien 
 - Theme: Bibliothek, Archiv, Informatik, Open Source
 - Github_username: akoezeibrahi


### [Inhaltverzeichnis:]()

[Einführung]()

[1_Technische Grundlagen]()

[2_Funktion und Aufbau von Bibliotheks- und Archivsystemen]()

[3_Repository-Software für Publikationen und Forschungsdaten ]()

[4_Metadaten modellieren und Schnittstellen nutzen]()

[5_Suchmaschinen und Discovery-Systeme]()

[6_Linked Data]()

[Schluss]()

..................................................................................................................................................................................................



[Einführung]()

Das Fach "BAIN" gehört zu der Vertiefung "Bibliotheksmanagement", welches ich ausgewählt habe. Da ich beruflich mit solchen Systemen aus dem Bibliotheksbereich zutun habe, ist es für mich nützlich und auch spannend, mich vertieft mit denen auseinanderzusetzen. Wie solche Systeme technisch im Hintergrund funktionieren und was alles zu solchen Systemen gehört, ist für mich neu. Vor allem sehe ich Vorteile darin, dass man bei solchen Themen im Bibliotheksbereich mitreden oder den Kontext verstehen kann. Das gemeinsame Dokument über [GWDG](https://pad.gwdg.de/Zi-mp8FEQXKV22eL6qUUWg?both) mit den relevanten Hinweisen und Informationen war sehr hilfreich.

Da ich den Unterricht aufgrund meiner [FCE-Prüfung](https://cambridge-exams.ch/de/fce-cambridge-english-first) am 13.03.2020 nicht besuchen konnte, musste ich einige Registrationen und Installationen nachträglich durchführen.

##  [1_Technische Grundlagen]()

## 1.1  Einrichten der Arbeitsumgebung (Linux)

Den Namen Linux habe ich nur als Betriebsystem gehört und mehr weiss ich darüber nicht. Da ich vorher meinen Dozenten informiert habe, habe ich einen Link für die Cloud-Plattform Microsoft Azure erhalten. Für die Erstellung eines Kontos musste ich jedoch ein Konto bei Micrsoft haben, damit die Registration einfacher erfolgen kann. Nachdem ich den Link erhalten habe, habe ich mich bei Azura Labs registriert und es sah wie folgt auf dem Printscreen aus:

![Screenshot Azure Lab Services - Meine virtuellen Computer](https://bain.felixlohmeier.de/images/01_azure-vms.png)

Damit ich die eigene virtuelle Maschine, welche auf dem [Linux Betriebsystem ](https://wiki.ubuntu.com/EoanErmine/ReleaseNotes ) basiert, haben kann, wurde ich anhand eines Links zur Cloud Plattform Microsoft Azure Lab Services eingeladen. In einem zweiten Schritt habe ich das [Microsoft Remote Desktop 10](https://apps.apple.com/de/app/microsoft-remote-desktop-10/id1295203466) für Mac installiert und mit der virtuellen Maschine auf dem Azura Lab verbunden. Ich habe noch keine Erfahrung mit solchen virtuellen Maschinen und deshalb brauche ich noch mehr Zeit, die Sache konkret zu verstehen. Ich bin daher sehr gespannt.

## 1.2 Unix Shell

Der Name Unix Shell sagte mir nicht viel. Natürlich kann es darn liegen, dass ich keine Ahnung von solchen Systemen habe. Gemäss der Quelle [tutorialspoint](https://www.tutorialspoint.com/unix/unix-what-is-shell.htm) wird unter einem Shell folgendes verstanden:

Unter einer Shell wird eine Umgebung, wo Befehle, Programme und Skripte ausgeführt werden können, verstanden. Sie stellt den Nutzenden eine Schnittstelle zum System UNIX bereit. Die Ein- und Ausgaben führen die Programme auf dieser Grundlage aus. Es gibt verschiedene Varianten von einer Shell, was auch bei anderen Betriebssystemen der Fall ist. Jede Shell-Variante hat ihren eigenen Satz von anerkannten Befehlen und Funktionen. Einige Varianten von einer Shell sind unten aufgeführt. In Unix gibt es zwei Haupttypen von Shells:

* Bourne-Shell 

* C-Shell 

1 Unterkategorien Von Bourne-Shell:
* Bourne-Muschel (sh)
* Korn-Schale (ksh)
* Bourne Again Schale (bash)
* POSIX-Schale (sh)

2 Unterkategorien Von C-Typ-Schalen:
* C-Schale (csh)
* TENEX/TOPS C-Shell (tcsh)

Die erste ursprüngliche Unix Shell (Bourne) wurde in den 1970er Jahren von [Stephen R. Bourne ](https://de.wikipedia.org/wiki/Stephen_R._Bourne) geschrieben. Diese Version wird am meisten genutzt, um die Skripte zu schreiben und diese Skritpte werden auf unterschiedlichen Unix-Varianten verwendet.

## 1.3 GitHub
Nachdem ich einige Möglichkeiten für die Erstellung vom Blog angeschaut habe, habe ich mich für [GitHub](https://github.com) entschieden. Andere Varianten wären Wordpress, GitLab, BitBucket SourceForge, Wix.com zum Erstellen eines Blogs. Das Registrieren beim GitHub war einfach und es gibt genügende Tutorials, um sich zu vertiefen, was ich noch vorhabe. Etwas Neues zu probieren und kennenzulernen macht mich neugierig.


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

Unter einem Bibliothekssystem wird, eine Datenbank verstanden, welche alle möglichen Geschäftsabläufe der bibliothekarischen Arbeit abbilden kann,verstanden. Bekannte Abläufe für Bibliotheken sind Erwerbung, Ausleihe, Katalogisieren, Rechnungen etc. Auch ist die Liste für die [Bibliothekssysteme](https://homepage.ruhr-uni-bochum.de/Joerg.Becker/bibliothekssysteme.htm ) sehr lang, aber nicht alle haben den gleichen Erfolg. In der Schweiz wird je nach Bibliothekystyp ein anderes System genutzt. Im Bereich Hochschul- und Zentralbibliotheken wird Aleph benutzt, aber bald wird dieses System von ALMA abgelöst. Beide Systeme gehören zur Firma [ExLibris](https://www.exlibrisgroup.com/de/). Im öffentlichen Bereich kommen andere Systeme zum Einsatz. Einige bekannte werden nachfolgend aufgelistet:[Winmedio Predata AG](https://www.predata.ch/de/Bibliothekssoftware/winMedionet), [Netbiblio ](http://www.alcoda.ch/index.php/de/), [Axiell Arena](https://www.axiell.com/solutions/library-software/), [Aleph](https://www.exlibrisgroup.com/de/products/aleph-integrated-library-system/), [SISIS-SunRise](https://www.oclc.org/de/sunrise.html), [ALMA](https://www.exlibrisgroup.com/de/produkte/alma-cloudgestuetzte-bibliotheksplattform/), [Koha](https://koha-community.org).


##  2.4. Funktion und Aufbau von Archivsystemen
 
 
 An einem  Samstag 25.04.2020 hatte ich vor, Zeit  mit meiner Familie zu verbringen aber die Realität hat mich daran erinert, dass ich trotz des Alters von 34 immer noch Student bin und deswegen müsse ich meine schulische Pfilichten erfüllen. Na ja, es ist ok, aber am Samstag sollten wir doch  frei haben oder nicht? Eben nicht. Im Kalender wurde es eingetragen, dass ich heute doch eine Vorlesung vom Modul BAIN habe. Grund dafür ist unser neues Lebenspartner "CORONA". Die Uhr zeigt 7:30 Uhr und ich bin noch im Bett mit Pijama und spiele mit Aline (meine 5 monatige Tochter). Nach dem Aktivitäten wie Wickeln von Aline, Füttern von Meerschweinchen und Frühstücken mit der Familie gemacht wurden, setzte ich mich vor dem PC und loge ich mich überaller, um start bereit für die Vorlesung zu sein. Ausser Schuhen anziehen, bin ich so bereit, als ob ich in der realen Vorlsung in Zürich bin. Worum es geht heute eigentlich? Funktion und Aufbau von Archivsystemen. Genauer gasagt, werden wir archivische Metadatenstandard wie [ISAD(G)](https://de.wikipedia.org/wiki/ISAD(G)),[ArchivesSpace ](http://archivesspace.org/community/whos-using-archivesspace) und Marktüberblick von Archivstysteme anschauen. Ich muss zuerst zugeben, dass die archivarische Themen nicht auf meiner Wünschliste sind, obwohl die Archive wichtige Funktionen wie Staat, Mesnchen etc.haben. Wenn ich ans Archiv denke, kommt der staubige Koffer von meinem Vater mit seiner behördlichen Akten, welche wir 8 Kinder alle jedes mal alle durchgehen müssten, bis wir etwas gewunden haben. Obwohl sich die Welt der Archive durch neue Möglichkeiten wie Internet, Technik verändert hat, ist sie für mich immer noch für mich staubig, zu verstehen.
 
 
 
 # Metadatenstandard & ArchivesSpace & Marktüberblick
 
 Es war mal Anfang von 2017 in Chur, als Herr Niklaus Stettler uns sein Wissen zu diesem Thema in einer Vorlesung vom Modul WOR2  mitgegeben hat. Der Metadatenstandard ISAD(G) mit anderen Standards wie ISAAR (Erschliessung der Akteure) und ISDF (Prozesserschliessung) wurden thematisiert. Trotzdem war es eine Auffrischung, wieder Blick ins Thema einwerfen zu dürfen. 
 
| Pflichsfellder|       
| ------ |     
| Signatur  |       
| Titel |
| 245_10_$a |  
| 250_$a    |   
| 260_$a    |    
| 300_$a    |  
| 520_$a   | 
| 650_$a   |          
| 900_$a   |

Signatur
Titel
Provenienz
Entstehungszeitraum
Umfang
Verzeichnungsstufe
 
 
 ##  [3_Repository-Software für Publikationen und Forschungsdaten]()
 
 Weiter abhier: iak
 
 
 ## [4_Metadaten modellieren und Schnittstellen nutzen]()

## [5_Suchmaschinen und Discovery-Systeme]()

## [6_Linked Data]()
## [7_Schluss]()

