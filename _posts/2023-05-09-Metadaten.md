---

date: 2023-05-09
title: "Metadaten modellieren und Schnittstellen nutzen, Teil II"

---

Liebes Tagebuch

Das war für mich ein schwieriger Block. 
Wir haben schön langsam mit Dozentenrückmeldung zu unseren Einträgen begonnen und sind direkt zu einer Einführung zu [ORCID](https://orcid.org/) übergegangen.
ORCID ist die Wissenschaftleridentifizierungsnummer, die du sicher schon kennst.
Darauf wurde researchgate.net erwähnt, was ich noch nicht kannte.
Es sei beliebt aber problematisch. 
Warum dem so sei wurde nicht erläutert. 
Für mich sieht es aus wie ein facebook/Tinder/LinkedIn für Wissenschaftler:innen.
Was alles beliebte, aber problematische Serviceanbieter sind.
Vielleicht meinte er das.

Es gieng verwirrend weiter.
Wir haben via Eingabebefehl verschiedene Erntemethoden von VuFindHarvest ausprobiert.
Nähmlich via Koha, ArchivesSpace und DSpace.
Bemerkenswert ist, das die Eingabebefehle Internetadressen enthielten, deren Inhalt dann geerntet wurde.
Kein Programm musste zwischengeschaltet werden.
Das ominöse OAI-PMH war Teil jedes Befehls, doch ob es ein Programm, ein Standard oder ein Algorythmus ist, erschloss sich mir erst als ich Doktor Wikipedia um [Rat](https://en.wikipedia.org/wiki/Open_Archives_Initiative_Protocol_for_Metadata_Harvesting) bat.
Die Antwort liegt im Namen, der nähmlich ein Acronym ist, das verrät, dass es sich um ein Protokoll, also einen Algorythmus - sprich eine Methode - handelt.
Bitte erinner mich dran bei der nächsten Verwirrung gleich Wikipedia zu besuchen.



------NOTIZEN------
Crosswalk DC zu MARC
von Lib o Cong
gut definiert
offizieller standard
ABER Orgs verwenden die Felder leicht unterschiedlicher
aus chaos wird mehr chaos
um es sinnvoll zu machen, wird von DOz empfohlen erst runter in dc zu pressen mit verweis zu orig
SCHLECHT für Migration
USECASE: eine format vom Verlag geliefert, anderes gebraucht

XSLT ist STANDART für XML
wie in Teil I (LINK) erwähnt, programmer historian und so
Online-Tool: http://xsltransform.net live konvertieren, PRAKTISCH
teils klappts, teils nicht
BSP: Referenz zu anderem xml ERROR
chatGPT? will nicht. Kanns verstehen und menschlich erklären, aber nicht konvertieren
Oh, liess sich überreden ein BSP zu machen
SEHR LANGSAM, schreibt die Zeilen einzeln
Resultat: https://florian896.github.io/lerntagebuch-bain/ClippyCodes.html

wir machens mit MarcEdit
fee to use, nicht open source
von einer person, aber so stabil und lange da, dass es zum Standard wurde.
man merkt, das von einem gemacht: alte logos, pixel, gewachsenes menü
ABER sehr mächtig, funzt gut
nicht jazzy, aber solide
untertitel verloren, versch verloren

besten validieren vorher und nacher
vorher felder anpassen etc
sachen gehen verloren
je nachdem was man will


JASON einfacher zu lesen als MARC21

Ende codi dokument Links und so, schaus an!
