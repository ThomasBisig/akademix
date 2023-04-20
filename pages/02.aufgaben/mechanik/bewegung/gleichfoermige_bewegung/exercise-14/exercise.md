---
title: Autofahrt mit Panne
taxonomy:
	id: 2023040520501112
	set: 0

	requires_physik: [Gleichförmige Bewegung, SI-Einheit]
	requires_mathematik: [Brüche umformen]

	category: exercises
	fach: Physik
	thema: [Mechanik, Bewegung, Gleichförmige Bewegung]
	art: Berechnung
	needsSupport: 0
	needsTool: 0

	hints: 2
	detail: 1
	bloom: 2
	schritte: 3
	schwierigkeit: 2
	realitaet: 
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230405
	source: 'LK1 Mechanik 2022, Thomas Bisig, thomas@akademix.ch'
	learning-objective: ''
	content-type: markdown
	media: no
	licence: 'CC BY-SA 4.0'

	status_tags: [content_created, review_0]
	status_exercise: [content_finished, illustration_na, files_na, review_1]
	status_solution: [content_finished, illustration_na, links_created, files_na, review_1]

mathjax:
  process: true
---

Die Ortschaften A und B sind $30\,km$ voneinander entfernt. Ein Automobilist durchfährt die ersten $20\,km$ mit $80\,\frac{km}{h}$. Eine Panne zwingt ihn, $30$ Minuten zu warten. Die restlichen $10\,km$ legt er dann mit $100\,\frac{km}{h}$ zurück.
1. Wie lange ist er unterwegs? (in Minuten)
2. Welches ist seine mittlere Geschwindigkeit zwischen A und B? (in $\frac{km}{h}$ und $\frac{m}{s}$)


[details="Tipp zur Gesamtzeit" class="tipp"]
Die Zeit, welche der Autofahrer unterwegs ist, kann in drei Abschnitte aufgeteilt werden. Im ersten und dritten Abschnitt liefert der Zusammenhang $\Delta s = v \cdot \Delta t$ (nach Umformung) die Antwort.
[/details]

[details="Tipp zur Streckenbestimmung" class="tipp"]
Die mittlere Geschwindigkeit berechnet sich aus der Gesamtstrecke und der Gesamtdauer.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. $51\,min$
2. $\approx 35.29\,\frac{km}{h},\approx 9.8\,\frac{m}{s}$

**Lösungsidee**: Die Autofahrt wird als drei einzelne Teile betrachtet, berechnet und wieder zusammengefügt.

**Lösungsweg**:

_Teil 1_

Die Zeiten können mit Hilfe des Zusammenhangs für [gleichförmige Bewegungen](../) $\Delta s = v \cdot \Delta t$ bzw. [umgeformt](../) nach $\Delta t = \frac{\Delta s}{v}$ wie folgt berechnet werden:
1. Für die erste Strecke braucht er die Zeit
$$
\Delta t_1=\frac{\Delta s}{v}=\frac{20\,km}{80\,{\frac{km}{h}}}=0.25\,h=15\,min
$$
2. Für die Panne benötigt er
$$
\Delta t_2 = 0.5\,h=30\,min
$$
3. Für die dritte Strecke braucht er die Zeit
$$
\Delta t_3=\frac{\Delta s}{v}=\frac{10\,km}{100\,{\frac{km}{h}}}=0.1\,h=6\,min
$$

Die Gesamtzeit ist dann
$$
t=\Delta t_1+\Delta t_2+\Delta t_3=15\,min + 30\,min + 6\,min = \underline{51\,min}
$$

_Teil 2_

Die [mittlere Geschwindigkeit](../) berechnet sich aus Gesamtstrecke $\Delta s$ durch Gesamtzeit $\Delta t$:

$$
v=\frac{\Delta s}{\Delta t}=\frac{30\,km}{0.25+0.5+0.1\,h}\approx\underline{35.29\,\frac{km}{h}}
$$

und [umgerechnet](../) in $\frac{m}{s}$ ergibt das $\approx \underline{9.80\,\frac{m}{s}}$.



[/details]