---
title: "Type variance"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Type_variance"
wikipedia_categories: ["Object-oriented programming", "Polymorphism (computer science)", "Programming language comparisons", "Type theory"]
related: ["[[Polymorphism (computer science)]]", "[[Bounded quantification]]", "[[Subtyping]]", "[[Ad hoc polymorphism]]", "[[Comparison of programming languages (object-oriented programming)]]", "[[Constructor (object-oriented programming)]]", "[[Duck typing]]", "[[Factory (object-oriented programming)]]", "[[Flow-sensitive typing]]", "[[Interface (object-oriented programming)]]"]
---

# Type variance

In computer programming, type variance is the relationship between subtypes of a composite type (e.g. List[Int]) and the subtypes of its components (e.g. Int). A language's chosen variance determines the relationship between, for example, a list of Cats and a list of Animals, or a function returning Cat and a function returning Animal. 
If the type Cat is a subtype of Animal, then an expression of type Cat should be substitutable wherever an expression of type Animal is used. Depending on the variance of the type constructor, the subtyping relation of the simple types may be either preserved, reversed, or ignored for the respective complex types. In many programming languages, for example, "list of Cat" will be a subtype of "list of Animal", because the list type constructor is covariant. This means that the subtyping relation of the simple types is preserved for the complex types. On the other hand, "function from Animal to String" is a subtype of "function from Cat to String" because the function type constructor is contravariant in the parameter type. Here, the subtyping relation of the simple types is reversed for the complex types.
A programming language designer will consider variance when devising typing rules for language features such as arrays, inheritance, and generic datatypes. By making type constructors covariant or contravariant instead of invariant, more programs will be accepted as well-typed. On the other hand, programmers often find contravariance unintuitive, and accurately tracking variance to avoid runtime type errors can lead to complex typing rules.
In order to keep the type system simple and allow useful programs, a language may treat a type constructor as invariant even if it would be safe to consider it variant, or treat it as covariant even though that could violate type safety.

## Related

- [[Polymorphism (computer science)]]
- [[Bounded quantification]]
- [[Subtyping]]
- [[Ad hoc polymorphism]]
- [[Comparison of programming languages (object-oriented programming)]]
- [[Constructor (object-oriented programming)]]
- [[Duck typing]]
- [[Factory (object-oriented programming)]]
- [[Flow-sensitive typing]]
- [[Interface (object-oriented programming)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Type_variance