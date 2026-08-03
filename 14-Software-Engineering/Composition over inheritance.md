---
title: "Composition over inheritance"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Composition_over_inheritance"
wikipedia_categories: ["Component-based software engineering", "Programming principles", "Software architecture"]
related: ["[[Inversion of control]]", "[[Cohesion (computer science)]]", "[[Common Component Architecture]]", "[[Component-based software engineering]]", "[[Coupling (computer programming)]]", "[[Dependency injection]]", "[[4+1 architectural view model]]", "[[Active reviews for intermediate designs]]", "[[Agent architecture]]", "[[Anemic domain model]]"]
---

# Composition over inheritance

In object-oriented programming, composition over inheritance (sometimes composition with forwarding or composite reuse) is a common design pattern that tries to achieve code reuse without requiring inheritance. Instead of having two child classes inherit functionality from a common parent, composition simulates inheritance by having the children include a copy of a "pseudo-parent" class as a field, which implements the functionality common to the two classes. Then, methods that would have been called on the child are instead called on the pseudo-parent, a technique called method forwarding.
Composition is generally used in languages where inheritance is unavailable or has an implementation that is considered inflexible, inconvenient, or inadequate (e.g. because a language lacks multiple inheritance). However, many problems that are easily solved with inheritance are difficult to solve using only composition; as a result, inheritance and object composition typically work hand-in-hand, as discussed in the book Design Patterns (1994).

## Related

- [[Inversion of control]]
- [[Cohesion (computer science)]]
- [[Common Component Architecture]]
- [[Component-based software engineering]]
- [[Coupling (computer programming)]]
- [[Dependency injection]]
- [[4+1 architectural view model]]
- [[Active reviews for intermediate designs]]
- [[Agent architecture]]
- [[Anemic domain model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Composition_over_inheritance