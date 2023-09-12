---
title: Lösung einer Wurzelgleichung
taxonomy:
	id: 2023091213262345
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
    - '/aufgaben/2023091213262345'

mathjax:
  process: true
---
Bestimme alle Werte $x \in \mathbb{R}$, welche die folgende Gleichung erfüllen:
$$
\sqrt{x^2-5}-\frac{2}{3}x=0
$$

Hinweis: Es ist nicht erlaubt, die Lösung mit Hilfe des Taschenrechners numerisch zu bestimmen.

[details="Tipp zum Vorgehen" class="tipp"]
- Führe die gegebene Gleichung in eine quadratische Gleichung über.
- Löse die quadratische Gleichung.
- Überprüfe alle Lösungen.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $3$

**Lösungsidee**: Quadrieren der Gleichung, Lösen der quadratischen Gleichung und überprüfen der gefundenen Lösungen.

**Lösungsweg**:

##### Teil 1
1. Die Gleichung wird zuerst in Wurzelterm und Nicht-Wurzelterm separiert:
$$
\sqrt{x^2-5}=\frac{2}{3}x
$$

2. Quadrieren der Gleichung liefert
$$
x^2-5=\frac{4}{9}x^2
$$

3. Umformen (Vereinfachen) und Wurzel ziehen:
$$
\begin{align}
\rightarrow &\frac{5}{9}x^2-5=0 \\
\rightarrow &\frac{5}{9}x^2=5 \\
\rightarrow &x^2=9 \\
\rightarrow &x=\pm 3
\end{align}
$$

4. Überprüfen der zwei gefundenen Lösungen durch Einsetzen in die ursprüngliche Gleichung:
$$
\begin{align}
x=3: &\sqrt{(3)^2-5}-\frac{2}{3}(3)=0 &&\rightarrow 0=0 &&&\rightarrow x=3 \textrm{ ist eine Lösung
} \\
x=-3: &\sqrt{(-3)^2-5}-\frac{2}{3}(-3)=0 &&\rightarrow 4=0 &&&\rightarrow x=-3 \textrm{ ist keine Lösung}\\
\end{align}
$$

[/details]