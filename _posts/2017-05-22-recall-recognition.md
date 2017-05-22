---
layout: post
title: Recall vs. Recognition – Wie wir die Welt wahrnehmen und was das für Interfaces bedeutet
excerpt_separator: <!-- more -->
category:
  - Einfach erklärt
image: /assets/bash.jpg
---

Eine der [_Zehn Usability Heuristiken von Nielsen_](/usability-heuristiken-nielsen) besagt, dass Wiedererkennung _(Recognition)_ besser ist als Erinnerung _(Recall)_.

Doch warum ist das so und wie setzen wir die Regel konkret beim Design von Interfaces um?

Dieser Artikel beleuchtet die psychologischen Hintergründe unserer Wahrnehmung. Er erklärt die Begriffe _Recall_ und _Recognition_, gibt anschauliche Beispiele und liefert schließlich praktische Ansätze für gutes Design.<!-- more -->

## Wie nehmen wir war?

### Bottom-Up und Top-Down

Nach [_Gibson_ und _Gregory_](https://simplypsychology.org/perception-theories.html) kann Wahrnehmung auf zwei Arten ablaufen. Bei der _Bottom-Up_-Verarbeitung nehmen wir einen Stimulus über unsere Sinne war. In der _Top-Down_-Verarbeitung hingegen schafft unsere Erfahrung Wissen und Erwartungen.

Unsere [Aufmerksamkeit ist selektiv](http://prometei.de/fileadmin/prometei.de/veranstaltungen/2008-05-28-Wickens_AppliedAttentionTheory.pdf) und richtet den Fokus auf bestimmte Objekte, während andere ausgeblendet werden. Für die Auswahl werden sowohl _Bottom-Up_-Kriterien – Salienz (Aufspringen) und Anstrengung – als auch _Top-Down_-Kriterien – Erwartung und Wert – herangezogen.

### Arbeitsgedächtnis und Chunking

Unser Arbeitsgedächtnis ist in seiner Kapazität begrenzt und kann lediglich 4 ± 1 Objekte auf einmal behalten.

Stell dir vor, du müsstest die Zahlen _0-2-2-1-8-9-9-2-0_ im Kopf behalten.

Neben ständiger Wiederholung wendet unser Gehirn noch einen weiteren Trick an, um solche Aufgaben zu bewältigen – das sogenannte [_Chunking_](https://www.verywell.com/chunking-how-can-this-technique-improve-your-memory-2794969). _Chunks_ sind logische Gruppierungen von Informationen. Von diesen kann das Arbeitsgedächtnis [7 ± 2](https://de.wikipedia.org/wiki/Chunking) behalten.

Die Telefonnummer _0221 8992-0_ wirst du dir sicherlich leichter merken können.

### Recognition vs. Recall

Die Ansätze der Bottom-Up und Top-Down Wahrnehmung lassen sich darauf übertragen, wie wir [auf unser Langzeitgedächtnis zugreifen](https://www.nngroup.com/articles/recognition-and-recall/). Bei der Wiedererkennung _(Recognition)_ von Objekten nehmen wir diese als _bekannt_ war. Im Zuge der Erinnerung _(Recall)_ greifen wir selber auf gespeicherte Informationen zurück.

Bei der _Wiedererkennung_ haben wir viele verschiedene Hinweise zur Verfügung – wenn wir uns _erinnern_, ist meistens nur einer vorhanden. Folglich fällt es uns wesentlich leichter, Objekte wiederzuerkennen, als sie selber zu reproduzieren.

Offene Fragen bereiten uns deshalb auch mehr Schwierigkeiten als Multiple-Choice-Tests.

## Erinnerung bei Interfaces

Als man Computer noch ausschließlich mit Befehlszeilen bediente, hatte man entsprechend wenig Hinweise und musste sich sowohl die Befehle, als auch deren Parameter und Reihenfolge merken. Aktuelle Beispiele für _Recall_ sind Short-Cuts, Gesten und das sogenannte _Burger-Menü_. Letzteres meint jene drei Striche, die sich in den Ecken vieler Webseiten finden und als _scheinbarer Standard_ so manche Hilflosigkeit zur Folge hatten.

![Befehlszeile bei MacOS](/assets/bash.jpg)

## Wiedererkennung bei Interfaces

Die Menüleiste ist ein gutes Beispiel für _Recognition_ – ob auf einer Webseite oder in Excel. Auf ihr finden wir die möglichen Funktionen und können einfach auf sie zugreifen. Icons, welche zusätzlich mit [(eindeutigem) Text](/information-architecture) versehen sind räumen Zweifel aus dem Weg. Die Präsentation zuletzt benutzter oder angesehener Objekte hilft uns ebenfalls bei der Bedienung.

In der Praxis kommt es häufig zu Mischformen aus _Recall_ und _Recognition_. Du erinnerst dich zum Beispiel an so einen _Blog_ zu _User Experience_ von _Johannes_, weißt aber nicht mehr die Adresse. Die Schlagwörter _(Recall)_ gibst du also in der Suchmaschine deiner Wahl ein und wählst aus den Suchergebnissen _(Recognition)_ das hoffentlich passende heraus.

## Gutes Design

Für leicht bedienbare Interfaces müssen wir also Wiedererkennung unterstützen und die [Informationen sichtbar und leicht zugänglich](/information-architecture) machen. Wenn komplett gestengesteuerte Apps beim ersten Öffnen ein viel zu langes Tutorial präsentieren, hilft das keinem. Besser sind Hinweise, die fest im Interface eingebettet sind. Elementare Aktionen sollten gut zugänglich und deren Icons mit Text versehen sein. Ähnliche Informationen können wir gruppieren oder so formatieren, dass _Chunking_ erleichtert wird. Die Einhaltung der _Interface Guidelines_ des Betriebssystems oder üblicher Webstandards ist ebenfalls zu empfehlen. Der User hat nämlich bereits unterbewusste Erwartungen an die Bedienung des Systems. Das können gängige Gesten am Smartphone sein (Wischen zum löschen) aber auch die Platzierung des Menüs (Oben oder links).

Sind diese Punkte berücksichtigt, kann sich unser Arbeitsgedächtnis mit der eigentlichen Aufgabe beschäftigen.

## Zusammenfassung

Wahrnehmung und Abruf aus dem Langzeitgedächtnis funktionieren also auf zwei Arten. _Bottom-Up_ bzw. _Wiedererkennung_ fällt uns dabei wesentlich leichter. Da unser Arbeitsgedächtnis zudem begrenzt in seinem Umfang ist, sollten wir die entsprechenden Aspekte beim Interfacedesign berücksichtigen.

Auch wenn es im Konflikt mit aktuellen Design-Trends steht, sollten wir nötige Hinweise dort geben, wo Wiedererkennung dem Nutzer hilft.
