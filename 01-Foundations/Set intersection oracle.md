---
title: "Set intersection oracle"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Set_intersection_oracle"
wikipedia_categories: ["Data structures", "Set theory"]
related: ["[[Active data structure]]", "[[Admissible set]]", "[[Almost]]", "[[Benacerraf's identification problem]]", "[[BIT predicate]]", "[[Block availability map]]", "[[Cabal (set theory)]]", "[[Cantor's diagonal argument]]", "[[Cantor's first set theory article]]", "[[Cantor's theorem]]"]
---

# Set intersection oracle

A set intersection oracle (SIO) is a data structure which represents a collection of sets and can quickly answer queries about whether the set intersection of two given sets is non-empty.
The input to the problem is n finite sets. The sum of the sizes of all sets is N (which also means that there are at most N distinct elements). The SIO should quickly answer any query of the form:

"Does the set Si intersect the set Sk"?

## Related

- [[Active data structure]]
- [[Admissible set]]
- [[Almost]]
- [[Benacerraf's identification problem]]
- [[BIT predicate]]
- [[Block availability map]]
- [[Cabal (set theory)]]
- [[Cantor's diagonal argument]]
- [[Cantor's first set theory article]]
- [[Cantor's theorem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Set_intersection_oracle