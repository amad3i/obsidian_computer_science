---
title: "Ambiguous viewpoint"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Ambiguous_viewpoint"
wikipedia_categories: ["Object-oriented programming", "Software design", "Software engineering stubs"]
related: ["[[Layer (object-oriented design)]]", "[[Convention over configuration]]", "[[Entity–control–boundary]]", "[[Environment discipline]]", "[[Hexagonal architecture (software)]]", "[[Interface segregation principle]]", "[[Object-oriented modeling]]", "[[Objectory]]", "[[Open–closed principle]]", "[[Package principles]]"]
---

# Ambiguous viewpoint

Object-oriented analysis and design (OOAD) models are often presented without clarifying the viewpoint represented by the model.  By default, these models denote an implementation viewpoint that visualises the structure of a computer program.  Mixed viewpoints do not support the fundamental separation of interfaces from implementation details, which is one of the primary benefits of the object-oriented paradigm. An ambiguous or mixed viewpoint is an anti-pattern.
In object-oriented analysis and design there are three viewpoints: The business viewpoint (the information that is domain specific and matters to the end user), the specification viewpoint (which defines the exposed interface elements of a class), and the implementation viewpoint (which deals with the actual internal implementation of the class).  If the viewpoint becomes mixed then these elements will blend together in a way which makes it difficult to separate out and maintain the internals of an object without changing the interface, one of the core tenets of object-oriented analysis and design.

## Related

- [[Layer (object-oriented design)]]
- [[Convention over configuration]]
- [[Entity–control–boundary]]
- [[Environment discipline]]
- [[Hexagonal architecture (software)]]
- [[Interface segregation principle]]
- [[Object-oriented modeling]]
- [[Objectory]]
- [[Open–closed principle]]
- [[Package principles]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Ambiguous_viewpoint