---
title: 'Auto putzen'
taxonomy:
	id: 2023082217030917
	set: 

	requires_physik: ['Kraftstoss','Impuls','Delta-Schreibweise']
	requires_mathematik: []

	category: ['exercises']
	fach: Physik
	thema: ['Impuls','Kraftstoss']
	art: ['Berechnung']
	needsSupport: 0
	needsTool: 0

	hints: 1
	bloom: 
	schritte: 9
	schwierigkeit: 2
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230828
	source: 'Giancoli Physik, Thomas Bisig, tbisig@pm.me'
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
    - '/aufgaben/2023082217030917'

mathjax:
  process: true
---

Aus einem Schlauch spritzen $1.5\,\frac{kg}{s}$ Wasser mit einer Geschwindigkeit von $20\,\frac{m}{s}$. Der Strahl ist auf die Seite eines Autos gerichtet. Die Seite des Autos stoppt das Wasser.
1. Wie gross ist die Kraft, die das Wasser auf das Auto ausübt?
2. Wie würde sich diese Kraft verändern, wenn das Wasser mit derselben Geschwindigkeit wieder zurückgeworfen werden würde?

[details="Tipp zum Vorgehen" class="tipp"]
- Fertige je eine Skizze mit Geschwindigkeitsvektor an
- Bestimme die Geschwindigkeitsänderung und daraus die Impulsänderung
- Berechne die auf die Wand wirkende Kraft
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
je nach Wahl der Richtungsachse ergibt sich 
- Teil 1: $30\,N$ oder $-30\,N$
- Teil 2: $60\,N$ oder $-60\,N$

**Lösungsidee**: Berechnung der Impulsänderung liefert die Kraft.

**Lösungsweg**:

In dieser Aufgabe ändert sich der [Impuls](/konzepte/impuls), somit wirkt eine Kraft.

##### Teil 1
1. Die Formel für den [Kraftstoss](/konzepte/kraftstoss) bei konstanter Kraft lautet
$$
\Delta p = F \cdot \Delta t
$$

2. Da wir an der Kraft interessiert sind, ergibt sich
$$
F = \frac{\Delta p}{\Delta t}
$$

3. Die Geschwindigkeit des Wasser ändert sich von $v_\textrm{Start}=20\,\frac{m}{s}$ zu $v_\textrm{Ende}=0\,\frac{m}{s}$. Die Impuls[änderung](/konzepte/delta-schreibweise) für $1.5\,kg$ Wasser ist demnach

$$
\begin{align}
\Delta p &= p_\textrm{Ende} - p_\textrm{Start} \\
&=m\cdot v_\textrm{Ende} - m \cdot v_\textrm{Start}\\
&=1.5 kg \cdot 0\,\frac{m}{s}-1.5 kg \cdot 20\,\frac{m}{s} \\
&=-30\,Ns
\end{align}
$$

4. Einsetzen (pro Sekunde) in (2) liefert

$$
F = \frac{\Delta p}{\Delta t}=\frac{-30\,Ns}{1\,s}=-30\,N
$$

5. Was bedeutet es, dass die Kraft negativ ist? Der Kraftstoss, den das Wasser erfährt um seine Richtung zu ändern, zeigt in die negative Richtung. Das Auto erfährt demnach einen Kraftstoss von $\underline{30\,N}$, wegen [Newton's drittem Gesetz](/konzepte/newtons-drittes-gesetz).

##### Teil 2
1. In dieser Aufgabe ändert sich die Richtung des Wassers. Deswegen müssen wir den Impuls als vektorielle Grösse betrachten und in einem Koordinatensystem arbeiten. Dh dass wir eine Richtung als positive Richtung wählen müssen. Wir wählen die Richtung, in welcher das Wasser auf das Auto trifft, als positive Richtung, somit wird das zurückgeworfene Wasser in die negative Richtung fliegen.

2. Dadurch sind die zwei Geschwindigkeiten gegeben als $v_\textrm{Start}=20\,\frac{m}{s}$ und $v_\textrm{Ende}=-20\,m/s$. Die Impulsänderung für $1.5\,kg$ Wasser ist demnach

$$
\begin{align}
\Delta p &= p_\textrm{Ende} - p_\textrm{Start} \\
&=m\cdot v_\textrm{Ende} - m \cdot v_\textrm{Start} \\
&=1.5 kg \cdot (-20\,\frac{m}{s})-1.5 kg \cdot 20\,\frac{m}{s} \\
&=-60\,Ns
\end{align}
$$

3. Einsetzen (pro Sekunde) liefert

$$
F = \frac{\Delta p}{\Delta t}=\frac{-60\,Ns}{1\,s}=-60\,N
$$

4. Was bedeutet es, dass die Kraft negativ ist? Der Kraftstoss, den das Wasser erfährt um seine Richtung zu ändern, zeigt in die negative Richtung. Das Auto erfährt demnach einen Kraftstoss von $\underline{60\,N}$, wegen [Newton's drittem Gesetz](/konzepte/newtons-drittes-gesetz).

[/details]