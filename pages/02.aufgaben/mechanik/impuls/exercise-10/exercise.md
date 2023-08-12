---
title: Impuls im freien Fall
taxonomy:
	id: 2023081116494567
	set:

	requires_physik: ["impuls","gleichmässige beschleunigung","SI-Einheit"]
	requires_mathematik: [Umformung]

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

Ein $146 g$ schwerer Ball werde fallengelassen.

Bestimme den Impuls
a) zum Zeitpunkt des Loslassens
b) nach $2$ Sekunden.

[details="Tipp zum Teil b" class="tipp"]
Mit Hilfe der gleichmässigen Beschleunigung findest du die Geschwindigkeit des Balls nach $2$ Sekunden.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $\approx 2.86\,Ns$

**Lösungsidee**:
Anwenden der Definition des Impulses. Die Geschwindigkeit im Teil b kann mit hilfe der gleichmässigen Beschleunigung gefunden werden.

**Lösungsweg**:
Der Impuls ist gegeben durch das Produkt der Masse in SI-Einheit $m=0.146\,kg$ und der Geschwindigkeit $v$

$$
$p=m\cdot v$ 
$$

_Teil a_
1. Die Geschwindigkeit beim Loslassen ist $v=0\,\frac{m}{s}$. Damit ergibt sich ein Impuls von
$$
$p=m\cdot v=m \cdot 0=0\,Ns$ 
$$

_Teil b_
1. Zur Bestimmung der Geschwindigkeit nach 2 Sekunden benutzen wir den Zusammenhang der [gleichmässigen Beschleunigung](\konzept\konzept-1\):

$$
a=\frac{\Delta v}{\Delta t}
$$

2. Die Beschleunigung ist die Erdbeschleunigung $a=g=9.81\,\frac{m}{s^2}$

3. Die Geschwindigkeitsänderung $\Delta v=v_\textrm{Ende}-v_\textrm{Anfang}$ ist die Differenz zwischen der Geschwindigkeit zu Beginn und der gesuchten Geschwindigkeit am Ende. Da $v_\textrm{Anfang}=0$ wird 

$$
\Delta v=v_\textrm{Ende}=v_\textrm{Ende}
$$

4. Einsetzen aller Grössen in die Formel der gleichmässigen Beschleunigung in (1) liefert:

$$
a=\frac{\Delta v}{\Delta t}\rightarrow 9.81\,\frac{m}{s^2}=\frac{v_\textrm{Ende}}{2\,s}
$$

5. [Auflösen](\konzept\konzept-1\) nach $v_\textrm{Ende}$ und berechnen ergibt

$$
v_\textrm{Ende}=9.81\,\frac{m}{s^2}\cdot 2\,s=19.62\,\frac{m}{s}
$$

6. Der Impuls nach $2\,s$ ist dann

$$
$p=m\cdot v=0.146\,kg \cdot 19.62\,\frac{m}{s}\approx \underline{2.86\,Ns}$ 
$$

[/details]