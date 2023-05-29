---
title: Delta-Schreibweise
taxonomy:
	requires_physik: []
	requires_mathematik: []

	category: concepts
	fach: Physik
	thema: [Mechanik, Bewegung, Delta-Schreibweise]

	autor: 'Thomas'
	version: 20230529
	source: 'Thomas Bisig (thomas@akademix.ch)'
	content-type: markdown
	media: 'thomas@akademix.ch'
	licence: 'CC BY-SA 4.0'

	status: review_0

	todo: ['Zeichnung korrigieren, (3)']
mathjax:
	process: true
---

# Delta-Schreibweise

> Die Delta-Schreibweise gibt die Änderung einer Grösse $x$ zwischen zwei Zeitpunkten an:
$$
\Delta x=x_\textrm{später}-x_\textrm{früher}
$$
Der griechische Grossbuchstabe **D**elta ($\Delta$) kann als Zeichen für **D**ifferenz verstanden werden.

![Zeit- und Ortsänderung als Beispiel der Delta-Schreibweise](Delta-Schreibweise.svg?resize=500,800&class=float-right)

- Ausgehend von einem (früheren) Zeitpunkt $1$ wird die Änderung bis zu einem (späteren) Zeitpunkt $2$ geschrieben als die Differenz der Grösse zu diesen zwei Zeiten
$$
\Delta x=x_2-x_1
$$
- Die Delta-Schreibweise kann auf alle Grössen angewendet werden, zB
	- den Ort $\Delta x$ (Ortsänderung),
	- die Geschwindigkeit $\Delta v$ (Geschwindigkeitsänderung),
	- die Zeit $\Delta t$ (Zeitänderung),
	- die Masse $\Delta m$ (Massenänderung).


### Beispiele

##### Fahrrad fährt vorwärts (Abbildung 2) 
Ein Fahrrad befindet sich
- zum Zeitpunkt $t_1=0\,s$ am Ort $x_1=10\,m$
- zum Zeitpunkt $t_2=5\,s$ am Ort $x_2=27\,m$

Damit ergibt sich eine
- Ortsänderung $\Delta x=x_2-x_1=27\,m-10\,m=17\,m$
- Zeitänderung $\Delta t=t_2-t_1=10\,s-0\,s=10\,s$

##### Fahrrad fährt rückwärts (Abbildung 3)
Ein Fahrrad befindet sich
- zum Zeitpunkt $t_1=5\,s$ am Ort $x_1=53\,m$
- zum Zeitpunkt $t_2=12\,s$ am Ort $x_2=13\,m$.

Damit ergibt sich eine
- Ortsänderung $\Delta x=x_2-x_1=13\,m-53\,m=-30\,m$
- Zeitänderung $\Delta t=t_2-t_1=12\,s-5\,s=7\,s$

##### Freifallender Körper
Die Änderung der Geschwindigkeit eines im luftleeren Raum fallenden Körpers vergrössert sich pro Sekunde um $9.81\,\frac{m}{s}$, dh innerhalb von einer Sekunde ist $\Delta v=9.81\,\frac{m}{s}$, innerhalb von zwei Sekunden $\Delta v=19.62\,\frac{m}{s}$.


### Wieso ist das hilfreich?
##### Generell
Eine kurze und einheitliche Schreibweise für Änderungen sind in der Physik von zentraler Bedeutung, da die Physik sich hauptsächlich mit sich verändernden Grössen beschäftigt.

##### Angewandt
Die einheitliche Grundlage (der Änderungsrate) der [mittleren Geschwindigkeit][1] und der [mittleren Beschleunigung][2] sind direkt ersichtlich.

##### Weiterführend
Die Mathematik bietet viele für die Physik essentielle Tools, welche auf der Delta-Schreibweise aufbauen. So kann z.B. der Übergang von mittleren Änderungsraten $\frac{\Delta x}{\Delta t}$ zu momentanen Änderungsraten $\frac{dx}{dt}$ dank der Differenzialrechnung vollzogen werden.

### Weiteres
- Die Grösse $\Delta x$ kann auch verstanden werden als die Menge die zu $x_1$ hinzugefügt werden muss, um $x_2$ zu erhalten:
$$
x_2=x_1+\Delta x
$$
- In Beispielen mit Diagrammen spielt die Achsenausrichtung keine Rolle. So kann z.B. die Ortsachse, wie im [$t-x$-Diagramm](/konzept/konzept-3/), auch vertikal verlaufen.
- Jedoch ist die Achsenrichtung von zentraler Bedeutung: so bewegt sich ein Körper mit $\Delta x>0$ (mit der Richtung der Ortsachse) vorwärts und mit $\Delta x<0$ (entgegen der Richtung der Ortsachse) rückwärts. 
- Die Bezeichnungen _Änderung_, _Veränderung_ und _Differenz_ werden gleichbedeutend genutzt. Beispiel: Zeit_änderung_, Zeit_veränderung_, Zeit_differenz_.

[1]: <konzepte/konzept-1/> "Name des Konzepts"
[2]: <konzepte/konzept-2/> "Name des Konzepts"