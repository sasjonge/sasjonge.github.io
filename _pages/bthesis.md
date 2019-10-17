---
title: "Subsumtionstest mittels SAT-Solver fur eine leichtgewichtige Beschreibungslogik mit Funktionalität"
permalink: /bthesis.html
---

The thesis is in german, but an abstract in english can be found below.

[Download the thesis here!](https://github.com/sasjonge/sasjonge.github.io/raw/master/files/ba_report.pdf)

Abstrakt
======

In seiner Thesis "Complexity of Subsumtion in Extensions of $\mathcal{E}\mathcal{L}$" hat Haase (2007) verschiedene Erweiterungen der Beschreibungslogik $\mathcal{E}\mathcal{L}$ diskutiert und dabei unter anderem für die Erweiterung um globale Fuktionalität ($\mathcal{E}\mathcal{L}^\mathcal{F}$) von Rollen gezeigt, dass Subsumtion bezüglich azyklischen TBoxen Co-NP-vollständig ist.

In dieser Arbeit wird das Subsumtionsproblem für $\mathcal{E}\mathcal{L}^\mathcal{F}$ auf das Erfüllbarkeitsproblem der Aussagenlogik reduziert um so einen Reasoner zu implementieren, der den "schweren" Teil an einen SAT-Solver auslagert. Dabei wird in dieser Arbeit zunächst die Reduktion beschrieben. Danach wird auf die Implementierung des Reasoner eingegangen, der einzelne Subsumtionen mithilfe von SAT-Solvern entscheiden kann. Zum Schluss vergleichen wir den hier implementierten Reasoner mit bereits existierenden Tableau- und Konsequenz-basierten Reasonern.

Um den implementierten Reasoner zur vollständigen Klassifikation einer Ontologie in $\mathcal{E}\mathcal{L}^\mathcal{F}$ nutzen zu können, werden weitere Optimierungen benötigt, die in dieser Thesis skizziert werden.

Abstract
======

In his thesis "Complexity of Subsumtion in Extensions of $\mathcal{E}\mathcal{L}$" Haase (2007) discussed various extensions of the description logic $\mathcal{E}\mathcal{L}$. The thesis shows that subsumption is intractable for, amongst others, the extension by global functionality ($\mathcal{E}\mathcal{L}^\mathcal{F}$) wrt. acyclic TBoxes.

This thesis shows, that it is possible to reduce subsumtion for $\mathcal{E}\mathcal{L}^\mathcal{F}$, and to implement a reasoner to decide subsumption, using a SAT-Solver for the "hard" part of the decision. In the first part we describe the reduction. Afterwards we discuss the implementation of the reasoner, which can decide single subsumptions with the help of SAT-Solver. Finally we compare the runtime of our implemented Reasoner with Tableau-based and consequence-based Reasoner.

Further optimizations, that are described in this thesis, are needed to use the implemented reasoner for the classification of an ontology in $\mathcal{E}\mathcal{L}^\mathcal{F}$.

Source
=======

Haase, C. (2007). Complexity of Subsumption in Extensions of EL. Diplom thesis, TU Dresden.