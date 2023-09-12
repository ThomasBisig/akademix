---
title: 'Boeing 747SP'
taxonomy:
	id: 2023081212438890
	set:

	requires_physik: ['Impuls','Mittlere Geschwindigkeit']
	requires_mathematik: ['Umformung']

	category: ['exercises']
	fach: Physik
	thema: ['Impuls']
	art: ['Berechnung','Recherche']
	needsSupport: 0
	needsTool: 0

	hints: 2
	bloom: 
	schritte: 5
	schwierigkeit: 2
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230813
	source: 'Thomas Bisig, thomas@akademix.ch'
	learning-objective: ''
	content-type: 'markdown'
	media: 'Thomas Bisig, thomas@akademix.ch'
	licence: 'CC BY-SA 4.0'

	status_tags: 2
	status_exercise: 2
	status_solution: 2

	todo: []

routes:
  aliases:
    - '/aufgaben/2023081212438890'
    
mathjax:
  process: true
---
![Person rennt mit Papierflieger über ihr](person-rennt-mit-flieger.svg?resize=250,300&class=float-right)
Zwei Körper können den gleichen Impuls haben, auch wenn sie sich unterschiedlich schnell bewegen:

Wie schnell muss eine maximal beladene _Boeing 747SP_ fliegen, um den gleichen Impuls zu haben wie eine $56 kg$ schwere Läuferin, welche die $100\,m$ in $12.56\,s$ zurücklegt?

[details="Tipp zur Geschwindigkeit" class="tipp"]
Mit Hilfe der gleichmässigen Bewegung findest du die Geschwindigkeit der Läuferin.
[/details]

[details="Tipp zur Boeing 747SP" class="tipp"]
Finde die fehlende Massenangabe im Internet.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $\approx 1.4\cdot 10^{-3}\,\frac{m}{s}$ oder $1.4\,\frac{mm}{s}$

**Lösungsidee**:
Die Berechnung der Geschwindigkeit der Läuferin liefert auch gleich ihren Impuls. Gleichsetzen mit dem unbekannten Impuls der _Boeing 747SP_ und nachschlagen der leeren Flugzeugmasse liefert nach Umformung die gesuchte Geschwindigkeit.

**Lösungsweg**:

Bemerkung: Der berechnete Impuls der Läuferin entspricht dem _mittleren_ Impuls, da sich die Geschwindigkeit der Läuferin während den $100\,m$ ändert.

_Impuls der Läuferin_

1. Die Masse $m=56\,kg$ ist bekannt, die (mittlere) Geschwindigkeit kann mit Hilfe der Formel für die [mittlere Geschwindigkeit](/konzepte/mittlere-geschwindigkeit) berechnet werden:
$$
\overline{v}=\frac{\Delta x}{\Delta t}=\frac{100\,m}{12.56\,s}\approx 7.96\,\frac{m}{s}
$$

2. Der (mittlere) [Impuls](/konzepte/impuls) der Läuferin ist dann

$$
\overline{p}_\textrm{Läuferin}=m\cdot \overline{v} = 56\,kg \cdot \frac{100\,m}{12.56\,s} \approx 445.86 Ns
$$

_Geschwindigkeit der Boeing 747SP_

4. Die Impulse sollen gleich sein, dh der (bekannte) Impuls der Läuferin $\overline{p}_\textrm{Läuferin}$ und der (unbekannte) Impuls $p_\textrm{Boeing}$ der _Boeing 747SP_ können gleichgesetzt werden:

$$
\overline{p}_\textrm{Läuferin}=p_\textrm{Boeing} \approx 445.86 Ns
$$

5. Die [maximale Startmasse der _Boeing 747SP_](https://de.wikipedia.org/wiki/Boeing_747#Technische_Daten) beträgt ungefähr $m_\textrm{Boeing}=317515\,kg$. Einsetzen aller bekannten Grössen in die Gleichung für den Impuls $p_\textrm{Boeing}=m_\textrm{Boeing}\cdot v_\textrm{Boeing}$

$$
445.86 Ns = 317515\,kg \cdot v_\textrm{Boeing}
$$

6. [Umformen](/konzepte/umformung) nach der Flugzeuggeschwindigkeit $v_\textrm{Boeing}$ und Berechnung liefert das Resultat:

$$
v_\textrm{Boeing}=\frac{445.86 Ns}{317515\,kg}\approx \underline{1.4\cdot 10^{-3}\,\frac{m}{s}}
$$

Das entspricht einer Geschwindigkeit von $1.4\,mm$ pro Sekunde.

[/details]