---
title: Geschwindigkeiten aus dem s-t-Diagramm bestimmen
taxonomy:
	id: 2023040921288382
	set: 0202304092106222

	requires_physik: [Gleichförmige Bewegung]
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
	realitaet: 
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230409
	source: 'Skript Mechanik 2022, Thomas Bisig, tbisig@pm.me'
	learning-objective: ''
	content-type: markdown
	media: yes
	licence: 'CC BY-SA 4.0'

	status_tags: review_0
	status_exercise: review_0
	status_solution: review_0

	todo: []

mathjax:
  process: true
---
![Bild](exercise-19-1.svg?resize=400,400&class=float-right) Das nebenstehende $s-t$-Diagramm zeigt den Ort $s$ eines Objektes zu einer bestimmten Zeit $t$ an.
1. Unterteile das $s-t$-Diagramm in fünf zeitliche Abschnitte, in welchen sich das Objekt jeweils gleichförmig bewegt.
2. Beschreibe in Worten, in welche Richtung sich das Objekt in jedem der fünf Bereiche bewegt.
3. In welchem Bereich bewegt sich das Objekt am schnellsten? ... am langsamsten?
4. Vervollständige die Tabelle mit Hilfe des Diagramms und berechne die zu jedem Bereich gehörende Geschwindigkeit.

| Abschnitt   | 1 | 2 | 3 | 4 | 5 |
| :---        |    :----:   |    :----:   |    :----:   |    :----:   |    :----:   |
| $\Delta s$  |    $20\,m$  |             |             |             |             |
| $\Delta t$  |    $2\,s$   |             |             |             |             |
| $v$         |             |  $20\,\frac{m}{s}$  |             |             |             |


[details="Tipp zum Vorgehen" class="tipp"]
- Lies für jeden Abschnitt die vergangene Zeit $\Delta t$ und die zurückgelegte Strecke $\Delta s$ aus dem Diagramm.
-  Berechne mit Hilfe des Zusammenhangs für gleichförmige Bewegungen $v=\frac{\Delta s}{\Delta t}$ die Geschwindigkeit.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. Siehe Abbildung
2. Teil 1 und 3: Bewegung vorwärts, Teil 2 und 5: Bewegung rückwärts, Teil 4: Stillstand
3. Teil 2 am schnellsten, Teil 4 am langsamsten
4. siehe unten

**Lösungsidee**: Zeit- und Streckendifferenzen aus dem Diagramm ablesen um die Geschwindigkeit zu berechnen.

**Lösungsweg**:
![Bild](exercise-19-2.svg?resize=400,400&class=float-right) 

_Teil 1_

Siehe Abbildung

_Teil 2_

Eine [positive Steigung bedeutet eine Vorwärtsbewegung](../), eine negative Steigung eine Rückwärtsbewegung. Eine Horizontale entspricht einem Stillstand des Objektes.

- Bereich 1: Bewegung vorwärts
- Bereich 2: Bewegung rückwärts
- Bereich 3: Bewegung vorwärts
- Bereich 4: Stillstand
- Bereich 5: Bewegung rückwärts

_Teil 3_

Je [steiler die Gerade im $s-t$-Diagramm](../) ist, je schneller bewegt sich das Objekt. Dabei ist es egal, ob es sich um eine positive oder negative Steigung handelt. Die Steigung ist im zweiten Bereich am grössten, dh das Objekt bewegt sich im zweiten Bereich am schnellsten. Im Stillstand bewegt sich das Objekt nicht, deswegen ist das Objekt im Teil 4 am langsamsten. 

_Teil 4_

Durch das Einzeichnen des [Steigungsdreiecks](..) vom Anfang bis am Ende jeden Abschnitts, können die Zeit- und Streckdifferenzen bestimmt werden. Im ersten Abschnitt bewegt sich das Objekt in $\Delta t_1=2\,s$ um $\Delta s_1=20\,m$ vorwärts, was einer [Geschwindigkeit](../) von

$$
v_1=\frac{\Delta s_1}{\Delta t_1}=\frac{20\,m}{2\,s}=10\,\frac{m}{s}
$$

Im dritten Bereich beträgt die Streckenänderung $\Delta s_5=-10\,m$ in einer Zeit von $\Delta t_5=1\,s$. Das entspricht einer Geschwindigkeit von

$$
v_5=\frac{\Delta s_5}{\Delta t_5}=\frac{-10\,m}{1\,s}=-10\,\frac{m}{s}
$$

Analog findet man die restlichen fehlenden Grössen.

| Abschnitt   | 1 | 2 | 3 | 4 | 5 |
|        ---: |    :----:   |    :----:   |    :----:   |    :----:   |    :----:   |
| $\Delta s$  |    $20\,m$   |    $-30\,m$   |    $20\,m$   |    $0\,m$   |    $-10\,m$   |
| $\Delta t$  |    $2\,s$   |    $1\,s$   |    $1\,s$   |    $1\,s$   |    $1\,s$   |
| $v$         |    $10\,\frac{m}{s}$   |    $-30\,\frac{m}{s}$   |    $20\,\frac{m}{s}$   |    $0\,\frac{m}{s}$   |    $-10\,\frac{m}{s}$   |
[/details]