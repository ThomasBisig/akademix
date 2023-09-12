---
title: Vom Dreieck zum Parallelogramm
taxonomy:
	id: 2023091212093117
	set: 0202309121326333

	requires_mathematik: ['Vektor','Vektorlänge','Stützvektor', 'Richtungsvektor',Parametergleichung','Umkehrung des Pythagoras','Parallelogramm']

	category: ['exercises']
	fach: Mathematik
	thema: ['Vektoren','Gesamtaufgabe']
	collection: ['Matur','kleine Matur']
	art: ['Berechnung']
	needsSupport: 0
	needsTool: 0

	hints: 2
	bloom: 
	schritte: 12
	schwierigkeit: 2
	realitaet: 0
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230912
	source: 'Thomas Bisig, thomas@akademix.ch'
	learning-objective: ''
	content-type: 'markdown'
	media: 'Thomas Bisig, thomas@akademix.ch'
	licence: 'CC BY-SA 4.0'

	status_tags: 1
	status_exercise: 1
	status_solution: 1

	todo: []

routes:
  aliases:
    - '/aufgaben/2023091212093117'

mathjax:
  process: true
---

Drei Punkte sind gegeben: $A(2|2|5)$,  $B(3|0|2)$,  $C(9|2|5)$

1. Bestimme eine Parametergleichung der Geraden $g$ durch die Punkte $A$ und $B$ und eine Parametergleichung der Geraden $h$ durch $B$ und $C$
2. Die drei Punkte spannen ein spezielles Dreieck auf. Um was für ein Dreieck handelt es sich?
3. Bestimme die Koordinaten eines vierten Punktes $D$, welcher mit den anderen drei Punkten ein Parallelogramm ABCD aufspannt.


[details="Tipp zum Teil 2" class="tipp"]
- Bestimme mögliche spezielle Dreiecke.
- Berechne alle Seitenlängen des Dreiecks.
- Berechne (evtl) alle Winkel des Dreiecks.
[/details]

[details="Tipp zum Teil 3" class="tipp"]
- Skizziere drei Punkte in zwei Dimensionen.
- Bestimme zeichnerisch den vierten Punkt, welcher die drei Punkte zu einem Parallelogramm ergänzt.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. eine mögliche Lösung g: $\vec{x}&=\begin{pmatrix}2\\2\\5\end{pmatrix}+k\cdot \begin{pmatrix}1\\-2\\-3\end{pmatrix}$ , $h: \vec{x}&=\begin{pmatrix}3\\0\\2\end{pmatrix}+k\begin{pmatrix}6\\2\\3\end{pmatrix}$
2. Das Dreieck $\Delta ABC$ ist ein gleichschenkliges, nicht-rechtwinkliges Dreieck.
3. $D(8|4|8)$, $D(-4|0|2)$, $D(10|0|2)$

**Lösungsidee**: Die Bestimmung aller Verbindungsvektoren und Erstellung einer Skizze liefert die gesuchten Lösungen.

**Lösungsweg**:

##### Teil 1
_(Es gibt beliebig viele Lösungen zu dieser Aufgabe)_
1. Die Beschreibung einer [Geraden als Parametergleichung](/konzepte/parametergleichung) benötigt einen [Stützvektor](/konzepte/stuetzvektor) $\vec{u}$ und einen [Richtungsvektor](/konzepte/richtungsvektor) $\vec{v}$:
$$
\vec{x}=\vec{u}+k\cdot \vec{v}
$$

2. Für die Gerade $g$ wird der Ortsvektor des Punktes $A$ als Stützvektor gewählt
$$
\vec{OA}=\begin{pmatrix}2\\2\\5\end{pmatrix}
$$
und als Richtungsvektor der Vektor von $A$ nach $B$
$$
\begin{align}
\vec{AB}&=\begin{pmatrix}3-2\\0-2\\2-5\end{pmatrix} \\
&=\begin{pmatrix}1\\-2\\-3\end{pmatrix}
\end{align}
$$

3. Damit ergibt sich für die Gerade $g$ die Parametergleichung:
$$
\begin{align}
g: \vec{x}&=\vec{OA}+k\cdot \vec{AB} \\
\rightarrow g: \vec{x}&=\begin{pmatrix}2\\2\\5\end{pmatrix}+k\cdot \begin{pmatrix}1\\-2\\-3\end{pmatrix}
\end{align}
$$

4. Für die Gerade $h$ wird der Ortsvektor des Punktes $B$ als Stützvektor gewählt
$$
\vec{OB}=\begin{pmatrix}3\\0\\2\end{pmatrix}
$$
und als Richtungsvektor der Vektor von $B$ nach $C$
$$
\begin{align}
\vec{BC}&=\begin{pmatrix}9-3\\2-0\\5-2\end{pmatrix} \\
&=\begin{pmatrix}6\\2\\3\end{pmatrix}
\end{align}
$$

5. Damit ergibt sich für die Gerade $h$ die Parametergleichung:
$$
\begin{align}
h: \vec{x}&=\vec{OB}+k\cdot \vec{BC} \\
\rightarrow h: \vec{x}&=\begin{pmatrix}3\\0\\2\end{pmatrix}+k\begin{pmatrix}6\\2\\3\end{pmatrix}
\end{align}
$$


##### Teil 2
1. Die Berechnung aller [Seitenlängen](/konzepte/vektorlaenge) des Dreiecks gibt einen ersten Hinweis auf die Antwort:
$$
\begin{align}
|\vec{AB}|&=\Bigg | \begin{pmatrix}1\\-2\\-3\end{pmatrix}\Bigg |=\sqrt{1^2+(-2)^2+(-3)^2}=\sqrt{14} \\
|\vec{BC}|&=\Bigg | \begin{pmatrix}6\\2\\3\end{pmatrix}\Bigg |=\sqrt{6^2+2^2+3^2}=7 \\
|\vec{AC}|&=\Bigg | \begin{pmatrix}7\\0\\0\end{pmatrix}\Bigg |=\sqrt{7^2+0^2+0^2}=7
\end{align}
$$
Das Dreieck $\Delta ABC$ ist gleichschenklig.

2. Abgesehen von den Seitenlängen, könnte es sich auch um ein rechtwinkliges Dreieck handeln. Um dies zu bestätigen oder zu widerlegen, könnten alle Winkel mit Hilfe des [Skalarproduktes](/konzepte/skalarprodukt) bestimmt werden.

3. Eine direktere Variante ist die Nutzung der [Umkehrung des Pythagoras](/konzepte/umkehrung-des-pythagoras): falls drei Dreiecksseiten $a,b,c$ die Gleichung $a^2+b^2=c^2$ erfüllen, ist das Dreieck rechtwinklig; falls sie die Gleichung nicht erfüllen, ist das Dreieck nicht rechtwinklig:
$$
\overline{BC}^2+\overline{AC}^2=98 \ne 14=\overline{AB}^2
$$

3. Somit handelt es sich beim Dreieck $\Delta ABC$ um ein gleichschenkliges, nicht-rechtwinkliges Dreieck.

##### Teil 3
1. Eine Skizze (in zwei Dimensionen) kann den Hinweis geben, wie der Punkt $D$ gefunden werden kann: in einem Parallelogramm sind gegenüberliegende Seiten parallel, so zB:
$$
\vec{BC} || \vec{AD}
$$

2. Somit ist eine mögliche Lösung für den Punkt $D$:
$$
\begin{align}
\vec{OD}&=\vec{OA}+\vec{BC}
\rightarrow \vec{OD}&=\begin{pmatrix}2\\2\\5\end{pmatrix}+\begin{pmatrix}6\\2\\3\end{pmatrix}
\rightarrow \vec{OD}&=\begin{pmatrix}8\\4\\8\end{pmatrix}
\end{align}
$$

3. Der Punkt $D$ hat demnach die Koordinaten $\underline{D(8|4|8)}$.

Alternative Lösungen: $D(-4|0|2)$, $D(10|0|2)$

[/details]