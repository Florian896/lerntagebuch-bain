---

date: 2023-05-16
title: "Suchmaschinen und Discovery-Systeme"

---

Liebes Tagebuch

Dieser Block war interessant aber auch sehr intensiv.
Er war sehr alltagsnah, mit wunderbaren echten Beispielen, und entsprechend technisch anspruchsvoll.
Es ist echt faszinierend und beeindruckend, aber mir fehlt die Konzentrationsfähigkeit etwas derart theoretisches zu machen.
Ich bleibe lieber hinter der Theke.

Wie du bereits dem Titel entnehmen kannst ging es um Suchmaschinen (Stichwort Solr) und Discovery-Systeme (vor allem VuFind).
VuFind ist ein modernes mächtiges Programm.
Es hat viele Funktionen und ein an sich gutes Nutzeroberflächendesign, das nicht allzu modern aussieht, aber sehr gut angepasst werden kann.
Es stehen viele Tutorials - auch mit Video - zur Verfügung, die von den Entwicklern produziert werden.
Dazu stehen die Benutzerhandbücher auf GitHub mit ausführlicher Dokumentation bereit.
Die Entwickler sind eine Open Source Community, die sehr aktiv an VuFind arbeiten.
Vier Personen stehen als am häufigsten Mitwirkende heraus und es handelt sich generell um eine gesunde Gemeinschaft.
Dazu kommt, dass zu den Nutzern unter anderem die Nationalbibliothek von Finnland zählt, was bedeutet, dass eine signifikante Organisation an der Weiterführung des Projektes interessiert ist.

Für die Suchfunktion von VuFind baut auf Solr auf.
Solr ist eine Open Source Suchplatform, die sich zum Industriestandard entwickelt hat.
Was Solr alles kann hat mich sehr beeindruckt.
Nun, bedenke, Solr ist nicht für die gemeinen Nutzenden gedacht, sondern als im Hintergrund laufendes Programm, das der Nutzerfreundlichen Fassade viele wunderbare Funktionen gibt.
Entsprechend sind zum Beispiel die Faccetten schwieriger zu finden als bei VuFind.
Ebenso steht die Konsistenzprüfung nicht im Vordergrund. 
Solr ist keine Datenbank, sondern eine Suchplatform.
Die Geschwindigkeit der Suchen steht im Fokus.
Dazu muss die integration von Schnittstellen, auch zu mehreren Datenbanken gleichzeitig, reibungslos funktionieren.
Zu meiner persönlichen Überraschung tut sie das auch.
Und das mit 

relevanzranking

----NOTIZEN----  

Elastic search und Solar sind die 2 Big Dogs
Solr schnell, 
indiziert
relevanzranking

--Dokument--
Horizontale vs. Vertikale Suchmaschine
Horizontal: unspezifische Suche über heterogene Datenbestände
erfordert kein Datenschema (“schema-less”)
erlaubt keine semantischen Abfragen oder Feldsuchen
Beispiele: Internetsuche, Volltextsuche
Vertikal: datenmodell-orientierte Suche über homogene Datenbestände
erfordert ein Datenschema
erfordert häufig Datenprozessierung zur Homogenisierung
Beispiele: Bibliothekskatalog, Online-Shop
--Dokument--

Suchoberfläche
Sehr kurze namen der Felder, Mouse over, gedacht für maschinen gelesen (BACKEND)

suche kommt zurück in JASON format

#### Gruppe 1

Unterschiede und Auffälligkeiten:
* Solr gibt mehr Information in der Ergebnisliste/Trefferliste
* VuFind hat direkte Filtermöglichkeiten/Facetten, bei Solr ist die Facettensuche versteckt und funktioniert nicht auf einen "klick"
* Solr braucht mehr Vorwissen (Felder) und eine gewisse Einarbeitungszeit
* VuFind liefert Vorschläge für weitere/alternative Schlagworte direkt zu Beginn ; bei Solr ist der Vorschlag versteckt zu finden
* Optik: die grafische Benutzeroberfläche ist für die Anwendung von Laien wichtig, weshalb VuFind besser geeignet wäre
* Verlinkungen bei Schlagworten, Verfassern etc. wie in VuFind fehlen bei Solr (oder sind auf den ersten Blick nicht erkennbar)

#### Gruppe 2

Unterschiede und Auffälligkeiten:
* Solr eigent sich nicht gut für Benutzer:innen / hat kein UI
* VuFind hat ein UI, welches verständlich ist für Nutzer:innen
* Man muss wissen, wie man Solr benutzen muss, ohne Handbuch / Vorwissen kann man nicht mal gut eine Suchabfrage machen.
* VuFind hat Verlinkungen zu beispielsweise Verfasser:in oder Schlagwort, Solr hat nur die URL zum Journal, keine Verlinkungen zu anderen Beiträgen
* Zusatz Featrues wie Teilen, Zitieren, Drucken etc.
* ähnliche Einträge - cooles Feature
* Sortierung VuFind ausführling, Sortierung Solr "nur" ASC / DESC
* "Writer Type" bei Solr kann sicherlich hilfreich sein. Es ist cool, dass die Daten in einem unterschiedlichen Format (schnell) angezeigt wird
* Bei VuFind gibt es eine Login-Funktion

#### Gruppe 3

Unterschiede und Auffälligkeiten:
* Solr ist mühsam für Laien zu lesen 
* in Solr sind zusätzliche Details enthalten, die auf VuFind nicht zu finden sind ("Quarterly, 1935-64", etc)

#### Ergänzungen

* Relevanzranking
* Nutzerfunktionen

ähnliche Schlagwörter == Facette
Relevanzranking: Feld und Multiplationsfaktor
	oft ausprobiert, Standart ist Erfahrungswert

autovervollständigung: sucht live, ist hier suchfeldabhängig
kann def wie lange warten bis suche (1 s oder so)

extra config file um std datei zu erhalten
text datei, können wir einfach ändern (breaks translation)

ID feld fehlt --> FEHLER, MUSS
MARC hat keins, wir schreiben eine rein
VuFind macht Mapping. 01 wird ID
recht komplex
Muss ev Mapping MARC zu VuF anpassen
müssen in MARCXML umwandeln. ZB DC oder so müssen wir ins MARC21XML umwandeln. SIEHE BILD MIT FLOWCHART

BSP
K10Plus 
10 Bundesländer
eigene Software mit Solr
nehmen öffentlich zugängliche Datensätze (pubMed und so) in ihren Index auf
Skripte, Translation-Map, 231 Millionen Datensätze
Bibis im Verbund kriegens gratis
eigenes ist eh drin

für Ausleihe brauchts dann nochmal Datenbank-Schnittstelle
Wer, Berechtigungen, 2 Schnittstellen (Unpaywall und DNB Verfügbarkeit), lädt sehr schnell!!
ALMA/PRIMO Blackbox, weil proprietär
Technisch getrennt, wird zusammen geleifert
(VuFind: Discovery)

Discovery Syst
Software | Daten (daten: meta-, etc)
