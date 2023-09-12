---
title: 'Kräfte beim Tennis'
taxonomy:
	id: 2023082217082823
	set: 

	requires_physik: ['Impuls','Kraftstoss','mittlere Kraft','Si-Einheit','Delta-Schreibweise']
	requires_mathematik: []

	category: ['exercises']
	fach: Physik
	thema: ['Impuls','Kraftstoss']
	art: ['Abschätzung','Recherche','Berechnung']
	needsSupport: 0
	needsTool: 0

	hints: 1
	bloom: 
	schritte: 9
	schwierigkeit: 3
	realitaet: 2
	kat_bruder:
	kat_proz_konz: 

	autor: 'Thomas'
	version: 20230905
	source: 'Thomas Bisig, thomas@akademix.ch'
	learning-objective: ''
	content-type: 'markdown'
	media: 'https://www.youtube.com/watch?v=VHV1YbeznCo'
	licence: 'CC BY-SA 4.0'

	status_tags: 1
	status_exercise: 1
	status_solution: 1

	todo: []

routes:
  aliases:
    - '/aufgaben/2023082217082823'

mathjax:
  process: true
---

![video.mov](tennis-hit.mp4?controls=0&autoplay=0&muted&resize=400,250&class=float-right)
1. Schätze die auf den Tennisball wirkende Kraft im Video ([142mph Serve - Racquet hits the ball 6000fps Super slow motion](https://www.youtube.com/watch?v=VHV1YbeznCo)) ab.

2. Handelt es sich um eine konstant oder nicht-konstant wirkende Kraft? Wie schätzt du deine Berechnung im ersten Teil ein?

[details="Tipp zum Vorgehen" class="tipp"]
- Entnimm alle Informationen aus dem Videotitel.
- Rechne die Informationen in SI-Einheiten um.
- Zähle die 'Frames' in welchen der Ball und der Schläger in Kontakt sind und berechne daraus die Kontaktzeit.
- Finde online die Masse eines Tennisballs.
- Nutze die Formel für den Kraftstoss zur Berechnung der Kraft.
[/details]

[details="Lösung" class="loesung"]
**Antwort**: $\approx 1200-1700\,N$

**Lösungsidee**: Wir bestimmen alle Grössen, welche zur Berechnung der Kraft $\overline{F}$ mit Hilfe des [Kraftstosses](/konzepte/kraftstoss) $\Delta p=\overline{F}\cdot \Delta t$ benötigt werden.

**Lösungsweg**:
##### Teil 1

1. Information sammeln: Die Informationen aus dem Videotitel sind die Geschwindigkeit $v_\textrm{Ende}=142 mph$ und die Anzahl 'Frames pro Sekunde' ($6000$).

2. Kontaktzeit $\Delta t$: Die Anzahl 'Frames' (einzelne Bilder), in welchen der Ball im Kontakt ist mit dem Schläger ist $13-18$. Wir nutzen $15$ Frames um weiterzurechnen.
Da $6000$ Frames eine Sekunde ergeben entsprechen $15$ Frames:

$$
\begin{align}
\Delta t&=\frac{15}{6000}\,s \\
&=0.0025\,s \\
&=2.5\cdot 10^{-3}\,s
\end{align}
$$

3. Endgeschwindigkeit: Die Geschwindigkeit ist in 'Miles per Second' angegeben, [umgerechnet](/konzepte/si-einheit) in 'Meter pro Sekunde' ergibt sich:

$$
\begin{align}
v_\textrm{Ende}&=142 \cdot \frac{\textrm{Miles}}{\textrm{Hour}} \\
&=142 \cdot \frac{\textrm{1609}\,m}{\textrm{3600}\,s} \\
&\approx 63.47\,\frac{m}{s}
\end{align}
$$

4. Anfangsgeschwindigkeit: Da der Ball zu Beginn in Ruhe ist, ist $v_\textrm{Start}=0\,\frac{m}{s}$.

5. Masse des Tennisballs: Die [Masse des Tennisballs](https://de.wikipedia.org/wiki/Tennisball) ist ungefähr $m=57.5\,g=0.0575\,kg$

6. [Impuls](/konzepte/impuls)änderung $\Delta p$: ist dann

$$
\begin{align}
\Delta p &= m\cdot v_\textrm{Ende}-m\cdot v_\textrm{Start} \\
&\approx 0.0575\,kg\cdot63.47\,\frac{m}{s}-0.0575\,kg\cdot0\,\frac{m}{s} \\
&\approx 0.0575\,kg \cdot 63.47\,\frac{m}{s} \\
&\approx 3.65\,Ns
\end{align}
$$

7. [Mittlere Kraft](/konzepte/mittlere-kraft) $\overline{F}$: Mit der Impuls[änderung](/konzepte/delta-schreibweise) $\Delta p$ und der Kontaktzeit $\Delta t$ wird die mittlere Kraft zu

$$
\begin{align}
\overline{F}&=\frac{\Delta p}{\Delta t} \\
&\approx\frac{3.65\,Ns}{2.5\cdot 10^{-3}} \\
&\approx 1460\,N
\end{align}
$$

8. Um ein Maximum und Minimum des Kraftstosses zu finden, berechnen wir noch die Fälle
- mit $13$ Frames: ergibt sich eine mittlere Kraft von $\approx 1684\,N$
- mit $18$ Frames: ergibt sich eine mittlere Kraft von $\approx 1216\,N$

##### Teil 2
Die Kraft ist nicht-konstant: die Kraft steigt von $0$ (beim Erstkontakt) auf ein Maximum an und sinkt dann wieder. Daraus folgt, dass die maximale Kraft (vermutlich) höher ist, als die berechnete mittlere Kraft auf den Ball bzw. den Tennisschläger.

##### Hintergrund
[https://laughingsquid.com/a-143-mph-tennis-serve-filmed-at-6000-frames-per-second/]

[/details]