---
title: "Logic programming"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Logic_programming"
wikipedia_categories: ["Computer-related introductions in 1972", "Logic", "Logic programming", "Programming paradigms"]
related: ["[[Belief revision]]", "[[Concurrent constraint logic programming]]", "[[Concurrent logic programming]]", "[[Focused proof]]", "[[Functional logic programming]]", "[[Probabilistic logic programming]]", "[[Abductive logic programming]]", "[[Advice taker]]", "[[Answer set programming]]", "[[Array programming]]"]
---

# Logic programming

Logic programming is a programming, database, and knowledge representation paradigm based on formal logic. A logic program is a set of sentences in logical form, representing knowledge about some problem domain. Computation is performed by applying logical reasoning to that knowledge, to solve problems in the domain.  Major logic programming language families include Prolog, Answer Set Programming (ASP), and Datalog. In all of these languages, rules are written in the form of clauses:

A :- B1, ..., Bn.
and are read as declarative sentences in logical form:

A if B1 and ... and Bn.
A is called the head of the rule, B1, ..., Bn is called the body, and the Bi are called literals or conditions. When n = 0, the rule is called a fact and is written in the simplified form:

A.
Queries (or goals) have the same syntax as the bodies of rules and are commonly written in the form:

?- B1, ..., Bn.
In the simplest case of Horn clauses (or "definite" clauses), all of the A, B1, ..., Bn are atomic formulae of the form p(t1 ,..., tm), where p is a predicate symbol naming a relation, like "motherhood", and the ti are terms naming objects (or individuals). Terms include both constant symbols, like "charles", and variables, such as X, which start with an upper case letter.
Consider, for example, the following Horn clause program:

Given a query, the program produces answers.
For instance for a query  ?- parent_child(X, william), the single answer is

Various queries can be asked.  For instance
the program can be queried both to generate grandparents and to generate grandchildren. It can even be used to generate all pairs of grandchildren and grandparents, or simply to check if a given pair is such a pair:

Although Horn clause logic programs are Turing complete, for most practical applications, Horn clause programs need to be extended to "normal" logic programs with negative conditions. For example, the definition of sibling uses a negative condition, where the predicate = is defined by the clause  X = X :

Logic programming languages that include negative conditions have the knowledge representation capabilities of a non-monotonic logic.
In ASP and Datalog, logic programs have only a declarative reading, and their execution is performed by means of a proof procedure or model generator whose behaviour is not meant to be controlled by the programmer. However, in the Prolog family of languages, logic programs also have a procedural interpretation as goal-reduction procedures. From this point of view, clause A :- B1,...,Bn is understood as:

to solve A, solve B1, and ... and solve Bn.
Negative conditions in the bodies of clauses also have a procedural interpretation, known as negation as failure: A negative literal  not B is deemed to hold if and only if the positive literal  B fails to hold.
Much of the research in the field of logic programming has been concerned with trying to develop a logical semantics for negation as failure and with developing other semantics and other implementations for negation. These developments have been important, in turn, for supporting the development of formal methods for logic-based program verification and program transformation.

## Related

- [[Belief revision]]
- [[Concurrent constraint logic programming]]
- [[Concurrent logic programming]]
- [[Focused proof]]
- [[Functional logic programming]]
- [[Probabilistic logic programming]]
- [[Abductive logic programming]]
- [[Advice taker]]
- [[Answer set programming]]
- [[Array programming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Logic_programming