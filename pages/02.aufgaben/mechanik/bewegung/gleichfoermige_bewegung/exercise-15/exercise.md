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
	source: 'Skript Mechanik 2022, Thomas Bisig, tbisig@pm.me'
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
![Das v-t-Diagramm einer Autofahrt](exercise15-1.svg?resize=400,400&class=float-right)
Ein Auto sei zum Zeitpunkt $t=0\,s$ am Ort $s=1\,m$ und fahre los.

Das Geschwindigkeits-Zeit-Diagramm ist nebenstehend abgebildet. Zeichne das zur Fahrt gehörende Orts-Zeit-Diagramm in ein neues Koordinatensystem vom Zeitpunkt $t=0\,s$ bis zum Zeitpunkt $t=12\,s$.

Beantworte mit Hilfe des Diagramms folgende Fragen:
1. An welchem Ort befindet sich das Auto nach $12\,s$?
2. Wie gross ist die mittlere Geschwindigkeit der Fahrt im Zeitraum von $s(0)$ bis $s(12)$?
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
1. $s(12)=16\,m$
2. $\overline{v}=1.25\,m/s$
3. $27\,m$

**Lösungsidee**: Mit Hilfe des gezeichneten Orts-Zeit-Diagramm können können alle drei Fragen beantwortet werden.

**Lösungsweg**:
![Das s-t und das v-t-Diagramm einer Autofahrt](exercise15-2.svg?resize=400,600&class=float-right) Um das [Orts-Zeit-Diagramm](../) zu zeichnen, kann das [Geschwindigkeits-Zeit-Diagramm](../) in drei Abschnitte unterteilt werden.
Im Koordinatensystem des Ort-Zeit-Diagramms beginnt das Auto am Ort $(0,1)$.
Im ersten Abschnitt fährt das Auto für $\Delta t=5\,s$ mit einer Geschwindigkeit von $v=3\,m/s$. Mit Hilfe der Formel für die [gleichförmige Bewegung](../) kann daraus die zurückgelegte Strecke $\Delta s$ für diesen Abschnitt berechnet werden:

$\Delta s=v\cdot \Delta t=3\,\frac{m}{s} \cdot 5\,s=15\,m$

Da die Autofahrt bei $s(0)=1\,m$ beginnt, endet sie nach $5\,s$ bei $s(5)=1\,m+15\,m=16\,m$. Das entspricht dem Punkt mit den Koordinaten (5,16). Für den zweiten Teil ist zu beachten, dass die Geschwindigkeit negativ ist und demnach die Strecke abgezählt werden muss und demnach $\Delta s$ negativ wird ("Das Auto fährt rückwärts."). Die Koordianten der Teile 2 und 3 sind $(8,10)$ und $(12,16)$.

_Teil 1_

Der Ort, wo sich das Auto nach $12\,s$ befindet, entspricht dem Ort $s(12)$ im Diagramm. Das Auto befindet sich demnach am Ort $s(12)=\underline{16\,m}$.

_Teil 2_

Nach $12\,s$ hat sich das Auto vom ursprünglichen Ort $s(0)=1\,m$ zum Ort $s(12)=16\,m$ bewegt. Das sind $\Delta s=s(12)-s(0)=15\,m$ in $\Delta t=12\,s$. Die mittlere Geschwindigkeit beträgt demnach

$\overline{v}=\frac{\Delta s}{\Delta t}=\frac{15\,m}{12\,s}=\underline{1.25\,m/s}$

_Teil 3_

Für alle drei Teilabschnitte kann die zurückgelegte Distanz aus dem Diagramm gelesen werden:

$s=15\,m+6\,m+6\,m=\underline{27 m}$



[/details]