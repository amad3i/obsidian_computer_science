---
title: "Precondition"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Precondition"
wikipedia_categories: ["Formal methods", "Logic in computer science", "Programming constructs"]
related: ["[[Postcondition]]", "[[1-in-3-SAT]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[Assertion (software development)]]", "[[Bisimulation]]", "[[Boolean satisfiability problem]]", "[[CompCert]]", "[[Formal verification]]", "[[Interference freedom]]"]
---

# Precondition

In computer programming, a precondition is a condition or predicate that must always be true just prior to the execution of some section of code or before an operation in a formal specification.
If a precondition is violated, the effect of the section of code becomes undefined and thus may or may not carry out its intended work.  Preconditions that are missing, insufficient, or not formally proved (or have an incorrect attempted proof), or are not checked statically or dynamically, can give rise to Security problems, particularly in unsafe languages that are not strongly typed.
Often, preconditions are simply included in the documentation of the affected section of code.  Preconditions are sometimes tested using guards or assertions within the code itself, and some languages have specific syntactic constructions for doing so.

## Related

- [[Postcondition]]
- [[1-in-3-SAT]]
- [[Agent verification]]
- [[Algebraic semantics (computer science)]]
- [[Assertion (software development)]]
- [[Bisimulation]]
- [[Boolean satisfiability problem]]
- [[CompCert]]
- [[Formal verification]]
- [[Interference freedom]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Precondition