---
title: 'Impuls im freien Fall'
taxonomy:
	id: 2023081116494567
	set:

	requires_physik: ['Impuls','Mittlere Beschleunigung','SI-Einheit']
	requires_mathematik: ['Umformung']

	category: ['exercises']
	fach: Physik
	thema: ['Impuls']
	art: ['Berechnung']
	needsSupport: 0
	needsTool: 0

	hints: 1
	bloom: 
	schritte: 6
	schwierigkeit: 2
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230813
	source: 'Thomas Bisig, thomas@akademix.ch'
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
    - '/aufgaben/2023081116494567'

mathjax:
  process: true
---

Ein $146 g$ schwerer Ball werde fallengelassen.

Bestimme den Impuls
1. zum Zeitpunkt des Loslassens
2. nach $2$ Sekunden.

[details="Tipp zum Teil 2" class="tipp"]
Mit Hilfe der mittleren Beschleunigung findest du die Geschwindigkeit des Balls nach $2$ Sekunden.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. $0\,Ns$
2. $\approx 2.86\,Ns$

**Lösungsidee**:
Anwenden der Definition des Impulses. Die Geschwindigkeit im Teil 2 kann mit Hilfe der mittleren Beschleunigung gefunden werden.

**Lösungsweg**:
Der [Impuls](/konzepte/impuls) $p$ ist gegeben durch das Produkt der Masse in [SI-Einheit](/konzepte/si-einheit) $m=0.146\,kg$ und der noch unbekannten Geschwindigkeit $v$

$$
p=m\cdot v
$$

_Teil 1_

1. Die Geschwindigkeit beim Loslassen ist $v=0\,\frac{m}{s}$. Damit ergibt sich ein Impuls von
$$
p=m\cdot v=m \cdot 0=\underline{0\,Ns} 
$$

_Teil 2_

1. Um den Impuls nach $2\,s$ berechnen zu können, müssen wir zuerst die Geschwindigkeit $v_\textrm{2s}$ nach $2\,s$ berechnen. Die Masse ist bereits bekannt.

2. Zur Bestimmung der Geschwindigkeit nach $2$ Sekunden benutzen wir den Zusammenhang der [mittleren Beschleunigung](/konzepte/mittlere-beschleunigung):
$$
\overline{a}=\frac{\Delta v}{\Delta t}
$$
Wobei die mittlere Beschleunigung $\overline{a}$ für den freien Falls zur Erdbeschleunigung $g$ wird $\overline{a}=g=9.81\,\frac{m}{s^2}$

4. Wir suchen die Endgeschwindigkeit $v_\textrm{2s}$, wobei die Anfangsgeschwindigkeit $v_\textrm{0s}=0$ ist (siehe Teil 1). Die Geschwindigkeitsänderung $\Delta v=v_\textrm{2s}-v_\textrm{0s}$ ist somit 
$$
\Delta v=v_{2s}-0=v_{2s}
$$
und wir finden einen Zusammenhang für die gesuchte Grösse $v_{2s}$ in dem alle Grössen in die Formel der mittleren Beschleunigung im zweiten Schritt eingesetzt werden:

$$
\overline{a}=\frac{\Delta v}{\Delta t}\rightarrow 9.81\,\frac{m}{s^2}=\frac{v_{2s}}{2\,s}
$$

4. [Auflösen](/konzepte/umformung) nach $v_{2s}$ und berechnen ergibt

$$
v_{2s}=9.81\,\frac{m}{s^2}\cdot 2\,s=19.62\,\frac{m}{s}
$$

5. Der Impuls nach $2\,s$ ist dann

$$
p=m\cdot v_{2s}=0.146\,kg \cdot 19.62\,\frac{m}{s}\approx \underline{2.86\,Ns}
$$

[/details]