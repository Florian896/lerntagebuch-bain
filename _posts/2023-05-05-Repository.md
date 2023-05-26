---

date: 2023-05-05
title: "Repository-Software für Publikationen und Forschungsdaten"

---

Liebes Tagebuch

Wir haben, wie der Titel schon verrät, Repository - also dedizierte Datenbanken - für Publikationen und Forschungsdaten angeschaut.
Früher wurden nur Artikel und Bücher publiziert, nicht die unverarbeiteten Daten.
Mit modernen Methoden und Möglichkeiten dank Repositories, werden heute die unglaublichen Mengen an Forschungsdaten roh - aber anonymisiert - gleich mitveröffentlicht, was weiterführende Forschung erleichtert.
Wir haben uns insbesondere auf das Open Source Programm DSpace konzentriert, weil es ein weitverbreitetes Programm mit grossem Marktanteil ist, das gratis genutzt werden kann.

Um DSpace anzuschauen hat uns der Dozent einen Code Space vorbereitet.
Er warnte uns, das das Initialisieren des Code Spaces ziemlich lange dauert.
Darum habe ich sofort meinen Code Space gestartet. 
Da ich die Vorlesung als Aufnahme in zweifafcher geschwindigkeit schaute, war ich nicht überrascht, als mein Code Space nicht rechtzeitig für die Übung bereit war.
Das Terminal war noch am erklären was es genau wie am installieren war.
Ich verstand nichts davon.
Ich liess es arbeiten und legte eine Pause ein.
Etwa vierzig Minuten später war das Terminal noch immer am schreiben, was mich misstrauisch stimmte.
Ich probierte ob es mich weitermachen liess und siehe da, es funktionierte!
Liebes Tagebuch, Computer nicht zu ernst zu nehmen und Dinge einfach auszuprobieren lohnt sich fast immer.
Im schlimmstem Fall kannst Du das Ding einfach Neustarten.

Mit DSpace zu arbeiten ist eine sehr involvierte Sache.
Die Benutzeroberfläche ist alles andere als intuitiv.
Die Menüs ändern sich je nachdem, in welcher Ansicht man sich befindet; um eine bestimmte Option zu finden, muss man zuerst in der richtigen Ansicht sein.
Hat man das erreicht, verstecken sich die Optionen unter allgemeinen Begriffen wie ``Create``.
Die Logik die sich dahinter verbirgt, verbirgt sich sehr gut.



-----------NOTIZEN-----------

Nachtrag:
werden DSpace anschauen (wiss publ)
wir vereinheitlichen mit MARC21 (könnten beliebiges anderes nehmen)
das Starten des CodeSpace geht ewig!
	nach 40 min warten realisiert, das Terminal hört nicht auf zu schreiben, kann trozdem weitermachen

Import (übung)
Teils Info wird nicht übernommen
besten maschinell überprüfen
schweirig zu navigieren
muss am richtigen ort hinnavigiren um die Optionen sichtbar zu machen

==> teils fehlen details (wenn es das feld nicht gib - MARC ist ja für bibis - wird das feld ge-dropped)
--> import kann wegen "fehler" abbrechen, weil datentyp

----------

Repository Software für Forschungsdaten

gibt viiel, open Science dings
häufigstes DSpace (Das schauen wir an)
Artikel, Thesis und dis, Bücher, etc
wächst
grün: zuerst verlag, verlag soll zitiert werden, aber auch open
gold: direkt open von anfang an
diamat: neuestes
OpenData: Forschungsdaten
Covid forschung konnte so beschleunigt werden
Klimawandel: gut gegen fake Science von Öl-Multis

re3data.org
verzeichnis von Repositories
Fach- vs Institutionelle Repositorien: Für Forschungsfach (Physich) oder von Institution (FHGR).

DSpace
TUHH Open Research: DSpace-CRIS (Curren Research Info System)
Zenodo von CERN: grosszügig, kostenfrei, gut, empfohlen

Dublin Core 
kernelemente, einige mehr in DC Space, wann eingereicht, veröffentlicht etc. Reicht für Publikationen oft aus

DUI: werden von verschiedenen Org ausgegeben
doi.org: DOI foundation 
Metadatenstandard: Qualified Dublin Core
DSpace 7 neu, recht anders. Wir schauen 6 an

anderes Menu oben bei admin-bereich

zur Übung "Erstellen Sie eine Community und legen Sie darin eine Collection an."

niemand hat die Berechtigungen entdeckt, drum nicht geklappt. sind unter Communiti anlegen --> edit --> EPerson nutzer zuweisen
...sehr intuitiv...
jeweils auf next. Zuerst Admin, dann Submittors, dann Workflow konfigurieren. Sehr Mächtig, sehr involviert
==> quasi das gegenteil von Apple

man kann dies umgehen via SWORD (link in Codi) ist Schnittstelle, Anzeige kann via RSS-feeds erfolgen
kann hochladen: zeugs ausfüllen (soll kunde das wirklich selbst alles? Ev nicht einheitlich so)
Dann Dokument hochladen

Review: Take Task, annehmen, kann auch zurückgeben
Bei collection definiert was Reviewer alles machen Kann/Muss
min Approve/Reject

Drübergeflogen in letzten min. Aus Codi kopiert:
---
Literatur zu DSpace
Präsentationsfolien und Videomitschnitte der Präsentationen auf den jährlichen D/A/CH-Anwendertreffen: https://wiki.lyrasis.org/display/DSPACE/DSpace+Praxistreffen+2023
Suchmaschinenoptimierung (SEO): Abschnitt im Nutzerhandbuch von DSpace zu SEO
Marktüberblick Repository-Software
Grundsätzliches zu Repositorien: https://open-access.network/informieren/publizieren/repositorien
Open Directory of Open Access Repositories (OpenDOAR)
Weltweit
Schweiz
Open Access Repository Ranking 2015 (via Wayback-Machine)
Relevante Systeme in D/A/CH
Alle Open Source!

DSpace
EPrints
Fedora / Islandora
InvenioRDM
besonders interessant, weil die zukünftige Basis von Zenodo am CERN
MyCoRe
OPUS
