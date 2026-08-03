---
title: "Binary moment diagram"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Binary_moment_diagram"
wikipedia_categories: ["Formal methods", "Graph data structures"]
related: ["[[1-in-3-SAT]]", "[[Abstract semantic graph]]", "[[Abstract state machine]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[Algebraic specification]]", "[[Algorithm characterizations]]", "[[And-inverter graph]]", "[[Applicative universal grammar]]", "[[Assertion (software development)]]"]
---

# Binary moment diagram

A binary moment diagram (BMD) is a generalization of the binary decision diagram (BDD) to linear functions over domains such as booleans (like BDDs), but also to integers or to real numbers.
They can deal with Boolean functions with complexity comparable to BDDs, but also some functions that are dealt with very inefficiently in a BDD are handled easily by BMD, most notably multiplication.
The most important properties of BMD is that, like with BDDs, each function has exactly one canonical representation, and many operations can be efficiently performed on these representations.
The main features that differentiate BMDs from BDDs are using linear instead of pointwise diagrams, and having weighted edges.
The rules that ensure the canonicity of the representation are:

Decision over variables higher in the ordering may only point to decisions over variables lower in the ordering.
No two nodes may be identical (in normalization such nodes all references to one of these nodes should be replaced be references to another)
No node may have all decision parts equivalent to 0 (links to such nodes should be replaced by links to their always part)
No edge may have weight zero (all such edges should be replaced by direct links to 0)
Weights of the edges should be coprime. Without this rule or some equivalent of it, it would be possible for a function to have many representations, for example 2x + 2 could be represented as 2 · (1 + x) or 1 · (2 + 2x).

## Related

- [[1-in-3-SAT]]
- [[Abstract semantic graph]]
- [[Abstract state machine]]
- [[Agent verification]]
- [[Algebraic semantics (computer science)]]
- [[Algebraic specification]]
- [[Algorithm characterizations]]
- [[And-inverter graph]]
- [[Applicative universal grammar]]
- [[Assertion (software development)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Binary_moment_diagram