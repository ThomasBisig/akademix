---
title: Eine Autofahrt mit Hilfe des t-x-Diagramms analysieren
taxonomy:
	id: 2023040615123221
	set: 0202304071720334

	requires_physik: [Gleichförmige Bewegung,t-v-Diagramm,t-x-Diagramm,Mittlere Geschwindigkeit]
	requires_mathematik: [Diagramm lesen, Diagramm zeichnen]

	category: exercises
	fach: Physik
	thema: [Mechanik, Bewegung, Gleichförmige Bewegung]
	art: [Berechnung, Diagramm]
	needsSupport: 0
	needsTool: 0

	hints: 3
	bloom: 2
	schritte: 4
	schwierigkeit: 3
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230508
	source: 'Thomas Bisig (thomas@akademix.ch)'
	learning-objective: ''
	content-type: markdown
	media: 'Thomas Bisig (thomas@akademix.ch)'
	licence: 'CC BY-SA 4.0'

	status_tags: 2
	status_exercise: 2
	status_solution: 2

	todo: ['']

mathjax:
  process: true
---
![Das t-v-Diagramm einer Autofahrt](exercise16-1.svg?resize=400,400&class=float-right)
Ein Auto sei zum Zeitpunkt $t=0\,s$ am Ort $x=10\,m$ und fahre los. Das $t-v$-Diagramm (Zeit-Geschwindigkeit) ist nebenstehend abgebildet.

Zeichne das zur Fahrt gehörende $t-x$-Diagramm (Zeit-Ort) in ein neues Koordinatensystem vom Zeitpunkt $t=0\,s$ bis zum Zeitpunkt $t=11\,s$.

Beantworte mit Hilfe des Diagramms folgende Fragen:
1. An welchem Ort befindet sich das Auto nach $11\,s$?
2. Wie gross ist die mittlere Geschwindigkeit der Fahrt im Zeitraum von $t=0$ bis $t=11$?
3. Angenommen, das Auto hätte einen Distanzmesser ("Meterzähler") eingebaut – um wie viel würde sich die Streckenanzeige ändern?


[details="Tipp zum Diagramm zeichnen" class="tipp"]
- Unterteile das $t-v$-Diagramm in drei Abschnitte.
- Lies für jeden Abschnitt die gefahrene Geschwindigkeit $v$ und die verstrichene Zeit $\Delta t$ aus dem Diagramm.
- Nutze den Zusammenhang zwischen $\Delta x$, $\Delta t$ und $v$ der gleichförmigen Bewegung.
[/details]

[details="Tipp zur mittleren Geschwindigkeit" class="tipp"]
- Lies aus dem Diagramm die zurückgelegte Strecke und die dafür benötigte Zeit ab.
- Benutze dann die Definition der mittleren Geschwindigkeit.
[/details]

[details="Tipp zum Distanzmesser" class="tipp"]
Lies für jeden der drei Abschnitte mit unterschiedlicher Geschwindigkeit heraus, wie viele Meter jeweils zurückgelegt wurden.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:

Diagramm: siehe Abbildung
1. $x(11)=5\,m$
2. $\overline{v}=-0.\overline{45}\,\frac{m}{s}$
3. $17\,m$

**Lösungsidee**: Mit Hilfe des gezeichneten $t-x$-Diagramm können können alle drei Fragen beantwortet werden.

**Lösungsweg**:
![Das $t-x$ und das $t-v$-Diagramm einer Autofahrt](exercise16-2.svg?resize=400,600&class=float-right) Um das [Zeit-Ort-Diagramm](/konzepte/konzept-1) zu zeichnen, kann das [Zeit-Geschwindigkeit-Diagramm](/konzepte/konzept-1) in drei Abschnitte unterteilt werden.
Im Koordinatensystem des Zeit-Ort-Diagramms beginnt das Auto am Ort mit den Koordinaten $(0,10)$.
Im ersten Abschnitt fährt das Auto für $\Delta t=3\,s$ mit einer Geschwindigkeit von $v=2\,\frac{m}{s}$. Mit Hilfe der Formel für die [gleichförmige Bewegung](/konzepte/konzept-1) kann daraus die zurückgelegte Strecke $\Delta x$ für diesen Abschnitt berechnet werden:

$$
\Delta x=v\cdot \Delta t=2\,\frac{m}{s} \cdot 3\,s=6\,m
$$

Da die Autofahrt bei $x(0)=10\,m$ beginnt, endet sie nach $3\,s$ bei $x(3)=10\,m+6\,m=16\,m$. Das entspricht dem Punkt mit den Koordinaten $(3,16)$. Für den zweiten und dritten Teil ist zu beachten, dass die Geschwindigkeit negativ ist und demnach die Strecke abgezählt werden muss und demnach $\Delta x$ negativ wird ("Das Auto fährt rückwärts."). Die jeweiligen Koordinaten sind $(8,11)$ und $(11,5)$.

_Teil 1_

Der Ort, wo sich das Auto nach $11\,s$ befindet, entspricht dem Ort $x(11)$ im Diagramm. Das Auto befindet sich demnach am Ort

$$
x(11)=\underline{5\,m}
$$

_Teil 2_

Nach $11\,s$ hat sich das Auto vom ursprünglichen Ort $x(0)=10\,m$ zum Ort $x(11)=5\,m$ bewegt. Das sind $\Delta x=x(11)-x(0)=-5\,m$ in $\Delta t=11\,s$. Die mittlere Geschwindigkeit beträgt demnach

$$
\overline{v}=\frac{\Delta x}{\Delta t}=\frac{-5\,m}{11\,s}=\underline{-0.\overline{45}\,\frac{m}{s}}
$$

_Teil 3_

Für alle drei Teilabschnitte kann die zurückgelegte Distanz aus dem Diagramm gelesen werden:

$$
6\,m+5\,m+6\,m=\underline{17 m}
$$

[/details]