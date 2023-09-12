---
title: Autofahrt mit unterschiedlicher Geschwindigkeit
taxonomy:
	id: 2023041516536565
	set: 0202304151653454

	requires_physik: [Mittlere Geschwindigkeit, SI-Einheit]
	requires_mathematik: []

	category: exercises
	fach: Physik
	thema: [Mechanik, Bewegung, Gleichförmige Bewegung]
	art: Berechnung
	needsSupport: 0
	needsTool: 0

	hints: 2
	bloom: 1
	schritte: 3
	schwierigkeit: 2
	realitaet: 
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230415
	source: 'Mechanik Skript 2022, Thomas Bisig (thomas@akademix.ch)'
	learning-objective: ''
	content-type: markdown
	media:
	licence: 'CC BY-SA 4.0'

	status_tags: 2
	status_exercise: 2
	status_solution: 2

	todo: []

mathjax:
  process: true
---
Berechne die mittlere Geschwindigkeit (in $\frac{m}{s}$) eines Wagens, der eine Strecke von $80\,km$ zurücklegt und dabei auf den ersten $30\,km$ mit $50\,\frac{km}{h}$ fährt und für die verbleibende Teilstrecke noch $30\,min$ benötigt.  

[details="Tipp zum Vorgehen" class="tipp"]
- Berechne die benötigte Gesamtzeit.
- Benutze die Definition der mittleren Geschwindigkeit.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $\overline{v} \approx 20.2\,\frac{m}{s}$

**Lösungsidee**: Benützung der mittleren Geschwindigkeit mit Hilfe der Gesamtzeit und Gesamtstrecke.

**Lösungsweg**:

1. Die [mittlere Geschwindigkeit](/konzepte/konzept-1) ist definiert als

$$
\overline{v}=\frac{\Delta x}{\Delta t}
$$

2. Die Gesamtstrecke $\Delta x$ ist bekannt, die Gesamtzeit $\Delta t$ jedoch nicht. Sie berechnet sich aus der Zeit für den ersten Teil $\Delta t_1$ und der Zeit für den zweiten Teil $\Delta t_2=0.5 h$.

3. Die Zeit $\Delta t_1$ findet man mit Hilfe der Umformung der mittleren Geschwindigkeit und den Angaben zu Strecke und Zeit im ersten Teil:

$$
\Delta t_1 = \frac{\Delta x_1}{\overline{v}}=\frac{30\,km}{50\,\frac{km}{h}}=0.6\,h
$$

Somit ergibt sich für die Gesamtzeit $\Delta t=\Delta t_1+\Delta t_2=0.6\,h+0.5\,h=1.1\,h$

4. [Umwandeln der Gesamtstrecke und der Gesamtzeit in die gesuchten Einheiten](/konzepte/konzept-1)

$$
\Delta x=80\,km=80000\,m \\
\Delta t=1.1\,h=3960\,s
$$

und einsetzen in die Definition der mittleren Geschwindigkeit:

$$
\overline{v}=\frac{80000\,m}{3960\,s} \approx \underline{20.2\,\frac{m}{s}}
$$

[/details]