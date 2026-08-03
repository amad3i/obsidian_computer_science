---
title: "Abstract data type"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Abstract_data_type"
wikipedia_categories: ["Abstract data types", "Data types", "Type theory"]
related: ["[[Algebraic data type]]", "[[Any type]]", "[[Associative array]]", "[[Bottom type]]", "[[Composite data type]]", "[[Enumerated type]]", "[[Flow-sensitive typing]]", "[[Function type]]", "[[Generalized algebraic data type]]", "[[Intersection type]]"]
---

# Abstract data type

In computer science, an abstract data type (ADT) is a mathematical model for data types, defined by its behavior (semantics) from the point of view of a user of the data, specifically in terms of possible values, possible operations on data of this type, and the behavior of these operations. This mathematical model contrasts with data structures, which are concrete representations of data, and represent the point of view of an implementer, not a user. For example, a stack has push/pop operations that follow a Last-In-First-Out rule, and can be concretely implemented using either a linked list or an array. Another example is a set which stores values, without any particular order, and no repeated values. Values themselves are not retrieved from sets; rather, one tests a value for membership to obtain a Boolean "in" or "not in".
ADTs are a theoretical concept, used in formal semantics and program verification and, less strictly, in the design and analysis of algorithms, data structures, and software systems. Most mainstream computer languages do not directly support formally specifying ADTs. However, various programming language features correspond to certain aspects of implementing ADTs and are often confused with ADTs themselves; these include abstract types, opaque data types, protocols, and design by contract. For example, in modular programming, the module declares procedures that correspond to the ADT operations, often with comments that describe the constraints. This information hiding strategy allows the implementation of the module to be changed without disturbing the client programs, but the module only informally defines an ADT. The notion of abstract data types is related to the concept of data abstraction, important in object-oriented programming and design by contract methodologies for software engineering.

## Related

- [[Algebraic data type]]
- [[Any type]]
- [[Associative array]]
- [[Bottom type]]
- [[Composite data type]]
- [[Enumerated type]]
- [[Flow-sensitive typing]]
- [[Function type]]
- [[Generalized algebraic data type]]
- [[Intersection type]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Abstract_data_type