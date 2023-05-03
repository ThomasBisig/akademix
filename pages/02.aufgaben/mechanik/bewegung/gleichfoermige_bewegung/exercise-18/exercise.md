---
title: Geschwindigkeiten aus dem t-x-Diagramm bestimmen
taxonomy:
	id: 2023040921064433
	set: 0202304092106222

	requires_physik: [Gleichförmige Bewegung, t-x-Diagramm]
	requires_mathematik: [Diagramm lesen, Steigungsdreieck]

	category: exercises
	fach: Physik
	thema: [Mechanik, Bewegung, Gleichförmige Bewegung]
	art: [Berechnung, Diagramm lesen]
	needsSupport: 0
	needsTool: 0

	hints: 2
	detail: 2
	bloom: 2
	schritte: 5
	schwierigkeit: 2
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230430
	source: 'Skript Mechanik 2022, Thomas Bisig (thomas@akademix.ch)'
	learning-objective: ''
	content-type: markdown
	media: 'Thomas Bisig (thomas@akademix.ch)'
	licence: 'CC BY-SA 4.0'

	status_tags: review_0
	status_exercise: review_0
	status_solution: review_0

	todo: []

mathjax:
  process: true
---
![Bild](exercise-18-1.svg?resize=400,400&class=float-right) Das nebenstehende $t-x$-Diagramm zeigt den Ort $x$ eines Objektes zu einer bestimmten Zeit $t$ an.
1. Unterteile das $t-x$-Diagramm in fünf zeitliche Abschnitte, in welchen sich das Objekt jeweils gleichförmig bewegt.
2. Beschreibe in Worten, in welche Richtung sich das Objekt in jedem der fünf Bereiche bewegt.
3. In welchem Bereich bewegt sich das Objekt am schnellsten? ... am langsamsten?
4. Vervollständige die Tabelle mit Hilfe des Diagramms und berechne die zu jedem Bereich gehörende Geschwindigkeit.

| Abschnitt   | 1 | 2 | 3 | 4 | 5 |
| :---        |    :----:   |    :----:   |    :----:   |    :----:   |    :----:   |
| $\Delta x$  |    $10\,m$  |             |             |             |             |
| $\Delta t$  |    $1\,s$   |             |             |             |             |
| $v$         |             |  $30\,\frac{m}{s}$  |             |             |             |


[details="Tipp zum Vorgehen" class="tipp"]
- Lies für jeden Abschnitt die vergangene Zeit $\Delta t$ und die zurückgelegte Strecke $\Delta x$ aus dem Diagramm.
-  Berechne mit Hilfe des Zusammenhangs für gleichförmige Bewegungen die Geschwindigkeit.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. Siehe Abbildung
2. Teil 1, 2 und 5: Bewegung vorwärts, Teil 3: Bewegung rückwärts, Teil 4: Stillstand
3. Teil 2 am schnellsten, Teil 4 am langsamsten
4. siehe unten

**Lösungsidee**: Zeit- und Ortsänderungen aus dem Diagramm ablesen um die Geschwindigkeit zu berechnen.

**Lösungsweg**:
![Bild](exercise-18-2.svg?resize=400,400&class=float-right) 

_Teil 1_

Siehe Abbildung

_Teil 2_
Eine [positive Steigung bedeutet eine Vorwärtsbewegung](/konzepte/konzept-1), eine negative Steigung eine Rückwärtsbewegung. Eine Horizontale entspricht einem Stillstand des Objektes.

- Bereich 1: Bewegung vorwärts
- Bereich 2: Bewegung vorwärts
- Bereich 3: Bewegung rückwärts
- Bereich 4: Stillstand
- Bereich 5: Bewegung vorwärts

_Teil 3_

Je [steiler die Gerade im $t-x$-Diagramm](/konzepte/konzept-1) ist, je schneller bewegt sich das Objekt. Dabei ist es egal, ob es sich um eine positive oder negative Steigung handelt. Die Steigung ist im zweiten Bereich am grössten, dh das Objekt bewegt sich im zweiten Bereich am schnellsten. Im Stillstand bewegt sich das Objekt nicht, deswegen ist das Objekt im Teil 4 am langsamsten. 

_Teil 4_

Durch das Einzeichnen des [Steigungsdreiecks](/konzepte/konzept-1) vom Anfang bis am Ende jeden Abschnitts, können die Zeit- und Ortsänderungen bestimmt werden. Im ersten Abschnitt bewegt sich das Objekt in $\Delta t_1=1\,s$ um $\Delta x_1=1\,m$ vorwärts, was einer [Geschwindigkeit](/konzepte/konzept-1) von

$$
v_1=\frac{\Delta x_1}{\Delta t_1}=\frac{10\,m}{1\,s}=10\,\frac{m}{s}
$$

Im dritten Bereich beträgt die Ortsänderung $\Delta x_3=-20\,m$ in einer Zeit von $\Delta t_2$. Das entspricht einer Geschwindigkeit von

$$
v_3=\frac{\Delta x_3}{\Delta t_3}=\frac{-20\,m}{2\,s}=-10\,\frac{m}{s}
$$

Analog findet man die restlichen fehlenden Grössen.

| Abschnitt   | 1 | 2 | 3 | 4 | 5 |
|        ---: |    :----:   |    :----:   |    :----:   |    :----:   |    :----:   |
| $\Delta x$  |    $10\,m$   |    $30\,m$   |    $-20\,m$   |    $0\,m$   |    $20\,m$   |
| $\Delta t$  |    $1\,s$   |    $1\,s$   |    $2\,s$   |    $1\,s$   |    $1\,s$   |
| $v$         |    $10\,\frac{m}{s}$   |    $30\,\frac{m}{s}$   |    $-10\,\frac{m}{s}$   |    $0\,\frac{m}{s}$   |    $20\,\frac{m}{s}$   |
[/details]