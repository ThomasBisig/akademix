---
title: Motorradfahrt auf der Autobahn
taxonomy:
	id: 2023041515488878
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
Normalerweise fährt eine Motorradfahrerin auf ihrem geraden Nachhauseweg eine mittlere Geschwindigkeit von $115\,\frac{km}{h}$. An diesem regnerischen Dienstagabend kann sie nur mit $98\,\frac{km}{h}$ fahren und kommt $20\,min$ später zu hause an als normalerweise.

1. Wie lange dauert die Fahrt normalerweise (in $min$)?
2. Wie lange ist der Nachhauseweg (in $km$)?

[details="Tipp zum Vorgehen" class="tipp"]
- Stelle für beide Fahrten eine korrekt Gleichung für die unbekannte Strecke auf. Bezeichne alle Grössen mit Variablen.
- Nutze die Informationen aus dem Text um Variablen zu eliminieren.
- Löse das Gleichungssystem.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. $\Delta t\approx 115\,min$
2. $\Delta x\approx 221\,km$

**Lösungsidee**: Die zwei Fahrten entsprechen zwei Gleichungen mit zwei Unbekannten, welche gemeinsam gelöst werden können.

**Lösungsweg**:

Der Index $n$ bezeichnet die Grössen für **n**ormale Fahrten, der Index $r$ bezeichnet die Grössen für die **r**egnerische Fahrt.

1. Die zwei Gleichungen können mit Hilfe der [Definition der mittleren Geschwindigkeit](/konzepte/konzept-1) wie folgt aufgestellt werden:

$$
\Delta x_n=v_n\cdot \Delta t_n\\
\Delta x_r=v_r\cdot \Delta t_r\\
$$

2. Die mittleren Geschwindigkeiten können für beide Fahrten direkt eingesetzt werden:

$$
\Delta x_n=115\,\frac{km}{h}\cdot \Delta t_n\\
\Delta x_r=98\,\frac{km}{h}\cdot \Delta t_r\\
$$

3. Die gefahrene Strecke ist dieselbe, dh dass $\Delta x_n=\Delta x_r$ bzw. die [zwei Gleichungen können gleichgesetzt](/konzepte/konzept-1) werden:

$$
115\,\frac{km}{h}\cdot \Delta t_n=98\,\frac{km}{h}\cdot \Delta t_r
$$

4. Mit der Zusatzinformation, dass die Fahrt im Regen [$20\,min=\frac{1}{3}\,h$](/konzepte/konzept-1) länger dauert

$$
\Delta t_r=\Delta t_n+\frac{1}{3}\,h
$$

erhalten wir eine Gleichung mit der einzigen Unbekannten $\Delta t_n$:

$$
115\,\frac{km}{h}\cdot \Delta t_n=98\,\frac{km}{h}\cdot (\Delta t_n+\frac{1}{3}\,h)
$$

_Teil 1_

Lösen der Gleichung nach $\Delta t_n$ (die Einheiten werden der Übersicht halber weggelassen):

$$
\begin{align}

115 \cdot \Delta t_n &= 98 \cdot (\Delta t_n+\frac{1}{3})\\

115 \cdot \Delta t_n &= 98 \cdot \Delta t_n + 98\cdot\frac{1}{3} \\

115 \cdot \Delta t_n - 98 \cdot \Delta t_n &= 98\cdot\frac{1}{3} \\

\Delta t_n \cdot (115-98)&= \frac{98}{3} \\

17 \cdot \Delta t_n &= \frac{98}{3}\\

\Delta t_n&=\frac{98}{3 \cdot 17} \\

\Delta t_n & \approx1.92\,h \approx \underline{115\,min}
\end{align}
$$

_Teil 2_

Einsetzen in die erste Gleichung des ursprünglichen Gleichungssystems

$$
\Delta x_n=115\,\frac{km}{h}\cdot \Delta t_n
$$

liefert

$$
\Delta x_n=115\,\frac{km}{h}\cdot \frac{98}{3\cdot 17}\,h \approx \underline{221\,km}
$$

[/details]