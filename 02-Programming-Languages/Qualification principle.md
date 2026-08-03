---
title: "Qualification principle"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Qualification_principle"
wikipedia_categories: ["Computer science stubs", "Programming language theory", "Programming language topic stubs"]
related: ["[[Semantic dictionary encoding]]", "[[Typed assembly language]]", "[[Divergence (computer science)]]", "[[Logic of Computable Functions]]", "[[Occam-π]]", "[[Real-time Programming Language]]", "[[Variadic]]", "[[A-normal form]]", "[[Abstract syntax]]", "[[Access query language]]"]
---

# Qualification principle

In programming language theory, the qualification principle states that any semantically meaningful syntactic class may admit local definitions. In other words, it's possible to include a block in any syntactic class, provided that the phrases of that class specify some kind of computation. (Watt 1990)
A common examples for of this principle includes:

block command -- a command containing a local declaration, which is used only for executing this command. In the following excerpt from a C program, tmp variable declared is local to the surrounding block command:

block expression -- an expression containing a local declaration, which is used only for evaluating this expression. In the following excerpt from ML program, local declaration of g can be used only during evaluation of the following expression:

block declaration is one containing a local declaration, the bindings produced by which are used only for elaborating the block declaration. In the following excerpt from ML program, local declaration of function leap, using an auxiliary function multiple:

## Related

- [[Semantic dictionary encoding]]
- [[Typed assembly language]]
- [[Divergence (computer science)]]
- [[Logic of Computable Functions]]
- [[Occam-π]]
- [[Real-time Programming Language]]
- [[Variadic]]
- [[A-normal form]]
- [[Abstract syntax]]
- [[Access query language]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Qualification_principle