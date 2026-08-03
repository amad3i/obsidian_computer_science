---
title: "Opaque data type"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Opaque_data_type"
wikipedia_categories: ["Data types", "Object-oriented programming"]
related: ["[[Interface (object-oriented programming)]]", "[[Polymorphism (computer science)]]", "[[Subtyping]]", "[[4D vector]]", "[[Abstract data type]]", "[[Abstraction (computer science)]]", "[[Address constant]]", "[[Algebraic data type]]", "[[Ambiguous viewpoint]]", "[[Anonymous function]]"]
---

# Opaque data type

In computer science, an opaque data type is a data type whose concrete data structure is not defined in an interface. This enforces information hiding, since its values can only be manipulated by calling subroutines that have access to the missing information. The concrete representation of the type is hidden from its users, and the visible implementation is incomplete. A data type whose representation is visible is called transparent. Opaque data types are frequently used to implement abstract data types.
Typical examples of opaque data types include handles for resources provided by an operating system to application software. For example, the POSIX standard for threads defines an application programming interface based on a number of opaque types that represent threads or synchronization primitives like mutexes or condition variables.
An opaque pointer is a special case of an opaque data type, a datatype that is declared to be a pointer to a record or data structure of some unspecified data type. For example, the standard library that forms part of the specification of the C programming language provides functions for file input and output that return or take values of type "pointer to FILE" that represent file streams (see C file input/output), but the concrete implementation of the type FILE is not specified.

## Related

- [[Interface (object-oriented programming)]]
- [[Polymorphism (computer science)]]
- [[Subtyping]]
- [[4D vector]]
- [[Abstract data type]]
- [[Abstraction (computer science)]]
- [[Address constant]]
- [[Algebraic data type]]
- [[Ambiguous viewpoint]]
- [[Anonymous function]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Opaque_data_type