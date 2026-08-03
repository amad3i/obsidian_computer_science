---
title: "Coinduction"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Coinduction"
wikipedia_categories: ["Category theory", "Functional programming", "Logic programming", "Mathematical induction", "Theoretical computer science"]
related: ["[[Corecursion]]", "[[Catamorphism]]", "[[Dis-unification]]", "[[F-algebra]]", "[[Functional logic programming]]", "[[Initial algebra]]", "[[Scientific community metaphor]]", "[[2-Yoneda lemma]]", "[[3-category]]", "[[A-normal form]]"]
---

# Coinduction

In computer science, coinduction is a technique for defining and proving properties of systems of concurrent interacting objects.
Coinduction is the mathematical dual to structural induction. Coinductively defined data types are known as codata and are typically infinite data structures, such as streams.
As a definition or specification, coinduction describes how an object may be "observed", "broken down" or "destructed" into simpler objects. As a proof technique, it may be used to show that an equation is satisfied by all possible implementations of such a specification.
To generate and manipulate codata, one typically uses corecursive functions, in conjunction with lazy evaluation.  Informally, rather than defining a function by pattern-matching on each of the inductive constructors, one defines each of the "destructors" or "observers" over the function result.
In programming, co-logic programming (co-LP for brevity) "is a natural generalization of logic programming and coinductive logic programming, which in turn generalizes other extensions of logic programming, such as infinite trees, lazy predicates, and concurrent communicating predicates. Co-LP has applications to rational trees, verifying infinitary properties, lazy evaluation, concurrent logic programming, model checking, bisimilarity proofs, etc." Experimental implementations of co-LP are available from the University of Texas at Dallas and in the language Logtalk (for examples see  ) and SWI-Prolog.

## Related

- [[Corecursion]]
- [[Catamorphism]]
- [[Dis-unification]]
- [[F-algebra]]
- [[Functional logic programming]]
- [[Initial algebra]]
- [[Scientific community metaphor]]
- [[2-Yoneda lemma]]
- [[3-category]]
- [[A-normal form]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Coinduction