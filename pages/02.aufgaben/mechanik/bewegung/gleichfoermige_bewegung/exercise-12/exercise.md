---
title: Mittlere Geschwindigkeit auf einer Joggingstrecke
taxonomy:
	id: 2023040317199880
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

	status_tags: 2
	status_exercise: 2
	status_solution: 2

	todo: ['']

mathjax:
  process: true
---
![Abbildung aus Workoutdoors einer Joggingstrecke](exercise-12-1.jpeg?class=img_exercise)
Nebenstehend abgebildet sind die Daten einer Joggingrunde, welche mit der App [Workoutdoors](http://www.workoutdoors.com) aufgezeichnet wurden. Leider ist bei der Übertragung der Daten der oberste Teil des Bildes verloren gegangen. Der Graph am unteren Rand zeigt die momentane Geschwindigkeit an.

Zum Glück wurden die Geschwindigkeitsdaten gesichert. Analysiere die [Daten](exercise-12-daten.xlsx):
1. Erstelle ein $t-v$-Diagramm,
2. Bestimme die mittlere Geschwindigkeit
3. Bestimme die zurückgelegte Strecke.

[details="Lösung" class="loesung"]
**Antwort**:
2. $\overline{v}=2.5\,\frac{m}{s}$
3. $\Delta x=\approx 10.7\,km$
**Lösungsweg**:
1. ![Diagramm der Joggingstrecke](t-v-diagramm.png?class=img_exercise) Nebenstehend ist das mit Excel erstellte [$t-v$-Diagramm](/konzepte/konzept-1). Die Geschwindigkeitsmessung erfolgt jede Sekunde, wie aus den Daten der ersten Spalte ersichtlich ist.
2. Die horizontale grüne Linie entspricht der (mit Augenmass bestimmten) [mittleren Geschwindigkeit](/konzepte/konzept-1). Sie liegt um die $2.5\,\frac{m}{s}$. Zwar ist im Datendokument keine Angabe zur Einheit der Geschwindigkeit gegeben, jedoch sind die [umgerechneten](/konzepte/konzept-1) $2.5\,\frac{m}{s}=9\,\frac{km}{h}$ ist jedoch die [plausiblere Grösse](/konzepte/konzept-1) als $2.5\,\frac{km}{h}$ .
3. Die Zeit für den Lauf kann aus der ersten Spalte gelesen werden. Aus der Differenz der Startzeit ('11:37:31') und der Endzeit ('12:48:50') ergibt sich eine Gesamtzeit $\Delta t = 4279\,s$ Die gelaufene Strecke $\Delta x$ kann mit Hilfe des Zusammenhangs der mittleren Geschwindigkeit bestimmt werden:

$$
\begin{align}
\Delta x 	&= \overline{v} \cdot \Delta t
					&= 2.5\,\frac{m}{s} \cdot 4279\,s
					& = 10697.5 m \underline{\approx 10.7\,km}
\end{align}
$$

![Gesamtsicht der Joggingstrecke in der App](exercise-12-2.png?class=img_exercise) In der nebenstehenden Ansicht aus der App ist ersichtlich, dass die so gemachte Abschätzung einen Fehler von

$$
\frac{10.98\,km-10.6975\,km}{10.98\,km}\approx 0.0257
$$

von rund $2.6%$ aufweist.

Dokumente:
- [Originaldaten](exercise-12-daten-orig.xlsx)
- [Lösungsexcel](exercise-12-daten-lsg.xlsx)
[/details]