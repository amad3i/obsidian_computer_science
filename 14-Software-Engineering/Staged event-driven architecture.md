---
title: "Staged event-driven architecture"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Staged_event-driven_architecture"
wikipedia_categories: ["Events (computing)", "Software architecture"]
related: ["[[Event-driven architecture]]", "[[4+1 architectural view model]]", "[[Active reviews for intermediate designs]]", "[[Agent architecture]]", "[[Anemic domain model]]", "[[Application domain]]", "[[Application server]]", "[[ArchiMate]]", "[[Architectural decision]]", "[[Architecturally significant requirements]]"]
---

# Staged event-driven architecture

The staged event-driven architecture (SEDA) refers to an approach to software architecture that decomposes a complex, event-driven application into a set of stages connected by queues. It avoids the high overhead associated with thread-based concurrency models (i.e. locking, unlocking, and polling for locks), and decouples event and thread scheduling from application logic. By performing admission control on each event queue, the service can be well-conditioned to load, preventing resources from being overcommitted when demand exceeds service capacity.
SEDA employs dynamic control to automatically tune runtime parameters (such as the scheduling parameters of each stage) as well as to manage load (like performing adaptive load shedding). Decomposing services into a set of stages also enables modularity and code reuse, as well as the development of debugging tools for complex event-driven applications.

## Related

- [[Event-driven architecture]]
- [[4+1 architectural view model]]
- [[Active reviews for intermediate designs]]
- [[Agent architecture]]
- [[Anemic domain model]]
- [[Application domain]]
- [[Application server]]
- [[ArchiMate]]
- [[Architectural decision]]
- [[Architecturally significant requirements]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Staged_event-driven_architecture