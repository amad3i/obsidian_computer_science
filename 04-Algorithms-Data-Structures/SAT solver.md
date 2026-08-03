---
title: "SAT solver"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/SAT_solver"
wikipedia_categories: ["Formal methods", "Logic in computer science", "Satisfiability problems"]
related: ["[[1-in-3-SAT]]", "[[Boolean satisfiability problem]]", "[[Satisfiability modulo theories]]", "[[XOR-SAT]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[Assertion (software development)]]", "[[Bisimulation]]", "[[CompCert]]", "[[Formal verification]]"]
---

# SAT solver

In computer science and formal methods, a SAT solver is a computer program which aims to solve the Boolean satisfiability problem (SAT). On input a formula over Boolean variables, such as "(x or y) and (x or not y)", a SAT solver outputs whether the formula is satisfiable, meaning that there are possible values of x and y which make the formula true, or unsatisfiable, meaning that there are no such values of x and y. In this case, the formula is satisfiable when x is true, so the solver should return "satisfiable". Since the introduction of algorithms for SAT in the 1960s, modern SAT solvers have grown into complex software artifacts involving a large number of heuristics and program optimizations to work efficiently.
By a result known as the Cook–Levin theorem, Boolean satisfiability is an NP-complete problem in general. As a result, only algorithms with exponential worst-case complexity are known. In spite of this, efficient and scalable algorithms for SAT were developed during the 2000s, which have contributed to dramatic advances in the ability to automatically solve problem instances involving tens of thousands of variables and millions of constraints.
SAT solvers often begin by converting a formula to conjunctive normal form. They are often based on core algorithms such as the DPLL algorithm, but incorporate a number of extensions and features. Most SAT solvers include time-outs, so they will terminate in reasonable time even if they cannot find a solution, with an output such as "unknown" in the latter case. Often, SAT solvers do not just provide an answer, but can provide further information including an example assignment (values for x, y, etc.) in case the formula is satisfiable or minimal set of unsatisfiable clauses if the formula is unsatisfiable.
Modern SAT solvers have had a significant impact on fields including software verification, program analysis, constraint solving, artificial intelligence, electronic design automation, and operations research. Powerful solvers are readily available as free and open-source software and are built into some programming languages such as exposing SAT solvers as constraints in constraint logic programming.

## Related

- [[1-in-3-SAT]]
- [[Boolean satisfiability problem]]
- [[Satisfiability modulo theories]]
- [[XOR-SAT]]
- [[Agent verification]]
- [[Algebraic semantics (computer science)]]
- [[Assertion (software development)]]
- [[Bisimulation]]
- [[CompCert]]
- [[Formal verification]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/SAT_solver