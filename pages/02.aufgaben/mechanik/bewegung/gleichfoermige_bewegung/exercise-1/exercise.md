---
title: Der Zug auf der Brücke
taxonomy:
	id: 2023040112397611
	set: 0202304021500123

	requires_physik: [Gleichförmige Bewegung, SI-Einheit]
	requires_mathematik: [Algebraische Umformung]

	category: exercises
	fach: Physik
	thema: [Mechanik, Bewegung, Gleichförmige Bewegung]
	art: Berechnung
	needsSupport: 0
	needsTool: 0

	hints: 2
	detail: 0
	bloom: 2
	schritte: 3
	schwierigkeit: 2
	realitaet: 2
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230419
	source: 'Skript Markus Wey, Skript Thomas Bisig (thomas@akademix.ch)'
	learning-objective: ''
	content-type: markdown
	media: 'thomas@akademix.ch'
	licence: 'CC BY-SA 4.0'

	status_tags: review_1
	status_exercise: review_1
	status_solution: review_1

	todo: ['Bild ohne sB sZ aber mit Distanzen, Farben']

mathjax:
  process: true
---
![Ein Zug fährt über eine Brücke](exercise1-1.svg?resize=400,150&class=float-right) Ein Güterzug hat eine Länge von $350\,m$ und eine Geschwindigkeit von $45\,rac{km}{h}$. Wie lange erfährt eine $220\,m$ lange Eisenbahnbrücke eine Belastung, wenn der Zug darüberfährt?

[details="Tipp zum Vorgehen" class="tipp"]
Wandle die Formel für die gleichförmige Bewegung $\Delta x=v \cdot \Delta t$ um, so dass ein Zusammenhang für die Zeit $\Delta t$ entsteht.
[/details]

[details="Tipp zur Streckenbestimmung" class="tipp"]
Überlege mit Hilfe einer Skizze, auf welcher Strecke $\Delta x$ der Zug die Brücke belastet.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $45.6\,s$

**Lösungsidee**: Bestimmung der Zeit $\Delta t$ mit Hilfe der Strecke $\Delta x$, der konstanten Geschwindigkeit $v$ und der Formel $\Delta x=v\cdot \Delta t$.

**Lösungsweg**:
![Ein Zug fährt über eine Brücke](exercise1-2.svg?resize=400,400&class=float-right) 
1. Der Zug belastet zuerst mit der Lokomotive und zuletzt mit dem hintersten Wagen die Brücke. Die Strecke $\Delta x$, während welcher der Zug die Brücke belastet, beträgt demnach

$$
\Delta x=350\,m + 220\,m=570\,m
$$

2. [Umwandeln](../../../../../konzepte/konzept-1) der Geschwindigkeit $v$ in $\frac{m}{s}$ ergibt

$$
v=45\,\frac{km}{h}=12.5\,\frac{m}{s}
$$

3. [Umformen](../../../../../konzepte/konzept-1) des [Zusammenhangs der geradlinigen Bewegung](../../../../../konzepte/konzept-1)

$$
\Delta x=v\cdot \Delta t
$$

und Einsetzen der gegebenen Grössen

$$
\Delta t=\frac{\Delta x}{v}=\frac{570\,m}{12.5\,\frac{m}{s}}=\underline{45.6\,s}
$$
[/details]