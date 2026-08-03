---
title: "Abstract type"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Abstract_type"
wikipedia_categories: ["Type theory"]
related: ["[[Abstract data type]]", "[[Ad hoc polymorphism]]", "[[Algebraic data type]]", "[[Any type]]", "[[Attribute domain]]", "[[Automath]]", "[[Axiom of reducibility]]", "[[Bottom type]]", "[[Bounded quantification]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]"]
---

# Abstract type

In programming languages, an abstract type (also known as existential types) is a type in a nominative type system that cannot be instantiated directly; by contrast, a concrete type can be instantiated directly. Instantiation of an abstract type can occur only indirectly, via a concrete subtype. 
An abstract type may provide no implementation, or an incomplete implementation. In some languages, abstract types with no implementation (rather than an incomplete implementation) are known as protocols, interfaces, signatures, or class types. In class-based object-oriented programming, abstract types are implemented as abstract classes (also known as abstract base classes), and concrete types as concrete classes. In generic programming, the analogous notion is a concept, which similarly specifies syntax and semantics, but does not require a subtype relationship: two unrelated types may satisfy the same concept.
Often, abstract types will have one or more implementations provided separately, for example, in the form of concrete subtypes that can be instantiated. In object-oriented programming, an abstract class may include abstract methods or abstract properties that are shared by its subclasses. Other names for language features that are (or may be) used to implement abstract types include traits, mixins, flavors, roles, or type classes.
Abstract types may also include any number of non-abstract methods and properties, such as when implementing the Template Method Pattern which uses a mixture of invariant methods with fixed implementations and hook methods which can be overridden in concrete subclasses to provide custonised logic.

## Related

- [[Abstract data type]]
- [[Ad hoc polymorphism]]
- [[Algebraic data type]]
- [[Any type]]
- [[Attribute domain]]
- [[Automath]]
- [[Axiom of reducibility]]
- [[Bottom type]]
- [[Bounded quantification]]
- [[Brouwer–Heyting–Kolmogorov interpretation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Abstract_type