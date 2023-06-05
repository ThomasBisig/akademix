---
title: Delta-Schreibweise
taxonomy:
	requires_physik: []
	requires_mathematik: []

	category: concepts
	fach: Physik
	thema: [Mechanik, Bewegung, Delta-Schreibweise]

	autor: 'Thomas'
	version: 20230605
	source: 'Thomas Bisig (thomas@akademix.ch)'
	content-type: markdown
	media: 'thomas@akademix.ch'
	licence: 'CC BY-SA 4.0'

	status: review_0

	todo: ['Neue Zeichnung hinzufügen']
mathjax:
	process: true
---

# Delta-Schreibweise

> Die Delta-Schreibweise gibt die Änderung einer Grösse $w$ zwischen zwei Zeitpunkten an:
$$
\Delta w=w_\textrm{Ende}-w_\textrm{Start}
$$

![Zeit- und Ortsänderung als Beispiel der Delta-Schreibweise](Delta-Schreibweise.svg?resize=500,700&class=float-right)

- Ausgehend von einem Startwert $w_\textrm{Start}$ wird die Änderung bis zu einem Endwert $w_\textrm{Ende}$
 geschrieben als die Differenz dieser Werte:
$$
\Delta w=w_\textrm{Ende}-w_\textrm{Start}
$$
- Der griechische Grossbuchstabe **D**elta ($\Delta$) kann als Zeichen für **D**ifferenz verstanden werden.
- Die Delta-Schreibweise kann auf alle Grössen angewendet werden, z.B.
	- den Ort $x$ &rarr; Ortsänderung $\Delta x$
	- die Geschwindigkeit $v$ &rarr; Geschwindigkeitsänderung $\Delta v$
	- die Zeit $t$ &rarr; Zeitänderung $\Delta t$
	- die Masse $m$ &rarr; Massenänderung $\Delta m$
	- die Temperatur $T$ &rarr; Temperaturänderung $\Delta T$


### Beispiele

##### Geschwindigkeitsänderung
Im Alltag nutzen wir den Begriff _Änderung_ auch von 'Start' bis 'Ende': Wenn ich heute ('Start') mit $8\,\frac{km}{h}$ laufe und morgen ('Ende') mit $12\,\frac{km}{h}$ entspricht das einer Geschwindigkeitsänderung von:
$$
\begin{align}
\Delta v	&= v_\textrm{Ende}-v_\textrm{Start} \\
			&= 12\,\frac{km}{h}-8\,\frac{km}{h} \\
			&= 4\,\frac{km}{h}
\end{align}
$$

##### Orts- und Zeitänderung
Ein Fahrrad befindet sich
- zum Zeitpunkt $t_\textrm{Start}=0\,s$ am Ort $x_\textrm{Start}=10\,m$
- zum Zeitpunkt $t_\textrm{Ende}=5\,s$ am Ort $x_\textrm{Ende}=27\,m$

Damit ergibt sich eine
- Ortsänderung $\Delta x=x_\textrm{Ende}-x_\textrm{Start}=27\,m-10\,m=17\,m$
- Zeitänderung $\Delta t=t_\textrm{Ende}-t_\textrm{Start}=10\,s-0\,s=10\,s$


### Wieso ist das hilfreich?
Eine kurze und einheitliche Schreibweise für Änderungen sind in der Physik von zentraler Bedeutung, da die Physik sich hauptsächlich mit sich verändernden Grössen beschäftigt.


### Weiteres
- **Umformung**: Die Änderung $\Delta w$ ist der Wert, der zum Startwert $w_\textrm{Start}$ hinzugefügt werden muss, um den Endwert $w_\textrm{Ende}$ zu erhalten. Dies folgt aus der Definition:
$$
\Delta w=w_\textrm{Ende}-w_\textrm{Start} \rightarrow w_\textrm{Ende}=w_\textrm{Start}+\Delta w
$$
- **Vorzeichen**: Das Vorzeichen des Wertes $\Delta w$ hat für jede betrachtete Grösse $w$ eine physikalische Interpretation, z.B.:
	- $\Delta x \gt 0$: Vorwärtsbewegung, $\Delta x \lt 0$: Rückwärtsbewegung (siehe [Beispiel t-x-Diagramm][1])
	- $\Delta v \gt 0$: Geschwindigkeitszunahme, $\Delta v \lt 0$: Geschwindigkeitsabnahme
	- $\Delta t \gt 0$: Zeit vergeht vorwärts, $\Delta t \lt 0$: Zeit vergeht rückwärts
	- $\Delta m \gt 0$: Massenzunahme, $\Delta m \lt 0$: Massenabnahme
	- $\Delta T \gt 0$: Temperaturzunahme, $\Delta T \lt 0$: Temperaturabnahme
- **Bezeichnungen**: Die Bezeichnungen _Änderung_, _Veränderung_ und _Differenz_ werden gleichbedeutend genutzt. Beispiel: Zeit_änderung_, Zeit_veränderung_, Zeit_differenz_.
- **Einheit**: Die Änderung $\Delta w$ hat dieselbe Dimension wie die Grösse $w$, da es sich um eine Differenz handelt. Beispiel: Ist $m$ eine Masse (in $kg$), so wird auch $\Delta m$ in $kg$ angegeben.
- **Formulierungen**: Der Index $1$ steht für den Start und der Index $2$ für das Ende, somit wird die ursprüngliche Formulierung kürzer:
$$
\Delta w = w_2 - w_1
$$

[1]: <konzepte/konzept-1/> "Name des Konzepts"