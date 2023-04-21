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
	version: 20230419
	source: 'Idee: University Physics 14th edition, angepasst und erweitert'
	learning-objective: ''
	content-type: markdown
	media: 'https://de.wikipedia.org/wiki/Seismische_Wellen#/media/Datei:Ondes_P_et_S_1d_30_petit.gif'
	licence: 'CC BY-SA 4.0'

	status_tags: review_0
	status_exercise: review_0
	status_solution: review_0

	todo: []

mathjax:
  process: true
---
![Primär und Sekundärwellen breiten sich mit unterschiedlicher Geschwindigkeit aus](Ondes_P_et_S_1d_30_petit.gif?resize=400,300&class=float-right) Erdbeben erzeugen mehrere Arten von Schockwellen. Die bekanntesten sind die _P-Wellen_ (primär oder pressure) und die _S-Wellen_ (sekundär oder Scherung).

In der Erdkruste bewegen sich die P-Wellen mit etwa $6.5\,\frac{km}{s}$ und die S-Wellen mit etwa $3.5\,\frac{km}{s}$. Die Zeitverzögerung zwischen dem Eintreffen dieser beiden Wellen an einer seismischen Aufzeichnungsstation gibt Geologen Aufschluss darüber, wie weit ein Erdbeben entfernt war.

1. Wenn die Zeitverzögerung $17\,s$ beträgt, wie weit entfernt von der seismischen Station hat sich das Erdbeben ereignet?

2. Verallgemeinere die Berechnung und leite daraus eine Faustregel ab, welche die Entfernung pro gemessener Sekunde abschätzt.

[details="Tipp zum Vorgehen Teil 1" class="tipp"]
- Stelle für beide Wellen eine korrekt Gleichung für die Entfernung auf. Bezeichne alle Grössen mit Variablen.
- Nutze die Informationen aus dem Text um Variablen zu eliminieren.
- Löse das Gleichungssystem.
[/details]

[details="Tipp zum Vorgehen Teil 2" class="tipp"]
Ersetze die $17\,s$ der vorhergehenden Aufgabe mit der Variablen $a$ und führe die Herleitung analog durch.
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
1. $128.9\,km$
2. Pro Sekunde Zeitdifferenz eine Distanz von $\approx 7.6\,km$.

**Lösungsidee**: Die zwei Wellenausbreitungen entsprechen zwei Gleichungen mit zwei Unbekannten, welche gemeinsam gelöst werden können.

**Lösungsweg**:
Der Index $P$ bezeichnet die Grössen für **P**-Wellen, der Index $S$ bezeichnet die Grössen für die **S**-Wellen.

_Teil 1_

1. Die zwei Gleichungen können mit Hilfe der [Definition der mittleren Geschwindigkeit](../../../../../konzepte/konzept-1) wie folgt aufgestellt werden:

$$
\Delta x_P=v_P\cdot \Delta t_P\\
\Delta x_S=v_S\cdot \Delta t_S\\
$$

2. Die mittleren Geschwindigkeiten können für beide Fahrten direkt eingesetzt werden:

$$
\Delta x_P=6.5\,\frac{km}{s}\cdot \Delta t_P\\
\Delta x_S=3.5\,\frac{km}{s}\cdot \Delta t_S\\
$$

3. Die von den Wellen zurückgelegte Strecke ist  in beiden Fällen dieselbe. Daraus folgt, dass $\Delta x_P=\Delta x_S$ bzw. dass die [zwei Gleichungen können gleichgesetzt](../../../../../konzepte/konzept-1) werden:

$$
6.5\,\frac{km}{s}\cdot \Delta t_P=3.5\,\frac{km}{s}\cdot \Delta t_S
$$

4. Mit der Zusatzinformation, dass die S-Wellen mit einer Verzögerung von $17\,s$ eintreffen

$$
\Delta t_S=\Delta t_P+17\,s
$$

erhalten wir eine Gleichung mit der einzigen Unbekannten $\Delta t_P$:

$$
6.5\,\frac{km}{s}\cdot \Delta t_P=3.5\,\frac{km}{s}\cdot (\Delta t_P+17\,s)
$$

5. Lösen der Gleichung nach $\Delta t_P$ (die Einheiten werden der Übersicht halber weggelassen):

$$
\begin{align}
6.5 \cdot \Delta t_P & = 3.5 \cdot (\Delta t_P+17)\\

6.5 \cdot \Delta t_P & = 3.5 \cdot \Delta t_P + 3.5 \cdot 17 \\

6.5 \cdot \Delta t_P - 3.5 \cdot \Delta t_P & = 3.5 \cdot 17 \\

\Delta t_P \cdot (6.5-3.5) & = 59.5 \\

3 \cdot \Delta t_P & = 59.5\\

\Delta t_P & =\frac{59.5}{3} \\

\Delta t_P & \approx 19.8\overline{3}\,s
\end{align}
$$


6. Einsetzen in die erste Gleichung des ursprünglichen Gleichungssystems

$$
\Delta x_P=6.5\,\frac{km}{s}\cdot \Delta t_P
$$

liefert

$$
\Delta x_P=6.5\,\frac{km}{s}\cdot 19.8\overline{3}\,s \approx \underline{128.9\,km}
$$

_Teil 2_

1. Wir ersetzen die Verzögerung von $17\,s$ mit der Variablen $a$, die in Sekunden gemessen wird. Damit findet sich analog zu obiger Herleitung:

$$
\begin{align}
\rightarrow 6.5 \cdot \Delta t_P & = 3.5 \cdot (\Delta t_P+a)\\

\rightarrow 6.5 \cdot \Delta t_P & = 3.5 \cdot \Delta t_P + 3.5 \cdot a \\

\rightarrow 6.5 \cdot \Delta t_P - 3.5 \cdot \Delta t_P & = 3.5 \cdot a \\

\rightarrow \Delta t_P \cdot (6.5-3.5) & = 3.5\cdot a \\

\rightarrow 3 \cdot \Delta t_P & = 3.5\cdot a\\

\rightarrow \Delta t_P & =\frac{3.5\cdot a}{3} \\

\rightarrow \Delta t_P & =\frac{3.5}{3} \cdot a
\end{align}
$$

2. Einsetzen in die erste Gleichung des ursprünglichen Gleichungssystems

$$
\Delta x_P=6.5\,\frac{km}{s}\cdot \Delta t_P
$$

liefert

$$
\Delta x_P=6.5\,\frac{km}{s}\cdot (\frac{3.5}{3} \cdot a)\approx 7.6\cdot a
$$

Pro gezählter Sekunde ab Eintreffen der Primärwellen befindet sich das Zentrum des Erdbebens in einer Entfernung von $\approx 7.6\,km$.

_Alternative zu Teil 2_

Da es sich beim Zusammenhang $\Delta s=v\cdot \Delta t$ um einen linearen Zusammenhang handelt, kann direkt aus dem ersten Teil geschlossen werden, dass wenn eine Zeitdifferenz von $17\,s$ einer Distanz von $128.9\,km$ entsprichen, $1\,s$ einer Distanz von $7.6\,km$ entspricht.

[/details]