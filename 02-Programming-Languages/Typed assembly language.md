---
title: "Typed assembly language"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Typed_assembly_language"
wikipedia_categories: ["Assembly languages", "Computer science stubs", "Cybersecurity engineering", "Programming language theory", "Programming language topic stubs"]
related: ["[[Qualification principle]]", "[[Semantic dictionary encoding]]", "[[Divergence (computer science)]]", "[[IBM 1401 Symbolic Programming System]]", "[[IJVM]]", "[[Logic of Computable Functions]]", "[[MACRO-11]]", "[[Occam-π]]", "[[Proof-carrying code]]", "[[Real-time Programming Language]]"]
---

# Typed assembly language

In computer science, a typed assembly language (TAL) is an assembly language that is extended to include a method of annotating the datatype of each value that is manipulated by the code. These annotations can then be used by a program (type checker) that processes the assembly language code in order to analyse how it will behave when it is executed.  Specifically, such a type checker can be used to prove the type safety of code that meets the criteria of some appropriate type system.
Typed assembly languages provide mechanisms for describing and verifying the types of values stored in registers and memory. These mechanisms allow the type system to enforce safe use of pointers, stack frames, and heap-allocated data structures, independent of any particular memory management strategy.
A typed assembly language can be used to support a trusted execution environment. As safety properties can be verified statically by checking the program's types, TAL based systems execute native code directly without relying on interpreted bytecode or a virtual machine.

## Related

- [[Qualification principle]]
- [[Semantic dictionary encoding]]
- [[Divergence (computer science)]]
- [[IBM 1401 Symbolic Programming System]]
- [[IJVM]]
- [[Logic of Computable Functions]]
- [[MACRO-11]]
- [[Occam-π]]
- [[Proof-carrying code]]
- [[Real-time Programming Language]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Typed_assembly_language