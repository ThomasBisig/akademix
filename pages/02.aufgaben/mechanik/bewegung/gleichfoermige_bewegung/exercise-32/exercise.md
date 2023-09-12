---
title: t-x-Diagramm eines Lastwagens
taxonomy:
	id: 2023041512360016
	set: 0202304151236775

	requires_physik: [Mittlere Geschwindigkeit, t-x-Diagramm]
	requires_mathematik: [Diagramm zeichnen]

	category: exercises
	fach: Physik
	thema: [Mechanik, Bewegung, Gleichförmige Bewegung]
	art: ['Diagramm']
	needsSupport: 0
	needsTool: 0

	hints: 2
	bloom: 1
	schritte: 2
	schwierigkeit: 2
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230430
	source: 'Buch: University Physics, Thomas Bisig (thomas@akademix.ch)'
	learning-objective: ''
	content-type: markdown
	media: 'Thomas Bisig (thomas@akademix.ch)'
	licence: 'CC BY-SA 4.0'

	status_tags: 2
	status_exercise: 2
	status_solution: 2

	todo: [illustration_loesung]

mathjax:
  process: true
---
Ein Lastwagen befindte sich bei $x_1 = 231\,m$ zum Zeitpunkt $t_1 = 12.0\,s$ und bei $x_2 = 35\,m$ zum Zeitpunkt $t_2 = 26.0\,s$.

1. Zeichne zwei mögliche $t-x$-Graphen für die Bewegung des Lastwagens.
2. Hat die mittlere Geschwindigkeit des Lastwagens denselben Wert für beide von dir gezeichneten $t-x$-Graphen? Wieso bzw. wieso nicht?

[details="Tipp zum Vorgehen" class="tipp"]
- Zeichne ein $t-x$-Koordinatensystem und die gegebenen Punkten $(t_1,x_1)$ und $(t_2,x_2)$.
- Welche Graphen zwischen den Punkten beschreiben eine mögliche Bewegung des Lastwagens?
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. siehe Abbildung
2. Die mittlere Geschwindigkeit hat denselben Wert von $\overline{v}=-14\,\frac{m}{s}$

**Lösungsidee**: Zeichnen eines $t-x$-Koordinatensystem mit den zwei Punkten $(t_1,x_1)$ und $(t_2,x_2)$ und nutze die Definition der mittleren Geschwindigkeit.

**Lösungsweg**:

_Teil 1_

- Zeichne ein [$t-x$-Koordinatensystem](/konzepte/konzept-1) mit den zwei Punkten $(t_1,x_1)=(12,231)$ und $(t_2,x_2)=(26,35)$. [Beide Achsen sind angeschrieben und die Skalen](/konzepte/konzept-1) sind eingezeichnet, wie in nebenstehender Abbildung.

- Alle Graphen, welche in der Zeit nicht zurücklaufen, sind mögliche Graphen der Bewegung des Lastwagens.

_Teil 2_

- Die Ortsänderung beträgt
$$
\Delta x=x_2-x_1=35\,m-231\,m=-196\,m
$$

und die dafür benötigte Zeit

$$
\Delta t=t_2-t_1=26\,s-12\,s=14\,s
$$

- Die Definition der [mittlere Geschwindigkeit](/konzepte/konzept-1) liefert dann unabhängig vom gewählten Weg

$$
\overline{v}=\frac{\Delta x}{\Delta t}=\frac{-196\,m}{14\,s} = \underline{-14\,\frac{m}{s}} 
$$

__Bemerkung__: Die mittlere Geschwindigkeit ist nicht dasselbe wie das [mittlere Tempo](/konzepte/konzept-1): das mittlere Tempo benutzt statt der Ortsänderung die zurückgelegte Strecke.

[/details]