---
title: "Refinement calculus"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Refinement_calculus"
wikipedia_categories: ["Formal methods", "Formal methods stubs", "Formal specification languages", "Logical calculi"]
related: ["[[Predicative programming]]", "[[Algebraic semantics (computer science)]]", "[[Axiomatic semantics]]", "[[B-Method]]", "[[Formal specification]]", "[[Language of Temporal Ordering Specification]]", "[[PlusCal]]", "[[ProCoS]]", "[[Semantics (programming languages)]]", "[[TLA+]]"]
---

# Refinement calculus

The refinement calculus is a formalized approach to stepwise refinement for program construction. The required behaviour of the final executable program is specified as an abstract and perhaps non-executable "program", which is then refined by a series of correctness-preserving transformations into an efficiently executable program.
Proponents include Ralph-Johan Back, who originated the approach in his 1978 PhD thesis On the Correctness of Refinement Steps in Program Development, and Carroll Morgan, especially with his book Programming from Specifications (Prentice Hall, 2nd edition, 1994, ISBN 0-13-123274-6). In the latter case, the motivation was to link Abrial's specification notation Z, via a rigorous relation of behaviour-preserving program refinement, to an executable programming notation based on Dijkstra's language of guarded commands. Behaviour-preserving in this case means that any Hoare triple satisfied by a program should also be satisfied by any refinement of it, which notion leads directly to specification statements as pre- and postconditions standing, on their own, for any program that could soundly be placed between them.

## Related

- [[Predicative programming]]
- [[Algebraic semantics (computer science)]]
- [[Axiomatic semantics]]
- [[B-Method]]
- [[Formal specification]]
- [[Language of Temporal Ordering Specification]]
- [[PlusCal]]
- [[ProCoS]]
- [[Semantics (programming languages)]]
- [[TLA+]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Refinement_calculus