---
title: Impulskomponenten beim Kugelstossen
taxonomy:
	id: 2023081213085523
	set:

	requires_physik: ["impuls"]
	requires_mathematik: ["Vektorielle Grössen"]

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
	version: 20230812
	source: 'University Physics (8.2), Thomas Bisig, tbisig@pm.me'
	learning-objective: ''
	content-type: markdown
	media: http://www.sportunterricht.de/lksport/kugelani-brian-n001.gif
	licence: 'CC BY-SA 4.0'

	status_tags: review_0
	status_exercise: review_0
	status_solution: review_0

	todo: []

mathjax:
  process: true
---
![Animation eines Kugelstosses](kugelani-brian-n001.gif?resize=400,400&class=float-right)
Bei  einer Leichtathletik-Veranstaltung wird die Kugelstosskugel mit einer Masse von $7.50\,kg$ mit einer Geschwindigkeit von $15.3\,\frac{m}{s}$ bei $41°$ über der Horizontalen gestossen. Wie gross sind die anfänglichen horizontalen und vertikalen Komponenten des Impulses?

[details="Tipp zum Vorgehen" class="tipp"]
Nutze dein Wissen der Trigonometrie um die anfänglichen Geschwindigkeiten zu berechnen.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $p_x=\approx 86.60\,Ns, p_y=\approx 75.28\,Ns$

**Lösungsidee**:
Die Trigonometrie liefert die Anfangsgeschwindigkeit in horizontaler und vertikaler Richtung. Diese Geschwindigkeit multipliziert mit der Masse ergeben die gesuchten Impulskomponenten.

**Lösungsweg**:
![Impulskomponenten eines Balls](impulskomponenten_eines_balls.svg?resize=400,400&class=float-right) 

1. Der Gesamtimpuls setzt sich (wie in der Skizze dargestellt) aus dem horizontalen und vertikalen Impuls zusammen, wobei der Abschusswinkel $\alpha = 41°$ beträgt.

2. Die jeweiligen Impulse sind das Produkt aus der Masse $m=7.5\,kg$ und der jeweiligen Geschwindigkeit.

3. Die Geschwindigkeit ist auch eine [vektorielle Grösse](/konzepte/konzept-8). Die Skizze mit den Komponenten ist analog auch für die Geschwindigkeiten korrekt. Die horizontale Geschwindigkeit $v_x$ kann direkt mit Hilfe des Kosinus berechnet werden:

$$
cos(\alpha)=\frac{v_x}{v}\rightarrow v_x=v\cdot cos(\alpha)=15.3\,\frac{m}{s} \cdot cos(41°)\approx 11.55\,\frac{m}{s}
$$

und damit auch gleich der horizontale Impuls $p_x$

$$
p_x=m\cdot v_x=7.5\,kg\cdot 11.55\,\frac{m}{s}\approx \underline{86.60\,Ns}
$$

3. Die vertikale Geschwindigkeit $v_y$ kann direkt mit Hilfe des Sinus berechnet werden:

$$
sin(\alpha)=\frac{v_x}{v}\rightarrow v_x=v\cdot sin(\alpha)=15.3\,\frac{m}{s} \cdot sin(41°)\approx 10.04\,\frac{m}{s}
$$

und damit auch gleich der horizontale Impuls $p_x$

$$
p_y=m\cdot v_y=7.5\,kg\cdot 10.04\,\frac{m}{s}\approx \underline{75.28\,Ns}
$$


[/details]