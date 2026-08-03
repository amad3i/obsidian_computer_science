---
title: "Loop variant"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Loop_variant"
wikipedia_categories: ["Control flow", "Formal methods"]
related: ["[[Loop invariant]]", "[[1-in-3-SAT]]", "[[Abstract state machine]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[Algebraic specification]]", "[[Algorithm characterizations]]", "[[And-inverter graph]]", "[[Applicative universal grammar]]", "[[Assertion (software development)]]"]
---

# Loop variant

In computer science, a loop variant is a mathematical function defined on the state space of a computer program whose value is monotonically decreased with respect to a (strict) well-founded relation by the iteration of a while loop under some invariant conditions, thereby ensuring its termination.  A loop variant whose range is restricted to the non-negative integers is also known as a bound function, because in this case it provides a trivial upper bound on the number of iterations of a loop before it terminates.  However, a loop variant may be transfinite, and thus is not necessarily restricted to integer values.
A well-founded relation is characterized by the existence of a minimal element of every non-empty subset of its domain.  The existence of a variant proves the termination of a while loop in a computer program by well-founded descent. A basic property of a well-founded relation is that it has no infinite descending chains.  Therefore a loop possessing a variant will terminate after a finite number of iterations, as long as its body terminates each time.
A while loop, or, more generally, a computer program that may contain while loops, is said to be totally correct if it is partially correct and it terminates.

## Related

- [[Loop invariant]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Loop_variant