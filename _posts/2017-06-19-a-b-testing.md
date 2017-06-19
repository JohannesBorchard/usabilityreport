---
layout: post
title: Warum du im Webdesign nicht auf dein Bauchgefühl, sondern auf A/B-Tests setzen solltest
excerpt_separator: <!-- more -->
category:
  - Methoden
image: /assets/split-test.jpg
---

Wenn du dich auf den Seiten von Google, Amazon oder Ebay bewegst, siehst du mit hoher Wahrscheinlichkeit nicht das selbe Layout wie alle anderen. Und wenn das der Fall ist, bist du Teil eines sogenannten _A/B-Tests_.

Warum diese Methode flächendeckend zum Einsatz kommt und wie du sie selber zur Verbesserung von Usability und User Experience verwendest, erfährst du in diesem Artikel.<!-- more -->

## Was ist ein A/B-Test

In einem _A/B-_ bzw. _Split-Test_ vergleichen wir zwei Versionen einer Webseite – _A_ und _B_ – um herauszufinden, welche besser funktioniert. Dafür sehen zeitgleich 50% der Nutzer die Originalseite und 50% die Abwandlung. Die dabei gesammelten anonymisierten Daten werten wir aus und können uns mit Zuversicht für eine der Ausführungen entscheiden. Dabei kommt es nicht selten zu überraschenden Ergebnissen.

Anders als bei _Multivariate-Tests_ untersuchen wir bei _A/B-Tests_ nur _eine Variable_ – etwa die Farbe eines Buttons oder auch die gesamte Seite. Das macht es uns einfach, die grundlegenden Prinzipen gelten dabei auch für _Multivariate-Tests_.

![A-B-Test](/assets/split-test.svg)

## Wofür brauche ich das?

Das Verfahren kommt [im Marketing](https://vwo.com/ab-testing/) schon länger zum Einsatz, lässt sich aber ebenso gut zur [Optimierung von Usability und User Experience](http://usabilitygeek.com/introduction-a-b-testing/) verwenden.

Je nach Motivation können wir effektiv die Rate an _Conversions_ (Zustandsänderung: z.B. Interessent wird Kunde) erhöhen, aber auch den Einfluss von Layout-Variationen und _Redesigns_ untersuchen. Nicht zuletzt wenden wir das Verfahren bei _Usability-Tests_ an.

Der Gegensatz wäre eine blinde Entscheidung aus dem Bauch heraus, die unbemerkt drastische Folgen zum Nachteil der Nutzer mit sich ziehen könnte.

Person X findet die Seite zu langweilig und möchte sie _nur etwas aufpeppen_, Person Y hat da letztens so ein _cooles Feature_ gesehen das bestimmt auch hier funktioniert und Person Z möchte sich künstlerisch im Layout verwirklichen.

_A/B-Tests_ hingegen erlauben es, uns von _zwei Varianten_ für die _objektiv bessere_ zu entscheiden.

## Was kann ich alles testen?

Ob zur Maximierung der _Conversion Rate_ oder zu Optimierung von Usability und User Experience lassen sich einige Elemente testen:

-   Startseite
    		\- Hintergrundfarbe
    		\- Titel und Überschriften
    		\- Header Bild
    		\- Testimonials
-   Call to Action (Aufruf etwa zur Registrierung)
    		\- Position auf der Seite
    		\- verwendetes Bild
    		\- Farbe, Größe und Position des Buttons
    		\- Formular
    		\- verwendeter Text
-   komplettes Redesign
-   neues oder überarbeitetes Feature
-   Prozess der Registrierung bzw. Anmeldung

### Metriken

Um uns zu entscheiden, müssen wir uns zunächst festlegen, was wir messen. Hierfür stehen uns eine Reihe an quantitativen Maßen zur Verfügung:

-   Absprungrate
-   _Conversion Rate_ (z.B. Anzahl der Käufe, Registrierungen, Downloads, ...)
-   Erfolg innerhalb eines Zeitrahmens (z.B. bei der Registrierung)
-   Zeit für eine Aufgabe
-   Anzahl der Fehler

## Wie teste ich am einfachsten?

_A/B-Tests_ sind angelehnt an den _wissenschaftlichen Prozess_ bzw. an das Verfahren des _Hypothesentests_. Wir stellen also widerlegbare Behauptungen über die Wirklichkeit auf, um sie dann empirisch zu testen. Anschließend entscheiden wir mit Hilfsmitteln, ob die Behauptung _statistisch signifikant_ ist.

1.  Wir untersuchen vorliegende Daten der Webseite, um Schwachpunkte zu finden, wie etwa eine hohe Absprungrate. Auf die Weise sind wir [effektiver als bei Entscheidungen aus dem Bauchgefühl](https://vwo.com/ab-testing/#!).
2.  Wo liegen die Ursachen der Probleme? Mit _Heatmaps_, _Visitor Recordings_, Formularanalysen und Umfragen versuchen wir, das Nutzerverhalten zu verstehen.
    ![Example Heatmap](/assets/heatmap.jpg)
3.  Auf Grundlage der gewonnenen Einsichten stellen wir nun eine Hypothese auf und entwerfen eine entsprechende Abwandlung der Seite.
4.  Nun testen wir die Hypothese, indem wir die Originalseite mit der Variation vergleichen.
    Zuerst legen wir die Größe der Stichprobe und Dauer des Tests fest. Mit [diesem Rechner](https://www.convert.com/tools/ab-test-duration-calculator/) können wir die entsprechende Werte herausfinden. Für „Number of Variations“ tragen wir „1“ ein und anstelle der _Conversion Rate_ können wir auch andere Maße eintragen, sofern diese relativ sind (z.B. von 30% Absprungrate auf 10% als Ziel).

    Mit Tools wie [Google Optimize](https://www.google.com/analytics/optimize/) (kostenlos, verwendet Google Analytics) oder [Optimizely](https://www.optimizely.com/plans/) (im _Starter Plan_ kostenlos) können wir den Test auf einfache Weise durchführen. Dazu verlinken wir Original und Variation, fügen den _Script_ in unseren Code ein und lassen den Test laufen.

5.  Ist der Test beendet, können wir unsere Daten auswerten. Zusätzlich zur Entscheidungshilfe in den Test-Tools empfehle ich dir, die Ergebnisse [extern auf Signifikanz zu prüfen](http://www.abtestcalculator.com). Das ist vor allem bei kleinen Veränderungen (Absprungrate fällt von 30% auf 25%) ratsam und du brauchst dafür nichtmal Excel zu starten.
    ![Significance](/assets/significance.jpg)
6.  Mit den neuen Einsichten kannst du nun die Abwandlung für alle Nutzer sichtbar schalten oder (wenn keine signifikante Verbesserung erreicht wurde) einen neuen Test durchführen. Außerdem empfiehlt es sich, deine gewonnenen Erfahrungen etwa in einem Blog mit anderen zu teilen.

## Fazit

_A/B-Tests_ sind vom Aufbau so simpel wie effektiv. Du _vermutest_, dass eine Variation der Webseite besser laufen könnte? Dann teste sie doch einfach gegen das Original und geh _auf Nummer sicher_. Der Aufwand ist gering und lohnt sich immer.
