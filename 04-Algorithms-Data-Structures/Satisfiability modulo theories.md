---
title: "Satisfiability modulo theories"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Satisfiability_modulo_theories"
wikipedia_categories: ["Constraint programming", "Electronic design automation", "Formal methods", "Logic in computer science", "NP-complete problems", "Satisfiability modulo theories solvers", "Satisfiability problems"]
related: ["[[1-in-3-SAT]]", "[[Boolean satisfiability problem]]", "[[XOR-SAT]]", "[[SAT solver]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[And-inverter graph]]", "[[Assertion (software development)]]", "[[Asynchronous system]]", "[[Bisimulation]]"]
---

# Satisfiability modulo theories

In computer science and mathematical logic, satisfiability modulo theories (SMT) is the problem of determining whether a mathematical formula is satisfiable. It generalizes the Boolean satisfiability problem (SAT) to more complex formulas involving real numbers, integers, and/or various data structures such as lists, arrays, bit vectors, and strings. The name is derived from the fact that these expressions are interpreted within ("modulo") a certain formal theory in first-order logic with equality (often disallowing quantifiers). SMT solvers are tools that aim to solve the SMT problem for a practical subset of inputs. SMT solvers such as Z3 and cvc5 have been used as a building block for a wide range of applications across computer science, including in automated theorem proving, program analysis, program verification, and software testing.
Since Boolean satisfiability is already NP-complete, the SMT problem is typically NP-hard, and for many theories it is undecidable. Researchers study which theories or subsets of theories lead to a decidable SMT problem and the computational complexity of decidable cases. The resulting decision procedures are often implemented directly in SMT solvers; see, for instance, the decidability of Presburger arithmetic. SMT can be thought of as a constraint satisfaction problem and thus a certain formalized approach to constraint programming.

## Related

- [[1-in-3-SAT]]
- [[Boolean satisfiability problem]]
- [[XOR-SAT]]
- [[SAT solver]]
- [[Agent verification]]
- [[Algebraic semantics (computer science)]]
- [[And-inverter graph]]
- [[Assertion (software development)]]
- [[Asynchronous system]]
- [[Bisimulation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Satisfiability_modulo_theories