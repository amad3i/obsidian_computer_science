---
title: "Construction and Analysis of Distributed Processes"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Construction_and_Analysis_of_Distributed_Processes"
wikipedia_categories: ["Concurrency (computer science)"]
related: ["[[Active object]]", "[[Balking pattern]]", "[[Barrier (computer science)]]", "[[Concurrency (computer science)]]", "[[Concurrency pattern]]", "[[Concurrency semantics]]", "[[E-LOTOS]]", "[[Hennessy–Milner logic]]", "[[History monoid]]", "[[Kim Guldstrand Larsen]]"]
---

# Construction and Analysis of Distributed Processes

CADP (Construction and Analysis of Distributed Processes) is a toolbox for the design of communication protocols and distributed systems. CADP  is developed by the CONVECS team (formerly by the VASY team) at INRIA Rhone-Alpes and connected to various complementary tools. CADP is maintained, regularly improved, and used in many industrial projects.
The purpose of the CADP toolkit is to facilitate the design of reliable systems by use of formal description techniques together with software tools for simulation, rapid application development, verification, and test generation.
CADP can be applied to any system that comprises asynchronous concurrency, i.e., any system whose behavior can be modeled as a set of parallel processes governed by interleaving semantics. Therefore, CADP can be used to design hardware architecture, distributed algorithms, telecommunications protocols, etc.
The enumerative verification (also known as explicit state verification) techniques implemented in CADP, though less general than theorem proving, enable an automatic, cost-efficient detection of design errors in complex systems.
CADP includes tools to support use of two approaches in formal methods, both of which are needed for reliable systems design:

Models provide mathematical representations for parallel programs and related verification problems. Examples of models are automata, networks of communicating automata, Petri nets, binary decision diagrams, boolean equation systems, etc. From a theoretical point of view, research on models seeks for general results, independent of any particular description language.
In practice, models are often too elementary to describe complex systems directly (this would be tedious and error-prone). A higher level formalism known as process algebra or process calculus is needed for this task, as well as compilers that translate high-level descriptions into models suitable for verification algorithms.

## Related

- [[Active object]]
- [[Balking pattern]]
- [[Barrier (computer science)]]
- [[Concurrency (computer science)]]
- [[Concurrency pattern]]
- [[Concurrency semantics]]
- [[E-LOTOS]]
- [[Hennessy–Milner logic]]
- [[History monoid]]
- [[Kim Guldstrand Larsen]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Construction_and_Analysis_of_Distributed_Processes