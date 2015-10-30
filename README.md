# wordpress-tabelle
Wordpress Tabelle für Empfehlungen / Test / Vergleich: [Webseite](http://microsd.github.io/wordpress-tabelle/)

Wie erstellt man in Wordpress mehrspaltige Tabelle, die auch auf dem Handy gut aussehen? Ein Beispiel für eine solche Tabelle ist [hier](http://www.micro-sd.net/micro-sd-128gb/) bzw. [hier](http://www.micro-sd.net/micro-sd-64gb/) exemplarisch für einen Vergleich von micro sd karten. Ich habe dort viel ausprobiert, jedoch stellt sich dieses Vorhaben als äußerst schwierig in Wordpress dar. Wie erstellt man nun eine Tabelle in Wordpress? Ich empfehle hier das Plugin TinyMCE: ![TinyMCE](https://raw.githubusercontent.com/microsd/wordpress-tabelle/master/images/tinymce.jpg) Nach der Installation über Wordpress erscheinen im Editor von Posts bzw. Pages zusätzliche Icons. Unter anderem ist dort auch ein Icon zum Erstellen einer Tabelle.
![Tabelle erstellen](https://raw.githubusercontent.com/microsd/wordpress-tabelle/master/images/tabelle.jpg)

Per Maus kann man dann die entsprechende Tabellengröße auswählen und bequem die einzelnen Felder per Maus ausfüllen. Wechselt man in den Text-Modus, kann jeder Eintrag zwischen den td-Tags bearbeitet werden.
Ein Hauptproblem bleibt jedoch: die Tabelle bricht nicht spaltenweise um, wie es für Tablets oder Smartphones sinnvoll wäre. Hierzu habe ich zwei Varianten realisiert.

1. Mittels Media-Queries und einem Custom-CSS Plugin einen spaltenweisen Umbruch realisieren, indem man zwei Tabellen pro Seite einfügt. Die erste Tabelle ist für breite Screens, die zweite Tabelle für schmale Screens. Per Media-Queries wird eine Tabelle angezeigt, die andere ausgeblendet, je nach Bildschirmbreite. Der Nachteil an dieser Lösung ist die Code-Dopplung auf der Wordpress-Seite. Man muss für jede Tabelle zwei Versionen pflegen.

2. Der einfachste Weg ist direkt nur auf die schmale Tabelle zu setzen. Dies hat außerdem den Vorteil, dass nur die wichtigste Information gezeigt wird und man unnütze Spalten gleich weglässt.
(http://www.oszilloskope.net)
