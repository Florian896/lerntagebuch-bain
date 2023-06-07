---
title: "Metadaten modellieren und Schnittstellen nutzen, Teil I (OpenRefine)"
date: 2023-02-28
---

Liebes Tagebuch

Heute haben wir uns mit Metadaten und mit der Bereinigung dreckiger Daten befasst.
Metadaten sind Daten über Daten, die Aufschluss über die Daten geben. 
Das klingt verwirrender als es ist.
Wenn Du einen Datensatz hast, kannst du diesen analysieren, indem Du dessen Eigenschaften anschaust.
Die grundlegende Fragte, die Du dabei stellst ist wie viele Instanzen von welchen Ausprägungen im Datensatz vorhanden sind.
Dazu muss der Datensatz in einheitlicher Form festgehalten sein.
Ist er das nicht, nennt man das "schmutzige Daten", oder auf Englisch "messy data", was direkt übersetzt "unordentliche Daten" bedeutet.
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
4. Wird das Programm noch entwickelt? Mit welcher Regelmässigkeit und Häufigkeit? Wie gross ist die Gemeinschaft, die (noch) entwickelt?  

Diese Dinge lassen sich wunderbar auf OpenRifines GitHub Profil überprüfen.
GitHub zeigt an welche Profile wann wie viel beigetragen haben. 
Eine Präsentation zur OpenSource Evaluation in grösserem Detail findest Du [hier](https://felixlohmeier.de/slides/2017-09-28_vufind-anwendertreffen-keynote.html#/).  
Wie Du siehst, stellt sich heraus, dass OpenRefine schon seit längerer Zeit auf GitHub beliebt ist.
Es gieng durch eine Durststrecke, wird inzwischen aber intensiv entwickelt.
Da die Anzahl an beitragenden Entwickelnden sehr gross ist, können wir davon ausgehen, dass das Projekt auf absehbare Zeit weiterentwickelt werden wird.
Je weniger Entwickelnde beteiligt sind, desto grösser ist die Chance, dass das Projekt aufgegeben wird.
Dazu kommen 200,000 USD pro Jahr, die von verschiedenen Seiten gespendet werden.  

Nun da wir eruiert haben, dass OpenRefine eine gute Wahl ist, widmen wir uns dem Umgang mit dem Programm selbst.
Es wird in der Regel lokal auf einem Computer installiert und über den Browser bedient.
In der Lektion konnten wir sehr einfach Inkonsistenzen und Fehler in einem Datensatz finden und bereinigen.
Formatierungen werden ignoriert und sind darum auch kein Problem.
Die Facettenansicht ist schlichtweg genial.
Pass einfach auf, dass Du nicht übersiehst, dass gleichzeitig aktive Facetten mit einem AND verknüpft sind.

Für tatsächliches Arbeiten mit dem Programm empfehle ich Dir eindringlichst die Lektionen auf [Library Carpentry](https://librarycarpentry.org/lc-open-refine/) durchzuarbeiten.
Sie sind gut verständlich und enthalten viele hilfreiche Übungsaufgaben.
Falls Du viele Texte vom Internet sammeln und analysieren willst, wirst du beim [Programming Historian](https://programminghistorian.org/en/lessons/) fündig, aber Achtung, es sind viele lange Texte.
Ein Handbuch findest Du [hier](https://it-in-bibliotheken.de).
Viel Spass!

Liebe Grüsse

Florian
