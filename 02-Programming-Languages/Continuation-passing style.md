---
title: "Continuation-passing style"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Continuation-passing_style"
wikipedia_categories: ["Continuations", "Functional programming", "Implementation of functional programming languages"]
related: ["[[A-normal form]]", "[[Partial application]]", "[[Supercombinator]]", "[[Actant]]", "[[Algebraic data type]]", "[[Anonymous function]]", "[[Applicative functor]]", "[[Arrow (computer science)]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]", "[[Catamorphism]]"]
---

# Continuation-passing style

In functional programming, continuation-passing style (CPS) is a style of programming in which control is passed explicitly in the form of a continuation. This is contrasted with direct style, which is the usual style of programming. Gerald Jay Sussman and Guy L. Steele, Jr. coined the phrase in AI Memo 349 (1975), which sets out the first version of the Scheme programming language.
John C. Reynolds gives a detailed account of the many discoveries of continuations.
A function written in continuation-passing style takes an extra argument: an explicit continuation; i.e., a function of one argument. When the CPS function has computed its result value, it "returns" it by calling the continuation function with this value as the argument. That means that when invoking a CPS function, the calling function is required to supply a procedure to be invoked with the subroutine's "return" value. Expressing code in this form makes a number of things explicit which are implicit in direct style. These include: procedure returns, which become apparent as calls to a continuation; intermediate values, which are all given names; order of argument evaluation, which is made explicit; and tail calls, which simply call a procedure with the same continuation, unmodified, that was passed to the caller.
Programs can be automatically transformed from direct style to CPS. Compilers for functional and logic programming languages often use CPS as an intermediate representation where a compiler for an imperative or procedural programming language would use static single assignment form (SSA). SSA is formally equivalent to a subset of CPS (excluding non-local control flow, which does not occur when CPS is used as intermediate representation). Functional compilers can also use A-normal form (ANF) (but only for languages requiring eager evaluation), rather than with thunks (described in the examples below) in CPS. CPS is used more frequently by compilers than by programmers as a local or global style.

## Related

- [[A-normal form]]
- [[Partial application]]
- [[Supercombinator]]
- [[Actant]]
- [[Algebraic data type]]
- [[Anonymous function]]
- [[Applicative functor]]
- [[Arrow (computer science)]]
- [[Brouwer–Heyting–Kolmogorov interpretation]]
- [[Catamorphism]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Continuation-passing_style