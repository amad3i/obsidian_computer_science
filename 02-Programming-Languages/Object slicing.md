---
title: "Object slicing"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Object_slicing"
wikipedia_categories: ["C++", "Object-oriented programming"]
related: ["[[Dominance (C++)]]", "[[Resource acquisition is initialization]]", "[[Virtual function]]", "[[Abstraction (computer science)]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]", "[[Association (object-oriented programming)]]", "[[Behavioral subtyping]]", "[[Bounded quantification]]", "[[C++]]"]
---

# Object slicing

In C++ programming, object slicing occurs when an object of a subclass type is copied to an object of superclass type: the superclass copy will not have any of the member variables or member functions defined in the subclass. These variables and functions have, in effect, been "sliced off".
More subtly, object slicing can likewise occur when an object of a subclass type is copied to an object of the same type by the superclass's assignment operator, in which case some of the target object's member variables will retain their original values instead of getting copied over from the source object.
This issue is not inherently unique to C++, but it does not occur naturally in most other object-oriented languages — not even in C++'s relatives such as D, Java, and C# — because copying of objects is not a basic operation in those languages. Instead, those languages prefer to manipulate objects via implicit references, such that only copying the reference is a basic operation. By contrast, in C++ objects are copied automatically whenever a function takes an object argument by value or returns an object by value. Meanwhile, Rust avoids object slicing entirely by avoiding structural inheritance, while using traits and dynamic dispatch to achieve polymorphism and enforcing type size safety using the std::marker::Sized trait.
Additionally, due to the lack of garbage collection in C++, programs will frequently copy an object whenever the ownership and lifetime of a single shared object would be unclear. For example, inserting an object into a standard library collection (such as a std::vector) typically involves making and inserting a copy into the collection.
When using method chaining and the fluent interface pattern, there is a potential risk of object slicing in C++ if a method from a base class is called on a derived class that returns a reference to the base class.
Object slicing has been the target of criticism for its subtleties.

## Related

- [[Dominance (C++)]]
- [[Resource acquisition is initialization]]
- [[Virtual function]]
- [[Abstraction (computer science)]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]
- [[Association (object-oriented programming)]]
- [[Behavioral subtyping]]
- [[Bounded quantification]]
- [[C++]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Object_slicing