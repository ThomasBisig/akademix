---
title: 'Welche Grössen sind in Stössen entscheidend?'
taxonomy:
	id: 2023081114424888
	set:

	requires_physik: []
	requires_mathematik: []

	category: ['exercises']
	fach: Physik
	thema: ['Impuls']
	art: ['Konzept']
	needsSupport: 0
	needsTool: 0

	hints: 0
	bloom: 
	schritte: 2
	schwierigkeit: 1
	realitaet: 2
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230813
	source: 'Thomas Bisig, thomas@akademix.ch'
	learning-objective: ''
	content-type: 'markdown'
	media:
	licence: 'CC BY-SA 4.0'

	status_tags: 2
	status_exercise: 2
	status_solution: 2

	todo: []

routes:
  aliases:
    - '/aufgaben/2023081114424888'

mathjax:
  process: true
---

Überlege dir Antworten zu folgenden Fragen. Mit Skizze.

1. Wenn ein Lastwagen frontal mit einem Kleinwagen zusammenstösst, welche Grösse(n) bestimmen, in welche Richtung sich das Wrack nach dem Zusammenstoss bewegt?
2. Wie entscheidest du beim Poolbillard, wie die weisse Kugel angeschlagen werden muss, um die Acht in die Tasche zu stossen?

[details="Lösung" class="loesung"]
_Teil 1_
![Person rennt mit Papierflieger über ihr](frontalkollision_lastwagen_pkw.svg?resize=400,500&class=float-right)

Die Geschwindigkeit und die Masse (bzw die jeweiligen Verhältnisse) der zwei Fahrzeuge entscheiden, welcher der drei Fälle eintrifft:

- __Meistens__: Da der Lastwagen schwerer ist, wird sich das Wrack bei gleicher Geschwindigkeit der Fahrzeuge __in die Fahrtrichtung des Lastwagens__ bewegen.
- __Selten__: Falls der Lastwagen sehr langsam und das Auto sehr schnell unterwegs ist, kann es sein, dass sich trotz der höheren Masse des Lastwagens das Wrack __in die Fahrtrichtung des Autos__ bewegt. Die Bedingung für das Geschwindigkeitsverhältnis folgt aus der Ungleichung der Beträge der [Impulse](/konzepte/impuls) $p_\textrm{Auto} \gt p_\textrm{LKW}$ und führt zu:

$$
m_\textrm{Auto} \cdot v_\textrm{Auto} \gt m_\textrm{LKW} \cdot v_\textrm{LKW} \rightarrow \frac{v_\textrm{Auto}}{v_\textrm{LKW}} \gt \frac{m_\textrm{LKW}}{m_\textrm{Auto}}
$$

- __Fast nie__: Das Wrack __steht gleich nach der Kollision still__, wenn der Betrag beider Impulse gleich ist $p_\textrm{Auto} = p_\textrm{LKW}$.

_Teil 2_

Da die zwei Kugeln die gleiche Masse haben, ist der Erfolg nur von der Geschwindigkeit der ersten und dem Stosswinkel abhängig.

[/details]