---
title: "Multi-adjoint logic programming"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Multi-adjoint_logic_programming"
wikipedia_categories: ["Computing stubs", "Programming languages"]
related: ["[[A+ (programming language)]]", "[[ABAP]]", "[[Ada (programming language)]]", "[[Address programming language]]", "[[ALGOL 68]]", "[[Apache Groovy]]", "[[APL (programming language)]]", "[[Apple (programming language)]]", "[[AppleScript]]", "[[AspectJ]]"]
---

# Multi-adjoint logic programming

Multi-adjoint logic programming defines syntax and semantics of a logic programming program in such a way that the underlying maths justifying the results are a residuated lattice and/or MV-algebra.
The definition of a multi-adjoint logic program is given, as usual in fuzzy logic programming, as a set of weighted rules and facts of a given formal language F. Notice that the use of different implications is allowed in these rules.
Definition: A multi-adjoint logic program is a set P of rules of the form <(A ←i B), δ> such that:
1. The rule (A ←i B) is a formula of F;
2. The confidence factor δ is an element (a truth-value) of L;
3. The head A is an atom;
4. The body B is a formula built from atoms B1, …, Bn (n ≥ 0) by the use of conjunctor, disjunctor, and aggregator.
5. Facts are rules with body ┬.
6. A query (or goal) is an atom intended as a question ?A prompting the system.

## Related

- [[A+ (programming language)]]
- [[ABAP]]
- [[Ada (programming language)]]
- [[Address programming language]]
- [[ALGOL 68]]
- [[Apache Groovy]]
- [[APL (programming language)]]
- [[Apple (programming language)]]
- [[AppleScript]]
- [[AspectJ]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multi-adjoint_logic_programming