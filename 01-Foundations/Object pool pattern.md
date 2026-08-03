---
title: "Object pool pattern"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Object_pool_pattern"
wikipedia_categories: ["Software design patterns", "Software optimization"]
related: ["[[Flyweight pattern]]", "[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]", "[[Analytical Performance Modeling]]", "[[Applicative functor]]", "[[Approximate computing]]"]
---

# Object pool pattern

The object pool pattern is a software creational design pattern that uses a set of initialized objects kept ready to use – a "pool" – rather than allocating and destroying them on demand. A client of the pool will request an object from the pool and perform operations on the returned object. When the client has finished, it returns the object to the pool rather than destroying it; this can be done manually or automatically.
Object pools are primarily used for performance: in some circumstances, object pools significantly improve performance. Object pools complicate object lifetime, as objects obtained from and returned to a pool are not actually created or destroyed at this time, and thus require care in implementation.

## Related

- [[Flyweight pattern]]
- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]
- [[Aggregate pattern]]
- [[Analytical Performance Modeling]]
- [[Applicative functor]]
- [[Approximate computing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Object_pool_pattern