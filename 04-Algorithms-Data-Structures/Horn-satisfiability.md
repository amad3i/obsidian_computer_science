---
title: "Horn-satisfiability"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Horn-satisfiability"
wikipedia_categories: ["Logic in computer science", "P-complete problems", "Satisfiability problems"]
related: ["[[1-in-3-SAT]]", "[[Boolean satisfiability problem]]", "[[Maximum satisfiability problem]]", "[[SAT solver]]", "[[Satisfiability modulo theories]]", "[[XOR-SAT]]", "[[Abstract rewriting system]]", "[[ACM Transactions on Computational Logic]]", "[[Agent verification]]", "[[Agentive logic]]"]
---

# Horn-satisfiability

In formal logic, Horn-satisfiability, or HORNSAT, is the problem of deciding whether a given conjunction of propositional Horn clauses is satisfiable or not. Horn-satisfiability and Horn clauses are named after Alfred Horn.
A Horn clause is a clause with at most one positive literal, called the head of the clause, and any number of negative literals, forming the body of the clause. A Horn formula is a propositional formula formed by conjunction of Horn clauses.
Horn satisfiability is actually one of the "hardest" or "most expressive" problems which is known to be computable in polynomial time, in the sense that it is a P-complete problem. The extension of the problem for quantified Horn formulae can be also solved in polynomial time.
The Horn satisfiability problem can also be asked for propositional many-valued logics. The algorithms are not usually linear, but some are polynomial; see Hähnle (2001 or 2003) for a survey.

## Related

- [[1-in-3-SAT]]
- [[Boolean satisfiability problem]]
- [[Maximum satisfiability problem]]
- [[SAT solver]]
- [[Satisfiability modulo theories]]
- [[XOR-SAT]]
- [[Abstract rewriting system]]
- [[ACM Transactions on Computational Logic]]
- [[Agent verification]]
- [[Agentive logic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Horn-satisfiability