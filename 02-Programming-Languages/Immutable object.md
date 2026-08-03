---
title: "Immutable object"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Immutable_object"
wikipedia_categories: ["Functional data structures", "Functional programming", "Object (computer science)"]
related: ["[[Purely functional data structure]]", "[[Stream (abstract data type)]]", "[[Zipper (data structure)]]", "[[A-normal form]]", "[[Actant]]", "[[Algebraic data type]]", "[[Anonymous function]]", "[[Applicative functor]]", "[[Arrow (computer science)]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]"]
---

# Immutable object

In object-oriented (OO) and functional programming, an immutable object (unchangeable object) is an object whose state cannot be modified after it is created. This is in contrast to a mutable object (changeable object), which can be modified after it is created. In some cases, an object is considered immutable even if some internally used attributes change, but the object's state appears unchanging from an external point of view. For example, an object that uses memoization to cache the results of expensive computations could still be considered an immutable object.
Strings and other concrete objects are typically expressed as immutable objects to improve readability and runtime efficiency in object-oriented programming. Immutable objects are also useful because they are inherently thread-safe. Other benefits are that they are simpler to understand and reason about and offer higher security than mutable objects.

## Related

- [[Purely functional data structure]]
- [[Stream (abstract data type)]]
- [[Zipper (data structure)]]
- [[A-normal form]]
- [[Actant]]
- [[Algebraic data type]]
- [[Anonymous function]]
- [[Applicative functor]]
- [[Arrow (computer science)]]
- [[Brouwer–Heyting–Kolmogorov interpretation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Immutable_object