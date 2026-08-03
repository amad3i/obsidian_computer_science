---
title: "Circuit breaker design pattern"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Circuit_breaker_design_pattern"
wikipedia_categories: ["Software design patterns"]
related: ["[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]", "[[Applicative functor]]", "[[Asynchronous method invocation]]", "[[Balking pattern]]", "[[Behavioral pattern]]"]
---

# Circuit breaker design pattern

The Circuit Breaker is a design pattern commonly used in software development to improve system resilience and fault tolerance. Circuit breaker pattern can prevent cascading failures particularly in distributed systems. In distributed systems, the Circuit Breaker pattern can be used to monitor service health and can detect failures dynamically. Unlike timeout-based methods, which can lead to delayed error responses or the premature failure of healthy requests, the Circuit Breaker pattern can proactively identify unresponsive services and can prevent repeated attempts. This approach can enhance the user experience. 
The circuit breaker pattern can be used in conjunction with other patterns, such as retry, fallback, and timeout, to enhance fault tolerance in systems.

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

- Wikipedia: https://en.wikipedia.org/wiki/Circuit_breaker_design_pattern