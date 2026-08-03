---
title: "A-normal form"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/A-normal_form"
wikipedia_categories: ["Functional programming", "Implementation of functional programming languages", "Programming language topic stubs"]
related: ["[[Continuation-passing style]]", "[[Functional logic programming]]", "[[Partial application]]", "[[Supercombinator]]", "[[Access query language]]", "[[Actant]]", "[[Alef (programming language)]]", "[[Algebraic data type]]", "[[Alpha (programming language)]]", "[[Anonymous function]]"]
---

# A-normal form

In computer science, A-normal form (abbreviated ANF, sometimes expanded as administrative normal form or as atomic normal form) is an intermediate representation of programs in functional programming language compilers. 
In ANF, all arguments to a function must be trivial (constants or variables).  That is, evaluation of each argument must halt immediately. 
ANF was introduced by Sabry and Felleisen in 1992 as a simpler alternative to continuation-passing style (CPS).  Some of the advantages of using CPS as an intermediate representation are that optimizations are easier to perform on programs in CPS than in the source language, and that it is also easier for compilers to generate machine code for programs in CPS. Flanagan et al. showed how compilers could use ANF to achieve those same benefits with one source-level transformation; in contrast, for realistic compilers the CPS transformation typically involves additional phases, for example, to simplify CPS terms.

## Related

- [[Continuation-passing style]]
- [[Functional logic programming]]
- [[Partial application]]
- [[Supercombinator]]
- [[Access query language]]
- [[Actant]]
- [[Alef (programming language)]]
- [[Algebraic data type]]
- [[Alpha (programming language)]]
- [[Anonymous function]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/A-normal_form