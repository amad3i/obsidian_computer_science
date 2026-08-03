---
title: "Multiton pattern"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Multiton_pattern"
wikipedia_categories: ["Software design patterns"]
related: ["[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]", "[[Applicative functor]]", "[[Asynchronous method invocation]]", "[[Balking pattern]]", "[[Behavioral pattern]]"]
---

# Multiton pattern

In software engineering, the multiton pattern is a design pattern which generalizes the singleton pattern. Whereas the  singleton allows only one instance of a class to be created, the multiton pattern allows for the controlled creation of multiple instances, which it manages through the use of a map.
Rather than having a single instance per application (e.g. the java.lang.Runtime object in the Java programming language) the multiton pattern instead ensures a single instance per key.
The multiton pattern does not explicitly appear as a pattern in the highly regarded object-oriented programming textbook Design Patterns. However, the book describes using a registry of singletons to allow subclassing of singletons, which is essentially the multiton pattern.

## Related

- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]
- [[Aggregate pattern]]
- [[Applicative functor]]
- [[Asynchronous method invocation]]
- [[Balking pattern]]
- [[Behavioral pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multiton_pattern