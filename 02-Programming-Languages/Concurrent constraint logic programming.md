---
title: "Concurrent constraint logic programming"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Concurrent_constraint_logic_programming"
wikipedia_categories: ["Concurrent computing", "Constraint logic programming", "Logic programming", "Programming paradigms"]
related: ["[[BNR Prolog]]", "[[Choreographic programming]]", "[[Concurrent logic programming]]", "[[Concurrent object-oriented programming]]", "[[Constraint logic programming]]", "[[Functional logic programming]]", "[[Logic programming]]", "[[Probabilistic logic programming]]", "[[Structured concurrency]]", "[[Abductive logic programming]]"]
---

# Concurrent constraint logic programming

Concurrent constraint logic programming is a version of constraint logic programming aimed primarily at programming concurrent processes rather than (or in addition to) solving constraint satisfaction problems. Goals in constraint logic programming are evaluated concurrently; a concurrent process is therefore programmed as the evaluation of a goal by the interpreter.
Syntactically, concurrent constraint logic programs are similar to non-concurrent programs, the only exception being that clauses include guards, which are constraints that may block the applicability of the clause under some conditions. Semantically, concurrent constraint logic programming differs from its non-concurrent versions because a goal evaluation is intended to realize a concurrent process rather than finding a solution to a problem. Most notably, this difference affects how the interpreter behaves when more than one clause is applicable: non-concurrent constraint logic programming recursively tries all clauses; concurrent constraint logic programming chooses only one. This is the most evident effect of an intended directionality of the interpreter, which never revise a choice it has previously taken. Other effects of this are the semantical possibility of having a goal that cannot be proved while the whole evaluation does not fail, and a particular way for equating a goal and a clause head.
Constraint handling rules can be seen as a form of concurrent constraint logic programming, but are used for programming a constraint simplifier or solver rather than concurrent processes.

## Related

- [[BNR Prolog]]
- [[Choreographic programming]]
- [[Concurrent logic programming]]
- [[Concurrent object-oriented programming]]
- [[Constraint logic programming]]
- [[Functional logic programming]]
- [[Logic programming]]
- [[Probabilistic logic programming]]
- [[Structured concurrency]]
- [[Abductive logic programming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Concurrent_constraint_logic_programming