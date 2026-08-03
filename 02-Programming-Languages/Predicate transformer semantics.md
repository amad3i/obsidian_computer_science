---
title: "Predicate transformer semantics"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Predicate_transformer_semantics"
wikipedia_categories: ["Edsger W. Dijkstra", "Formal methods", "Program logic"]
related: ["[[Interference freedom]]", "[[1-in-3-SAT]]", "[[Abstract state machine]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[Algebraic specification]]", "[[Algorithm characterizations]]", "[[And-inverter graph]]", "[[Applicative universal grammar]]", "[[Assertion (software development)]]"]
---

# Predicate transformer semantics

Predicate transformer semantics were introduced by Edsger Dijkstra in his seminal paper "Guarded commands, nondeterminacy and formal derivation of programs". They define the semantics of an imperative programming paradigm by assigning to each statement in this language a corresponding predicate transformer: a total function between two predicates on the state space of the statement. In this sense, predicate transformer semantics are a kind of denotational semantics. Actually, in guarded commands, Dijkstra uses only one kind of predicate transformer: the well-known weakest preconditions (see below).
Moreover, predicate transformer semantics are a reformulation of Floyd–Hoare logic. Whereas Hoare logic is presented as a deductive system, predicate transformer semantics (either by weakest-preconditions or by strongest-postconditions see below) are complete strategies to build valid deductions of Hoare logic. In other words, they provide an effective algorithm to reduce the problem of verifying a Hoare triple to the problem of proving a first-order formula. Technically, predicate transformer semantics perform a kind of symbolic execution of statements into predicates: execution runs backward in the case of weakest-preconditions, or runs forward in the case of strongest-postconditions.

## Related

- [[Interference freedom]]
- [[1-in-3-SAT]]
- [[Abstract state machine]]
- [[Agent verification]]
- [[Algebraic semantics (computer science)]]
- [[Algebraic specification]]
- [[Algorithm characterizations]]
- [[And-inverter graph]]
- [[Applicative universal grammar]]
- [[Assertion (software development)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Predicate_transformer_semantics