---
title: "Void type"
tags: ["cs", "general-cs", "advanced"]
domain: General CS
level: advanced
source: "https://en.wikipedia.org/wiki/Void_type"
wikipedia_categories: ["Data types", "Type theory", "Unknown content"]
related: ["[[Abstract data type]]", "[[Algebraic data type]]", "[[Any type]]", "[[Bottom type]]", "[[Composite data type]]", "[[Empty type]]", "[[Enumerated type]]", "[[Flow-sensitive typing]]", "[[Function type]]", "[[Generalized algebraic data type]]"]
---

# Void type

The void type, in several programming languages, more so curly bracket programming languages derived from C and ALGOL 68, is the return type of a function that returns normally, but provides no result value to its caller. Usually such functions are called for their side effects, such as performing some task or writing to their input parameters. The use of the void data type in such context is comparable to procedures in Pascal and syntactic constructs which define subroutines in Visual Basic. It is also similar to the unit type used in functional programming languages and type theory. See Unit type#In programming languages for a comparison.
C and C++ also support the void pointer (or pointer to void type), denoted void*, but this is an unrelated notion. Variables of this type are pointers to data of an unspecified type, so in this context (but not the others) void* acts roughly like a universal or any type; it does not literally "point" to a void in memory. A program can convert a pointer to any type of data (except a function pointer) to a pointer to void and back to the original type without losing information, which makes these pointers useful for polymorphic functions. The C language standard does not guarantee that the different pointer types have the same size or alignment.

## Related

- [[Abstract data type]]
- [[Algebraic data type]]
- [[Any type]]
- [[Bottom type]]
- [[Composite data type]]
- [[Empty type]]
- [[Enumerated type]]
- [[Flow-sensitive typing]]
- [[Function type]]
- [[Generalized algebraic data type]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Void_type