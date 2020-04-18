 - Title: Modulblog BAIN
 - Author: Ibrahim Akoezel
 - E-Mail: ibrahim.akoezel@stud.fhgr.ch
 - Description: Einblick in Bibliotheken und Archiven eingesetzten Softwares und Technologien 
 - Theme: Bibliothek, Archiv, Informatik, Open Source
 - Github_username: akoezeibrahi


[Inhaltverzeichnis]()

[1_Einführung]()

[2_Technische Grundlagen]()

[3_Funktion und Aufbau von Bibliotheks- und Archivsystemen]()

[4_Repository-Software für Publikationen und Forschungsdaten ]()

[5_Metadaten modellieren und Schnittstellen nutzen]()

[6_Suchmaschinen und Discovery-Systeme]()

[7_Linked Data]()

[8_Schluss]()

..............................................................................................................................



[Einführung]()

Das Fach "BAIN" gehört zu der Vertiefung "Bibliotheksmanagement", welches ich ausgewählt habe. Da ich beruflich mit solchen Systemen aus dem Bibliotheksbereich zutun habe, ist es für mich nützlich und auch spannend, mich vertieft mit denen auseinanderzusetzen. Wie solche Systeme technisch im Hintergrund funktionieren und was alles zu solchen Systemen gehört, ist für mich neu. Vor allem sehe ich Vorteile darin, dass man bei solchen Themen im Bibliotheksbereich mitreden oder den Kontext verstehen kann. Das gemeinsame Dokument über [GWDG](https://pad.gwdg.de/Zi-mp8FEQXKV22eL6qUUWg?both) mit den relevanten Hinweisen und Informationen war sehr hilfreich.

Da ich den Unterricht aufgrund meiner [FCE-Prüfung](https://cambridge-exams.ch/de/fce-cambridge-english-first) am 13.03.2020 nicht besuchen konnte, musste ich einige Registrationen und Installationen nachträglich durchführen.

## 1_ Technische Grundlagen

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

Am Anfang der virtuellen Vorlesung am 03.04.2020 haben wir uns einige aktuellen Beispiele wie [Tagesspiegel](https://interaktiv.tagesspiegel.de/lab/die-globale-verbreitung-des-coronavirus-im-zeitverlauf/) und [Johns Hopkins](https://coronavirus.jhu.edu/map.html) im Hinblick auf Datenvisualisierung angeschaut und kommentiert. Wie die Autorin "Cole Nussbaumer Knaflic" in Ihrem Buch [Storytelling mit Daten] (https://www.beck-elibrary.de/10.15358/9783800653751/storytelling-mit-daten) schreibt, sollten einige Vorüberlegungen gemacht werden, bevor die Daten visualisiet werden. Auf die W- Fragen wem, was, wie und wann vermittelt werden, sollte eingegangen werden. Wie kann die Aufmerksamkeit des Publikums gewonnen werden und welche Emotionen werden die Daten auslösen? Und wird der Kontext meiner Datenvisualisierung richtig vermittelt? Welche Diagrame oder Abbildung für welche Fragestellung geeignet ist? Und weitere Fragen müssen beantwortet werden, bevor es losgeht. Daten sollten so visualisiert und dargestelt werden, damit die Gesichten beim Publikum gut ankommen können.


##  2.2. Koha

Das Bibliotheksystem [Koha](https://koha-community.org) kannte ich vorher nicht. 

Koha ist das erste Automatisierungspaket für freie Software-Bibliotheken. Es wird weltweit eingesetzt und seine Entwicklung wird von einer wachsenden Gemeinschaft von Benutzern gesteuert, die zusammenarbeiten, um ihre technologischen Ziele zu erreichen. Der Funktionsumfang von Koha wird ständig weiterentwickelt und erweitert, um den Bedürfnissen seiner Benutzer gerecht zu werden. 


Das erste freie und quelloffene Bibliothekssystem der Welt

Koha ist ein voll ausgestattetes, skalierbares Bibliotheksverwaltungssystem. Die Entwicklung wird von Bibliotheken unterschiedlicher Art und Größe, Freiwilligen und unterstützenden Unternehmen weltweit gesponsert.

##  2.3. Metadatenstandards MARC21 und Dublin Core

Die MARC-Formate sind Standards für die Repräsentation und den Tausch von Daten in maschinenlesbarer Form. Verantwortlich für die Pflege und Entwicklung von MARC 21 ist das Network Development and MARC Standards Office (NDMSO), das vom MARC Advisory Committee unterstützt wird. Es steht auch eine XML-Variante des Formats zur Verfügung.Quelle:http://www.loc.gov/marc/umb/

Der Dublin Core, ein Satz von fünfzehn generischen, weit verbreiteten Elementen - Schöpfer, Beitragender, Herausgeber, Titel, Datum, Sprache, Format, Thema, Beschreibung, Identifikator, Beziehung, Quelle, Typ, Umfang und Rechte - wurde erstmals bei einem Treffen 1995 in Dublin, Ohio, entworfen, um zunächst die Informationssuche in einem explosionsartig wachsenden Web durch die Einbettung einfacher, kartenkatalogartiger Metadaten in seine Seiten zu erleichtern. Eine vielfältige Gemeinschaft von Bibliothekaren, Technologen und Forschern schloss sich der in einer Reihe von lebhaften Workshops und Konferenzen verfolgten und verfeinerten Idee an, durch einen Kern gemeinsamer Semantik eine grobe Interoperabilität zwischen Sprachen und Disziplinen zu erreichen. Aufeinanderfolgende Entwicklungen in der Webtechnologie zogen diese Gemeinschaft in zwei Richtungen:

Dublin Core™ Metadaten, oder genauer gesagt Metadaten "im Stil von Dublin Core™", sind Metadaten, die für die Interoperabilität auf der Grundlage der Prinzipien des Semantic Web oder Linked Data entwickelt wurden. Metadaten in diesem Stil verwenden Uniform Resource Identifiers (URIs) als globale Bezeichner sowohl für die Dinge, die durch die Metadaten beschrieben werden, als auch für die Begriffe, mit denen sie beschrieben werden (Vokabulare). Dieser Stil zeichnet sich durch das Anwendungsprofil aus - eine Spezifikation, die im Einzelnen darlegt, wie bekannte generische Vokabulare wie der Dublin Core verwendet, eingeschränkt oder mit spezielleren Vokabularen kombiniert werden, um die Anforderungen spezifischer Anwendungen zu erfüllen. Anwendungsprofile stehen im Mittelpunkt der Dublin Core™ Gemeinschaft, seit sie im Jahr 2000 zum ersten Mal in Mode kamen.Quelle: https://dublincore.org/resources/metadata-basics/

 

The Dublin Core Metadata Element Set:
| Nummer| Feld|    Nummer|   Feld      |
| ------ | ------ |------ | ------     |
| 1   | Title|        9|     Format|
| 2   | Subject|     10|     Identifier
| 3   | Description| 11|     Language|
| 4   | SCreator|    12|     Relation|
| 5   | Publisher|   13|     Coverage|
| 6   | Contributor| 14|     Rights||
| 7   | Date|        15|     Source|
| 8   | Type|


##  2.3. Marktüberblick Bibliothekssysteme

Winmedio Predata AG
…
Netbiblio
…
Axiell Arena
…
Aleph
…
SISIS-SunRise
…
ALMA
…
Koha
 
