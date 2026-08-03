---
title: "Singly rooted hierarchy"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Singly_rooted_hierarchy"
wikipedia_categories: ["Computer programming stubs", "Object-oriented programming"]
related: ["[[Association (object-oriented programming)]]", "[[Convention over Code]]", "[[Indexer (programming)]]", "[[Runtime Callable Wrapper]]", "[[Abstraction (computer science)]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Aggregate pattern]]", "[[Ambiguous viewpoint]]", "[[ASCEND]]"]
---

# Singly rooted hierarchy

The singly rooted hierarchy, in object-oriented programming, is a characteristic of most (but not all) object-oriented programming languages. In most such languages, in fact, all classes inherit directly or indirectly from a single root, usually with a name similar to Object; all classes then form a common inheritance hierarchy.
This idea was introduced first by Smalltalk, and was since used in most other object-oriented languages (notably Java with java.lang.Object and C# with System.Object). This feature is especially useful for container libraries - they only need to allow putting an Object in a container to allow objects of any class to be put in the container.
A notable exception is C++, where (mainly for compatibility with C and efficiency) there is no single object hierarchy. Containers in C++ have been implemented with multiple inheritance, and with help of template-based generic programming by Bjarne Stroustrup. Although no root class exists in C++, there is an any type, std::any, which acts as a type-erased container; Rust also features a similar std::any::Any type-erased any type. Also, like in C, a void* may point to any object. Other object-oriented languages without a singly rooted hierarchy include Objective-C and PHP.

## Related

- [[Association (object-oriented programming)]]
- [[Convention over Code]]
- [[Indexer (programming)]]
- [[Runtime Callable Wrapper]]
- [[Abstraction (computer science)]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Aggregate pattern]]
- [[Ambiguous viewpoint]]
- [[ASCEND]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Singly_rooted_hierarchy