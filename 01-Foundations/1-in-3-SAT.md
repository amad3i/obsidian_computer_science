---
title: "1-in-3-SAT"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/1-in-3-SAT"
wikipedia_categories: ["Boolean algebra", "Electronic design automation", "Formal methods", "Logic in computer science", "NP-complete problems", "Satisfiability problems"]
related: ["[[Boolean satisfiability problem]]", "[[XOR-SAT]]", "[[Satisfiability modulo theories]]", "[[Logic optimization]]", "[[SAT solver]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[And-inverter graph]]", "[[Assertion (software development)]]", "[[Asynchronous system]]"]
---

# 1-in-3-SAT

In computational complexity, one-in-three 3-SAT (also known variously as 1-in-3-SAT and exactly-1 3-SAT) is an NP-complete variant of the Boolean satisfiability problem. 
Given a conjunctive normal form with three literals per clause, the problem is to determine whether there exists a truth assignment to the variables so that each clause has exactly one TRUE literal (and thus exactly two FALSE literals). In contrast, ordinary 3-SAT requires that every clause has at least one TRUE literal. Formally, a one-in-three 3-SAT problem is given as a generalized conjunctive normal form with all generalized clauses using a ternary operator R that is TRUE just if exactly one of its arguments is. When all the variables of a one-in-three 3-SAT formula have the same literal, the satisfiability problem is called one-in-three monotone 3-SAT.
One-in-three 3-SAT, together with its monotone case, is listed as NP-complete problem "LO4" in the standard reference Computers and Intractability: A Guide to the Theory of NP-Completeness by Michael R. Garey and David S. Johnson.  One-in-three 3-SAT was proved to be NP-complete by Thomas Jerome Schaefer as a special case of Schaefer's dichotomy theorem, which asserts that any problem generalizing Boolean satisfiability in a certain way is either in the class P or is NP-complete.

## Related

- [[Boolean satisfiability problem]]
- [[XOR-SAT]]
- [[Satisfiability modulo theories]]
- [[Logic optimization]]
- [[SAT solver]]
- [[Agent verification]]
- [[Algebraic semantics (computer science)]]
- [[And-inverter graph]]
- [[Assertion (software development)]]
- [[Asynchronous system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/1-in-3-SAT