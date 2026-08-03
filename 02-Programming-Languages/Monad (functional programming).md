---
title: "Monad (functional programming)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Monad_(functional_programming)"
wikipedia_categories: ["1991 in computing", "Functional programming", "Programming idioms", "Software design patterns"]
related: ["[[Applicative functor]]", "[[Resource acquisition is initialization]]", "[[Store-passing style]]", "[[A-normal form]]", "[[Abstract factory pattern]]", "[[Actant]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]"]
---

# Monad (functional programming)

In functional programming, monads are a way to structure computations as a sequence of steps, where each step produces a value, plus some extra information about the computation, such as a potential failure, non-determinism, or side effect. More formally, a monad is a type constructor M equipped with two operations, return : <A>(a : A) -> M(A) which lifts a value into the monadic context, and bind : <A,B>(m_a : M(A), f : A -> M(B)) -> M(B) which chains monadic computations. In simpler terms, monads can be thought of as interfaces implemented on type constructors, that allow for functions to abstract over various type constructor variants that implement monad (e.g. Option, List, etc.).
Both the concept of a monad and the term originally come from category theory, where a monad is defined as an endofunctor with additional structure. Research beginning in the late 1980s and early 1990s established that monads could bring seemingly disparate computer-science problems under a unified, functional model. Category theory also provides a few formal requirements, known as the monad laws, which should be satisfied by any monad and can be used to verify monadic code.
Since monads make semantics explicit for a kind of computation, they can also be used to implement convenient language features. Some languages, such as Haskell, even offer pre-built definitions in their core libraries for the general monad structure and common instances.

## Related

- [[Applicative functor]]
- [[Resource acquisition is initialization]]
- [[Store-passing style]]
- [[A-normal form]]
- [[Abstract factory pattern]]
- [[Actant]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Monad_(functional_programming)