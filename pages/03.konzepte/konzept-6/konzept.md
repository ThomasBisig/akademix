---
title: Delta-Schreibweise
taxonomy:
	requires_physik: []
	requires_mathematik: []

	category: concepts
	fach: Physik
	thema: [Mechanik, Bewegung, Delta-Schreibweise]

	autor: 'Thomas'
	version: 20230603
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

> Die Delta-Schreibweise gibt die Änderung einer Grösse $w$ zwischen zwei Zeitpunkten an:
$$
\Delta w=w_\textrm{später}-w_\textrm{früher}
$$

![Zeit- und Ortsänderung als Beispiel der Delta-Schreibweise](Delta-Schreibweise.svg?resize=500,700&class=float-right)

- Ausgehend von einem früheren Wert $w_{1}$ wird die Änderung bis zu einem späteren Wert $w_{2}$
 geschrieben als die Differenz dieser Werte:
$$
\Delta w=w_{2}-w_{1}
$$
- Der griechische Grossbuchstabe **D**elta ($\Delta$) kann als Zeichen für **D**ifferenz verstanden werden.
- Die Delta-Schreibweise kann auf alle Grössen angewendet werden, z.B.
	- den Ort $\Delta x \rightarrow$ Ortsänderung
	- die Geschwindigkeit $\Delta v\rightarrow$ Geschwindigkeitsänderung
	- die Zeit $\Delta t\rightarrow$ Zeitänderung
	- die Masse $\Delta m\rightarrow$ Massenänderung


### Beispiele

##### Geschwindigkeitsänderung
Im Alltag nutzen wir den Begriff _Änderung_ meistens auch von 'früher' zu 'später': Wenn ich heute mit $8\,\frac{km}{h}$ laufe und morgen mit $12\,\frac{km}{h}$ entspricht das einer Geschwindigkeitsänderung von $+4\,\frac{km}{h}$:
$$
4\,\frac{km}{h} = 12\,\frac{km}{h}-8\,\frac{km}{h}
$$

##### Orts- und Zeitänderung
Ein Fahrrad befindet sich
- zum Zeitpunkt $t_1=0\,s$ am Ort $x_1=10\,m$
- zum Zeitpunkt $t_2=5\,s$ am Ort $x_2=27\,m$

Damit ergibt sich eine
- Ortsänderung $\Delta x=x_2-x_1=27\,m-10\,m=17\,m$
- Zeitänderung $\Delta t=t_2-t_1=10\,s-0\,s=10\,s$

### Wieso ist das hilfreich?
Eine kurze und einheitliche Schreibweise für Änderungen sind in der Physik von zentraler Bedeutung, da die Physik sich hauptsächlich mit sich verändernden Grössen beschäftigt.

### Weiteres
- Die Änderung $\Delta w$ ist der Wert, der zum früheren Wert $w_1$ hinzugefügt werden muss, um den späteren Wert $w_2$ zu erhalten. Dies folgt aus der Definition:
$$
\Delta w=w_2-w_1 \rightarrow w_2=w_1+\Delta w
$$
- Das Vorzeichen des Wertes $\Delta w$ hat für jede betrachtete Grösse $w$ eine physikalische Interpretation, z.B.:
	- $\Delta x>0$: Vorwärtsbewegung, $\Delta x<0$: Rückwärtsbewegung
	- $\Delta v>0$: Geschwindigkeitszunahme, $\Delta v<0$: Geschwindigkeitsabnahme
	- $\Delta t>0$: Zeit vergeht vorwärts, $\Delta t<0$: Zeit vergeht rückwärts
	- $\Delta m>0$: Massenzunahme, $\Delta m>0$: Massenabnahme
- Die Bezeichnungen _Änderung_, _Veränderung_ und _Differenz_ werden gleichbedeutend genutzt. Beispiel: Zeit_änderung_, Zeit_veränderung_, Zeit_differenz_.

[1]: <konzepte/konzept-1/> "Name des Konzepts"
[2]: <konzepte/konzept-2/> "Name des Konzepts"