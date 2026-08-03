---
title: "Multi-stage programming"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Multi-stage_programming"
wikipedia_categories: ["Programming paradigms", "Type systems"]
related: ["[[Array programming]]", "[[Aspect-oriented programming]]", "[[Attribute-oriented programming]]", "[[Automata-based programming]]", "[[Automata-based programming (Shalyto's approach)]]", "[[Automatic programming]]", "[[Choreographic programming]]", "[[Comparison of multi-paradigm programming languages]]", "[[Concurrent constraint logic programming]]", "[[Concurrent logic programming]]"]
---

# Multi-stage programming

Multi-stage programming (MSP) is a variety of metaprogramming in which compilation is divided into a series of intermediate phases, allowing typesafe run-time code generation.
Statically defined types are used to verify that dynamically constructed types are valid and do not violate the type system.
In MSP languages, expressions are qualified by notation that specifies the phase at which they are to be evaluated. By allowing the specialization of a program at run-time, MSP can optimize the performance of programs: it can be considered as a form of partial evaluation that performs computations at compile-time as a trade-off to increase the speed of run-time processing.
Multi-stage programming languages support constructs similar to the Lisp construct of quotation and eval, except that scoping rules are taken into account.

## Related

- [[Array programming]]
- [[Aspect-oriented programming]]
- [[Attribute-oriented programming]]
- [[Automata-based programming]]
- [[Automata-based programming (Shalyto's approach)]]
- [[Automatic programming]]
- [[Choreographic programming]]
- [[Comparison of multi-paradigm programming languages]]
- [[Concurrent constraint logic programming]]
- [[Concurrent logic programming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multi-stage_programming