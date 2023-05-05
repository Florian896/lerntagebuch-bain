---
title: "Funktion und Aufbau von Bibliothekssystemen Teil II"
date: 2023-04-04
---

Liebes Tagebuch

Nach längerer Pause setzte die Vorlesung fort wo sie aufgehört hatte.
In der Mitte des Themas "Funktion und Aufbau von Bibliothekssystemen".
Falls du Mühe hast dich zu erinnern, findest du meine Ausführungen dazu [hier](https://florian896.github.io/lerntagebuch-bain/2023/03/07/Bibliotheksysteme1.html) und das Gemeinsame Vorlesungs-Dokument [hier](https://pad.gwdg.de/glYuuHwsS6aokIat19Kxpg).  

Doch zuerst erhielten wir Feedback zu unseren Ausführungen in unseren Tagebüchern.
Meine Bemerkungen zu ChatGPT wurden als interessant hervorgehoben. 
Das hat mich gefreut.
Andere Studierende haben die "Usability", also die Benutzerfreundlichkeit, bemängelt.
Wenn man die Bibliothekssysteme mit Programmen für die breite Öffentlichkeit vergleicht, fallen sie durchaus auf wie der Dorn im Auge.
Als täglicher Nutzer eines dieser Programme (WinMedio), muss ich jedoch in einem Punkt widersprechen.
Der "Mangel", dass ein Suchschlitz für viele Funktionen verwendet wird, ist ein mir sehr wichtiges Feature.
Die Praxis ist nämlich eine ständige Nutzung des Programms, während des gesamten Thekendienstes.
Entsprechend ist der Programmspezifische Wissensstand sehr hoch und die Geschwindigkeit der Hauptfokus.
Gibt es mehrere Optionen etwas zu erreichen, wähle ich immer die schnellste.
Die blosse Vorstellung eines Waldes an Suchschlitzen verstört mich aufs tiefste.
Insbesondere, da bereits jetzt WinMedio teilweise das Verhalten ändert, je nachdem welcher Reiter auf der linken Seite (Katalog, Ausleihe, Nutzerkonten, etc.) aktiv ist; Das führt zu hoher Komplexität und erschwert das Einarbeiten neuer Mitarbeitenden erheblich. 
Eine Nutzerfreundliche Überarbeitung dieser Programme, die die Möglichkeit eines effizienten Arbeitens mit im Blick behält, würde ich allerdings sehr begrüssen.

Lass uns nun zur Lerneinheit zurückkehren.
Wir haben uns mit der Konfiguration von Koha, dem Datenimport und dem Datenexport beschäftigt.
Meiner Meinung nach kannst du das Konfigurieren am besten lernen, indem du "explorativ herumklickst", sprich die Verschiedenen Optionen nutzt und beobachtest was passiert.
Zum Glück gibt es eine [Demoversion](https://koha.adminkuhn.ch:8443/) wo du das ausprobieren kannst.
Benutzername ist ``demo`` und das Passwort ist auch ``demo``.
Viel Spass!
Um es weniger ironisch zu formulieren: Ich glaube um dieses Programm wirklich zu verstehen und zu beherrschen müsstest du eine Weile regelmässig damit arbeiten.
Ich empfehle mindestens sechs Monate für alle Programme dieser Art.

Datenexport und Datenimport funktioniert, indem man eine sogenannte [Schnittstelle](https://de.wikipedia.org/wiki/Schnittstelle) ansteuert.
Eine Schnittstelle ist ein Teil eines Programms, der nur der Kommunikation dient.
Das kann kommunikation mit Menschen oder mit anderen Programmen sein.
Die Schnittstelle die wir benuten heisst OAI-PMH.
Das steht für ``Open Archives Initiative Protocol for Metadata Harvesting``.
Koha unterstützt als offenes Programm diverse Schnittstellen.
Auf die anderen sind wir aber nicht eingegangen.
In einer folgenden Lerneinheit werden wir noch mehr dazu lernen.

Die Marktsituation ist etwas besorgniserregend, aber noch haltbar.
Wie in jedem freien Markt kaufen die verschiedenen Anbieter einander auf.
Weil Grösse ein beachtlicher Marktvorteil ist, funktioniert die Taktik und führt, mit Zeit und Kapitalismus, richtung Monopol.
Die aktuelle Situation, wer wen gekauft hat, lässt sich [hier ablesen](https://librarytechnology.org/mergers/).
Zum Glück gibt es noch Open Source Alternativen, wie Koha, was das Monopol verhindert.
Ein Open Source Projekt kann man nähmlich nicht kaufen.

Liebe Grüsse

Florian
