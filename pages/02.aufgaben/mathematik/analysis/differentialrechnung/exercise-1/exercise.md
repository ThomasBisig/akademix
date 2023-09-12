---
title: Kurvendiskussion eines Polynoms
taxonomy:
	id: 2023091118233324
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
    - '/aufgaben/2023091118233324'

mathjax:
  process: true
---
1. Bestimme für die Funktion $f(x)$ alle Nullpunkte, Extrema (Hoch- und Tiefpunkte) und Wendepunkte.
$$
f(x)=\frac{1}{3}x^3-4x-\frac{11}{3}
$$

2. Skizziere den Graphen $f(x)$


[details="Tipp zum Vorgehen" class="tipp"]
- Finde in deiner Formelsammlung zuerst die Bedingungen für die gesuchten Punkte.
- Leite dann die Funktion (mindestens) zwei Mal ab.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
![Nullpunkte, Hoch-und-Tiefpunkte, Wendepunkte eines Polynoms](Nullpunkte-Hoch-und-Tiefpunkte-Wendepunkte.png?resize=200,200&class=float-right) 
- $N(-1|0)$, $N(3.854|0)$, $N(-2.854|0)$
- $H(-2|\frac{5}{3})$, $T(2|-9)$
- $W(0|-\frac{11}{3})$

**Lösungsidee**: Die Bedingungen für die gesuchten Punkte ergeben Gleichungen, welche einzeln gelöst werden.

**Lösungsweg**:

##### Nullpunkte
1. Bedingung, dass $x$ eine [Nullpunkte](/konzepte/nullpunkte) ist, ist:
$$
f(x)=0 \rightarrow \frac{1}{3}x^3-4x-\frac{11}{3} = 0
$$

2. Mit Hilfe des Taschenrechners (_polysolve_) ergeben sich drei Nullpunkte:
$$
N(-1|0), N(3.854|0), N(-2.854|0)
$$

Alternative ohne Taschenrechner: Durch [Faktorisierung](/konzepte/faktorisieren) der Funktion ergibt sich
$$
\frac{1}{3}(x+1)(x^2-x-11)=0
$$
Diese Gleichung kann mit Hilfe der [quadratischen Lösungsformel](/konzepte/quadratische-loesungsformel) gelöst werden.

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
&f'(x)=x^2-4=0  \\
&\rightarrow (x+2)(x-2)=0 \\
&\rightarrow x=\pm 2
\end{align}
$$

3. Um zu entscheiden, ob es sich um einen Hoch- oder Tiefpunkt handelt, muss die zweite Ableitung berechnet werden
$$
f''(x)=2x
$$

4. ... und die Werte $x=\pm 2$ eingesetzt werden
$$
\begin{align}
x=2 &\rightarrow f''(2)=4>0 &&\rightarrow \textrm{Tiefpunkt} \\
x=-2 &\rightarrow f''(-2)=-4<0 &&\rightarrow \textrm{Hochpunkt}
\end{align}
$$

5. Die $x$-Koordinate ist für beide Extrema bestimmt, die $y$-Koordinate wird mit Hilfe der Funktion $f(x)$ bestimmt:
$$
\begin{align}
x=2 &\rightarrow f(2)=-9 &\rightarrow T(2|-9) \\
x=-2 &\rightarrow f(-2)=\frac{5}{3} &\rightarrow H(-2|\frac{5}{3})
\end{align}
$$

##### Wendepunkt
1. Die Bedingung, dass $x$ eine [Wendepunkt](/konzepte/wendepunkt) ist, ist:
$$
f''(x)=0 \textrm{ und } f'''(x) \ne 0
$$

2. Die zweite Ableitung gleich null gesetzt liefert einen Kandidaten für den Wendepunkt
$$
f''(x)=2x=0 \rightarrow x=0
$$

3. Überprüfung mit Hilfe der dritten Ableitung, ob wirklich ein Wendepunkt vorliegt:
$$
f'''(x)=2 \rightarrow f'''(0) \ne 0 \rightarrow \textrm{Wendepunkt}
$$

4. Die $x$-Koordinate des Wendepunktes ist bestimmt, die $y$-Koordinate wird mit Hilfe der Funktion $f(x)$ bestimmt:
$$
x=0 \rightarrow f(0)=-\frac{11}{3} \rightarrow W(2|-\frac{11}{3})
$$

##### Skizze
![Nullpunkte, Hoch-und-Tiefpunkte, Wendepunkte eines Polynoms](Nullpunkte-Hoch-und-Tiefpunkte-Wendepunkte.png?resize=400,400&class=float-right) 
Mit Hilfe der oben bestimmten Punkte, lässt sich der Graph der Funktion skizzieren.
- Nullpunkte in rot
- Hoch- und Tiefpunkt in grün
- Wendepunkt in blau

([Download des Geogebra-Dokuments](exercise-5.ggb))

[/details]