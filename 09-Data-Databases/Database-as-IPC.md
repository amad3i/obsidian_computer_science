---
title: "Database-as-IPC"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Database-as-IPC"
wikipedia_categories: ["Anti-patterns", "Computer science stubs", "Databases"]
related: ["[[Connection string]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Altibase]]", "[[Analog image processing]]", "[[Anemic domain model]]", "[[AQUA@home]]", "[[Asynchrony (computer programming)]]", "[[Attentive user interface]]", "[[Autocommit]]"]
---

# Database-as-IPC

In computer programming, Database-as-IPC may be considered an anti-pattern where a disk persisted table in a database is used as the message queue store for routine inter-process communication (IPC) or subscribed data processing. If database performance is of concern, alternatives include sockets, network socket, or message queue.
British computer scientist, Junade Ali, defined the Database-as-IPC Anti-Pattern as using a database to "schedule jobs or queue up tasks to be completed", noting that this anti-pattern centres around using a database for temporary messages instead of persistent data.

## Related

- [[Connection string]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Altibase]]
- [[Analog image processing]]
- [[Anemic domain model]]
- [[AQUA@home]]
- [[Asynchrony (computer programming)]]
- [[Attentive user interface]]
- [[Autocommit]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Database-as-IPC