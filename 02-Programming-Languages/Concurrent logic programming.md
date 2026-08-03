---
title: "Concurrent logic programming"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Concurrent_logic_programming"
wikipedia_categories: ["Concurrent programming languages", "Logic programming", "Parallel computing", "Programming paradigms"]
related: ["[[Flow-based programming]]", "[[Parallel programming model]]", "[[Algorithmic skeleton]]", "[[Concurrent Collections]]", "[[Concurrent constraint logic programming]]", "[[Dataflow programming]]", "[[Functional logic programming]]", "[[Logic programming]]", "[[Partitioned global address space]]", "[[Probabilistic logic programming]]"]
---

# Concurrent logic programming

Concurrent logic programming is a variant of logic programming designed for parallel computing in which programs are sets of guarded Horn clauses of the form:

H :- G1, …, Gn | B1, …, Bn.
The conjunction G1, … , Gn is called the guard of the clause, and | is the commitment operator. 
Declaratively, guarded Horn clauses are read as ordinary logical implications:

H if G1 and … and Gn and B1 and … and Bn.
However, procedurally, when there are several clauses whose heads H match a given goal, then all of the clauses are executed in parallel, checking whether their  guards G1, … , Gn hold. If the guards of more than one clause hold, then a committed choice is made to one of the clauses, and execution proceeds with the subgoals B1, …, Bn  of the chosen clause. These subgoals can also be executed in parallel. Thus concurrent logic programming implements a form of "don't care nondeterminism", rather
than "don't know nondeterminism".

## Related

- [[Flow-based programming]]
- [[Parallel programming model]]
- [[Algorithmic skeleton]]
- [[Concurrent Collections]]
- [[Concurrent constraint logic programming]]
- [[Dataflow programming]]
- [[Functional logic programming]]
- [[Logic programming]]
- [[Partitioned global address space]]
- [[Probabilistic logic programming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Concurrent_logic_programming