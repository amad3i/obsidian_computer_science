---
title: "Block contention"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Block_contention"
wikipedia_categories: ["Computer science stubs", "Database management systems"]
related: ["[[Bidirectionalization]]", "[[ACID]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Analog image processing]]", "[[ANSI-SPARC Architecture]]", "[[AQUA@home]]", "[[Armstrong's axioms]]", "[[Array DBMS]]", "[[Asynchrony (computer programming)]]"]
---

# Block contention

In database management systems, block contention (or data contention) refers to multiple processes or instances competing for access to the same index or data block at the same time. In general this can be caused by very frequent index or table scans, or frequent updates. Concurrent statement executions by two or more instances may also lead to contention, and subsequently busy waiting for the process without the lock.

## Related

- [[Bidirectionalization]]
- [[ACID]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Analog image processing]]
- [[ANSI-SPARC Architecture]]
- [[AQUA@home]]
- [[Armstrong's axioms]]
- [[Array DBMS]]
- [[Asynchrony (computer programming)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Block_contention