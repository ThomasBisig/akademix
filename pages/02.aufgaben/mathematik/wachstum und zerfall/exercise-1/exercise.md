---
title: Radioaktives Jod
taxonomy:
	id: 2023091116023422
	set: 0202309111652443

	requires_mathematik: ['Exponentielle Prozesse']

	category: ['exercises']
	fach: Mathematik
	thema: ['Exponentielle Prozesse']
	collection: ['Matur','kleine Matur']
	art: ['Berechnung']
	needsSupport: 0
	needsTool: 0

	hints: 3
	bloom: 
	schritte: 10
	schwierigkeit: 2
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230911
	source: 'Thomas Bisig, thomas@akademix.ch'
	learning-objective: ''
	content-type: 'markdown'
	media: 
	licence: 'CC BY-SA 4.0'

	status_tags: 1
	status_exercise: 1
	status_solution: 1

	todo: []

routes:
  aliases:
    - '/aufgaben/2023091116023422'

mathjax:
  process: true
---
$120\,g$ radioaktives Jod-131 zerfällt exponentiell und hat eine Halbwertszeit von $8$ Tagen.

1. Berechne die tägliche Abnahme in Prozent.
2. Stelle eine Funktion $J(t)$ auf, mit deren Hilfe zu jedem Zeitpunkt $t$ (in Tagen) die verbleibende Menge an Jod berechnet werden kann.
3. Wie lange dauert es, bis nur noch $10\,mg$ Jod übrig sind?


[details="Tipp zu Teil 1" class="tipp"]
Finde eine Gleichung, welche dir die tägliche Abnahme in Zusammenhang mit der Halbwertszeit bringt.
[/details]

[details="Tipp zu Teil 2" class="tipp"]
Die Art der beschreibenden Funktion steht in der Aufgabenstellung.
[/details]

[details="Tipp zu Teil 3" class="tipp"]
Erstelle und löse mit Hilfe von (1) und (2) die Exponentialgleichung.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: 
1. $\approx 8.30\%$
2. $J(t)=120\cdot 0.917^t$
3. $\approx 108.41$

**Lösungsidee**: 

**Lösungsweg**:

##### Teil 1
1. Die tägliche Abnahme sei $q$. Dann bedeutet eine Halbwertszeit von 8 Tagen formal, dass
$$
120\,g\cdot q^8 = 60\,g
$$

2. Auflösen nach $q$ liefert:
$$
q^8=\frac{1}{2} \rightarrow q=\sqrt[8]{0.5}\approx 0.917
$$

3. Somit beträgt die tägliche Abnahme in Prozent
$$
(1-0.917) \cdot 100=\underline{8.30\%}
$$

##### Teil 2
1. Exponentielle Zusammenhänge haben die Form $f(t)=a\cdot q^{t}$. Damit ergibt sich für die $120\,g$ radioaktives Jod
$$
\underline{J(t)=120\,g\cdot 0.917^t}
$$

##### Teil 3
1. Gesucht ist in der Aufgabe die Dauer $t$, bis nur noch $J(t)=10\,mg=0.01\,g$ radioaktives Jod vorhanden sind.

2. Mit Hilfe von (2) ergibt sich die Gleichung
$$
0.01\,g=120\,g\cdot 0.917^t
$$

3. Umformen, so dass der Logarithmus 'einfacher' angewendet werden kann
$$
\frac{0.01}{120}=0.917^t
$$

4. ... und anwenden des Logarithmus auf beiden Seiten
$$
\log{\frac{0.01}{120}}=\log{0.917^t}
$$

5. Mit Hilfe des [Logarithmusgesetz für Potenzen](/konzepte/logarithmusgesetz-fuer-potenzen) kann die Gleichung in zwei Schritten nach der gesuchten Zeit $t$ gelöst werden:

$$
\log{\frac{0.01}{120}}=t\cdot \log{0.917}\rightarrow t=\frac{\log{\frac{0.01}{120}}}{\log{0.917}}\approx 108.41
$$

6. Es dauert demnach ungefähr $\underline{108.41}$ Tage, bis nur noch $10\,mg$ radioaktives Jod vorhanden sind.

[/details]