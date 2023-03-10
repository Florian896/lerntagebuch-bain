---
title: "Funktion und Aufbau von Bibliothekssystemen, Teil I"
date: 2023-03-07
---

Liebes Tagebuch

Heute haben wir uns mit dem Bibliotheksystem Koha befasst. 
Wie Du vielleicht schon weisst, wird in der Bibliotheksinformatik vieles im dedizierten MARC21-Format katalogisiert.
MARC21 ist meiner Meinung nach mit Abstand die beste aller Nutzerunfeindlichen Optionen.
Es ist mit Feldern aufgebaut, die jeweils klar definierte Daten erhalten.
Die Felder sind Dreistellig beginnend bei 000 nummeriert und das 0 wird dabei wie jede andere Zahl behandelt. 
Entsprechend sind die führenden Nullen auch bedeutungstragend, was in verschiedenen Programmumgebungen zu vorhersehbaren sowie unvorhergesehenen Problemen führt.
(Vermutlich auch zu Problemen die sowohl unvorhergesehen als auch vorhersebar sind.)
Die Zahl muss wohl als Datentyp String behandelt werden, was Sinnvoll ist, da diese Zahlen nur als Namen der Felder fungieren und unter keinen Umständen mit ihnen gerechnet werden sollte. 
MARC21 gibt es auch als XML, was für Menschen sogar noch schwieriger zu lesen ist. 
Im Unterbau werden die Daten als [Graf](https://de.wikipedia.org/wiki/Graphdatenbank) vernetzt.
Das erlaubt eine Vernetzung und Verlinkung der Daten. Wir haben im Modul SESY viel darüber gelernt.

Zum Glück existieren Programme, mit sinnvolen Nutzeroberflächen, welche sogar menschenlesbar bennannt sind, zur Verfügung.
Diese Programme füllen die ensprechenden Felder in MARC21 ein.
Wie zum Beispiel Koha.
Lauss uns das, wie wir [gelernt](https://florian896.github.io/lerntagebuch-bain/2023/02/28/OpenRefine.html) haben, evaluieren.
Koha ist ein OpenSource Programm.
Zur Unterstützung ziehen wir [Open Hub](https://openhub.net/p/koha) heran.
Sofort sehen wir oben rechts, dass Koha eine "sehr hohe Aktivitätsrate" zeigt.
Der höchste Wert der Skala.
Es sind nur 21 Bewertungen vorhanden, leder alle ohne Text, aber sie geben alle Koha die volle Punktzahl.
Von den 573 Mitwirkenden wurden 48 Tausend Beiträge verzeichnet.
Das sind sehr viele Beiträge von sehr vielen Menschen, wie auch Open Hub in klaren Worten bestätigt:

> Koha has a well established, mature codebase maintained by a very large development team with stable Y-O-Y commits

Die Graphen weiter unten bestätigen erneut, dass das Projekt über lange Zeit schon stabiel läuft.
Koha ist offensichtlich ein sehr gesundes Projekt, mit vielen überzeigten Beitragenden.
Es wurde seit dem Jahr 2000 konstant gepflegt und weiterentwickelt.



Liebe Grüsse

Florian

++++++notizen+++++++

MARC21
MRC: Binärformat für MARC21
DOC: für wörd
MARCXML gibt es
Felder und so das trockene zeugs erklärt
Kenn ich schon. Das ganze mit 240 $a blablabla
Oh wunder, es gibt sofware, die das ganze lesbarer macht via Mapping und so 
es ist ein GRAF, blubb
gibt instanzen vs manifestationen (Göhtes Faust vs ein Buch)
Ich HOFFE ChatGPT kann MARC21 schon bälder als die prohezeiten 20 Jahre ablösen
schnarch
Als ich erwachte:
vgl DublinCore vs MARC21
Dublin hat sprechende Felder (sinnvolle Namen)
generell leider noch nicht (HOW??) veralters zeug
 MARC mehr info
Dublin ohne Handbuch verständlich, MARC nicht

+++aus gemeinsamem dok+++
Regelwerk vs. Datenformat
Ein Regelwerk bildet die theoretische Grundlage für die Katalogisierung. Es definiert, wie eine Ressource zu beschreiben ist. Dazu gehören in der Regel inhaltliche Kategorien und normierte Vokabulare.
Functional Requirements for Bibliographic Records (FRBR) und Resource Description and Access (RDA) sind Regelwerke
Ein Datenformat erlaubt die praktische Repräsentation eines Katalogisats. Es definiert, wie Informationen zu kodieren sind. Dazu gehören Datenstrukturen und -typen.
MARC21 und BIBFRAME sind Datenformate
Note:
Regelwerke und Datenformate ergänzen einander und sind nicht immer trennscharf zu unterscheiden. Beispielsweise umfasst BIBFRAME auch Aspekte eines Regelwerks (z. B. Abstraktionsebenen). Man spricht deshalb auch von einem Datenmodell.
+++aus gemeinsamem dok+++

openhub.net zums evaluieren
e-res modul kommt. in Entwicklung
Demoversion
