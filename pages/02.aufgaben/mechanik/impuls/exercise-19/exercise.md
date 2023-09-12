---
title: 'Zwei Autokollisionen'
taxonomy:
	id: 2023082217055101
	set: 

	requires_physik: ['Kraftstoss','Impuls','mittlere Kraft']
	requires_mathematik: []

	category: ['exercises']
	fach: Physik
	thema: ['Impuls','Kraftstoss']
	art: ['Konzept']
	needsSupport: 0
	needsTool: 0

	hints: 1
	bloom: 
	schritte: 4
	schwierigkeit: 1
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230828
	source: 'Thomas Bisig, thomas@akademix.ch'
	learning-objective: ''
	content-type: 'markdown'
	media: 'Thomas Bisig, thomas@akademix.ch'
	licence: 'CC BY-SA 4.0'

	status_tags: 1
	status_exercise: 1
	status_solution: 1

	todo: []

routes:
  aliases:
    - '/aufgaben/2023082217055101'

mathjax:
  process: true
---
![Zwei unterschiedliche Autokollisionen](zwei-autokollisionen.svg?resize=400,400&class=float-right)
In nebenstehender Abbildung sind zwei Kollisionen eines Auto mit einer Wand illustriert (links und rechts). Angenommen, die Dauer der Kollision und die Kollisionsgeschwindigkeit seien in beiden Fällen die gleichen:

In welchem Fall sind die Kräfte auf die Fahrgäste kleiner?

[details="Tipp zum Vorgehen" class="tipp"]
Nutze die Formel für den Kraftimpuls um die einzig entscheidende Grösse zu identifizieren.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: die rechte Abbildung

**Lösungsidee**: Die Formel für den Kraftimpuls zeigt, dass die Geschwindigkeits- bzw. die Impulsänderung die einzig entscheidende Grösse ist.

**Lösungsweg**:

1. In dieser Aufgabe ändert sich der [Impuls](/konzepte/impuls), somit wirkt eine Kraft.

2. Wir nehmen an, die Kraft sei nicht konstant. Dann gelten die Zusammenhänge des Kraftstosses für die [mittlere Kraft](/konzepte/mittlere-kraft). Die Formel für den [Kraftstoss](/konzepte/kraftstoss) für die mittlere Kraft lautet
$$
\Delta p = \overline{F} \cdot \Delta t
$$

3. Da wir an der Kraft interessiert sind, ergibt sich
$$
\overline{F} = \frac{\Delta p}{\Delta t}
$$

4. Da $\Delta t$ in beiden Fällen gleich sein soll und die Geschwindigkeit _vor_ der Kollision auch, entscheidet nur die Geschwindigkeit _nach_ der Kollision über die wirkenden Kräfte.
- in der rechten Abbildung ist die Geschwindigkeit _nach_ der Kollision null, dh nur der Impuls _vor_ der Kollision ist entscheidend.
- in der linken Abbildung ist die Geschwindigkeit _nach_ der Kollision kleiner (kürzerer Pfeil) und entgegengesetzt ([vektorielle Grösse](/konzepte/vektorielle-groesse)) der Geschwindigkeit _vor_ der Kollision. Die Impulsänderung ist grösser als wie in der rechten Abbildung, somit auch die wirkende (mittlere) Kraft.

[/details]