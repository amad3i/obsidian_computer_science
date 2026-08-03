---
title: "Supercombinator"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Supercombinator"
wikipedia_categories: ["Functional programming", "Implementation of functional programming languages", "Lambda calculus", "Theoretical computer science stubs"]
related: ["[[A-normal form]]", "[[Anonymous function]]", "[[Continuation-passing style]]", "[[Currying]]", "[[Function application]]", "[[Higher-order function]]", "[[Lambda lifting]]", "[[Partial application]]", "[[Actant]]", "[[Algebraic data type]]"]
---

# Supercombinator

A supercombinator is a mathematical expression which is fully bound and self-contained. It may be either a constant or a combinator where all the subexpressions are supercombinators. Supercombinators are used in the implementation of functional languages.
In mathematical terms, a lambda expression S is a supercombinator of arity n if it has no free variables and is of the form λx1.λx2...λxn.E (with n ≥ 0, so that lambdas are not required) such that E itself is not a lambda abstraction and any lambda abstraction in E is again a supercombinator.

## Related

- [[A-normal form]]
- [[Anonymous function]]
- [[Continuation-passing style]]
- [[Currying]]
- [[Function application]]
- [[Higher-order function]]
- [[Lambda lifting]]
- [[Partial application]]
- [[Actant]]
- [[Algebraic data type]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Supercombinator