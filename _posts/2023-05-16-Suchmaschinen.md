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
Die Entwickler sind eine Offene Quelle Gemeinschaft, die sehr aktiv an VuFind arbeiten.
Vier Personen stehen als am häufigsten Mitwirkende heraus und es handelt sich generell um eine gesunde Gemeinschaft.
Dazu kommt, dass zu den Nutzern unter anderem die Nationalbibliothek von Finnland zählt, was bedeutet, dass eine signifikante Organisation an der Weiterführung des Projektes interessiert ist.

Für die Suchfunktion von VuFind baut auf Solr auf.
Solr ist eine Open Source Suchplattform, die sich zum Industriestandard entwickelt hat.
Was Solr alles kann hat mich sehr beeindruckt.
Nun, bedenke, Solr ist nicht für die gemeinen Nutzenden gedacht, sondern als im Hintergrund laufendes Programm, das der Nutzerfreundlichen Fassade viele wunderbare Funktionen gibt.
Entsprechend sind zum Beispiel die Facetten schwieriger zu finden als bei VuFind.
Ebenso steht die Konsistenzprüfung nicht im Vordergrund. 
Solr ist keine Datenbank, sondern eine Suchplattform.
Die Geschwindigkeit der Suchen steht im Fokus.
Dazu muss die Integration von Schnittstellen, auch zu mehreren Datenbanken gleichzeitig, reibungslos funktionieren.
Zu meiner persönlichen Überraschung tut sie das auch.
Und das mit all den Funktionen die man sich nur wünschen kann.
Ein Grund dafür wird die Indexierung, die vorgenommen wird sein, aber auch dann ist die Geschwindigkeit von Solr eindrücklich.
Es bietet sogar ein Relevanzranking, indem es Treffer in verschiedenen Feldern mit verschiedenen Zahlen multipliziert.
Welches Feld welche Zahl erhält wurde durch Erfahrungswerte bestimmt.
Schlussendlich wird das Suchresultat im JASON Format ausgegeben.
Das ist gerade so menschenlesbar, dafür aber sehr praktisch für Schnittstellen, die Solr einbinden.

Ein cleverer Schachzug von VuFind ist es, die Facetten, die Solr angibt als "ähnliche Schlagwörter" anzuzeigen.
Damit wird eine sehr praktische Funktionalität einfach eingebunden und in selbsterklärender Form den Nutzenden angeboten.
Auch eine Autovervollständigung wird angeboten, die sogar Suchfeld-spezifisch ist.
Solr ist schnell genug um das sinnvoll umzusetzen.

Ein Trick den wir gelernt haben, ist die ``config`` Datei zu kopieren und unsere Einstellungen (via Textbearbeitung) an der Kopie vorzunehmen.
So löscht uns kein Update Einstellungen.

Ich habe es gar nicht gemerkt, aber hier macht das Bild aus dem Unterricht endlich Sinn:

![ ](https://pad.gwdg.de/uploads/c8d2a2dc-b427-4330-a665-b355a2a85f50.png)

Solr braucht sein Input in MARC21-XML und kann wunderbar in VuFind ausgegeben werden!

Liebe Grüsse

Florian
