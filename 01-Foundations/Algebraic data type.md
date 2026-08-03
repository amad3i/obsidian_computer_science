---
title: "Algebraic data type"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Algebraic_data_type"
wikipedia_categories: ["Composite data types", "Data types", "Functional programming", "Type theory"]
related: ["[[Generalized algebraic data type]]", "[[Composite data type]]", "[[Cons]]", "[[Intersection type]]", "[[Option type]]", "[[Polymorphism (computer science)]]", "[[Product type]]", "[[Quotient type]]", "[[Type class]]", "[[Type family]]"]
---

# Algebraic data type

In computer programming, especially in functional programming and type theory, an algebraic data type (ADT) is a composite data type, i.e. a type formed by combining other types.
An algebraic data type is defined by two key constructions: a sum and a product. These are sometimes referred to as "OR" and "AND" types.
A sum type is a choice between possibilities. The value of a sum type can match one of several defined variants. For example, a type representing the state of a traffic light could be either Red, Amber, or Green. A shape type could be either a Circle (which stores a radius) or a Square (which stores a width). In formal terms, these variants are known as tagged unions or disjoint unions. Each variant has a name, called a constructor, which can also carry data. Enumerated types are a simple form of sum type where the constructors carry no data.
A product type combines types together. A value of a product type will contain a value for each of its component types. For example, a Point type might be defined to contain an x coordinate (an integer) and a y coordinate (also an integer). Formal examples of product types include tuples and records. The set of all possible values of a product type is the Cartesian product of the sets of its component types.
Values of algebraic data types are typically handled using pattern matching. This feature allows a programmer to check which constructor a value was made with and extract the data it contains in a convenient and type-safe way.

## Related

- [[Generalized algebraic data type]]
- [[Composite data type]]
- [[Cons]]
- [[Intersection type]]
- [[Option type]]
- [[Polymorphism (computer science)]]
- [[Product type]]
- [[Quotient type]]
- [[Type class]]
- [[Type family]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Algebraic_data_type