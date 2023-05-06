---
title: Eine Autofahrt mit Hilfe des t-x-Diagramms analysieren
taxonomy:
	id: 2023040615120093
	set: 0202304071720334

	requires_physik: [Gleichförmige Bewegung,t-v-Diagramm,t-x-Dagramm,Mittlere Geschwindigkeit]
	requires_mathematik: [Diagramm lesen, Diagramm zeichnen]

	category: exercises
	fach: Physik
	thema: [Mechanik, Bewegung, Gleichförmige Bewegung]
	art: [Berechnung, Diagramm]
	needsSupport: 0
	needsTool: 0

	hints: 3
	detail: 1
	bloom: 2
	schritte: 4
	schwierigkeit: 3
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230503
	source: 'Thomas Bisig (thomas@akademix.ch)'
	learning-objective: ''
	content-type: markdown
	media: 'Thomas Bisig (thomas@akademix.ch)'
	licence: 'CC BY-SA 4.0'

	status_tags: review_0
	status_exercise: review_0
	status_solution: review_0

	todo: ['']

mathjax:
  process: true
---
![Das t-v-Diagramm einer Autofahrt](exercise15-1.svg?resize=400,400&class=float-right)
Ein Auto sei zum Zeitpunkt $t=0\,s$ am Ort $x=1\,m$ und fahre los.

Das $t-v$-Diagramm (Zeit-Geschwindigkeit) ist nebenstehend abgebildet. Zeichne das zur Fahrt gehörende $t-x$-Diagramm (Zeit-Ort) in ein neues Koordinatensystem vom Zeitpunkt $t=0\,s$ bis zum Zeitpunkt $t=12\,s$.

Beantworte mit Hilfe des Diagramms folgende Fragen:
1. An welchem Ort befindet sich das Auto nach $12\,s$?
2. Wie gross ist die mittlere Geschwindigkeit der Fahrt im Zeitraum von $t=0$ bis $t=12$?
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
1. $x(12)=16\,m$
2. $\overline{v}=1.25\,\frac{m}{s}$
3. $27\,m$

**Lösungsidee**: Mit Hilfe des gezeichneten $t-x$-Diagramm können können alle drei Fragen beantwortet werden.

**Lösungsweg**:
![Das $t-x$ und das $t-v$-Diagramm einer Autofahrt](exercise15-2.svg?resize=400,600&class=float-right) Um das [Zeit-Ort-Diagramm](/konzepte/konzept-1) zu zeichnen, kann das [Zeit-Geschwindigkeit-Diagramm](/konzepte/konzept-1) in drei Abschnitte unterteilt werden.
Im Koordinatensystem des Zeit-Ort-Diagramms beginnt das Auto am Ort mit den Koordinaten $(0,1)$.
Im ersten Abschnitt fährt das Auto für $\Delta t=5\,s$ mit einer Geschwindigkeit von $v=3\,\frac{m}{s}$. Mit Hilfe der Formel für die [gleichförmige Bewegung](/konzepte/konzept-1) kann daraus die zurückgelegte Strecke $\Delta x$ für diesen Abschnitt berechnet werden:

$$
\Delta x=v\cdot \Delta t=3\,\frac{m}{s} \cdot 5\,s=15\,m
$$

Da die Autofahrt bei $x(0)=1\,m$ beginnt, endet sie nach $5\,s$ bei $x(5)=1\,m+15\,m=16\,m$. Das entspricht dem Punkt mit den Koordinaten (5,16). Für den zweiten Teil ist zu beachten, dass die Geschwindigkeit negativ ist und demnach die Strecke abgezählt werden muss und demnach $\Delta x$ negativ wird ("Das Auto fährt rückwärts."). Die Koordianten der Teile 2 und 3 sind $(8,10)$ und $(12,16)$.

_Teil 1_

Der Ort, wo sich das Auto nach $12\,s$ befindet, entspricht dem Ort $x(12)$ im Diagramm. Das Auto befindet sich demnach am Ort

$$
x(12)=\underline{16\,m}
$$

_Teil 2_

Nach $12\,s$ hat sich das Auto vom ursprünglichen Ort $x(0)=1\,m$ zum Ort $x(12)=16\,m$ bewegt. Das sind $\Delta x=x(12)-x(0)=15\,m$ in $\Delta t=12\,s$. Die mittlere Geschwindigkeit beträgt demnach

$$
\overline{v}=\frac{\Delta x}{\Delta t}=\frac{15\,m}{12\,s}=\underline{1.25\,\frac{m}{s}}
$$

_Teil 3_

Für alle drei Teilabschnitte kann die zurückgelegte Distanz aus dem Diagramm gelesen werden:

$$
15\,m+6\,m+6\,m=\underline{27 m}
$$

[/details]