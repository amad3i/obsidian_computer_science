---
title: "TLA+"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/TLA+"
wikipedia_categories: ["Concurrency (computer science)", "Formal methods", "Formal methods tools", "Formal specification languages", "Software using the BSD license", "Specification languages"]
related: ["[[B-Method]]", "[[Language of Temporal Ordering Specification]]", "[[Algebraic semantics (computer science)]]", "[[Concurrency semantics]]", "[[Formal methods]]", "[[Formal specification]]", "[[Kim Guldstrand Larsen]]", "[[Knowledge Based Software Assistant]]", "[[Object-Z]]", "[[PlusCal]]"]
---

# TLA+

TLA+ is a formal specification language developed by Leslie Lamport. It is used for designing, modelling, documentation, and verification of programs, especially concurrent systems and distributed systems. TLA+ is considered to be exhaustively-testable pseudocode, and its use likened to drawing blueprints for software systems; TLA is an acronym for Temporal Logic of Actions.
For design and documentation, TLA+ fulfills the same purpose as informal technical specifications. However, TLA+ specifications are written in a formal language of logic and mathematics, and the precision of specifications written in this language is intended to uncover design flaws before system implementation is underway.
Since TLA+ specifications are written in a formal language, they are amenable to finite model checking. The model checker finds all possible system behaviours up to some number of execution steps, and examines them for violations of desired invariance properties such as safety and liveness. TLA+ specifications use basic set theory to define safety (bad things won't happen) and temporal logic to define liveness (good things eventually happen).
TLA+ is also used to write machine-checked proofs of correctness both for algorithms and mathematical theorems. The proofs are written in a declarative, hierarchical style independent of any single theorem prover backend. Both formal and informal structured mathematical proofs can be written in TLA+; the language is similar to LaTeX, and tools exist to translate TLA+ specifications to LaTeX documents.
TLA+ was introduced in 1999, following several decades of research into a verification method for concurrent systems. Ever since, a toolchain has been developed, including an IDE and a distributed model checker. The pseudocode-like language PlusCal was created in 2009; it transpiles to TLA+ and is useful for specifying sequential algorithms. TLA+2 was announced in 2014, expanding language support for proof constructs. The current TLA+ reference is The TLA+ Hyperbook by Leslie Lamport.

## Related

- [[B-Method]]
- [[Language of Temporal Ordering Specification]]
- [[Algebraic semantics (computer science)]]
- [[Concurrency semantics]]
- [[Formal methods]]
- [[Formal specification]]
- [[Kim Guldstrand Larsen]]
- [[Knowledge Based Software Assistant]]
- [[Object-Z]]
- [[PlusCal]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/TLA+