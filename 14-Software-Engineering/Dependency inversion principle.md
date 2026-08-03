---
title: "Dependency inversion principle"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Dependency_inversion_principle"
wikipedia_categories: ["Programming principles", "Software design patterns"]
related: ["[[Black box]]", "[[Inversion of control]]", "[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]", "[[Applicative functor]]", "[[Asynchronous method invocation]]"]
---

# Dependency inversion principle

In object-oriented design, the dependency inversion principle is a specific methodology for loosely coupled software modules. When following this principle, the conventional dependency relationships established from high-level, policy-setting modules to low-level, dependency modules are reversed, thus rendering high-level modules independent of the low-level module implementation details. The principle states:

By dictating that both high-level and low-level objects must depend on the same abstraction, this design principle inverts the way some people may think about object-oriented programming.
The idea behind points A and B of this principle is that when designing the interaction between a high-level module and a low-level one, the interaction should be thought of as an abstract interaction between them. This has implications for the design of both the high-level and the low-level modules: the low-level one should be designed with the interaction in mind and it may be necessary to change its usage interface.
In many cases, thinking about the interaction itself as an abstract concept allows for reduction of the coupling between the components without introducing additional coding patterns and results in a lighter and less implementation-dependent interaction schema. When this abstract interaction schema is generic and clear, this design principle leads to the dependency inversion pattern described below.

## Related

- [[Black box]]
- [[Inversion of control]]
- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]
- [[Aggregate pattern]]
- [[Applicative functor]]
- [[Asynchronous method invocation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dependency_inversion_principle