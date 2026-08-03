---
title: "Interface (object-oriented programming)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Interface_(object-oriented_programming)"
wikipedia_categories: ["Data types", "Object-oriented programming", "Programming language comparisons"]
related: ["[[Polymorphism (computer science)]]", "[[Boxing (computer programming)]]", "[[Comparison of programming languages (object-oriented programming)]]", "[[Constructor (object-oriented programming)]]", "[[Factory (object-oriented programming)]]", "[[Flow-sensitive typing]]", "[[Opaque data type]]", "[[Option type]]", "[[Property (programming)]]", "[[Subtyping]]"]
---

# Interface (object-oriented programming)

In object-oriented programming, an interface or protocol type  is a data type that acts as an abstraction of a class. It describes a set of method signatures, the implementations of which may be provided by multiple classes that are otherwise not necessarily related to each other. A class which provides the methods listed in an interface is said to implement the interface, or to adopt the protocol.
Interfaces are useful for encapsulation and reducing coupling. For example, in Java, the java.lang.Comparable<T> interface specifies the method compareTo(). Thus, a sorting method only needs to take objects of types which implement java.lang.Comparable<T> to sort them, without knowing about the inner nature of the class (except that two of these objects can be compared via compareTo()).

## Related

- [[Polymorphism (computer science)]]
- [[Boxing (computer programming)]]
- [[Comparison of programming languages (object-oriented programming)]]
- [[Constructor (object-oriented programming)]]
- [[Factory (object-oriented programming)]]
- [[Flow-sensitive typing]]
- [[Opaque data type]]
- [[Option type]]
- [[Property (programming)]]
- [[Subtyping]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Interface_(object-oriented_programming)