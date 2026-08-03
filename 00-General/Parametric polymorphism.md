---
title: "Parametric polymorphism"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Parametric_polymorphism"
wikipedia_categories: ["Generic programming", "Polymorphism (computer science)", "Type theory"]
related: ["[[Polymorphism (computer science)]]", "[[Ad hoc polymorphism]]", "[[Bounded quantification]]", "[[Intersection type]]", "[[Intersection type discipline]]", "[[Parametricity]]", "[[Subtyping]]", "[[System F]]", "[[Type variable]]", "[[Type variance]]"]
---

# Parametric polymorphism

In programming languages and type theory, parametric polymorphism allows a single piece of code to be given a "generic" type, using variables in place of actual types, and then instantiated with particular types as needed. Parametrically polymorphic functions and data types are sometimes called generic functions and generic datatypes, respectively, and they form the basis of generic programming.
Parametric polymorphism may be contrasted with ad hoc polymorphism. Parametrically polymorphic definitions are uniform: they behave identically regardless of the type they are instantiated at. In contrast, ad hoc polymorphic definitions are given a distinct definition for each type. Thus, ad hoc polymorphism can generally only support a limited number of such distinct types, since a separate implementation has to be provided for each type.
The usual theoretical device for studying parametric polymorphism is system F, which extends simply typed lambda calculus with quantification over types.

## Related

- [[Polymorphism (computer science)]]
- [[Ad hoc polymorphism]]
- [[Bounded quantification]]
- [[Intersection type]]
- [[Intersection type discipline]]
- [[Parametricity]]
- [[Subtyping]]
- [[System F]]
- [[Type variable]]
- [[Type variance]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Parametric_polymorphism