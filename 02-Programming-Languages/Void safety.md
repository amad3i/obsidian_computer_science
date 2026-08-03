---
title: "Void safety"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Void_safety"
wikipedia_categories: ["Computer science stubs", "Object-oriented programming"]
related: ["[[First-class message]]", "[[Object hierarchy]]", "[[Abstraction (computer science)]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Ambiguous viewpoint]]", "[[Analog image processing]]", "[[AQUA@home]]", "[[ASCEND]]", "[[Association (object-oriented programming)]]"]
---

# Void safety

Void safety (also known as null safety) is a guarantee within an object-oriented programming language that no object references will have null or void values.
In object-oriented languages, access to objects is achieved through references (or, equivalently, pointers). A typical call is of the form x.f(a, ...), where f denotes an operation and x denotes a reference to some object. At execution time, however, a reference can be void (or null). In such cases, the call above will be a void call, leading to a run-time exception, often resulting in abnormal termination of the program.
Void safety is a static (compile-time) guarantee that a void call will never arise.

## Related

- [[First-class message]]
- [[Object hierarchy]]
- [[Abstraction (computer science)]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Ambiguous viewpoint]]
- [[Analog image processing]]
- [[AQUA@home]]
- [[ASCEND]]
- [[Association (object-oriented programming)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Void_safety