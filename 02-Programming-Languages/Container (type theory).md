---
title: "Container (type theory)"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Container_(type_theory)"
wikipedia_categories: ["Programming language theory stubs", "Type theory"]
related: ["[[Principal type]]", "[[Refinement type]]", "[[Stream (abstract data type)]]", "[[Type inhabitation]]", "[[Typing environment]]", "[[Typing rule]]", "[[Abstract data type]]", "[[Abstract type]]", "[[Ad hoc polymorphism]]", "[[Algebraic data type]]"]
---

# Container (type theory)

In type theory, a discipline within mathematical logic, containers are abstractions which permit various "collection types", such as lists and trees, to be represented in a uniform way. A (unary) container is defined by a type of shapes S and a type family of positions P, indexed by S. The extension of a container is a family of dependent pairs consisting of a shape (of type S) and a function from positions of that shape to the element type. Containers can be seen as canonical forms (standard form) for collection types.
For lists, the shape type is the natural numbers (including zero). The corresponding position types are the types of natural numbers less than the shape, for each shape.
For trees, the shape type is the type of trees of units (that is, trees with no information in them, just structure). The corresponding position types are isomorphic to the types of valid paths from the root to particular nodes on the shape, for each shape.
Note that the natural numbers are isomorphic to lists of units. In general the shape type will always be isomorphic to the original non-generic container type family (list, tree etc.) applied to unit.
One of the main motivations for introducing the notion of containers is to support generic programming in a dependently typed setting.

## Related

- [[Principal type]]
- [[Refinement type]]
- [[Stream (abstract data type)]]
- [[Type inhabitation]]
- [[Typing environment]]
- [[Typing rule]]
- [[Abstract data type]]
- [[Abstract type]]
- [[Ad hoc polymorphism]]
- [[Algebraic data type]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Container_(type_theory)