---
title: "Stream (abstract data type)"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Stream_(abstract_data_type)"
wikipedia_categories: ["Functional data structures", "Functional programming", "Programming language theory stubs", "Type theory"]
related: ["[[Algebraic data type]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]", "[[Container (type theory)]]", "[[Generalized algebraic data type]]", "[[Immutable object]]", "[[Initial algebra]]", "[[Option type]]", "[[Polymorphism (computer science)]]", "[[Principal type]]", "[[Purely functional data structure]]"]
---

# Stream (abstract data type)

In type theory and functional programming, a stream is a potentially infinite analog of a list, given by the coinductive definition:

Generating and computing with streams requires lazy evaluation, either implicitly in a lazily evaluated language or by creating and forcing thunks in an eager language. In total languages they must be defined as codata and can be iterated over using (guarded) corecursion.

Java provides the Stream interface under the java.util.stream namespace.
JavaScript provides the ReadableStream, WritableStream and TransformStream interfaces.
Python have the StreamReader and StreamWriter classes in the asyncio module.
.NET provides the abstract class Stream which is implemented by classes such as FileStream and MemoryStream.
In Rust a struct can implement the Read trait. There is also the Cursor struct wraps an in-memory buffer.

## Related

- [[Algebraic data type]]
- [[Brouwer–Heyting–Kolmogorov interpretation]]
- [[Container (type theory)]]
- [[Generalized algebraic data type]]
- [[Immutable object]]
- [[Initial algebra]]
- [[Option type]]
- [[Polymorphism (computer science)]]
- [[Principal type]]
- [[Purely functional data structure]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stream_(abstract_data_type)