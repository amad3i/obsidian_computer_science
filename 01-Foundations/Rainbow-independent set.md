---
title: "Rainbow-independent set"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Rainbow-independent_set"
wikipedia_categories: ["Graph theory", "NP-complete problems", "Rainbow problems"]
related: ["[[Graph coloring]]", "[[Graph homomorphism]]", "[[Homeomorphism (graph theory)]]", "[[1-in-3-SAT]]", "[[3-dimensional matching]]", "[[Albertson index]]", "[[Arc routing]]", "[[Bicircular matroid]]", "[[Biclustering]]", "[[Boolean satisfiability problem]]"]
---

# Rainbow-independent set

In graph theory, a rainbow-independent set (ISR) is an independent set in a graph, in which each vertex has a different color.
Formally, let G = (V, E) be a graph, and suppose vertex set V is partitioned into m subsets V1, …, Vm, called "colors". A set U of vertices is called a rainbow-independent set if it satisfies both the following conditions:

It is an independent set – every two vertices in U are not adjacent (there is no edge between them);
It is a rainbow set – U contains at most a single vertex from each color Vi.
Other terms used in the literature are independent set of representatives, independent transversal, and independent system of representatives.
As an example application, consider a faculty with m departments, where some faculty members dislike each other. The dean wants to construct a committee with m members, one member per department, but without any pair of members who dislike each other. This problem can be presented as finding an ISR in a graph in which the nodes are the faculty members, the edges describe the "dislike" relations, and the subsets  V1, …, Vm are the departments.

## Related

- [[Graph coloring]]
- [[Graph homomorphism]]
- [[Homeomorphism (graph theory)]]
- [[1-in-3-SAT]]
- [[3-dimensional matching]]
- [[Albertson index]]
- [[Arc routing]]
- [[Bicircular matroid]]
- [[Biclustering]]
- [[Boolean satisfiability problem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rainbow-independent_set