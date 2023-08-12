---
title: 'Impulskomponenten eines Balls'
taxonomy:
	id: 2023081114590010
	set:

	requires_physik: ['Impuls']
	requires_mathematik: ['Pythagoras', 'Trigonometrie', 'Umformung']

	category: ['Exercise']
	fach: Physik
	thema: ['Impuls']
	art: ['Berechnung']
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
	version: 20230812
	source: 'Thomas Bisig, tbisig@pm.me'
	learning-objective: ''
	content-type: 'markdown'
	media: 'Thomas Bisig, tbisig@pm.me'
	licence: 'CC BY-SA 4.0'

	status_tags: 'review_0'
	status_exercise: 'review_0'
	status_solution: 'review_0'

	todo: []

routes:
  aliases:
    - '/aufgaben/2023081114590010'

mathjax:
  process: true
---

![Impulskomponenten eines Balls](impulskomponenten_eines_balls.svg?resize=400,300&class=float-right) 

Ein Ball habe in $x$-Richtung einen Impuls von $p_x=11.3\,Ns$ und in $y$-Richtung einen Impuls von $p_y=7.6\,Ns$. 

1. Berechne den Gesamtimpuls der Bewegung.
2. Berechne die Richtung der Bewegung als Winkel zur $x$-Achse.
3. Wie würde das Ergebnis lauten, wenn es sich beim Impuls um eine skalare Grösse handeln würde?

[details="Tipp zum Gesamtimpuls" class="tipp"]
Finde das rechtwinklige Dreieck und nutze den Pythagoras.
[/details]

[details="Tipp zur Richtung" class="tipp"]
Nutze das rechtwinklige Dreieck und dein Wissen aus der Trigonometrie um den Winkel zu bestimmen.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. $\approx 13.62\,Ns$
2. $\approx 33.92°$
3. $18.9\,Ns$

**Lösungsidee**:
Da die zwei Impulskomponenten und der Gesamtimpuls ein rechtwinkliges Dreieck bilden, kann der Pythagoras und die Sätze aus der Trigonometrie genutzt werden.

**Lösungsweg**:

_Teil 1_

1. Der [Satz des Pythagoras](/konzepte/pythagoras) lautet für das rechtwinklige Dreieck aus [Impulskomponenten](/konzepte/impuls) $p_x$ und $p_x$ und Gesamtimpuls $p$:

$$
p^2=p_x^2+p_y^2
$$

2. Damit berechnet sich der Gesamtimpuls zu (ohne Einheiten)

$$
p=\sqrt{p_x^2+p_y^2}=\sqrt{11.3^2+7.6^2}\approx\underline{13.62\,Ns} 
$$

_Teil 2_

1. Die Impulskomponenten bilden die Katheten eines rechtwinkligen Dreiecks, in welchem die Hypotenuse gegeben ist durch den Gesamtimpuls.

2. Mit Hilfe des [Tangens bzw. des Cotangens](/konzepte/trigonometrie) können wir den gesuchten Winkel $\alpha$ nach [Umformung](/konzepte/umformung) berechnen:

$$
tan(\alpha)=\frac{p_y}{p_x}\rightarrow \alpha=tan^{-1}(\frac{p_y}{p_x})
$$

3. Einsetzen liefert das Ergebnis
$$
\alpha=tan^{-1}(\frac{7.6\,Ns}{11.3\,Ns})\approx \underline{33.92°}
$$

_Teil 3_

Skalare Grössen (wie zB die Masse) können direkt addiert werden:

$$
p=p_x+p_y=11.3\,Ns+7.6\,Ns=\underline{18.9\,Ns}
$$

Diese Resultat ist für vektorielle Grössen wie den Impuls falsch!
[/details]