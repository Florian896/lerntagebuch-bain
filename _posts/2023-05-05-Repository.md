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
Die Menüs ändern sich je nachdem, in welcher Ansicht man sich befindet; um eine bestimmte Option zu finden, muss man zuerst zum richtigen Ort navigieren.
Hat man das erreicht, verstecken sich die Optionen unter allgemeinen Begriffen wie ``Create``.
Die Logik die sich dahinter verbirgt, verbirgt sich sehr gut.
Dafür lässt sich alles individuell einrichtien.
Es scheint sehr mächtig zu sein und vermutlich ist die Systeminfrastruktur genial, was bedeutet, dass es eine super Option ist, wenn man die grosse Einarbeitungshürde bezwingt.

Um das Program kennenzulernen haben wir eine Datei importiert und wieder exportiert.
Wir haben MARC21 verwendet, was ein Format ist, das für Bibliotheken entwickelt wurde.
Wir hätten ein beliebeiges anderes nehmen können, aber ich bin froh haben wir dieses genommen, weil ich bereits damit vertraut bin.
Wir verglichen unseren Datensatz vor dem Import, danach und nach dem Export.
Verlustfrei ist anders.
Jegliche Felder die DSpace nicht kennt weden einfach ignoriert und nicht importiert.
Scheinbar ist das nicht nur ein Problem mit MARC21, sondern generell bei jedem konvertieren.
Bei kleinen Übungsdatensätzen kann händisch verglichen und korrigiert werden, bei grösseren jedoch, beischpielsweise von einem Archiv, wird das schwierig bis unmöglich.
Es ist also ein maschinelles Überprüfen des Resultats nötig.
Wie so eine Prüfung vollbracht werden könnte, haben wir jedoch nicht behandelt.
Wird ein Datentyp nicht erkannt, kann sogar der ganze Import mit einer Fehlermeldung abbrechen.
In mir entstand der Eindruck, dass jedes importieren ein fehleranfälliger aufwendiger Prozess ist, der leicht unterschätzt wird.
Ich werde versuchen zu verhindern für einen verantwortlich zu sein.

Mir geht schon wieder die Tinte aus.
Lass mich zum Abschied noch ein paar weiterführende Verweise anführen.

+ [Verzeichnis von Repositories](re3data.org)
+ [Präsentationsfolien und Videomitschnitte der Präsentationen auf den jährlichen D/A/CH-Anwendertreffen](https://wiki.lyrasis.org/display/DSPACE/DSpace+Praxistreffen+2023)
+ [Abschnitt im Nutzerhandbuch von DSpace zu SEO](https://wiki.lyrasis.org/display/DSDOC7x/Search+Engine+Optimization)
+ [DSpace](https://www.dspace.org)
+ [EPrints](https://www.eprints.org)
+ [Fedora](http://fedorarepository.org) / [Islandora](https://islandora.ca)
+ [InvenioRDM](https://invenio-software.org/products/rdm/)
  - besonders interessant, weil die zukünftige Basis von Zenodo am CERN
+ [MyCoRe](https://www.mycore.de)
+ [OPUS](https://www.opus-repository.org)


Liebe Grüsse

Florian
