---
title: "Corecursion"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Corecursion"
wikipedia_categories: ["Category theory", "Functional programming", "Recursion", "Self-reference", "Theoretical computer science"]
related: ["[[Coinduction]]", "[[Catamorphism]]", "[[F-algebra]]", "[[Impredicativity]]", "[[Initial algebra]]", "[[Recursion]]", "[[Recursive definition]]", "[[Self-reference]]", "[[2-Yoneda lemma]]", "[[3-category]]"]
---

# Corecursion

In computer science, corecursion is a type of operation that is dual to (structural) recursion. Whereas recursion consumes a data structure by first handling the topmost layer before descending into its inner parts, corecursion produces a data structure by first defining the topmost layer before defining its inner parts. Corecursion is a particularly important in total languages, as it allows encoding potentially non-terminating computations in a context where every function must terminate. It is supported by theorem provers Agda and Rocq.
Both corecursion and recursion can be thought of as operating on trees, which include data structures like lists and streams as special cases. Since recursion must terminate, it only works on trees that are well-founded, i.e. not infinitely deep, which are called data or initial data types; on the other hand, corecursion produces codata or final data types, which includes infinitely deep trees. Codata cannot be represented in memory directly, so is often implemented using self-referential data structures or lazy evaluation.

## Related

- [[Coinduction]]
- [[Catamorphism]]
- [[F-algebra]]
- [[Impredicativity]]
- [[Initial algebra]]
- [[Recursion]]
- [[Recursive definition]]
- [[Self-reference]]
- [[2-Yoneda lemma]]
- [[3-category]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Corecursion