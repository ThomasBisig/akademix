---
title: Radioaktives Cer
taxonomy:
	id: 2023091116539629
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
    - '/aufgaben/2023091116539629'

mathjax:
  process: true
---
$1.1\,kg$ radioaktives Cer-145 zerfällt exponentiell und hat eine Halbwertszeit von $3$ Minuten.

1. Berechne die minütliche Abnahme in Prozent.
2. Stelle eine Funktion $C(t)$ auf, mit deren Hilfe zu jedem Zeitpunkt $t$ (in Minuten) die verbleibende Menge an Cer berechnet werden kann.
3. Wie lange dauert es, bis nur noch $50\,g$ Cer übrig sind?


[details="Tipp zu Teil 1" class="tipp"]
Finde eine Gleichung, welche dir die sekündliche Abnahme in Zusammenhang mit der Halbwertszeit bringt.
[/details]

[details="Tipp zu Teil 2" class="tipp"]
Die Art der beschreibenden Funktion steht in der Aufgabenstellung.
[/details]

[details="Tipp zu Teil 3" class="tipp"]
Erstelle und löse mit Hilfe von (1) und (2) die Exponentialgleichung.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: 
1. $\approx 20.63\%$
2. $C(t)=1.1\,kg\cdot 0.794^t$
3. $\approx 13.38$

**Lösungsidee**: 

**Lösungsweg**:

##### Teil 1
1. Die Abnahme pro Minute sei $q$. Dann bedeutet eine Halbwertszeit von $3$ Minuten formal, dass
$$
1.1\,kg\cdot q^3 = 0.55\,kg
$$

2. Auflösen nach $q$ liefert:
$$
q^3=\frac{1}{2} \rightarrow q=\sqrt[8]{0.5}\approx 0.794
$$

3. Somit beträgt die tägliche Abnahme in Prozent
$$
(1-0.794) \cdot 100=\underline{20.63\%}
$$

##### Teil 2
1. Exponentielle Zusammenhänge haben die Form $f(t)=a\cdot q^{t}$. Damit ergibt sich für die $1.1\,kg$ radioaktivem Cer
$$
\underline{C(t)=1.1\,kg\cdot 0.794^t}
$$

##### Teil 3
1. Gesucht ist in der Aufgabe die Dauer $t$, bis nur noch $C(t)=50\,g=0.05\,kg$ radioaktives Cer vorhanden sind.

2. Mit Hilfe von (2) ergibt sich die Gleichung
$$
0.05\,kg=1.1\,kg\cdot 0.794^t
$$

3. Umformen, so dass der Logarithmus 'einfacher' angewendet werden kann
$$
\frac{0.05}{1.1}=0.794^t
$$

4. ... und anwenden des Logarithmus auf beiden Seiten
$$
\log{\frac{0.05}{1.1}}=\log{0.794^t}
$$

5. Mit Hilfe des [Logarithmusgesetz für Potenzen](/konzepte/logarithmusgesetz-fuer-potenzen) kann die Gleichung in zwei Schritten nach der gesuchten Zeit $t$ gelöst werden:

$$
\log{\frac{0.05}{1.1}}=t\cdot \log{0.794}\rightarrow t=\frac{\log{\frac{0.05}{1.1}}}{\log{0.794}}\approx 13.38
$$

6. Es dauert demnach ungefähr $\underline{13.38}$ Minuten, bis nur noch $50\,g$ radioaktives Cer vorhanden sind.

[/details]