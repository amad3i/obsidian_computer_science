---
title: "Interference freedom"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Interference_freedom"
wikipedia_categories: ["Formal methods", "Logic in computer science", "Program logic"]
related: ["[[1-in-3-SAT]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[Assertion (software development)]]", "[[Bisimulation]]", "[[Boolean satisfiability problem]]", "[[CompCert]]", "[[Dynamic logic (modal logic)]]", "[[Formal verification]]", "[[Logic in computer science]]"]
---

# Interference freedom

In computer science, interference freedom is a technique for proving partial correctness of
concurrent programs with shared variables. Hoare logic had been introduced earlier
to prove the correctness of sequential programs. In her PhD thesis (and papers arising from it ) under advisor David Gries, Susan Owicki 
extended this work to apply to concurrent programs.
Concurrent programming had been in use since the mid-1960s for coding operating systems as sets of concurrent processes (see, in particular, Dijkstra.), but there was no formal mechanism for proving correctness. Reasoning about interleaved execution sequences of the individual processes was difficult, was error prone, and didn't scale up. Interference freedom applies to proofs instead of execution sequences; one shows that execution of one process cannot interfere with the correctness proof of another process.
A range of intricate concurrent programs have been proved correct using interference freedom, and interference freedom provides the basis for much of the ensuing work on developing concurrent programs with shared variables and proving them correct. The Owicki-Gries paper An axiomatic proof technique for parallel programs  received the 1977 ACM Award for best paper in programming languages and systems.
Note. Lamport presents a similar idea. He writes, "After writing the initial version of this paper, we learned of the recent work of Owicki." His paper has not received as much attention as Owicki-Gries, perhaps because it used flow charts instead of the text of programming constructs like the if statement and while loop. Lamport was generalizing Floyd's method, while Owicki-Gries was generalizing Hoare's method.
Essentially, all later work in this area uses text and not flow charts. Another difference is mentioned below in the section on Auxiliary variables.

## Related

- [[1-in-3-SAT]]
- [[Agent verification]]
- [[Algebraic semantics (computer science)]]
- [[Assertion (software development)]]
- [[Bisimulation]]
- [[Boolean satisfiability problem]]
- [[CompCert]]
- [[Dynamic logic (modal logic)]]
- [[Formal verification]]
- [[Logic in computer science]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Interference_freedom