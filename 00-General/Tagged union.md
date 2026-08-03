---
title: "Tagged union"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Tagged_union"
wikipedia_categories: ["Data types", "Type theory"]
related: ["[[Abstract data type]]", "[[Algebraic data type]]", "[[Any type]]", "[[Bottom type]]", "[[Composite data type]]", "[[Enumerated type]]", "[[Flow-sensitive typing]]", "[[Function type]]", "[[Generalized algebraic data type]]", "[[Intersection type]]"]
---

# Tagged union

In computer science, a tagged union, also called a variant, variant record, choice type, discriminated union, disjoint union, sum type, or coproduct, is a data structure used to hold a value that could take on several different, but fixed, types. Only one of the types can be in use at any one time, and a tag field explicitly indicates which type is in use. It can be thought of as a type that has several "cases", each of which should be handled correctly when that type is manipulated. This is critical in defining recursive datatypes, in which some component of a value may have the same type as that value, for example in defining a type for representing trees, where it is necessary to distinguish multi-node subtrees and leaves. Like ordinary unions, tagged unions can save storage by overlapping storage areas for each type, since only one is in use at a time.

## Related

- [[Abstract data type]]
- [[Algebraic data type]]
- [[Any type]]
- [[Bottom type]]
- [[Composite data type]]
- [[Enumerated type]]
- [[Flow-sensitive typing]]
- [[Function type]]
- [[Generalized algebraic data type]]
- [[Intersection type]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tagged_union