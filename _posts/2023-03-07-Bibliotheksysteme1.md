---
title: "Funktion und Aufbau von Bibliothekssystemen, Teil I"
date: 2023-03-07
---

Liebes Tagebuch

Heute haben wir uns mit dem Bibliothekssystem Koha befasst. 
Wie Du vielleicht schon weisst, wird in der Bibliotheksinformatik vieles im dedizierten MARC21-Format katalogisiert.
MARC21 ist meiner Meinung nach mit Abstand die beste aller Nutzerunfreundlichen Optionen.
Es ist mit Feldern aufgebaut, die jeweils klar definierte Daten erhalten.
Die Felder sind Dreistellig beginnend bei 000 nummeriert und das 0 wird dabei wie jede andere Zahl behandelt. 
Entsprechend sind die führenden Nullen auch bedeutungstragend, was in verschiedenen Programmumgebungen zu vorhersehbaren sowie unvorhergesehenen Problemen führt.
(Vermutlich auch zu Problemen die sowohl unvorhergesehen als auch vorhersehbar sind.)
Die Zahl muss wohl als Datentyp String behandelt werden, was Sinnvoll ist, da diese Zahlen nur als Namen der Felder fungieren und unter keinen Umständen mit ihnen gerechnet werden sollte. 
MARC21 gibt es auch als XML, was für Menschen sogar noch schwieriger zu lesen ist. 
Im Unterbau werden die Daten als [Graf](https://de.wikipedia.org/wiki/Graphdatenbank) vernetzt.
Das erlaubt eine Vernetzung und Verlinkung der Daten. Wir haben im Modul SESY viel darüber gelernt.

Ich habe ChatGPT hierbei um Hilfe gefragt. Leider ist es noch nicht soweit, dass es mit MARC21 Daten umgehen kann. Wir müssen uns wohl vorerst noch selbst darum kümmern.
Ich bezweifle jedoch, dass wir uns - wie der Dozent meinte - noch ein bis zwei Dekaden mit MARC21 herumschlagen werden.
ChatGPT oder ein Nachfolger wird das meiner Meinung nach weit vorher für uns übernehmen.
Die grosse Frag ist, wie viele von uns dann noch eine Arbeitsstelle haben werden.

Für die Zwischenzeit existieren zum Glück Programme, mit sinnvollen Nutzeroberflächen, welche sogar menschenlesbar benannt sind, zur Verfügung.
Diese Programme füllen die entsprechenden Felder in MARC21 ein.
Wie zum Beispiel Koha.
Lauss uns das, wie wir [gelernt](https://florian896.github.io/lerntagebuch-bain/2023/02/28/OpenRefine.html) haben, evaluieren.
Koha ist ein OpenSource Programm.
Zur Unterstützung ziehen wir [Open Hub](https://openhub.net/p/koha) heran.
Sofort sehen wir oben rechts, dass Koha eine "sehr hohe Aktivitätsrate" zeigt.
Der höchste Wert der Skala.
Es sind nur 21 Bewertungen vorhanden, leider alle ohne Text, aber sie geben alle Koha die volle Punktzahl.
Von den 573 Mitwirkenden wurden 48 Tausend Beiträge verzeichnet.
Das sind sehr viele Beiträge von sehr vielen Menschen, wie auch Open Hub in klaren Worten bestätigt:

> Koha has a well established, mature codebase maintained by a very large development team with stable Y-O-Y commits

Die Graphen weiter unten bestätigen erneut, dass das Projekt über lange Zeit schon stabiel läuft.
Koha ist offensichtlich ein sehr gesundes Projekt, mit vielen überzeigten Beitragenden.
Es wurde seit dem Jahr 2000 konstant gepflegt und weiterentwickelt.

Wenn Du Koha startest, siehst du gleich, dass es grafisch nicht sehr modern, aber funktionell einwandfrei und gut verständlich gestaltet ist.
Das Programm an sich ist sehr mächtig und auf alle erdenkliche Aufgaben von Bibliotheken ausgelegt.
Zum Glück lässt es sich auf einfache Weise bis ins kleinste Detail für den Eigenbedarf anpassen. 
Das einzige was Koha im Moment noch fehlt, ist die Möglichkeit Onlinemedien zu verwalten.
Diese Funktionalität befindet sich zur Zeit in Entwicklung und ist dank Kohas grossen Entwicklergemeinschaft bald zu erwarten.

Liebe Grüsse

Florian
