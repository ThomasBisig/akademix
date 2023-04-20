---
title: Distanzmessungen
taxonomy:
	id: 2023041420103343
	set: 0202304142011775

	requires_physik: [Gleichförmige Bewegung]
	requires_mathematik: [Algebraische Umformung]

	category: exercises
	fach: Physik
	thema: [Mechanik, Bewegung, Gleichförmige Bewegung]
	art: Berechnung
	needsSupport: 0
	needsTool: 0

	hints: 1
	detail: 0
	bloom: 1
	schritte: 2
	schwierigkeit: 1
	realitaet: 
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230414
	source: 'www.physica.ch, angepasst'
	learning-objective: ''
	content-type: markdown
	media:
	licence: 'CC BY-SA 4.0'

	status_tags: review_0
	status_exercise: review_1
	status_solution: review_1

	todo: []

mathjax:
  process: true
---
![Ein Schiff nutzt Schall zur Tiefenbestimmung](exercise30-1.svg?resize=400,280&class=float-right) Zur Ermittlung der Meerestiefe wird von einem Schiff aus an der Wasseroberfläche ein kurzes Ultraschallsignal ausgesandt. Das Signal kehrt, nachdem es vom Meeresboden reflektiert wurde, nach $1.6\,s$ wieder an die Oberfläche zurück.

Wie tief ist an dieser Stelle das Meer, wenn die Schallgeschwindigkeit im Meerwasser $1440\,\frac{m}{s}$ beträgt?

[details="Tipp zum Vorgehen" class="tipp"]
Der Zusammenhang der gleichförmigen Bewegung liefert für die Durchschnittsgeschwindigkeit $\overline{v}=\frac{\Delta s}{\Delta t}$ die Antwort.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $\underline{1152\,m}$

**Lösungsidee**: Die Zeit für einen Weg und die Geschwindigkeit in den Zusammenhang der gleichförmigen Bewegung einsetzen.

**Lösungsweg**:
- Da das Signal die gesuchte Strecke zwei Mal zurücklegt (runter und rauf), beträgt die Zeit für den Weg bis zum Meeresboden $\Delta t=0.8\,s$.

- [Umformen](../) des [Zusammenhangs der gleichförmigen Bewegung](../) liefert für die für die Strecke

$$
\Delta s=\overline{v}\cdot {\Delta t}=1440\,\frac{m}{s}\cdot 0.8\,s = \underline{1152\,m}
$$

[/details]