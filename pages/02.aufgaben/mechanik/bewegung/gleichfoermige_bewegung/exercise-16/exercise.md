---
title: Eine Autofahrt mit Hilfe des s-t-Diagramms analysieren
taxonomy:
	id: 2023040615120093
	set: 0202304071720334

	requires_physik: [Gleichförmige Bewegung,Geschwindigkeits-Zeit-Diagramm, Orts-Zeit-Diagramm,Mittlere Geschwindigkeit]
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
	realitaet: 
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230407
	source: 'neu, nach Skript Mechanik 2022, Thomas Bisig, tbisig@pm.me'
	learning-objective: ''
	content-type: markdown
	media: yes
	licence: 'CC BY-SA 3.0'

	status_tags: [content_created, review_0]
	status_exercise: [content_finished, illustration_finished, files_na, review_1]
	status_solution: [content_finished, illustration_finished, links_missing, files_na, review_1]

mathjax:
  process: true
---
![Das v-t-Diagramm einer Autofahrt](exercise16-1.svg?resize=400,400&class=float-right)
Ein Auto sei zum Zeitpunkt $t=0\,s$ am Ort $s=10\,m$ und fahre los.

Das Geschwindigkeits-Zeit-Diagramm ist nebenstehend abgebildet. Zeichne das zur Fahrt gehörende Orts-Zeit-Diagramm in ein neues Koordinatensystem vom Zeitpunkt $t=0\,s$ bis zum Zeitpunkt $t=11\,s$.

Beantworte mit Hilfe des Diagramms folgende Fragen:
1. An welchem Ort befindet sich das Auto nach $11\,s$?
2. Wie gross ist die mittlere Geschwindigkeit der Fahrt im Zeitraum von $s(0)$ bis $s(11)$?
3. Angenommen, das Auto hätte einen Distanzmesser ("Meterzähler") eingebaut – um wie viel würde sich die Streckenanzeige ändern?


[details="Tipp zum Diagramm zeichnen" class="tipp"]
- Unterteile das Geschwindigkeits-Zeit-Diagramm in drei Abschnitte.
- Lies für jeden Abschnitt die gefahrene Geschwindigkeit $v$ und die verstrichene Zeit $\Delta t$ aus dem Diagramm.
- Nutze den Zusammenhang zwischen $\Delta s$, $\Delta t$ und $v$ der gleichförmigen Bewegung.
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
1. $s(11)=5\,m$
2. $\overline{v}=-0.\overline{45}\,m/s$
3. $17\,m$

**Lösungsidee**: Mit Hilfe des gezeichneten Orts-Zeit-Diagramm können können alle drei Fragen beantwortet werden.

**Lösungsweg**:
![Das s-t und das v-t-Diagramm einer Autofahrt](exercise16-2.svg?resize=400,600&class=float-right) Um das [Orts-Zeit-Diagramm](../) zu zeichnen, kann das [Geschwindigkeits-Zeit-Diagramm](../) in drei Abschnitte unterteilt werden.
Im Koordinatensystem des Ort-Zeit-Diagramms beginnt das Auto am Ort $(0,10)$.
Im ersten Abschnitt fährt das Auto für $\Delta t=3\,s$ mit einer Geschwindigkeit von $v=2\,m/s$. Mit Hilfe der Formel für die [gleichförmige Bewegung](../) kann daraus die zurückgelegte Strecke $\Delta s$ für diesen Abschnitt berechnet werden:

$\Delta s=v\cdot \Delta t=2\,\frac{m}{s} \cdot 3\,s=6\,m$

Da die Autofahrt bei $s(0)=10\,m$ beginnt, endet sie nach $3\,s$ bei $s(3)=10\,m+6\,m=16\,m$. Das entspricht dem Punkt mit den Koordinaten $(3,16)$. Für den zweiten und dritten Teil ist zu beachten, dass die Geschwindigkeit negativ ist und demnach die Strecke abgezählt werden muss und demnach $\Delta s$ negativ wird ("Das Auto fährt rückwärts."). Die jeweiligen Koordinaten sind $(8,11)$ und $(11,5)$.

_Teil 1_

Der Ort, wo sich das Auto nach $11\,s$ befindet, entspricht dem Ort $s(11)$ im Diagramm. Das Auto befindet sich demnach am Ort $s(11)=\underline{5\,m}$.

_Teil 2_

Nach $11\,s$ hat sich das Auto vom ursprünglichen Ort $s(0)=10\,m$ zum Ort $s(11)=5\,m$ bewegt. Das sind $\Delta s=s(11)-s(0)=-5\,m$ in $\Delta t=11\,s$. Die mittlere Geschwindigkeit beträgt demnach

$\overline{v}=\frac{\Delta s}{\Delta t}=\frac{-5\,m}{11\,s}=\underline{-0.\overline{45}\,m/s}$

_Teil 3_

Für alle drei Teilabschnitte kann die zurückgelegte Distanz aus dem Diagramm gelesen werden:

$s=6\,m+5\,m+6\,m=\underline{17 m}$



[/details]