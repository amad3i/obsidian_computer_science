---
title: "X-Machine Testing"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/X-Machine_Testing"
wikipedia_categories: ["Software testing", "Theory of computation"]
related: ["[[Stream X-Machine]]", "[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ackermann function]]", "[[Ad hoc testing]]", "[[Admissible numbering]]", "[[Agent verification]]", "[[Agile testing]]"]
---

# X-Machine Testing

The (Stream) X-Machine Testing Methodology is a complete functional testing approach to software- and hardware testing that exploits the scalability of the Stream X-Machine model of computation.  
Using this methodology, it is likely to identify a finite test-set that exhaustively determines whether the tested system's implementation matches its specification.  This goal is achieved by a divide-and-conquer approach, in which the design is decomposed by refinement into a collection of Stream X-Machines, which are implemented as separate modules, then tested bottom-up.  At each integration stage, the testing method guarantees that the tested components are correctly integrated.
The methodology overcomes formal undecidability limitations by requiring that certain design for test principles are followed during specification and implementation.  The resulting scalability means that practical software and hardware systems consisting of hundreds of thousands of states and millions of transitions have been tested successfully.

## Related

- [[Stream X-Machine]]
- [[-dev-full]]
- [[A-B testing]]
- [[Acceptance test-driven development]]
- [[Acceptance testing]]
- [[Ackermann function]]
- [[Ad hoc testing]]
- [[Admissible numbering]]
- [[Agent verification]]
- [[Agile testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/X-Machine_Testing