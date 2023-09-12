---
title: 'Nicht konstante Kräfte'
taxonomy:
	id: 2023082217075298
	set: 

	requires_physik: ['Kraftstoss','mittlere Kraft']
	requires_mathematik: ['Diagramme']

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
	version: 20230822
	source: 'Thomas Bisig, thomas@akademix.ch'
	learning-objective: ''
	content-type: 'markdown'
	media: 'Thomas Bisig, thomas@akademix.ch'
	licence: 'CC BY-SA 4.0'

	status_tags: 0
	status_exercise: 1
	status_solution: 1

	todo: []

routes:
  aliases:
    - '/aufgaben/2023082217075298'

mathjax:
  process: true
---
![Drei Graphen nicht konstanter Kräfte](nicht-konstante-kraefte.svg?resize=600,400&class=float-right)
Die Kräfte, welche während einem Stoss wirken, sind selten konstant. Vielmehr wird die Kraft in Kollisionen zu Beginn grösser, bis sie ein Maximum erreicht hat, um dann wieder auf null abzuklingen.

Bestimme aus den $t-F$-Diagrammen jeweils die mittlere Kraft $\overline{F}$ und den Kraftstoss.

[details="Tipp zum Vorgehen" class="tipp"]
- Finde die Horizontale (=mittlere Kraft), welche am besten die nicht-konstante Kraft über den gegebenen Zeitraum annähert.
- Bestimme den Kraftstoss
[/details]

[details="Lösung" class="loesung"]
**Antwort**:
- $\overline{F_1}=150\,N \rightarrow \Delta p_1=1500\,Ns$
- $\overline{F_2}=6.5\,N \rightarrow \Delta p_2=5.2\,Ns$
- $\overline{F_3}\approx 19\,N \rightarrow \Delta p_3 \approx 8.55\,Ns$

**Lösungsidee**: Bestimmung der Horizontalen (=mittlere Kraft), welche am besten die nicht-konstante Kraft über den gegebenen Zeitraum annähert. Bestimmung der Zeit der Krafteinwirkung ergibt den Kraftstoss.

**Lösungsweg**:
Herauslesen der Zeitdauer $\Delta t$ und der [mittleren Kraft](/konzepte/mittlere-kraft) $\overline{F}$ aus dem [Diagramm](/konzepte/diagramme) ergeben den [Kraftstoss](/konzepte/kraftstoss) $\Delta p=\overline{F}\cdot \Delta t$

##### Teil 1

1. Angenommen im ersten Teil entspreche die Kraft $100\,N$ und die zwei Kräfte wirken genau gleich lang, ergibt eine mittlere Kraft von
$$
\overline{F_1}=\underline{150\,N}
$$

2. Die Zeit, während der die Kraft wirkt, ist
$$
\Delta t_1=10\,s
$$

3. Somit ergibt sich für den Kraftstoss

$$
\Delta p_1=\overline{F_1}\cdot \Delta t_1=150\,N \cdot 10\,s=\underline{1500\,N}
$$

##### Teil 2
1. Bei einer Geraden entspricht die Horizontale durch die mittlere Höhe der Geraden dem Mittelwert:
$$
\overline{F_2}=\frac{13\,N}{2}=\underline{6.5\,N}
$$

2. Die Zeit, während der die Kraft wirkt, ist
$$
\Delta t_2=0.8\,s
$$

3. Somit ergibt sich für den Kraftstoss

$$
\Delta p_2=\overline{F_2}\cdot \Delta t_2=6.5\,N \cdot 0.8\,s=\underline{5.2\,N}
$$

##### Teil 3
1. Der Mittelwert über den Zeitraum befindet sich etwa auf einem Drittel der Höhe:
$$
\overline{F_3}=\frac{57.1\,N}{3}\approx \underline{19\,N}
$$

2. Die Zeit, während der die Kraft wirkt, ist ungefähr
$$
\Delta t_3 \approx 0.45\,s
$$

3. Somit ergibt sich für den Kraftstoss

$$
\Delta p_3=\overline{F_3}\cdot \Delta t_3 \approx 19\,N \cdot 0.45\,s \approx \underline{8.55\,N}
$$





[/details]