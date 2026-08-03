---
title: "Monad transformer"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Monad_transformer"
wikipedia_categories: ["Functional programming"]
related: ["[[A-normal form]]", "[[Actant]]", "[[Algebraic data type]]", "[[Anonymous function]]", "[[Applicative functor]]", "[[Arrow (computer science)]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]", "[[Catamorphism]]", "[[Coinduction]]", "[[Cons]]"]
---

# Monad transformer

In functional programming, a monad transformer is a type constructor which takes a monad as an argument and returns a monad as a result.
Monad transformers can be used to compose features encapsulated by monads – such as state, exception handling, and I/O – in a modular way. Typically, a monad transformer is created by generalising an existing monad; applying the resulting monad transformer to the identity monad yields a monad which is equivalent to the original monad (ignoring any necessary boxing and unboxing).

## Related

- [[A-normal form]]
- [[Actant]]
- [[Algebraic data type]]
- [[Anonymous function]]
- [[Applicative functor]]
- [[Arrow (computer science)]]
- [[Brouwer–Heyting–Kolmogorov interpretation]]
- [[Catamorphism]]
- [[Coinduction]]
- [[Cons]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Monad_transformer