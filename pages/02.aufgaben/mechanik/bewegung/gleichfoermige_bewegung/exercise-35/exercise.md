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
	schritte: 3
	schwierigkeit: 3
	realitaet: 
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230415
	source: 'neu erfunden'
	learning-objective: ''
	content-type: markdown
	media:
	licence: 'CC BY-SA 4.0'

	status_tags: review_0
	status_exercise: review_1
	status_solution: review_1

	todo: []

mathjax:
  process: true
---
Normalerweise fährt eine Motorradfahrerin auf ihrem geraden Nachhauseweg eine mittlere Geschwindigkeit von $106\,\frac{km}{h}$. An diesem verkehrsfreien Donnerstagabend kann sie aber mit $118\,\frac{km}{h}$ fahren und kommt $10\,min$ früher zu hause an als normalerweise.

1. Wie lange dauert normalerweise die Fahrt (in $min$)?
2. Wie lange ist der Nachhauseweg (in $km$)?

[details="Tipp zum Vorgehen" class="tipp"]
- Stelle für beide Fahrten eine korrekt Gleichung für die Entfernung auf. Bezeichne alle Grössen mit Variablen.
- Nutze die Informationen aus dem Text um Variablen zu eliminieren.
- Löse das Gleichungssystem.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. $\Delta t\approx 98\,min$
2. $\Delta s\approx 174\,km$

**Lösungsidee**: Die zwei Fahrten entsprechen zwei Gleichungen mit zwei Unbekannten, welche gemeinsam gelöst werden können.

**Lösungsweg**:

Der Index $n$ bezeichnet die Grössen für **n**ormale Fahrten, der Index $v$ bezeichnet die Grössen für die **v**erkehrsfreie Fahrt.

1. Die zwei Gleichungen können mit Hilfe der [Definition der mittleren Geschwindigkeit](../) wie folgt aufgestellt werden:

$$
\Delta s_n=\overline{v_n}\cdot \Delta t_n\\
\Delta s_v=\overline{v_v}\cdot \Delta t_v\\
$$

2. Die mittleren Geschwindigkeiten können für beide Fahrten direkt eingesetzt werden:

$$
\Delta s_n=106\,\frac{km}{h}\cdot \Delta t_n\\
\Delta s_v=118\,\frac{km}{h}\cdot \Delta t_v\\
$$

3. Die gefahrene Strecke ist dieselbe, dh dass $\Delta s_n=\Delta s_r$ bzw. die [zwei Gleichungen können gleichgesetzt](../) werden:

$$
106\,\frac{km}{h}\cdot \Delta t_n=118\,\frac{km}{h}\cdot \Delta t_v
$$

4. Mit der Zusatzinformation, dass die Fahrt im Regen [$10\,min=\frac{1}{6}\,h$](../) weniger lang dauert

$$
\Delta t_v=\Delta t_n-\frac{1}{6}\,h
$$

erhalten wir eine Gleichung mit der einzigen Unbekannten $t_n$:

$$
106\,\frac{km}{h}\cdot \Delta t_n=118\,\frac{km}{h}\cdot (\Delta t_n-\frac{1}{6}\,h)
$$

_Teil 1_

Lösen der Gleichung nach $\Delta t_n$ (die Einheiten werden der Übersicht halber weggelassen):

$$
\rightarrow 106 \cdot \Delta t_n = 118 \cdot (\Delta t_n-\frac{1}{6})\\

\rightarrow 106 \cdot \Delta t_n = 118 \cdot \Delta t_n - 118\cdot\frac{1}{6} \\

\rightarrow 106 \cdot \Delta t_n - 118 \cdot \Delta t_n = -118\cdot\frac{1}{6} \\

\rightarrow \Delta t_n \cdot (106-118)= -\frac{118}{6} \\

-12 \cdot \Delta t_n = -\frac{118}{6}\\

12 \cdot \Delta t_n = \frac{118}{6}\\

\rightarrow \Delta t_n=\frac{118}{6 \cdot 12} \\

\rightarrow \Delta t_n\approx 1.64\,h \approx \underline{98\,min}
$$

_Teil 2_

Einsetzen in die erste Gleichung des ursprünglichen Gleichungssystems

$$
\Delta s_n=106\,\frac{km}{h}\cdot \Delta t_n
$$

liefert

$$
\Delta s_n=106\,\frac{km}{h}\cdot \frac{118}{6\cdot 12}\,h \approx \underline{174\,km}
$$

[/details]