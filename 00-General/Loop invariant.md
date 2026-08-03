---
title: "Loop invariant"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Loop_invariant"
wikipedia_categories: ["Control flow", "Formal methods"]
related: ["[[Loop variant]]", "[[1-in-3-SAT]]", "[[Abstract state machine]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[Algebraic specification]]", "[[Algorithm characterizations]]", "[[And-inverter graph]]", "[[Applicative universal grammar]]", "[[Assertion (software development)]]"]
---

# Loop invariant

In computer science, a loop invariant is a property of a program loop that is true before (and after) each iteration. It is a logical assertion, sometimes checked with a code assertion. Knowing its invariant(s) is essential in understanding the effect of a loop.
In formal program verification, particularly the Floyd-Hoare approach, loop invariants are expressed by formal predicate logic and used to prove properties of loops and by extension algorithms that employ loops (usually correctness properties). The loop invariants will be true on entry into a loop and following each iteration, so that on exit from the loop, both the loop invariants and the loop termination condition can be guaranteed.
From a programming methodology viewpoint, the loop invariant can be viewed as a more abstract specification of the loop, which characterizes the deeper purpose of the loop beyond the details of this implementation. A survey article covers fundamental algorithms from many areas of computer science (searching, sorting, optimization, arithmetic etc.), characterizing each of them from the viewpoint of its invariant.
Because of the similarity of loops and recursive programs, proving partial correctness of loops with invariants is very similar to proving the correctness of recursive programs via induction.  In fact, the loop invariant is often the same as the inductive hypothesis to be proved for a recursive program equivalent to a given loop.

## Related

- [[Loop variant]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Loop_invariant