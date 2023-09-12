---
title: 'Impulskomponenten beim Kugelstossen'
taxonomy:
	id: 2023081213085523
	set:

	requires_physik: ['Impuls']
	requires_mathematik: ['Vektorielle Grösse','Trigonometrie']

	category: ['exercises']
	fach: Physik
	thema: ['Impuls']
	art: ['Berechnung']
	needsSupport: 0
	needsTool: 0

	hints: 1
	bloom: 
	schritte: 4
	schwierigkeit: 2
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230813
	source: 'University Physics (8.2), Thomas Bisig, thomas@akademix.ch'
	learning-objective: ''
	content-type: 'markdown'
	media: 'http://www.sportunterricht.de/lksport/kugelani-brian-n001.gif'
	licence: 'CC BY-SA 4.0'

	status_tags: 2
	status_exercise: 2
	status_solution: 2

	todo: ['Bild gif rein']

routes:
  aliases:
    - '/aufgaben/2023081213085523'

mathjax:
  process: true
---
Bei einer Leichtathletik-Veranstaltung wird die Kugelstosskugel mit einer Masse von $7.50\,kg$ mit einer Geschwindigkeit von $15.3\,\frac{m}{s}$ bei $41°$ über der Horizontalen gestossen. Wie gross sind die anfänglichen horizontalen und vertikalen Komponenten des Impulses?

[details="Tipp zum Vorgehen" class="tipp"]
Nutze dein Wissen der Trigonometrie um die anfänglichen Geschwindigkeiten zu berechnen.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $p_x\approx 86.60\,Ns, p_y\approx 75.28\,Ns$

**Lösungsidee**:
Die Trigonometrie liefert die Anfangsgeschwindigkeit in horizontaler und vertikaler Richtung. Diese Geschwindigkeit multipliziert mit der Masse ergeben die gesuchten Impulskomponenten.

**Lösungsweg**:
![Impulskomponenten eines Balls](impulskomponenten_eines_balls.svg?resize=400,400&class=float-right) 

1. Der [Gesamtimpuls](/konzepte/impuls) $\vec{p}$ setzt sich (wie in der Skizze dargestellt) aus dem horizontalen und vertikalen Impuls zusammen, wobei der Abschusswinkel $\alpha = 41°$ beträgt.

2. Der Betrag des Gesamtimpulses $p=|\vec{p}|$ ist das Produkt aus der Masse $m=7.5\,kg$ und der Anfangsgeschwindigkeit $v=15.3\,\frac{m}{s}$:

$$
p=m\cdot v=7.5\,kg \cdot 15.3\,\frac{m}{s}=114.75\,Ns
$$

3. Der Impuls ist eine [vektorielle Grösse](/konzepte/vektorielle-groesse). Die Skizze mit den Komponenten liefert für den Impuls in horizontaler Richtung $p_x$ mit Hilfe des [Kosinus](/konzepte/trigonometrie):

$$
cos(\alpha)=\frac{p_x}{p}\rightarrow p_x=p\cdot cos(\alpha)=114.75\,Ns \cdot cos(41°)\approx \underline{86.60\,Ns}
$$

4. Die vertikale Komponente des Impulses $p_y$ kann direkt mit Hilfe des [Sinus](/konzepte/trigonometrie) berechnet werden:

$$
sin(\alpha)=\frac{p_y}{p}\rightarrow p_y=p\cdot sin(\alpha)=114.75\,Ns \cdot sin(41°)\approx \underline{75.28\,Ns}
$$


[/details]