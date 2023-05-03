---
title: Autofahrt mit Panne
taxonomy:
	id: 2023043013441001
	set: 0202304301344555

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
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230430
	source: 'LK1 Mechanik 2022, Thomas Bisig (thomas@akademix.ch)'
	learning-objective: ''
	content-type: markdown
	media: no
	licence: 'CC BY-SA 4.0'

	status_tags: review_0
	status_exercise: review_0
	status_solution: review_0

	todo: ['']

mathjax:
  process: true
---

Zwei Ortschaften sind $50\,km$ voneinander entfernt. Ein Automobilist durchfährt die ersten $30\,km$ mit $60\,\frac{km}{h}$. Eine Panne zwingt ihn, $20$ Minuten zu warten. Die restliche Distanz legt er dann mit $80\,\frac{km}{h}$ zurück.

1. Wie lange ist er unterwegs? (in Minuten)
2. Welches ist seine mittlere Geschwindigkeit zwischen den Ortschaften? (in $\frac{km}{h}$ und $\frac{m}{s}$)


[details="Tipp zur Gesamtzeit" class="tipp"]
Die Zeit, welche der Autofahrer unterwegs ist, kann in drei Abschnitte aufgeteilt werden. Im ersten und dritten Abschnitt liefert der Zusammenhang der gleichförmigen Bewegung die Antwort.
[/details]

[details="Tipp zur Streckenbestimmung" class="tipp"]
Die mittlere Geschwindigkeit berechnet sich aus der Gesamtstrecke und der Gesamtdauer.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. $\Delta t = 65\,min$
2. $\overline{v} \approx 46.15\,\frac{km}{h},\approx 12.82\,\frac{m}{s}$

**Lösungsidee**: Die Autofahrt wird als drei einzelne Teile betrachtet, berechnet und wieder zusammengefügt.

**Lösungsweg**:

_Teil 1_

Die Zeiten können mit Hilfe des Zusammenhangs für [gleichförmige Bewegungen](/konzepte/konzept-1) $\Delta x = v \cdot \Delta t$ bzw. [umgeformt](/konzepte/konzept-1) nach $\Delta t = \frac{\Delta x}{v}$ wie folgt berechnet werden:
1. Für die erste Strecke braucht er die Zeit
$$
\Delta t_1=\frac{\Delta x_1}{v_1}=\frac{30\,km}{60\,{\frac{km}{h}}}=0.5\,h=30\,min
$$
2. Für die Panne benötigt er
$$
\Delta t_2 = 0.\overline{3}\,h = 20\,min
$$
3. Für die dritte Strecke braucht er die Zeit
$$
\Delta t_3=\frac{\Delta x_3}{v_3}=\frac{20\,km}{80\,{\frac{km}{h}}}=0.25\,h=15\,min
$$

Die Gesamtzeit ist dann
$$
t=\Delta t_1+\Delta t_2+\Delta t_3=30\,min + 20\,min + 15\,min = \underline{65\,min}
$$

_Teil 2_

Die [mittlere Geschwindigkeit](/konzepte/konzept-1) berechnet sich aus Gesamtstrecke $\Delta x$ durch Gesamtzeit $\Delta t$:

$$
v=\frac{\Delta x}{\Delta t}=\frac{50\,km}{0.5+0.\overline{3}\,h+0.25\,h}\approx\underline{46.15\,\frac{km}{h}}
$$

und [umgerechnet](/konzepte/konzept-1) in $\frac{m}{s}$ ergibt das $\approx \underline{12.82\,\frac{m}{s}}$.

[/details]