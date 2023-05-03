---
title: Motorradfahrt auf der Autobahn
taxonomy:
	id: 2023041516311112
	set: 0202304151548667

	requires_physik: [Mittlere Geschwindigkeit, SI-Einheit]
	requires_mathematik: [Gleichungssystem]

	category: exercises
	fach: Physik
	thema: [Mechanik, Bewegung, Gleichförmige Bewegung]
	art: Berechnung
	needsSupport: 0
	needsTool: 0

	hints: 3
	detail: 0
	bloom: 2
	schritte: 4
	schwierigkeit: 3
	realitaet: 2
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230430
	source: 'Thomas Bisig (thomas@akademix.ch)'
	learning-objective: ''
	content-type: markdown
	media:
	licence: 'CC BY-SA 4.0'

	status_tags: review_1
	status_exercise: review_1
	status_solution: review_1

	todo: []

mathjax:
  process: true
---
Normalerweise fährt eine Motorradfahrerin auf ihrem geraden Nachhauseweg eine mittlere Geschwindigkeit von $106\,\frac{km}{h}$. An diesem verkehrsfreien Donnerstagabend kann sie aber mit $118\,\frac{km}{h}$ fahren und kommt $10\,min$ früher zu hause an als normalerweise.

1. Wie lange dauert die Fahrt normalerweise (in $min$)?
2. Wie lange ist der Nachhauseweg (in $km$)?

[details="Tipp zum Vorgehen" class="tipp"]
- Stelle für beide Fahrten eine korrekt Gleichung für die unbekannte Strecke auf. Bezeichne alle Grössen mit Variablen.
- Nutze die Informationen aus dem Text um Variablen zu eliminieren.
- Löse das Gleichungssystem.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. $\Delta t\approx 98\,min$
2. $\Delta x\approx 174\,km$

**Lösungsidee**: Die zwei Fahrten entsprechen zwei Gleichungen mit zwei Unbekannten, welche gemeinsam gelöst werden können.

**Lösungsweg**:

Der Index $n$ bezeichnet die Grössen für **n**ormale Fahrten, der Index $f$ bezeichnet die Grössen für die verkehrs**f**reie Fahrt.

1. Die zwei Gleichungen können mit Hilfe der [Definition der mittleren Geschwindigkeit](/konzepte/konzept-1) wie folgt aufgestellt werden:

$$
\Delta x_n=v_n\cdot \Delta t_n\\
\Delta x_f=v_f\cdot \Delta t_f\\
$$

2. Die mittleren Geschwindigkeiten können für beide Fahrten direkt eingesetzt werden:

$$
\Delta x_n=106\,\frac{km}{h}\cdot \Delta t_n\\
\Delta x_f=118\,\frac{km}{h}\cdot \Delta t_f\\
$$

3. Die gefahrene Strecke ist dieselbe, dh dass $\Delta x_n=\Delta x_f$ bzw. die [zwei Gleichungen können gleichgesetzt](/konzepte/konzept-1) werden:

$$
106\,\frac{km}{h}\cdot \Delta t_n=118\,\frac{km}{h}\cdot \Delta t_f
$$

4. Mit der Zusatzinformation, dass die Fahrt im Regen [$10\,min=\frac{1}{6}\,h$](/konzepte/konzept-1) weniger lang dauert

$$
\Delta t_f=\Delta t_n-\frac{1}{6}\,h
$$

erhalten wir eine Gleichung mit der einzigen Unbekannten $t_n$:

$$
106\,\frac{km}{h}\cdot \Delta t_n=118\,\frac{km}{h}\cdot (\Delta t_n-\frac{1}{6}\,h)
$$

_Teil 1_

Lösen der Gleichung nach $\Delta t_n$ (die Einheiten werden der Übersicht halber weggelassen):

$$
\begin{align}
106 \cdot \Delta t_n &= 118 \cdot (\Delta t_n-\frac{1}{6})\\

106 \cdot \Delta t_n &= 118 \cdot \Delta t_n - 118\cdot\frac{1}{6} \\

106 \cdot \Delta t_n - 118 \cdot \Delta t_n &= -118\cdot\frac{1}{6} \\

\Delta t_n \cdot (106-118)&= -\frac{118}{6} \\

-12 \cdot \Delta t_n &= -\frac{118}{6}\\

12 \cdot \Delta t_n &= \frac{118}{6}\\

\Delta t_n&=\frac{118}{6 \cdot 12} \\

\Delta t_n & \approx 1.64\,h \approx \underline{98\,min}
\end{align}
$$

_Teil 2_

Einsetzen in die erste Gleichung des ursprünglichen Gleichungssystems

$$
\Delta x_n=106\,\frac{km}{h}\cdot \Delta t_n
$$

liefert

$$
\Delta x_n=106\,\frac{km}{h}\cdot \frac{118}{6\cdot 12}\,h \approx \underline{174\,km}
$$

[/details]