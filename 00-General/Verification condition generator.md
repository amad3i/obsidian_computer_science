---
title: "Verification condition generator"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Verification_condition_generator"
wikipedia_categories: ["Computer science stubs", "Formal methods"]
related: ["[[Concurrency semantics]]", "[[PlusCal]]", "[[ProCoS]]", "[[Retrenchment (computing)]]", "[[Symbolic simulation]]", "[[1-in-3-SAT]]", "[[Abstract state machine]]", "[[Agent verification]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]"]
---

# Verification condition generator

A verification condition generator is a common sub-component of an automated program verifier that synthesizes formal verification conditions by analyzing a program's source code using a method based upon Hoare logic. VC generators may require that the source code contains logical annotations provided by the programmer or the compiler such as pre/post-conditions and loop invariants (a form of proof-carrying code). VC generators are often coupled with SMT solvers in the backend of a program verifier. After a verification condition generator has created the verification conditions they are passed to an automated theorem prover, which can then formally prove the correctness of the code.
Methods have been proposed to use the operational semantics of machine languages to automatically generate verification condition generators.

## Related

- [[Concurrency semantics]]
- [[PlusCal]]
- [[ProCoS]]
- [[Retrenchment (computing)]]
- [[Symbolic simulation]]
- [[1-in-3-SAT]]
- [[Abstract state machine]]
- [[Agent verification]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Verification_condition_generator