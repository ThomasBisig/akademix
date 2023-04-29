---
title: Mittlere Geschwindigkeit auf einer Joggingstrecke
taxonomy:
	id: 2023042921319988
	set: 0202304031125126

	requires_physik: [Mittlere Geschwindigkeit, Plausibilitätsüberlegung, SI-Einheit, t-v-Diagramm]
	requires_mathematik: [Diagramme lesen]

	category: exercises
	fach: Physik
	thema: [Mechanik, Bewegung, Mittlere Geschwindigkeit]
	art: Analyse
	needsSupport: 0
	needsTool: 'xls'

	hints: 0
	detail: 0
	bloom: 3
	schritte: 3
	schwierigkeit: 3
	realitaet: 1
	kat_bruder:
	kat_proz_konz:

	autor: 'Thomas'
	version: 20230429
	source: 'Thomas Bisig (thomas@akademix.ch)'
	learning-objective: ''
	content-type: markdown
	media: 'Thomas Bisig (thomas@akademix.ch)'
	licence: 'CC BY-SA 4.0'

	status_tags: review_1
	status_exercise: review_0
	status_solution: review_0

	todo: ['']

mathjax:
  process: true
---
![Abbildung aus Workoutdoors einer Joggingstrecke](exercise-40-1.png?class=img_exercise)
Nebenstehend abgebildet sind die Daten einer Joggingrunde, welche mit der App [Workoutdoors](http://www.workoutdoors.com) aufgezeichnet wurden. Leider ist bei der Übertragung der Daten der oberste Teil des Bildes verloren gegangen. Der Graph am unteren Rand zeigt die momentane Geschwindigkeit an.

Zum Glück wurden die Geschwindigkeitsdaten gesichert. Analysiere die [Daten](exercise-40-daten.xlsx):
1. Erstelle ein $t-v$-Diagramm,
2. Bestimme die mittlere Geschwindigkeit
3. Bestimme die zurückgelegte Strecke.

[details="Lösung" class="loesung"]
**Antwort**:
2. $\overline{v}=2.4\,\frac{m}{s}$
3. $\Delta x=\approx 8\,km$
**Lösungsweg**:
1. ![Diagramm der Joggingstrecke](t-v-diagramm.png?class=img_exercise) Nebenstehend ist das mit Excel erstellte [$t-v$-Diagramm](/konzepte/konzept-1). Die Geschwindigkeitsmessung erfolgt jede Sekunde, wie aus den Daten der ersten Spalte ersichtlich ist.
2. Die horizontale grüne Linie entspricht der (mit Augenmass bestimmten) [mittleren Geschwindigkeit](/konzepte/konzept-1). Sie liegt um die $2.4\,\frac{m}{s}$. Zwar ist im Datendokument keine Angabe zur Einheit der Geschwindigkeit gegeben, jedoch sind die [umgerechneten](/konzepte/konzept-1) $2.4\,\frac{m}{s}=8.64\,\frac{km}{h}$ ist jedoch die [plausiblere Grösse](/konzepte/konzept-1) als $2.4\,\frac{km}{h}$ .
3. Die Zeit für den Lauf kann aus der ersten Spalte gelesen werden. Aus der Differenz der Startzeit ('14:11:14') und der Endzeit ('15:06:37') ergibt sich eine Gesamtzeit $\Delta t = 3323\,s$ Die gelaufene Strecke $\Delta x$ kann mit Hilfe des Zusammenhangs der mittleren Geschwindigkeit bestimmt werden:

$$
\begin{align}
\Delta x 	&= \overline{v} \cdot \Delta t
					&= 2.4\,\frac{m}{s} \cdot 3323\,s
					& = 7975.2 m \underline{\approx 8\,km}
\end{align}
$$

![Gesamtsicht der Joggingstrecke in der App](exercise-40-2.png?class=img_exercise) In der nebenstehenden Ansicht aus der App ist ersichtlich, dass die so gemachte Abschätzung einen Fehler von

$$
\frac{8.2\,km-8\,km}{8.2\,km}\approx 0.025
$$

von rund $2.5%$ aufweist.

Dokumente:
- [Originaldaten](exercise-40-daten-orig.xlsx)
- [Lösungsexcel](exercise-40-daten-lsg.xlsx)
[/details]
