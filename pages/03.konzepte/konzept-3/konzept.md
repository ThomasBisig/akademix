---
title: t-x-Diagramm
taxonomy:
	requires_physik: [Delta-Schreibweise]
	requires_mathematik: [Diagramm lesen]

	category: concepts
	fach: Physik
	thema: [Mechanik, Bewegung]

	autor: 'Thomas'
	version: 20230606
	source: 'Thomas Bisig (thomas@akademix.ch)'
	content-type: markdown
	media: 'thomas@akademix.ch'
	licence: 'CC BY-SA 4.0'

	status: review_0

	todo: []

routes:
  aliases:
    - '/konzepte/zeit-ort-diagramm'

mathjax:
	process: true
---

# Zeit-Ort-Diagramm

> Das Zeit-Ort-Diagramm ($t-x$-Diagramm) beschreibt den Ort $x$ eines Objektes zu einer bestimmten Zeit $t$.

![Zeit-Ort-Diagramm (t-x-Diagramm) theoretische Darstellung](Zeit-Ort-Diagramm-theoretisch.svg?resize=450,300&class=float-right)

- Die horizontale Achse beschreibt die Zeit $t$, die vertikale Achse den Ort $x$.
- Die Punkte im Diagramm werden mit Hilfe von Koordinaten z.B. $(t_1,x_1)$ beschrieben.
- Die Krümmung der Kurve bestimmt die Bewegungsrichtung:
	- eine steigende Kurve entspricht einer Vorwärtsbewegung: [$\Delta x \gt 0$][1]
	- eine fallende Kurve einer Rückwärtsbewegung: $\Delta x \lt 0$
	- eine Horizontale einem Stillstand $\Delta x=0$

### Beispiel
![Beispiel eines Zeit-Ort-Diagramm (t-x-Diagramm)](Zeit-Ort-Diagramm-Beispiel.svg?resize=450,350&class=float-right) Das abgebildete Diagramm kann wie folgt gelesen werden:

##### Wo befindet sich das Objekt
Das Objekt bewegt sich vom Punkt $(5,3)$ zum Ort $(12,9)$:
	- Start: Zur Zeit $5\,s$ befindet sich das Auto am Ort $3\,m$
	- Ende: Zur Zeit $12\,s$ befindet sich das Auto am Ort $9\,m$

##### Wie bewegt sich das Objekt
Die Richtung der Bewegung des Objektes kann wie folgt aus dem Diagramm gelesen werden:
	- Im ersten Abschnitt (1) ist die Ortsverschiebung in Richtung der Ortsachse, d.h. $\Delta x \gt 0$. Das bedeutet, dass es sich um eine Vorwärtsbewegung handelt.
	- Im zweiten Abschnitt (2) findet keine Ortsverschiebung statt, d.h. $\Delta x=0$. Das Objekt steht still.
	- Im dritten Abschnitt (3) ist die Ortsverschiebung entgegen der Ortsachse, d.h. $\Delta x \lt 0$. Das bedeutet, dass es sich um eine Rückwärtsbewegung handelt.

### Wieso ist das hilfreich?
Bewegungen von Objekten können mit Hilfe eines $t-x$-Diagramms dargestellt und [Geschwindigkeiten][1] aus dem Diagramm gelesen werden.

### Weiteres
- **1-Dimensional**: Das $t-x$-Diagramm beschreibt eine Bewegung in einer Dimension.
- **Zeitrichtung**: Physikalisch sind nur Bewegungen, für welche $\Delta t \gt 0$ gilt, möglich (d.h. die Zeit geht immer vorwärts, steht nie still oder geht rückwärts).
- **Bezeichnungen**: Das Diagramm hat auch andere Bezeichnungen: Ort-Zeit-Diagramm, Weg-Zeit-Diagramm, $s-t$-Diagramm

[1]: <konzepte/konzept-1/> "Name des Konzepts"
