---
title: "Ontology Partitioning using E-Connections: Revisited"
permalink: /mthesis.html
---

[Download the thesis here!](https://github.com/sasjonge/sasjonge.github.io/raw/master/files/ma_report.pdf)

Abstract
======

Modularity of ontologies has received increased attention in the past. For ontologies,
methods for extracting a module and also methods for decomposing an ontology into
several parts were developed. So far, many and also successful module extraction meth-
ods have been investigated, whereas only a few and often less successful decomposition
methods have been investigated. In this thesis, we investigate the decomposition method
“Partitioning using E-connections”, which was first introduced by Cuenca Grau et al.
(2005, 2006). During our investigation of the existing notation, algorithm, and imple-
mentation, we developed a simplified notation and extended it to the full OWL 2, with
the exception of the universal role. In this thesis, we develop a new, conceptually much
simpler algorithm that runs in a linear rather than the original quadratic runtime. The
algorithm is deterministic and allows simplified proofs of correctness and maximality. To
test partitioning using E-connections, we implement the algorithm in Java and evaluate
it on a large and diverse established corpus of biomedical ontologies. It turns out that
the algorithm is fast in practice, but for “usable” decompositions, one needs heuristics in
most cases, which we develop and investigate in this thesis. Furthermore, we investigate
the transfer of partitioning using E-connections to other fragments of First-Order Logic.

Source
=======

Cuenca Grau, B., Parsia, B., and Sirin, E. (2009b). Ontology integration using E-
Connections. In Stuckenschmidt et al. (2009), pages 293–320.

Cuenca Grau, B., Parsia, B., Sirin, E., and Kalyanpur, A. (2005). Automatic partitioning
of OWL ontologies using E-Connections. In Proc. of DL-05, volume 147 of CEUR-
WS.org.