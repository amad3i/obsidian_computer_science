---
title: "Dispose pattern"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Dispose_pattern"
wikipedia_categories: ["Memory management", "Object-oriented programming", "Software design patterns"]
related: ["[[Finalizer]]", "[[List of software anti-patterns]]", "[[Mixin]]", "[[Resource acquisition is initialization]]", "[[bss]]", "[[Abstract factory pattern]]", "[[Abstraction (computer science)]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]"]
---

# Dispose pattern

In object-oriented programming, the dispose pattern is a design pattern for resource management. In this pattern, a resource is held by an object, and released by calling a conventional method – usually called close, dispose, free, release depending on the language – which releases any resources the object is holding onto. Many programming languages offer language constructs to avoid having to call the dispose method explicitly in common situations.
The dispose pattern is primarily used in languages whose runtime environment have automatic garbage collection (see motivation below).

## Related

- [[Finalizer]]
- [[List of software anti-patterns]]
- [[Mixin]]
- [[Resource acquisition is initialization]]
- [[bss]]
- [[Abstract factory pattern]]
- [[Abstraction (computer science)]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dispose_pattern