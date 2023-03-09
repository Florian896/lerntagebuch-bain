---
title: "Metadaten modellieren und Schnittstellen nutzen, Teil I (OpenRefine)"
date: 2023-02-28
---

Liebes Tagebuch

Heute haben wir uns mit Metadaten und mit der Bereinigung dreckiger Daten befasst.
Metadaten sind Daten über Daten, die Aufschluss über die Daten geben. 
Das klingt verwirrender als es ist.
Wenn Du einen Datensatz hast, kannst du diesen analysieren, indem Du dessen Eigenschaften anschaust.
Die grundlegende Fragte, die Du dabei stellst ist wieviele Instanzen von welchen Ausprägungen im Datensatz vorhanden sind.
Dazu muss der Datensatz in einheitlicher Form festgehalten sein.
Ist er das nicht, nennt man das "schmutizge Daten", oder auf Englisch "messy data", was direkt übersetzt "unordentliche Daten" bedeutet.
Hat man schmutzige Daten, kann man sie mit Programmen wie OpenRefine (be-)reinigen.
OpenRefine ist ein OpenSource Programm das wir heute kennenlernten.
Die Internetauftritt von OpenRefine beschreibt es so:  
> OpenRefine is a powerful free open source tool for working with messy data: cleaning it; transforming it from one format to the other and extending it with web services and external data.  

Es kann also auch Daten in andere Formate übersetzen und sie sogar mit Hilfe des Internets erweitern.
Das klingt sehr gut, aber wie weit können wir der Werbung trauen?  
Lass uns erst das Programm evaluieren!
Wir können gleich lernen, wie wir eine solche Evaluation angehen können.
Dazu werfen wir erst einen Blick auf die Beurteilungen und auf seinen Auftritt.
Wir achten dabei gezielt auf vier Dinge.
1. Wer sind die Nutzenden und in welcher Sprache nutzen sie das Programm?
2. Wozu nutzen sie das Programm?  
OpenRefine hat diese Daten für uns bereits [Zusammengetragen](https://openrefine.org/blog/2022/06/28/2022-survey-results.html).
3. Wird das Programm tatsächlich für die Dinge genutzt für die es entwickelt wurde?
4. Wird das Programm noch entwickelt? Mit welcher regelmässigkeit und häufigkeit? Wie gross ist die Gemeinschaft, die (noch) entwickelt?  

Diese Dinge lassen sich wunderbar auf OpenRifines GitHub Profiel überprüfen.
GitHub zeigt an welche Profiele wann wieviel beigetragen haben. 
Eine Präsentation zur OpenSource Evaluation in grösserem Detail findest Du [hier](https://felixlohmeier.de/slides/2017-09-28_vufind-anwendertreffen-keynote.html#/).  
Wie Du siehst, stellt sich heraus, dass OpenRefine schon seit längerer Zeit auf GitHub beliebt ist.
Es gieng durch eine Durststrecke, wird inzwischen aber intensiev entwickelt.
Da die Anzahl an beitragenden Entwickelnden sehr gross ist, können wir davon ausgehen, dass das Projekt auf absehbare Zeit weiterentwickelt werden wird.
Je weniger Entwickelnde beteiligt sind, desto grösser ist die Chanze, dass das Projekt aufgegeben wird.
Dazu kommen 200,000 USD pro Jahr, die von verschiedenen Seiten gespendet werden.  

Nun da wir eruiert haben, dass OpenRefine eine gute Wahl ist, widmen wir uns dem Umgang mit dem Programm selbst.
Es wird in der Regel lokal auf einem Computer installiert und über den Browser bedient.
Wir finden eine grafische Oberfläche, die einem klassischen Tabellenverarbeitungsprogramm ähnelt.
Nach dem Import unserer Daten können wir über die zahlreichen Menuoptionen unseren Datensatz bearbeiten.

--------------------
OpRe kann gut daten bereinigen, verwalten und so
Fehler bereinigen (text im Zahlenfeld oder so) gibt es selbst bei national Bibi. 
Daten visualisierung

CodeSpaces öffnen
Ports
forward Port 3333 (wie im Terminal erwähnt)
warten

Alle Daten die wir importieren werden zu einem "Projekt" (import --> projekt --> export)
Clipboard: zwischenablage (copy paste)
LibCarpentry lesson: https://librarycarpentry.org/lc-open-refine/

WebURL mit link (provided) einspeisen
OpRe ignoriert alle grafischen formatierungen (fett, farbig, hintergrundfarbe, etc)
unten praktische einstellungen
.csv tabellendaten, separiert mit komma, wenn komma im feld, mit "" umschlossen
man kann andere Symbole dazu definieren
CREATE PROJECT
gemischte Ansicht, websuche/tabellenansicht (laaaange tabellen in HTML killen den pc)
pfeil bei Spaltentitel: Language --> facet --> textfacet
links gucken
oho, English vs EN (homogenisierung nötig)
verbreiteste Form Sprache als 3 Zeichen
wir gehen mal zur Mehrhiet: Engl --> EN
Hover over English --> Edit --> EN tippen --> Apply
oben UNDO / REDO (aber nur der Reihenfolge nach möglich)

mehrere Facetten können gleichzeitig gezeigt werden
ist AND verknüpfung (OR wäre komplizierter)
Author: müssens aufsplitten.
mehrere werte pro zellen, müssen wir splitten
	Authors -->Edit cells --> Split multi-varied cells
	| als seperator --> ok
Zu viele links 
	set choice count limit
jetzt sehen wir den häufigsten
click clustor
Method und so rumspielen
Namen Homogenisieren
(natürlich Entscheidungen nötig, wie machen wirs /ist es richtig?)
	richtiges anklicken
	Merge select3ed &re-cluster

DOI nicht gut als ID
	duplikate
	blank
gut immer im ROWS modus (Show as:)
oben steht was wir ansehen in fett
	immer ansehen! --> orientieren
lässt sich range als facette eingeben?
ja --> Date--> edit cells --> Common transoforms --> to date 
Date --> facet --> timeline facet
drag range

Reconciliation
Titel ist nur als Teil der citation da
general refine expression language
citation --> Edit column --> Add column based on this column
New colomn name: Journal
value.split("[trennzeichen, hier ", " ]")
das gibt Array, (ZÄHLT VON NULL)
darum [0] fürs erste Feld absplitten
Journal--> Reconsile --> Start reconsiling
auf service clicken (gibt noch andere)
rechts auf ISSN, ISSN p236 auswählen
kann daten ergänzen, via reconsiliation! (s. gemeinsames dok)
Remember: delete Codespace

---------------------

Libsrary Carpentry

Literaturempfehlungen
Library Carpentry Lessons: https://librarycarpentry.org/lessons/ - Peer reviewed Lehrmaterialien (IT 4 Librarians)
Programming Historian Lessons: https://programminghistorian.org/en/lessons/ - lange Texte, peer reviewed, HOWTO mit OpenRefine webscraping
Handbuch IT in Bibliotheken: https://it-in-bibliotheken.de - 
---------------------
