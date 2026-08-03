---
title: "Dependency injection"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Dependency_injection"
wikipedia_categories: ["Component-based software engineering", "Software architecture", "Software design patterns"]
related: ["[[Inversion of control]]", "[[Bulkhead pattern]]", "[[Common Component Architecture]]", "[[Component-based software engineering]]", "[[Composition over inheritance]]", "[[Data, context and interaction]]", "[[Debugging pattern]]", "[[JSP model 1 architecture]]", "[[JSP model 2 architecture]]", "[[Multitier architecture]]"]
---

# Dependency injection

In software engineering, dependency injection is a programming technique in which an object or function receives other objects or functions that it requires, as opposed to creating them internally. Dependency injection aims to separate the concerns of constructing objects and using them, leading to loosely coupled programs. The pattern ensures that an object or function that wants to use a given service should not have to know how to construct those services. Instead, the receiving "client" (object or function) is provided with its dependencies by external code (an "injector"), which it is not aware of. Dependency injection makes implicit dependencies explicit and helps solve the following problems:

How can a class be independent from the creation of the objects it depends on?
How can an application and the objects it uses support different configurations?
Dependency injection is often used to keep code in-line with the dependency inversion principle.
In statically typed languages using dependency injection means that a client only needs to declare the interfaces of the services it uses, rather than their concrete implementations, making it easier to change which services are used at runtime without recompiling.
Application frameworks often combine dependency injection with inversion of control. Under inversion of control, the framework first constructs an object (such as a controller), and then passes control flow to it. With dependency injection, the framework also instantiates the dependencies declared by the application object (often in the constructor method's parameters), and passes the dependencies into the object.
Dependency injection implements the idea of "inverting control over the implementations of dependencies", which is why certain Java frameworks generically name the concept "inversion of control" (not to be confused with inversion of control flow).

## Related

- [[Inversion of control]]
- [[Bulkhead pattern]]
- [[Common Component Architecture]]
- [[Component-based software engineering]]
- [[Composition over inheritance]]
- [[Data, context and interaction]]
- [[Debugging pattern]]
- [[JSP model 1 architecture]]
- [[JSP model 2 architecture]]
- [[Multitier architecture]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dependency_injection