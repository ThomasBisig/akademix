---
title: Boeing 747SP
taxonomy:
	id: 2023081212438890
	set:

	requires_physik: ["impuls","Gleichförmige Bewegung"]
	requires_mathematik: [Umformung]

	category: exercise
	fach: Physik
	thema: [impuls]
	art: ["Berechnung","Recherche"]
	needsSupport: 0
	needsTool: 0

	hints: 
	detail: 
	bloom: 
	schritte: 
	schwierigkeit: 
	realitaet:
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230812
	source: 'Thomas Bisig, tbisig@pm.me'
	learning-objective: ''
	content-type: markdown
	media:
	licence: 'CC BY-SA 4.0'

	status_tags: review_0
	status_exercise: review_0
	status_solution: review_0

	todo: []

mathjax:
  process: true
---

Zwei Körper  können den gleichen Impuls haben, auch wenn sie sich unterschiedlich schnell bewegen:
Wie schnell muss eine maximal beladene Boeing 747SP fliegen, um den gleichen Impuls zu haben wie eine $56 kg$ schwere Läuferin, welche die $100\,m$ in $12.56\,s$ zurücklegt?

[details="Tipp zur Geschwindigkeit" class="tipp"]
Mit Hilfe der gleichmässigen Bewegung findest du die Geschwindigkeit der Läuferin.
[/details]

[details="Tipp zur Boeing 747SP" class="tipp"]
Finde die fehlende Massenangabe im Internet.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $\approx 1.4\cdot 10^{-3}\,\frac{m}{s}$

**Lösungsidee**:
Berechnung der Geschwindigkeit der Läuferin liefert auch ihren Impuls. Gleichsetzen mit dem unbekannten Impuls der Boeing 747SP und nachschlagen der leeren Flugzeugmasse liefert die gesuchte Geschwindigkeit.

**Lösungsweg**:
Bemerkung: Der berechnete Impuls der Läuferin entspricht dem _mittleren_ Impuls, da sich die Geschwindigkeit der Läuferin während den $100\,m$ ändert.

1. Der (mittlere) Impuls der Läuferin ist gegeben durch das Produkt der Masse und der Geschwindigkeit:

$$
p=m\cdot v
$$

2. Die Masse $m=56\,kg$ ist bekannt, die (mittlere) Geschwindigkeit kann mit Hilfe der Formel für die [gleichförmige Bewegung](/konzepte/konzept-2) berechnet werden:
$$
$v=\frac{\Delta x}{\Delta t}=\frac{100\,m}{12.56\,s}\approx 7.96\,\frac{m}{s}$ 
$$

3. Der (mittlere) Impuls der Läuferin ist dann

$$
p_\textrm{Läuferin}=m\cdot v = 56\,kg \cdot \frac{100\,m}{12.56\,s} \approx 445.86 Ns
$$

4. Die Impuls sollen gleich sein, dh der Impuls der (bekannte) Impuls der Läuferin $p_\textrm{Läuferin}$ und der (unbekannte) Impuls $p_\textrm{Boeing}$ der Boeing 747SP können gleichgesetzt werden:

$$
p_\textrm{Läuferin}=p_\textrm{Boeing 747}
$$

5. Die [maximale Startmasse der Boeing 747SP](https://de.wikipedia.org/wiki/Boeing_747#Technische_Daten) beträgt ungefähr $m_\textrm{Boeing 747}=317515\,kg$. Einsetzen aller bekannten Grössen in die vorhergehende Gleichung liefert:

$$
445.86 Ns = 317515\,kg \cdot v_\textrm{Boeing 747}
$$

6. Umformen nach der Flugzeuggeschwindigkeit und Berechnung liefert das Resultat:

$$
v_\textrm{Boeing 747}=\frac{445.86 Ns}{317515\,kg}\approx \underline{1.4\cdot 10^{-3}\,\frac{m}{s}}
$$

Das entspricht einer Geschwindigkeit von $1.4 mm$ pro Sekunde.

[/details]