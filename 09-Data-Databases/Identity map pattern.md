---
title: "Identity map pattern"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Identity_map_pattern"
wikipedia_categories: ["Architectural pattern (computer science)", "Computer science stubs", "Software design patterns"]
related: ["[[Action–domain–responder]]", "[[Active record pattern]]", "[[Concurrency pattern]]", "[[Data access object]]", "[[Data mapper pattern]]", "[[Data transfer object]]", "[[Distributed design patterns]]", "[[Entity component system]]", "[[Front controller]]", "[[Generation gap (pattern)]]"]
---

# Identity map pattern

In database design, the identity map pattern is a database access design pattern used to improve performance by providing a context-specific, in-memory cache to prevent duplicate retrieval of the same object data from the database.
If the requested data has already been loaded from the database, the identity map returns the same instance of the already instantiated object, but if it has not been loaded yet, it loads it and stores the new object in the map. In this way, it follows a similar principle to lazy loading.
There are 4 types of identity maps

Explicit
Generic
Session
Class

## Related

- [[Action–domain–responder]]
- [[Active record pattern]]
- [[Concurrency pattern]]
- [[Data access object]]
- [[Data mapper pattern]]
- [[Data transfer object]]
- [[Distributed design patterns]]
- [[Entity component system]]
- [[Front controller]]
- [[Generation gap (pattern)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Identity_map_pattern