---
title: Integration mit unbekannter Grenze
taxonomy:
	id: 2023090713428821
	set: 0202309071633119

	requires_mathematik: ['Integral', 'Stammfunktion','Quadratische Lösungsformel']

	category: ['exercises']
	fach: Mathematik
	thema: ['Integral']
	collection: ['Matur','kleine Matur']
	art: ['Berechnung']
	needsSupport: 0
	needsTool: 0

	hints: 1
	bloom: 
	schritte: 5
	schwierigkeit: 2
	realitaet: 0
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230907
	source: 'Thomas Bisig, thomas@akademix.ch'
	learning-objective: ''
	content-type: 'markdown'
	media: 
	licence: 'CC BY-SA 4.0'

	status_tags: 0
	status_exercise: 0
	status_solution: 0

	todo: []

routes:
  aliases:
    - '/aufgaben/2023090713428821'

mathjax:
  process: true
---

Bestimme den Wert für $k$ so, dass die Gleichung stimmt.

$$
\int_1^k \frac{1}{2}x-3\,dx=-6.25
$$

Hinweis: Es ist nicht erlaubt, $k$ mit Hilfe des Taschenrechners zu 'erraten'.

[details="Tipp zum Vorgehen" class="tipp"]
- Werte das Integral aus, als wüsstest du den Wert für $k$.
- Bestimme $k$ aus der daraus entstehenden Gleichung.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $k=6$

**Lösungsidee**: Finden der Stammfunktion und Einsetzen der Grenzen liefert eine Gleichung für den gesuchten Parameter $k$.

**Lösungsweg**:
_(siehe unten für einen alternativen Lösungsweg)_
1. Eine [Stammfunktion](/konzepte/stammfunktion) $F(x)$ der Funktion $f(x)=\frac{1}{2}x-3$ ist
$$
F(x)=\frac{1}{4}x^2-3x+C
$$

2. Das [Integral](/konzepte/integral) kann dann mit Hilfe des [Fundamentalsatz der Analysis](/konzepte/fundamentalsatz-der-analysis) geschrieben werden als

$$
\begin{align}
\int_1^k \frac{1}{2}x-3\,dx&=\frac{1}{4}x^2-3x \Big|_1^k \\
&=(\frac{1}{4}k^2-3k)-(\frac{1}{4}\cdot 1^2-3\cdot 1)
\end{align}
$$

3. Vereinfachung des rechten Terms und Nutzung der Gleichheit, die in der Aufgabenstellung gegeben ist, ergibt die Gleichung für $k$:
$$
\frac{1}{4}k^2-3k+\frac{11}{4}=-6.25\\
$$

4. Umformung der quadratischen Gleichungen:
$$
\frac{1}{4}k^2-3k-9=0
$$

5. Benutzung der [quadratischen Lösungsformel](/konzepte/quadratische-loesungsformel) mit den Koeffizienten $a=\frac{1}{4}$, $b=3$ und $c=-9$:
$$
\underline{k=6}
$$

##### Bemerkung
Die quadratische Gleichung in (4) kann auch gelöst werden, indem sie zuerst in [Normalform](/konzepte/normalform) gebracht wird:
$$
k^2-12k-36=0
$$

und faktorisiert wird
$$
(k-6)^2=0 \rightarrow k=6
$$

##### Alternativer Lösungsweg
1. Mit Hilfe einer Zeichnung lässt sich erkennen, dass es sich bei der gesuchten geometrischen Figur um ein Dreieck mit einer unbekannter Seitenlänge handelt.

2. Die zweite Seitenlänge des flächebestimmenden Dreiecks lässt sich berechnen mit $f(1)=-2.5$.

3. Die gegebene Fläche des Dreiecks ($-6.25$), berechnet mit der bekannten ($-2.5$) und unbekannten Seite ($k$) bestimmt den gesuchten Wert $k$:
$$
\frac{(-2.5)\cdot k}{2}=-6.25 \rightarrow k=6
$$

[/details]