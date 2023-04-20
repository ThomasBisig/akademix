---
title: Abstandsanalyse
taxonomy:
	id: 2023041617171733
	set: 0202304161717889

	requires_physik: [Mittlere Geschwindigkeit, SI-Einheit]
	requires_mathematik: [Gleichungssystem]

	category: exercises
	fach: Physik
	thema: [Mechanik, Bewegung, Gleichförmige Bewegung]
	art: Berechnung
	needsSupport: 0
	needsTool: 0

	hints: 4
	detail: 0
	bloom: 2
	schritte: 5
	schwierigkeit: 3
	realitaet: 
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230416
	source: 'neu, thomas@akademix.ch'
	learning-objective: ''
	content-type: markdown
	media: 'https://commons.wikimedia.org/wiki/File:Lightning_NOAA.jpg'
	licence: 'CC BY-SA 4.0'

	status_tags: review_0
	status_exercise: review_0
	status_solution: review_0

	todo: []

mathjax:
  process: true
---
![Mehrere Wolke-zu-Boden- und Wolke-zu-Wolke-Blitzeinschläge während der Nacht. Beobachtet während eines nächtlichen Gewitters.](Lightning_NOAA.jpg?resize=400,300&class=float-right) In aller Regel tritt ein Blitz während eines Gewitters infolge einer elektrostatischen Aufladung der wolkenbildenden Wassertröpfchen oder der Regentropfen auf. Er wird dabei vom Donner begleitet.

Während der Blitz (bzw. das Blitzlicht) sich mit Lichtgeschwindigkeit vion $3\cdot 10^8\,\frac{km}{s}$ ausbreitet, breitet sich der Schall des Donners mit einer Geschwindigkeit von $340\,\frac{m}{s}$ aus.

Die Zeitverzögerung zwischen dem Eintreffen dieser beiden Signale kann dir Aufschluss darüber geben, wie weit ein Blitz bzw. das dazugehörige Gewitter, entfernt ist.

1. Wenn die Zeitverzögerung $6\,s$ beträgt, wie weit entfernt von dir findet das Gewitter statt?

2. Verallgemeinere die Berechnung und leite daraus eine Faustregel ab, welche die Entfernung pro Zeit abschätzt.

[details="Tipp zum Vorgehen Teil 1" class="tipp"]
- Stelle für beide Wellen eine korrekt Gleichung für die Entfernung auf. Bezeichne alle Grössen mit Variablen.
- Nutze die Informationen aus dem Text um Variablen zu eliminieren.
- Löse das Gleichungssystem.
[/details]

[details="Tipp zum Vorgehen Teil 2" class="tipp"]
Ersetze die $6\,s$ der vorhergehenden Aufgabe mit der Variablen $a$ und führe die Herleitung analog durch.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. $\approx 2\,km$
2. Drei Sekunden entsprechen einem Kilometer

**Lösungsidee**: Die zwei Wellenausbreitungen entsprechen zwei Gleichungen mit zwei Unbekannten, welche gemeinsam gelöst werden können.

**Lösungsweg**:

Der Index $B$ bezeichnet die Grössen für den **B**litz, der Index $D$ bezeichnet die Grössen für den **D**onner.

_Teil 1_

1. Die zwei Gleichungen können mit Hilfe der [Definition der mittleren Geschwindigkeit](../) wie folgt aufgestellt werden:

$$
\Delta x_B=\overline{v_B}\cdot \Delta t_B\\
\Delta x_D=\overline{v_D}\cdot \Delta t_D\\
$$

2. Die mittleren Geschwindigkeiten können für beide Fahrten direkt eingesetzt werden (die Schallgeschwindigkeit umwandeln in $\frac{km}/{s}$):

$$
\Delta x_B=3\cdot 10^8\,\frac{km}{s}\cdot \Delta t_B\\
\Delta x_D=0.34\,\frac{km}{s}\cdot \Delta t_D\\
$$

3. Die von den Wellen zurückgelegte Strecke ist  in beiden Fällen dieselbe. Daraus folgt, dass $\Delta x_B=\Delta x_D$ bzw. dass die [zwei Gleichungen können gleichgesetzt](../) werden:

$$
3\cdot 10^8\,\frac{km}{s}\cdot \Delta t_B=0.34\,\frac{km}{s}\cdot \Delta t_D
$$

4. Mit der Zusatzinformation, dass der Schall des Donners mit einer Verzögerung von [$6\,s$](../) eintrifft

$$
\Delta t_D=\Delta t_B+6\,s
$$

erhalten wir eine Gleichung mit der einzigen Unbekannten $\Delta t_B$:

$$
3\cdot 10^8\,\frac{km}{s}\cdot \Delta t_B=0.34\,\frac{km}{s}\cdot (\Delta t_B+6\,s)
$$

5. Lösen der Gleichung nach $\Delta t_B$ (die Einheiten werden der Übersicht halber weggelassen):

$$
\begin{align}
\rightarrow 3\cdot 10^8 \cdot \Delta t_P & = 0.34 \cdot (\Delta t_P+6)\\

\rightarrow 3\cdot 10^8 \cdot \Delta t_P & = 0.34 \cdot \Delta t_P + 0.34 \cdot 6 \\

\rightarrow 3\cdot 10^8 \cdot \Delta t_P - 0.34 \cdot \Delta t_P & = 0.34 \cdot 6 \\

\rightarrow \Delta t_P \cdot (3\cdot 10^8-0.34) & = 2.04 \\

\rightarrow \Delta t_P & =\frac{2.04}{3\cdot 10^8-0.34} \\

\rightarrow \Delta t_P & \approx 6.8e-9\,s
\end{align}
$$


6. Einsetzen in die erste Gleichung des ursprünglichen Gleichungssystems

$$
\Delta x_B=3\cdot 10^8\,\frac{km}{s}\cdot \Delta t_B
$$

liefert

$$
\Delta x_B=3\cdot 10^8\,\frac{km}{s}\cdot 6.8e-9\,s \approx \underline{2\,km}
$$

_Teil 2_

1. Wir ersetzen die Verzögerung von $6\,s$ mit der Variablen $a$, die in Sekunden gemessen wird. Damit findet sich analog zu obiger Herleitung:

$$
\begin{align}
\rightarrow 3\cdot 10^8 \cdot \Delta t_P & = 0.34 \cdot (\Delta t_P+a)\\

\rightarrow 3\cdot 10^8 \cdot \Delta t_P & = 0.34 \cdot \Delta t_P + 0.34 \cdot a \\

\rightarrow 3\cdot 10^8 \cdot \Delta t_P - 0.34 \cdot \Delta t_P & = 0.34 \cdot a \\

\rightarrow \Delta t_P \cdot (3\cdot 10^8-0.34) & = 0.34 \cdot a \\

\rightarrow \Delta t_P & =\frac{0.34 \cdot a}{3\cdot 10^8-0.34} \\

\rightarrow \Delta t_P & = \frac{0.34}{3\cdot 10^8-0.34} \cdot a
\end{align}
$$

2. Einsetzen in die erste Gleichung des ursprünglichen Gleichungssystems

$$
\Delta x_P=3\cdot 10^8\,\frac{km}{s}\cdot \Delta t_P
$$

liefert

$$
\Delta x_P=3\cdot 10^8\,\frac{km}{s}\cdot (\frac{0.34}{3\cdot 10^8-0.34} \cdot a)\approx a \cdot 0.34\,km
$$

Pro gezählter Sekunde ab Eintreffen des Blitzes befindet sich das Zentrum des Erdbebens in einer Entfernung von $\approx 0.34\,km$: drei Sekunden entsprechen einem Kilometer.

_Alternative zu Teil 2_

Da es sich beim Zusammenhang $\Delta s=\overline{v}\cdot \Delta t$ um einen linearen Zusammenhang handelt, kann direkt aus dem ersten Teil geschlossen werden, dass wenn eine Zeitdifferenz von $6\,s$ einer Distanz von $2\,km$ entspricht, $3\,s$ einer Distanz von $1\,km$ entspricht.

[/details]