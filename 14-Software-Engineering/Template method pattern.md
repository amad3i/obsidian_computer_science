---
title: "Template method pattern"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Template_method_pattern"
wikipedia_categories: ["Method (computer programming)", "Software design patterns"]
related: ["[[Double dispatch]]", "[[Factory method pattern]]", "[[Non-virtual interface pattern]]", "[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]", "[[Applicative functor]]"]
---

# Template method pattern

In object-oriented programming, the template method is one of the behavioral design patterns identified by Gamma et al. in the book Design Patterns.  The template method is a method in a superclass, usually an abstract superclass, and defines the skeleton of an operation in terms of a number of high-level steps.  These steps are themselves implemented by additional helper methods in the same class as the template method.
The helper methods may be either abstract methods, in which case subclasses are required to provide concrete implementations, or hook methods, which have empty bodies in the superclass. Subclasses can (but are not required to) customize the operation by overriding the hook methods.  The intent of the template method is to define the overall structure of the operation, while allowing subclasses to refine, or redefine, certain steps.

## Related

- [[Double dispatch]]
- [[Factory method pattern]]
- [[Non-virtual interface pattern]]
- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]
- [[Aggregate pattern]]
- [[Applicative functor]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Template_method_pattern