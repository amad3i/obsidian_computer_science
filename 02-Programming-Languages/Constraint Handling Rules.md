---
title: "Constraint Handling Rules"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Constraint_Handling_Rules"
wikipedia_categories: ["Concurrent programming languages", "Constraint logic programming", "Constraint programming languages", "Declarative programming languages"]
related: ["[[BNR Prolog]]", "[[Erlang (programming language)]]", "[[Janus (concurrent constraint programming language)]]", "[[Lucid (programming language)]]", "[[SequenceL]]", "[[XProc]]", "[[-Lisp]]", "[[QL]]", "[[Actor-Based Concurrent Language]]", "[[AgentSheets]]"]
---

# Constraint Handling Rules

Constraint Handling Rules (CHR) is a declarative, rule-based programming language, introduced in 1991 by Thom Frühwirth at the time with European Computer-Industry Research Centre (ECRC) in Munich, Germany. Originally intended for constraint programming, CHR finds applications in grammar induction, type systems, abductive reasoning, multi-agent systems, natural language processing, compilation, scheduling, spatial-temporal reasoning, testing, and verification.
A CHR program, sometimes called a constraint handler, is a set of rules that maintain a constraint store, a multi-set of logical formulas. Execution of rules may add or remove formulas from the store, thus changing the state of the program. The order in which rules "fire" on a given constraint store is non-deterministic, according to its abstract semantics and deterministic (top-down rule application), according to its refined semantics.
Although CHR is Turing complete, it is not commonly used as a programming language in its own right.  Rather, it is used to extend a host language with constraints. Prolog is by far the most popular host language and CHR is included in several Prolog implementations, including SICStus and SWI-Prolog, although CHR implementations also exist for Haskell, Java, C, SQL, and JavaScript. In contrast to Prolog, CHR rules are multi-headed and are executed in a committed-choice manner using a forward chaining algorithm.

## Related

- [[BNR Prolog]]
- [[Erlang (programming language)]]
- [[Janus (concurrent constraint programming language)]]
- [[Lucid (programming language)]]
- [[SequenceL]]
- [[XProc]]
- [[-Lisp]]
- [[QL]]
- [[Actor-Based Concurrent Language]]
- [[AgentSheets]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Constraint_Handling_Rules