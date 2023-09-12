---
title: Lösung einer Wurzelgleichung
taxonomy:
	id: 2023091212586601
	set: 0202309121326112

	requires_mathematik: ['quadratische Gleichung']

	category: ['exercises']
	fach: Mathematik
	thema: ['quadratische Gleichung']
	collection: ['Matur','kleine Matur']
	art: ['Berechnung']
	needsSupport: 0
	needsTool: 0

	hints: 1
	bloom: 
	schritte: 4
	schwierigkeit: 2
	realitaet: 0
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230911
	source: 'Thomas Bisig, thomas@akademix.ch'
	learning-objective: ''
	content-type: 'markdown'
	media: 
	licence: 'CC BY-SA 4.0'

	status_tags: 1
	status_exercise: 1
	status_solution: 1

	todo: []

routes:
  aliases:
    - '/aufgaben/2023091212586601'

mathjax:
  process: true
---
Bestimme alle Werte $x \in \mathbb{R}$, welche die folgende Gleichung erfüllen:
$$
\frac{1}{2}x+\sqrt{5-x^2}=0
$$

Hinweis: Es ist nicht erlaubt, die Lösung mit Hilfe des Taschenrechners numerisch zu bestimmen.

[details="Tipp zum Vorgehen" class="tipp"]
- Führe die gegebene Gleichung in eine quadratische Gleichung über.
- Löse die quadratische Gleichung.
- Überprüfe alle Lösungen.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $-2$

**Lösungsidee**: Quadrieren der Gleichung, Lösen der quadratischen Gleichung und überprüfen der gefundenen Lösungen.

**Lösungsweg**:

##### Teil 1
1. Die Gleichung wird zuerst in Wurzelterm und Nicht-Wurzelterm separiert:
$$
\sqrt{5-x^2}=-\frac{1}{2}x
$$

2. Quadrieren der Gleichung liefert
$$
5-x^2=\frac{1}{4}x^2
$$

3. Umformen (Vereinfachen) und Wurzel ziehen:
$$
\begin{align}
\rightarrow &\frac{5}{4}x^2-5=0 \\
\rightarrow &\frac{5}{4}x^2=5 \\
\rightarrow &x^2=4 \\
\rightarrow &x=\pm 2
\end{align}
$$

4. Überprüfen der zwei gefundenen Lösungen durch Einsetzen in die ursprüngliche Gleichung:
$$
\begin{align}
x=2: &\frac{1}{2}(2)+\sqrt{5-2^2}=0 &&\rightarrow 2=0 &&&\rightarrow x=2 \textrm{ ist keine Lösung
} \\
x=-2: &\frac{1}{2}(-2)+\sqrt{5-(-2)^2}=0 &&\rightarrow 0=0 &&&\rightarrow x=-2 \textrm{ ist eine Lösung}\\
\end{align}
$$

[/details]