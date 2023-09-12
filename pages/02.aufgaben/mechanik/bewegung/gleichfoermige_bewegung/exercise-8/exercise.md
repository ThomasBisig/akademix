---
title: Der Zug auf der Brücke
taxonomy:
	id: 2023040113161276
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
	bloom: 2
	schritte: 5
	schwierigkeit: 3
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230503
	source: 'Thomas Bisig (thomas@akademix.ch)'
	learning-objective: ''
	content-type: markdown
	media: 'thomas@akademix.ch'
	licence: 'CC BY-SA 4.0'

	status_tags: 2
	status_exercise: 2
	status_solution: 2

	todo: ['Bild und Farben']

mathjax:
  process: true
---
![Ein Zug fährt über eine Brücke](exercise1-1.svg?resize=400,150&class=float-right) Ein Zug mit einer bestimmten Länge fährt mit einer bestimmten Geschwindigkeit über eine Brücke mit einer bestimmten Länge.
1. Wie lange wird die Brücke belastet, während der Zug darüberfährt?
2. Was ist die Voraussetzung an die Geschwindigkeit des Zuges, dass die Formel stimmt?
3. Was muss bei der Angabe der Werte (für Geschwindigkeit und Längen) beachtet werden, dass die Formel stimmt?

[details="Tipp zum Vorgehen" class="tipp"]
Nutze die Formel für die gleichförmige Bewegung, um einen Zusammenhang für die Zeit $\Delta t$ zu finden.
[/details]

[details="Tipp zur Streckenbestimmung" class="tipp"]
Überlege mit Hilfe einer Skizze, auf welcher Strecke $\Delta x$ der Zug die Brücke belastet.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $\Delta t=\frac{\Delta x_{Z}+\Delta x_{B}}{v}$

**Lösungsidee**: Bestimmung der Zeit $\Delta t$ mit Hilfe der Strecke $\Delta x$, der konstanten Geschwindigkeit $v$ und der Formel $\Delta x=v\cdot \Delta t$.

**Lösungsweg**

_Teil 1_

![Ein Zug fährt über eine Brücke](exercise1-2.svg?resize=500,400&class=float-right) 
1. Die benötigten Grössen sind wie folgt definiert:
	- $\Delta t$: die gesuchte Zeitspanne
	- $\Delta x_{Z}$: die Länge des Zuges
	- $\Delta x_{B}$: die Länge der Brücke
	- $v$: die Geschwindigkeit des Zuges

2. Der Zug belastet zuerst mit der Lokomotive und zuletzt mit dem hintersten Wagen die Brücke. Die Strecke $\Delta x$, über welche der Zug die Brücke belastet, beträgt demnach

$$
\Delta x_{Z}+\Delta x_{B}
$$

3. [Umformen](/konzepte/konzept-1) des [Zusammenhangs der gleichförmigen Bewegung](/konzepte/konzept-1)

$$
\Delta x=v\cdot \Delta t \rightarrow \Delta t=\frac{\Delta x}{v}
$$

und Einsetzen der gegebenen Grössen

$$
\Delta t=\frac{\Delta x}{v}=\frac{\Delta x_{Z}+\Delta x_{B}}{v}
$$


_Teil 2_

Die Geschwindigkeit des Zuges muss konstant sein.

_Teil 3_

Alle Angaben müssen in denselben Einheiten angegeben werden (zB SI-Einheiten).
[/details]