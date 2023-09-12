---
title: 'Ball prallt gegen Wand'
taxonomy:
	id: 2023082217023334
	set: 

	requires_physik: ['Kraftstoss','Impuls']
	requires_mathematik: ['Wissenschaftliche Schreibweise','vektorielle Grösse']

	category: ['exercises']
	fach: Physik
	thema: ['Impuls','Kraftstoss']
	art: ['Berechnung']
	needsSupport: 0
	needsTool: 0

	hints: 0
	bloom: 
	schritte: 8
	schwierigkeit: 2
	realitaet: 1
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230822
	source: 'Thomas Bisig, thomas@akademix.ch'
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
    - '/aufgaben/2023082217023334'

mathjax:
  process: true
---
![Fangen mit gestreckten und gebeugten Armen](ball-trifft-auf-wand.svg?resize=400,200&class=float-right)
Du schiesst einen Ball der Masse $m=0.4\,kg$ gegen eine Wand. Der Ball bewegt sich horizontal nach links mit einer Geschwindigkeit von $30\,m/s$ beim Auftreffen auf die Wand. Der Ball wird horizontal nach rechts zurückgeworfen mit einer Geschwindigkeit von $20\,m/s$. 

1. Wie gross ist die Kraft auf die Wand, wenn der Ball $10^{-2}\,s$ im Kontakt ist mit der Wand?
2. Wo geht der "fehlende" Impuls hin?


[details="Tipp zum Vorgehen" class="tipp"]
- Fertige je eine Skizze mit Geschwindigkeitsvektor an
- Bestimme die Geschwindigkeitsänderung und daraus die Impulsänderung
- Berechne die auf die Wand wirkende Kraft
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
je nach Wahl der Richung: $2000\,N$ oder $-2000\,N$

**Lösungsidee**: Da der Impuls eine vektorielle Grösse ist, müssen wir die Bewegungsrichtung mit berücksichtigen. Mit der Impulsänderung, kann die Kraft auf die Wand berechnet werden.

**Lösungsweg**:

![Fangen mit gestreckten und gebeugten Armen](ball-trifft-auf-wand-und-prallt-ab.svg?resize=400,400&class=float-right)
In dieser Aufgabe ändert sich der [Impuls](/konzepte/impuls), somit wirkt eine Kraft.

##### Teil 1
1. Wir nehmen an, die wirkende Kraft während dem Abbremsen sei konstant.

2. Die Formel für den [Kraftstoss](/konzepte/kraftstoss) bei konstanter Kraft lautet
$$
\Delta p = F \cdot \Delta t
$$

3. Da wir an der Kraft interessiert sind, ergibt sich
$$
F = \frac{\Delta p}{\Delta t}
$$

4. In dieser Aufgabe ändert sich die Richtung des Balls. Deswegen müssen wir den Impuls als vektorielle Grösse betrachten und in einem Koordinatensystem arbeiten. Dh dass wir eine Richtung als positive Richtung wählen müssen. Wir wählen die einfallende Richtung (nach links) als positive Richtung, somit wird der zurückgeworfene Ball in die negative Richtung fliegen.

5. Dadurch sind die zwei Geschwindigkeiten gegeben als $v_\textrm{Start}=30\,\frac{m}{s}$ und $v_\textrm{Ende}=-20\,\frac{m}{s}$.

6. Die Impuls[differenz](/konzepte/delta-schreibweise) $\Delta p=p_\textrm{Ende}-p_\textrm{Start}$ beträgt
$$
\begin{align}
\Delta p&=p_\textrm{Ende}-p_\textrm{Start} \\
&=m\cdot v_\textrm{Ende}-m\cdot v_\textrm{Start} \\
&=0.4\,kg \cdot (-20\,\frac{m}{s})-0.4\,kg \cdot 30\,\frac{m}{s}=-20\,Ns
\end{align}
$$

7. Einsetzen in die Formel aus (3) ergibt
$$
F = \frac{\Delta p}{\Delta t}=\frac{-20\,Ns}{0.01\,s}=-2000\,N
$$

8. Die berechnete Kraft ist die Kraft, welche die Wand auf den Ball ausübt und ihn so zur Richtungs- bzw. Impulsänderung zwingt. Diese Kraft zeigt nach rechts (negative Richtung), was Sinn ergibt, denn der Ball ändert seine Bewegung von einer Rechts- in eine Linksbewegung. Die Kraft, welche der Ball auf die Wand ausübt ist, ist nach dem [dritten Gesetz von Newton](/konzepte/newtons-drittes-gesetz) $\underline{2000\,Ns}$.


##### Teil 2
Die Wand nimmt den Impuls 'auf'. Da sie schwer ist, ist die Bewegung der Wand (bzw. das Vibrieren) nicht wahrzunehmen.
[/details]