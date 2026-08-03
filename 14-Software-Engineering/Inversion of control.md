---
title: "Inversion of control"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Inversion_of_control"
wikipedia_categories: ["Architectural pattern (computer science)", "Component-based software engineering", "Programming principles", "Software architecture", "Software design patterns"]
related: ["[[Composition over inheritance]]", "[[Dependency injection]]", "[[Multitier architecture]]", "[[Action–domain–responder]]", "[[Active record pattern]]", "[[Black box]]", "[[Bulkhead pattern]]", "[[Cohesion (computer science)]]", "[[Common Component Architecture]]", "[[Component-based software engineering]]"]
---

# Inversion of control

In software design, inversion of control (IoC) is a design principle in which custom-written portions of a computer program receive the flow of control from an external source (e.g. a framework). The term "inversion" is historical: a software architecture with this design "inverts" control as compared to procedural programming. In procedural programming, a program's custom code calls reusable libraries to take care of generic tasks, but with inversion of control, it is the external code or framework that is in control and calls the custom code.
Inversion of control has been widely used by application development frameworks since the rise of GUI environments and continues to be used both in GUI environments and in web server application frameworks. Inversion of control makes the framework extensible by the methods defined by the application programmer.
Event-driven programming is often implemented using IoC so that the custom code need only be concerned with the handling of events, while the event loop and dispatch of events/messages is handled by the framework or the runtime environment. In web server application frameworks, dispatch is usually called routing, and handlers may be called endpoints.

## Related

- [[Composition over inheritance]]
- [[Dependency injection]]
- [[Multitier architecture]]
- [[Action–domain–responder]]
- [[Active record pattern]]
- [[Black box]]
- [[Bulkhead pattern]]
- [[Cohesion (computer science)]]
- [[Common Component Architecture]]
- [[Component-based software engineering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Inversion_of_control