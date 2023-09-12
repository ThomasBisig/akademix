---
title: 'Geschwindigkeit eines Autos'
taxonomy:
	id: 2023081116426382
	set:

	requires_physik: ['Impuls']
	requires_mathematik: ['Umformung','Vektorielle Grösse']

	category: ['exercises']
	fach: Physik
	thema: ['Impuls']
	art: ['Berechnung']
	needsSupport: 0
	needsTool: 0

	hints: 1
	bloom: 
	schritte: 3
	schwierigkeit: 1
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230813
	source: 'physica.ch (556), Thomas Bisig, thomas@akademix.ch'
	learning-objective: ''
	content-type: 'markdown'
	media:
	licence: 'CC BY-SA 4.0'

	status_tags: 2
	status_exercise: 2
	status_solution: 2

	todo: []

routes:
  aliases:
    - '/aufgaben/2023081116426382'

mathjax:
  process: true
---

Ein Auto  der Masse $m=1200\,kg$ besitzt einen Impuls von $p=5.4\cdot10^4 \,Ns$.

Berechne die Geschwindigkeit des Autos.

[details="Tipp zum Vorgehen" class="tipp"]
Nutze die Definition des Impulses.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $162\,\frac{km}{h}$ bzw. $45\,\frac{m}{s}$

**Lösungsidee**: Umformung der Definition des Impulses liefert die Geschwindigkeit.

**Lösungsweg**

1. Da in diesem Beispiel die Bewegungsrichtung keine Rolle spielt, können die [Vektorpfeile](/konzepte/vektorielle-groesse) weggelassen werden ($\vec{p}\rightarrow p$ und $\vec{v}\rightarrow v$).

2. Der [Impuls](/konzepte/impuls) ist gegeben durch das Produkt der Masse und der Geschwindigkeit

$$
p=m\cdot v
$$

3. [Umformung des Zusammenhangs](/konzepte/umformung) und Einsetzen der gegebenen Grössen liefert die Geschwindigkeit in $\frac{m}{s}$:

$$
v=\frac{p}{m}=\frac{5.4\cdot10^4 \,Ns}{1200\,kg}=\underline{45\,\frac{m}{s}}
$$

Das entspricht einer Geschwindigkeit von $162\,\frac{km}{h}$.

[/details]