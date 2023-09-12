---
title: Parallele und Senkrechte Vektoren
taxonomy:
	id: 2023091122015654
	set: 0202309112215668

	requires_mathematik: ['Vektor','Skalarprodukt','Lage von Vektoren','Gleichungssystem','quadratische Lösungsformel','Faktorisieren']

	category: ['exercises']
	fach: Mathematik
	thema: ['Vektoren','Lage von Vektoren']
	collection: ['Matur','kleine Matur']
	art: ['Berechnung']
	needsSupport: 0
	needsTool: 0

	hints: 1
	bloom: 
	schritte: 8
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
    - '/aufgaben/2023091122015654'

mathjax:
  process: true
---

Beantworte folgende Fragen:
1. Für welche(n) Wert(e) $k \in \mathbb{R}$ sind die zwei Vektoren $\begin{pmatrix}3\\k\end{pmatrix}$ und $\begin{pmatrix}-4\\8\end{pmatrix}$ parallel?
2. Für welche(n) Wert(e) $h \in \mathbb{R}$ sind die zwei Vektoren $\begin{pmatrix}h^2\\1-h\\-5.5\end{pmatrix}$ und $\begin{pmatrix}1\\-1\\2\end{pmatrix}$ senkrecht?


[details="Tipp zum Vorgehen" class="tipp"]
- Beide Aufgaben lassen sich in ein Gleichungssystem überführen.
- Die Lösung des Gleichungssystems ist/sind die gesuchte(n) Grösse(n)
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. $-6$
2. $-4$ und $3$

**Lösungsidee**: Die Bedingungen für eine parallele bzw. senkrechte Lage liefert ein Gleichungssystem, dessen Lösung die gesuchten Werte sind.

**Lösungsweg**:

##### Teil 1
1. [Vektoren](/konzepte/vektor/) sind dann [parallel](/konzepte/lage-von-vektoren), wenn der eine Vektor als Vielfaches des anderen geschrieben werden kann (dh die zwei Vektoren zeigen in dieselbe Richtung bzw. in die Gegenrichtung, müssen aber nicht gleich lang sein)

2. In einer Gleichung formuliert, heisst das: existiert ein (oder mehrere) Wert(e) $s$, so dass folgende Gleichung stimmt?
$$
s\cdot \begin{pmatrix}3\\k\end{pmatrix}=\begin{pmatrix}-4\\8\end{pmatrix}
$$

3. Diese Gleichung liefert ein [Gleichungssystem](/konzepte/gleichungssystem). Aus der Gleichung für die $x$-Komponente folgt:
$$
s\cdot 3=-4 \rightarrow s=-\frac{4}{3}
$$

4. Aus der Gleichung für die $y$-Komponente folgt dann:
$$
-\frac{4}{3}\cdot k=8 \rightarrow \underline{k=-6}
$$

Dh dass nur für $k=-6$ die zwei Vektoren parallel sind.

##### Teil 2
1. Vektoren stehen dann [senkrecht](/konzepte/lage-von-vektoren) zueinander, wenn das [Skalarprodukt](/konzepte/skalarprodukt) der zwei Vektoren gleich null ist.

2. Eingesetzt bedeutet dies
$$
\begin{pmatrix}h^2\\1-h\\-5.5\end{pmatrix}\cdot\begin{pmatrix}1\\-1\\2\end{pmatrix}=h^2\cdot 1+(1-h)\cdot (-1)+(-5.5)\cdot 2 = 0
$$

3. Vereinfachung des quadratischen Terms liefert
$$
h^2+h-12=0
$$

4. Durch [Faktorisierung](/konzepte/faktorisieren), mit der [quadratischen Lösungsformel](/konzepte/quadratische-loesungsformel) oder mit Hilfe des Taschenrechners (_polysolve_) können die zwei Lösungen bestimmt werden:
$$
\begin{align}
&h^2+h-12=0 \\
&\rightarrow (h+4)(h-3)=0 \\
&\rightarrow \underline{h=-4, 3}
\end{align}
$$

Dh dass die zwei Vektoren für die zwei Werte $h=-4, 3$ senkrecht zueinander stehen.

[/details]