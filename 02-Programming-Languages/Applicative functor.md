---
title: "Applicative functor"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Applicative_functor"
wikipedia_categories: ["Functional programming", "Programming idioms", "Software design patterns"]
related: ["[[Monad (functional programming)]]", "[[Resource acquisition is initialization]]", "[[Store-passing style]]", "[[A-normal form]]", "[[Abstract factory pattern]]", "[[Actant]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]"]
---

# Applicative functor

In functional programming, an applicative functor, or an applicative for short, is an intermediate structure between functors and monads. Applicative functors allow for functorial computations to be sequenced (unlike plain functors), but don't allow using results from prior computations in the definition of subsequent ones (unlike monads).
In terms of category theory, applicative functors may be defined as lax monoidal functors with tensorial strength. This may not be the most obvious categorification of the standard definition of applicative functor given below, but they are equivalent in the category of Haskell types. Note that the observation that all monads are applicative functors is specific to the category of Haskell types, and is not true in general with this categorical definition of applicative functor; monads in an arbitrary category need not preserve any monoidal product.
Applicative functors were introduced in 2008 by Conor McBride and Ross Paterson in their paper Applicative programming with effects.
Applicative functors first appeared as a library feature in Haskell, but have since spread to other languages such as  Idris, Agda, OCaml, Scala, and F#. Glasgow Haskell, Idris, and F# offer language features designed to ease programming with applicative functors.
In Haskell, applicative functors are implemented in the Applicative type class.
While in languages like Haskell monads are applicative functors, this is not always the case in general settings of category theory—examples of monads which are not strong can be found on Math Overflow.

## Related

- [[Monad (functional programming)]]
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

- Wikipedia: https://en.wikipedia.org/wiki/Applicative_functor