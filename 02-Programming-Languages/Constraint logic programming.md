---
title: "Constraint logic programming"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Constraint_logic_programming"
wikipedia_categories: ["Constraint logic programming", "Constraint programming", "Logic programming"]
related: ["[[BNR Prolog]]", "[[Concurrent constraint logic programming]]", "[[Narrowing of algebraic value sets]]", "[[Abductive logic programming]]", "[[Advice taker]]", "[[Algorithm selection]]", "[[Allen's interval algebra]]", "[[Answer set programming]]", "[[Artificial intelligence in fraud detection]]", "[[Autoepistemic logic]]"]
---

# Constraint logic programming

Constraint logic programming is a form of constraint programming, in which logic programming is extended to include concepts from constraint satisfaction. A constraint logic program is a logic program that contains constraints in the body of clauses. An example of a clause including a constraint is A(X,Y) :- X+Y>0, B(X), C(Y). In this clause, X+Y>0 is a constraint; A(X,Y), B(X), and C(Y) are literals as in regular logic programming. This clause states one condition under which the statement A(X,Y) holds: X+Y is greater than zero and both B(X) and C(Y) are true.
As in regular logic programming, programs are queried about the provability of a goal, which itself may contain constraints in addition to literals. A proof for a goal is composed of clauses whose bodies are satisfiable constraints and literals that can in turn be proved using other clauses. Execution is performed by an interpreter, which starts from the goal and recursively scans the clauses trying to prove the goal. Constraints encountered during this scan are placed in a set called the constraint store. If this set is found out to be unsatisfiable, the interpreter backtracks, trying to use other clauses for proving the goal. In practice, satisfiability of the constraint store may be checked using an incomplete algorithm, which does not always detect inconsistency.

## Related

- [[BNR Prolog]]
- [[Concurrent constraint logic programming]]
- [[Narrowing of algebraic value sets]]
- [[Abductive logic programming]]
- [[Advice taker]]
- [[Algorithm selection]]
- [[Allen's interval algebra]]
- [[Answer set programming]]
- [[Artificial intelligence in fraud detection]]
- [[Autoepistemic logic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Constraint_logic_programming