---
title: Integration mit unbekannter Grenze
taxonomy:
	id: 2023090716334566
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
    - '/aufgaben/2023090716334566'

mathjax:
  process: true
---

Bestimme den Wert für $k$ so, dass die Gleichung stimmt.

$$
\int_k^4 4x+8\,dx=72
$$

Hinweis: Es ist nicht erlaubt, $k$ mit Hilfe des Taschenrechners zu 'erraten'.

[details="Tipp zum Vorgehen" class="tipp"]
- Werte das Integral aus, als wüsstest du den Wert für $k$.
- Bestimme $k$ aus der daraus entstehenden Gleichung.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $k=-2$

**Lösungsidee**: Finden der Stammfunktion und Einsetzen der Grenzen liefert eine Gleichung für den gesuchten Parameter $k$.

**Lösungsweg**:

1. Eine [Stammfunktion](/konzepte/stammfunktion) $F(x)$ der Funktion $f(x)=4x-8$ ist
$$
F(x)=2x^2+8x
$$

2. Das [Integral](/konzepte/integral) kann  dann mit Hilfe des [Fundamentalsatz der Analysis](/konzepte/fundamentalsatz-der-analysis) geschrieben werden als

$$
\begin{align}
\int_k^4 4x+8\,dx&=2x^2+8x \Big|_k^4 \\
&=(2\cdot 4^2+8\cdot 4)-(2\cdot k^2+8\cdot k)
\end{align}
$$

3. Vereinfachung des rechten Terms und Nutzung der Gleichheit, die in der Aufgabenstellung gegeben ist, ergibt die Gleichung für $k$:
$$
-2k^2-8k+64=72\\
$$

4. Umformung der quadratischen Gleichungen:
$$
2k^2+8k+8=0
$$

5. Benutzung der [quadratischen Lösungsformel](/konzepte/quadratische-loesungsformel) mit den Koeffizienten $a=2$, $b=8$ und $c=8$:
$$
\underline{k=-2}
$$

##### Bemerkung
Die quadratische Gleichung in (4) kann auch gelöst werden, indem sie zuerst in [Normalform](/konzepte/normalform) gebracht wird:
$$
k^2+4k+4=0
$$

und faktorisiert wird
$$
(k+2)^2=0 \rightarrow k=-2
$$

[/details]