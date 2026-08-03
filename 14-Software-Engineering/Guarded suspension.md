---
title: "Guarded suspension"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Guarded_suspension"
wikipedia_categories: ["Computer programming stubs", "Software design patterns"]
related: ["[[Action–domain–responder]]", "[[Active object]]", "[[Aggregate pattern]]", "[[Balking pattern]]", "[[Broker pattern]]", "[[Data transfer object]]", "[[Head–body pattern]]", "[[Lazy loading]]", "[[UI data binding]]", "[[Abstract factory pattern]]"]
---

# Guarded suspension

In concurrent programming, guarded suspension is a software design pattern for managing operations that require both a lock to be acquired and a precondition to be satisfied before the operation can be executed. The guarded suspension pattern is typically applied to method calls in object-oriented programs, and involves suspending the method call, and the calling thread, until the precondition (acting as a guard) is satisfied.

## Related

- [[Action–domain–responder]]
- [[Active object]]
- [[Aggregate pattern]]
- [[Balking pattern]]
- [[Broker pattern]]
- [[Data transfer object]]
- [[Head–body pattern]]
- [[Lazy loading]]
- [[UI data binding]]
- [[Abstract factory pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Guarded_suspension