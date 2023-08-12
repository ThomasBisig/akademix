---
title: Impulskomponenten eines Balls
taxonomy:
	id: 2023081114590010
	set:

	requires_physik: [impuls]
	requires_mathematik: [pythagoras, trigonometrie]

	category: exercise
	fach: Physik
	thema: [impuls]
	art: ["Berechnung"]
	needsSupport: 0
	needsTool: 0

	hints: 
	detail: 
	bloom: 
	schritte: 
	schwierigkeit: 
	realitaet:
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230811
	source: 'Thomas Bisig, tbisig@pm.me'
	learning-objective: ''
	content-type: markdown
	media:
	licence: 'CC BY-SA 4.0'

	status_tags: review_0
	status_exercise: review_0
	status_solution: review_0

	todo: []

mathjax:
  process: true
---

![Impulskomponenten eines Balls](impulskomponenten_eines_balls.svg?resize=400,400&class=float-right) 

Ein Ball habe in $x$-Richtung einen Impuls von $p_x=11.3\,Ns$ und in $y$-Richtung einen Impuls von $p_y=7.6\,Ns$, wie in der Skizze dargestellt. 

a) Berechne den Gesamtimpuls der Bewegung.
b) Berechne die Richtung der Bewegung als Winkel zur $x$-Achse.
c) Wie würde das Ergebnis lauten, wenn es sich beim Impuls um eine skalare Grösse handeln würde?

[details="Tipp zum Gesamtimpuls" class="tipp"]
Finde das rechtwinklige Dreieck und nutze den Pythagoras.
[/details]

[details="Tipp zur Richtung" class="tipp"]
Nutze das rechtwinklige Dreieck und dein Wissen aus der Trigonometrie um den Winkel zu bestimmen.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
a) $\approx 13.62\,Ns$
b) $\ang{33.92}$
c) $18.9\,Ns$

**Lösungsidee**:
Da die Komponenten und der Gesamtimpuls ein rechtwinkliges Dreieck bilden, kann der Pythagoras und die Sätze aus der Trigonometrie genutzt werden.

**Lösungsweg**:

_Teil a_
1. Der Satz des Pythagoras lautet für das rechtwinklige Dreieck aus Impulskomponenten $p_x$ und $p_x$ und Gesamtimpuls $p$:

$$
p^2=p_x^2+p_y^2
$$

2. Damit berechnet sich der Gesamtimpuls zu (ohne Einheiten)

$$
p=\sqrt{p_x^2+p_y^2}=\sqrt{11.3^2+7.6^2}\approx\underline{13.62\,Ns} 
$$

_Teil b_
1. Die Impulskomponenten bilden die Katheten eines rechtwinkligen Dreiecks, in welchem die Hypotenuse gegeben ist durch den Gesamtimpuls.

2. Mit hilfe des Tangens bzw. des Cotangens können wir den gesuchten Winkel $\alpha$ berechnen:

$$
tan(\alpha)=\frac{p_y}{p_x}\rightarrow \alpha=tan^{-1}(\frac{p_y}{p_x})
$$

3. Einsetzen liefert das Ergebnis
$$
\alpha=tan^{-1}(\frac{7.6\,Ns}{11.3\,Ns})\approx \underline{\ang{33.92}}
$$

_Teil c_

Skalare Grössen (wie zB die Masse) können direkt addiert werden:

$$
p=p_x+p_y=11.3\,Ns+7.6\,Ns=\underline{18.9\,Ns}
$$

Diese Resultat ist für vektorielle Grössen wie den Impuls falsch!
[/details]