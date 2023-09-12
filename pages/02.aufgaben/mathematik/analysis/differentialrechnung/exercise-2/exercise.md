---
title: Kurvendiskussion eines Polynoms
taxonomy:
	id: 2023091120466650
	set: 0202309112046771

	requires_mathematik: ['Ableitung','Nullpunkt','Extremum','Wendepunkt','Diagramm']

	category: ['exercises']
	fach: Mathematik
	thema: ['Ableitung','Kurvendiskussion']
	collection: ['Matur','kleine Matur']
	art: ['Berechnung','Diagramm']
	needsSupport: 0
	needsTool: 0

	hints: 1
	bloom: 
	schritte: 12
	schwierigkeit: 2
	realitaet: 0
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230911
	source: 'Rhyn (Analysis), abgeändert Thomas Bisig, thomas@akademix.ch'
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
    - '/aufgaben/2023091120466650'

mathjax:
  process: true
---
1. Bestimme für die Funktion $f(x)$ alle Nullpunkte, Extrema (Hoch- und Tiefpunkte) und Wendepunkte.
$$
f(x)=\frac{1}{5}(x^3-3x^2-9x+2)
$$

2. Skizziere den Graphen $f(x)$


[details="Tipp zum Vorgehen" class="tipp"]
- Finde in deiner Formelsammlung zuerst die Bedingungen für die gesuchten Punkte.
- Leite dann die Funktion (mindestens) zwei Mal ab.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
![Nullpunkte, Hoch-und-Tiefpunkte, Wendepunkte eines Polynoms](Nullpunkte-Hoch-und-Tiefpunkte-Wendepunkte.png?resize=300,300&class=float-right) 
- $N(-2|0)$, $N(0.209|0)$, $N(4.791|0)$
- $H(-1|\frac{7}{5})$, $T(3|-5)$
- $W(-1|-\frac{9}{5})$

**Lösungsidee**: Die Bedingungen für die gesuchten Punkte ergeben Gleichungen, welche einzeln gelöst werden.

**Lösungsweg**:

##### Nullpunkte
1. Bedingung, dass $x$ eine [Nullpunkte](/konzepte/nullpunkte) ist, ist:
$$
f(x)=0 \rightarrow \frac{1}{5}(x^3-3x^2-9x+2) = 0
$$

2. Mit Hilfe des Taschenrechners (_polysolve_) ergeben sich drei Nullpunkte:
$$
N(-2|0), N(0.209|0), N(4.791|0)
$$

##### Extrema
1. Die Bedingung, dass $x$ eine [Hochpunkt](/konzepte/extremum) ist, ist:
$$
f'(x)=0 \textrm{ und } f''(x)<0
$$
und die Bedingung, dass $x$ eine [Tiefpunkt](/konzepte/extremum) ist, ist:
$$
f'(x)=0 \textrm{ und } f''(x)>0
$$

2. Die erste Ableitung der Funktion $f(x)$ gleichgesetzt mit null liefert alle möglichen Kandidaten für ein Extrema (entweder [Faktorisieren](/konzepte/faktorisieren) oder mit [quadratischer Lösungsformel](/konzepte/quadratische-loesungsformel) lösen):
$$
\begin{align}
&f'(x)=\frac{3}{5}x^2-\frac{6}{5}x-\frac{9}{5}=0 \\
&\rightarrow x^2-2x-3=0 \\
&\rightarrow (x-3)(x+1)=0 \\
&\rightarrow x=-1, +3
\end{align}
$$

3. Um zu entscheiden, ob es sich um einen Hoch- oder Tiefpunkt handelt, muss die zweite Ableitung berechnet werden
$$
f''(x)=\frac{6}{5}(x-1)
$$

4. ... und die Werte $x=-1, +3$ eingesetzt werden
$$
\begin{align}
x=-1 &\rightarrow f''(-1)=\frac{-12}{5}<0 &&\rightarrow \textrm{Hochpunkt} \\
x=3 &\rightarrow f''(3)=\frac{12}{5}>0 &&\rightarrow \textrm{Tiefpunkt}
\end{align}
$$

5. Die $x$-Koordinate ist für beide Extrema bestimmt, die $y$-Koordinate wird mit Hilfe der Funktion $f(x)$ bestimmt:
$$
\begin{align}
x=-1 &\rightarrow f(-1)=\frac{7}{5} &\rightarrow H(-1|\frac{7}{5}) \\
x=3 &\rightarrow f(3)=-5 &\rightarrow T(3|-5)
\end{align}
$$

##### Wendepunkt
1. Die Bedingung, dass $x$ eine [Wendepunkt](/konzepte/wendepunkt) ist, ist:
$$
f''(x)=0 \textrm{ und } f'''(x) \ne 0
$$

2. Die zweite Ableitung gleich null gesetzt liefert einen Kandidaten für den Wendepunkt
$$
f''(x)=\frac{6}{5}(x-1)=0 \rightarrow x=1
$$

3. Überprüfung mit Hilfe der dritten Ableitung, ob wirklich ein Wendepunkt vorliegt:
$$
f'''(x)=\frac{6}{5} \rightarrow f'''(1) \ne 0 \rightarrow \textrm{Wendepunkt}
$$

4. Die $x$-Koordinate des Wendepunktes ist bestimmt, die $y$-Koordinate wird mit Hilfe der Funktion $f(x)$ bestimmt:
$$
x=1 \rightarrow f(1)=-\frac{9}{5} \rightarrow W(1|-\frac{9}{5})
$$

##### Skizze
![Nullpunkte, Hoch-und-Tiefpunkte, Wendepunkte eines Polynoms](Nullpunkte-Hoch-und-Tiefpunkte-Wendepunkte.png?resize=400,400&class=float-right)
Mit Hilfe der oben bestimmten Punkte, lässt sich der Graph der Funktion skizzieren.
- Nullpunkte in rot
- Hoch- und Tiefpunkt in grün
- Wendepunkt in blau

([Download des Geogebra-Dokuments](exercise-6.ggb))

[/details]