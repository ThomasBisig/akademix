---
title: 'Drei Autos bremsen ab'
taxonomy:
	id: 2023082217009283
	set: 

	requires_physik: ['Kraftstoss','Impuls']
	requires_mathematik: ['Diagramme lesen','Umformung']

	category: ['exercises']
	fach: Physik
	thema: ['Impuls','Kraftstoss']
	art: ['Berechnung','Diagramm']
	needsSupport: 0
	needsTool: 0

	hints: 0
	bloom: 
	schritte: 6
	schwierigkeit: 1
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230822
	source: 'Impulse, Thomas Bisig, thomas@akademix.ch'
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
    - '/aufgaben/2023082217009283'

mathjax:
  process: true
---
![v-t-Diagramme von drei abbremsenden Autos](drei-autos-bremsen-ab.svg?resize=250,500&class=float-right)
Drei Autos (A, B und C) gleicher Masse ($m=1500\,kg$) fahren mit einer Geschwindigkeit von $20\,\frac{m}{s}$. Die drei Autos kommen auf unterschiedliche Weise zum Stillstand.

Stehen alle drei Autos, ist ihr [Impuls](/konzepte/impuls) wieder gleich, nämlich gleich null, somit haben alle Autos gleich viel Impuls "verloren".

1. Die drei [t-v-Diagramme](/konzepte/t-v-diagramm) der drei Autos sind rechts abgebildet. In welchem Auto werden die (mit)fahrenden Personen die grösste Kraft spüren?

2. Berechne die auf das jeweilige Auto wirkende Kraft:
	- Auto A lässt das Auto ausrollen und steht nach einer Minute still.
	- Auto B tritt auf die Bremse und steht nach $5$ Sekunden still.
	- Auto C befindet sich in einem Crashtest und steht nach $0.5\,s$ still.


[details="Tipp zum Vorgehen" class="tipp"]
- Berechne die Impulsdifferenz
- Forme die Formel für den Kraftstoss um
- Setze die gegebenen Grössen in die Formel ein
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. unterstes Diagramm
2. $1500\,N$, $6000\,N$, $60000\,N$

**Lösungsidee**: Formel für den Kraftstoss nach der Kraft umformen und die gegebenen Grössen einsetzen.

**Lösungsweg**:
##### Teil 1
Da die Anfangs- und Endgeschwindigkeit wie auch die Masse der drei Autos dieselbe ist, muss nur die Abbremszeit betrachtet werden: je kürzer die Abbremszeit umso höher die wirkende Kraft.

Somit werden die Mitfahrenden im Auto mit dem untersten Diagramm ('Crashtest') die grösste Kraft spüren.


##### Teil 2
1. Wir nehmen an, die wirkende Kraft während dem Abbremsen sei konstant.

2. Die Formel für den [Kraftstoss](/konzepte/kraftstoss) bei konstanter Kraft lautet
$$
\Delta p = F \cdot \Delta t
$$

3. Da wir an der Kraft interessiert sind, ergibt sich
$$
F = \frac{\Delta p}{\Delta t}
$$

4. Die Impuls[differenz](/konzepte/delta-schreibweise) $\Delta p=p_\textrm{Ende}-p_\textrm{Start}$ beträgt für alle drei Autos gleich viel und zwar
$$
\Delta p=1500\,kg \cdot 20\,\frac{m}{s}-1500\,kg \cdot 0\,\frac{m}{s}=30000\,Ns
$$

5. Einsetzen in die Formel aus (3) ergibt für die unterschiedlichen $\Delta t$:
- $F_1 = \frac{\Delta p}{\Delta t}=\frac{30000\,Ns}{60\,s}=\underline{500\,N}$
- $F_2 = \frac{\Delta p}{\Delta t}=\frac{30000\,Ns}{5\,s}=\underline{6000\,N}$
- $F_3 = \frac{\Delta p}{\Delta t}=\frac{30000\,Ns}{0.5\,s}=\underline{60000\,N}$

[/details]