---
title: "Travelling salesman problem"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Travelling_salesman_problem"
wikipedia_categories: ["Combinatorial optimization", "Computational problems in graph theory", "Graph algorithms", "Hamiltonian paths and cycles", "Metaphors referring to people", "NP-complete problems", "NP-hard problems", "Travelling salesman problem"]
related: ["[[Bottleneck traveling salesman problem]]", "[[Graph bandwidth]]", "[[Graph coloring]]", "[[Longest path problem]]", "[[Subgraph isomorphism problem]]", "[[Substructure search]]", "[[Wiener connector]]", "[[A- search algorithm]]", "[[Arc routing]]", "[[B-]]"]
---

# Travelling salesman problem

In the theory of computational complexity, the travelling salesman problem (TSP) asks the following question: "Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city exactly once and returns to the origin city?" It is an NP-hard problem in combinatorial optimization, important in theoretical computer science and operations research.
The travelling purchaser problem, the vehicle routing problem and the ring star problem are three generalizations of TSP.
The decision version of the TSP (where given a length L, the task is to decide whether the graph has a tour whose length is at most L) belongs to the class of NP-complete problems. Thus, it is possible that the worst-case running time for any algorithm for the TSP increases superpolynomially (but no more than exponentially) with the number of cities.
The problem was first formulated in 1930 and is one of the most intensively studied problems in optimization. It is used as a benchmark for many optimization methods. Even though the problem is computationally difficult, many heuristics and exact algorithms are known, so that some instances with tens of thousands of cities can be solved completely, and even problems with millions of cities can be approximated within a small fraction of 1%.
The TSP has several applications even in its purest formulation, such as planning, logistics, and the manufacture of microchips. In warehouse operations, order picking routes are often modelled as variants of the travelling salesman problem, where a picker must visit multiple storage locations and return to a start or drop-off point while minimizing travel distance or time.
Slightly modified, it appears as a sub-problem in many areas, such as DNA sequencing. In these applications, the concept city represents, for example, customers, soldering points, or DNA fragments, and the concept distance represents travelling times or cost, or a similarity measure between DNA fragments. The TSP also appears in astronomy, as astronomers observing many sources want to minimize the time spent moving the telescope between the sources; in such problems, the TSP can be embedded inside an optimal control problem. In many applications, additional constraints such as limited resources or time windows may be imposed.

## Related

- [[Bottleneck traveling salesman problem]]
- [[Graph bandwidth]]
- [[Graph coloring]]
- [[Longest path problem]]
- [[Subgraph isomorphism problem]]
- [[Substructure search]]
- [[Wiener connector]]
- [[A- search algorithm]]
- [[Arc routing]]
- [[B-]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Travelling_salesman_problem