---
title: Die Einheit der Beschleunigung
taxonomy:
	id: 2023040218568872
	set: 02023040415274445

	requires_physik: [Beschleunigung, SI-Einheiten]
	requires_mathematik: [Brüche umformen, Änderungen]

	category: exercises
	fach: Physik
	thema: [Mechanik, Bewegung, Beschleunigung]
	art: Herleitung
	needsSupport: 0
	needsTool: 0

	hints: 1
	bloom: 1
	schritte: 2
	schwierigkeit: 1
	realitaet: 0
	kat_bruder:
	kat_proz_konz:

	autor: 'Thomas'
	version: 20230428
	source: 'Thomas Bisig (thomas@akademix.ch)'
	learning-objective: ''
	content-type: markdown
	media: no
	licence: 'CC BY-SA 4.0'

	status_tags: 2
	status_exercise: 2
	status_solution: 2

	todo: ['']

mathjax:
  process: true
---
Leite die physikalische Einheit der Beschleunigung her.

[details="Tipp zum Vorgehen" class="tipp"]
Benutze die Definition der Beschleunigung und setze die entsprechenden SI-Einheiten ein.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $[a]=\frac{\frac{m}{s}}{s}=\frac{m}{s^2}$

**Lösungsidee**: Nutzung der Definition der Beschleunigung und Einsetzen der entsprechenden SI-Einheiten.

**Lösungsweg**:
1. Die [Beschleunigung](/konzepte/konzept-1) ist definiert als die [Geschwindigkeitsänderung](/konzepte/konzept-1) $\Delta v$ pro Zeitänderung $\Delta t$, formal $\frac{\Delta v}{\Delta t}$
2. Einsetzen der [Einheiten](/konzepte/konzept-1) für $\Delta v$ ($\frac{m}{s}$) und $\Delta t$ ($s$) und [Umformen](/konzepte/konzept-1) ergibt:

$$
\begin{align}
[a]	&= \frac{[\Delta v]}{[\Delta t]} \\
		&=\frac{\frac{m}{s}}{s} \\
		&=\underline{\frac{m}{s^2}}
\end{align}
$$

[/details]