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

Es ging verwirrend weiter.
Wir haben via Eingabebefehl verschiedene Erntemethoden von VuFindHarvest ausprobiert.
Nämlich via Koha, ArchivesSpace und DSpace.
Bemerkenswert ist, das die Eingabebefehle Internetadressen enthielten, deren Inhalt dann geerntet wurde.
Kein extra Programm musste zwischengeschaltet werden.
Das ominöse OAI-PMH war Teil jedes Befehls, doch ob es ein Programm, ein Standard oder ein Algorithmus ist, erschloss sich mir erst als ich Doktor Wikipedia um [Rat](https://en.wikipedia.org/wiki/Open_Archives_Initiative_Protocol_for_Metadata_Harvesting) bat.
Die Antwort liegt im Namen, der nämlich ein Akronym ist, das verrät, dass es sich um ein Protokoll, also einen Algorithmus - sprich eine Methode - handelt.
Bitte erinner mich dran bei der nächsten Verwirrung gleich Wikipedia zu besuchen.

Eine Konvertierung eines Metadatenstandards in einen anderen, nennt man gemeinhin einen "Crosswalk".
Wie zum Beispiel ein Crosswalk von DC zu MARC21-XML.
Fleissig wie ich bin, habe ich gleich [Überprüft was ChatGPT aus der Aufgabe macht](https://florian896.github.io/lerntagebuch-bain/ClippyCodes.html).
Es lässt sich validieren.
Ob es fehlerfrei und vollständig ist, kann ich leider nicht mit abschliessender Sicherheit sagen.
Für meine Augen sieht es aber gut aus.
Es dauert jedoch sehr lange, da ChatGPT jede Zeile einzeln generiert.

Die Bibliothek des Verkehrs (Library of Congress) hat einen offiziellen Standard definiert, der eigentlich im Idealfall verlustfrei sein sollte.
Ein Kommilitone meldete sich aber sofort und erläuterte, dass die Standards je nach Organisation verschieden interpretiert würden.
Eine Konvertierung eines ganzen Datensatzes von einer anderen Organisation würde wohl aus Chaos noch mehr Chaos machen.
Tatsächliche Verwendung in der Praxis finden Corsswalks eher via einer (verlustbehafteten) Vereinfachung des Datensatzes dank DC-Komprimierung.
Das Resultat muss formell, aber vor allem auch inhaltlich validiert werden.
Womit man wieder bei einem Ähnlichen Problem ist wie am Anfang.
Effektiv kann es hilfreich sein, wenn beispielsweise der Verlag Daten in einem für uns ungünstigen Format liefert.

Was wir nutzen ist ein sehr sympathisches Programm namens MarcEdit.
Es ist nicht Offene Quelle, aber durchaus gratis zu benutzen.
Es wird von einer einzelnen Person entwickelt und unterhalten.
Das schlägt sich im Design durchaus nieder. 
Die Nutzeroberfläche wirkt improvisiert und etwas uneinheitlich; da sie über die Jahre so "gewachsen" ist.
Es ist das Gegenteil von Apple.
Überhaupt nicht Hochglanz, dafür höchst anpassbar, schlank und äusserst kompatibel mit verschiedenen Systemen.
Es hat einen angenehmen Charakter.
Dazu kommt, dass es schon lange existiert und konsistent stabil ist.
Deshalb hat es sich als Standard durchgesetzt.
Natürlich kann auch MarcEdit nicht Zaubern und Konvertierung bleibt verlustbehaftet.

Zum Abschluss habe ich noch ein paar Links für dich.
 + [Der Programminghistorian ist wie immer empfehlenswert](https://programminghistorian.org/en/lessons/transforming-xml-with-xsl)
 + [Ein (beschränktes) Online-Tool](http://xsltransform.net)
 + [MarcEdit!](https://marcedit.reeset.net)
 + [MarcEdit Lektion von Library Carpentry](https://librarycarpentry.org/lc-marcedit/)
 + [OpenRefine Wiki](https://github.com/OpenRefine/OpenRefine/wiki/Export-as-MARCXML)
 + [Weitere Tools zur Metadatentransformation](https://pad.gwdg.de/#Weitere-Tools-zur-Metadatentransformation)


Liebe Grüsse

Florian
