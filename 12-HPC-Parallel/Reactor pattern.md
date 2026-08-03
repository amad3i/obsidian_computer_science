---
title: "Reactor pattern"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Reactor_pattern"
wikipedia_categories: ["Concurrent computing", "Events (computing)", "Software design patterns"]
related: ["[[Concurrency pattern]]", "[[Data transfer object]]", "[[Interceptor pattern]]", "[[Proactor pattern]]", "[[Thread pool]]", "[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Actor model]]"]
---

# Reactor pattern

The reactor software design pattern is an event handling strategy that can respond to many potential service requests concurrently. The pattern's key component is an event loop, running in a single thread or process, which demultiplexes incoming requests and dispatches them to the correct request handler.
By relying on event-based mechanisms rather than blocking I/O or multi-threading, a reactor can handle many concurrent I/O bound requests with minimal delay.
A reactor also allows for easily modifying or expanding specific request handler routines, though the pattern does have some drawbacks and limitations.
With its balance of simplicity and scalability, the reactor has become a central architectural element in several server applications and software frameworks for networking. Derivations such as the multireactor and proactor also exist for special cases where even greater throughput, performance, or request complexity are necessary.

## Related

- [[Concurrency pattern]]
- [[Data transfer object]]
- [[Interceptor pattern]]
- [[Proactor pattern]]
- [[Thread pool]]
- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Actor model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Reactor_pattern