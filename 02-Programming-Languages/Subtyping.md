---
title: "Subtyping"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Subtyping"
wikipedia_categories: ["Data types", "Object-oriented programming", "Polymorphism (computer science)", "Type theory"]
related: ["[[Polymorphism (computer science)]]", "[[Bounded quantification]]", "[[Intersection type]]", "[[Type variance]]", "[[Abstract data type]]", "[[Ad hoc polymorphism]]", "[[Algebraic data type]]", "[[Any type]]", "[[Bottom type]]", "[[Composite data type]]"]
---

# Subtyping

In programming language theory, subtyping (also called subtype polymorphism or inclusion polymorphism) is a form of type polymorphism. A subtype is a datatype that is related to another datatype (the supertype) by some notion of substitutability, meaning that program elements (typically subroutines or functions), written to operate on elements of the supertype, can also operate on elements of the subtype. 
If S is a subtype of T, the subtyping relation (written as S <: T,  S ⊑ T, or  S ≤: T ) means that any term of type S can safely be used in any context where a term of type T is expected. The precise semantics of subtyping here crucially depends on the particulars of how "safely be used" and "any context" are defined by a given type formalism or programming language. The type system of a programming language essentially defines its own subtyping relation, which may well be trivial, should the language support no (or very little) conversion mechanisms.
Due to the subtyping relation, a term may belong to more than one type. Subtyping is therefore a form of type polymorphism. In object-oriented programming the term 'polymorphism' is commonly used to refer solely to this subtype polymorphism, while the techniques of parametric polymorphism would be considered generic programming.
Functional programming languages often allow the subtyping of records. Consequently, simply typed lambda calculus extended with record types is perhaps the simplest theoretical setting in which a useful notion of subtyping may be defined and studied. Because the resulting calculus allows terms to have more than one type, it is no longer a "simple" type theory. Since functional programming languages, by definition, support function literals, which can also be stored in records, records types with subtyping provide some of the features of object-oriented programming. Typically, functional programming languages also provide some, usually restricted, form of parametric polymorphism. In a theoretical setting, it is desirable to study the interaction of the two features; a common theoretical setting is system F<:. Various calculi that attempt to capture the theoretical properties of object-oriented programming may be derived from system F<:.
The concept of subtyping is related to the linguistic notions of hyponymy and holonymy. It is also related to the concept of bounded quantification in mathematical logic (see Order-sorted logic). Subtyping should not be confused with the notion of (class or object) inheritance from object-oriented languages; subtyping is a relation between types (interfaces in object-oriented parlance) whereas inheritance is a relation between implementations stemming from a language feature that allows new objects to be created from existing ones. In a number of object-oriented languages, subtyping is called interface inheritance, with inheritance referred to as implementation inheritance.

## Related

- [[Polymorphism (computer science)]]
- [[Bounded quantification]]
- [[Intersection type]]
- [[Type variance]]
- [[Abstract data type]]
- [[Ad hoc polymorphism]]
- [[Algebraic data type]]
- [[Any type]]
- [[Bottom type]]
- [[Composite data type]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Subtyping