---
title: "Postcondition"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Postcondition"
wikipedia_categories: ["Formal methods", "Logic in computer science", "Mathematics of computing", "Programming constructs"]
related: ["[[Precondition]]", "[[1-in-3-SAT]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[Assertion (software development)]]", "[[Bisimulation]]", "[[Boolean satisfiability problem]]", "[[CompCert]]", "[[Formal verification]]", "[[Interference freedom]]"]
---

# Postcondition

In computer programming, a postcondition is a condition or predicate that must always be true just after the execution of some section of code or after an operation in a formal specification. Postconditions are sometimes tested using assertions within the code itself. Often, postconditions are simply included in the documentation of the affected section of code.
For example: The result of a factorial is always an integer and greater than or equal to 1. So a program that calculates the factorial of an input number would have postconditions that the result after the calculation be an integer and that it be greater than or equal to 1.  Another example: a program that calculates the square root of an input number might have the postconditions that the result be a number and that its square be equal to the input.

## Related

- [[Precondition]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Postcondition