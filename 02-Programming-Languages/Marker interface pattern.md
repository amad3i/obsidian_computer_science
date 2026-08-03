---
title: "Marker interface pattern"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Marker_interface_pattern"
wikipedia_categories: ["Java (programming language)", "Software design patterns"]
related: ["[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[AgentSheets]]", "[[Aggregate pattern]]", "[[Applicative functor]]", "[[Asynchronous method invocation]]", "[[Balking pattern]]"]
---

# Marker interface pattern

The marker interface pattern is a design pattern in computer science, used with languages that provide run-time type information about objects. It provides a means to associate metadata with a class where the language does not have explicit support for such metadata.
To use this pattern, a class implements a marker interface (also called tagging interface) which is an empty interface, and methods that interact with instances of that class test for the existence of the interface. Whereas a typical interface specifies functionality (in the form of method declarations) that an implementing class must support, a marker interface need not do so. The mere presence of such an interface indicates specific behavior on the part of the implementing class. Hybrid interfaces, which both act as markers and specify required methods, are possible but may prove confusing if improperly used.

## Related

- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]
- [[AgentSheets]]
- [[Aggregate pattern]]
- [[Applicative functor]]
- [[Asynchronous method invocation]]
- [[Balking pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Marker_interface_pattern