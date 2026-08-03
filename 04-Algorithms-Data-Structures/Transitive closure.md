---
title: "Transitive closure"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Transitive_closure"
wikipedia_categories: ["Binary relations", "Closure operators", "Graph algorithms"]
related: ["[[A- search algorithm]]", "[[Alpha–beta pruning]]", "[[Aperiodic graph]]", "[[B-]]", "[[Barabási–Albert model]]", "[[Belief propagation]]", "[[Bellman–Ford algorithm]]", "[[Bianconi–Barabási model]]", "[[Bidirectional search]]", "[[BIT predicate]]"]
---

# Transitive closure

In mathematics, the transitive closure R+ of a homogeneous binary relation R on a set X is the smallest relation on X that contains R and is transitive. For finite sets, "smallest" can be taken in its usual sense, of having the fewest related pairs; for infinite sets R+ is the unique minimal transitive superset of R.
For example, if X is a set of airports and x R y means "there is a direct flight from airport x to airport y" (for x and y in X), then the transitive closure of R on X is the relation R+ such that x R+ y means "it is possible to fly from x to y in one or more flights".
More formally, the transitive closure of a binary relation R on a set X is the smallest (w.r.t. ⊆) transitive relation R+ on X such that R ⊆ R+; see Lidl & Pilz (1998, p. 337). We have R+ = R if, and only if, R itself is transitive.
Conversely, transitive reduction reduces a minimal relation S from a given relation R such that they have the same closure, that is, S+ = R+; however, many different S with this property may exist.
Both transitive closure and transitive reduction are also used in the closely related area of graph theory.

## Related

- [[A- search algorithm]]
- [[Alpha–beta pruning]]
- [[Aperiodic graph]]
- [[B-]]
- [[Barabási–Albert model]]
- [[Belief propagation]]
- [[Bellman–Ford algorithm]]
- [[Bianconi–Barabási model]]
- [[Bidirectional search]]
- [[BIT predicate]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Transitive_closure