---
title: "Double-checked locking"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Double-checked_locking"
wikipedia_categories: ["Concurrency control", "Software design patterns"]
related: ["[[Lock (computer science)]]", "[[Monitor (synchronization)]]", "[[Readers–writer lock]]", "[[Reentrant mutex]]", "[[Abstract factory pattern]]", "[[ACID]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]"]
---

# Double-checked locking

In software engineering, double-checked locking (also known as "double-checked locking optimization") is a software design pattern used to reduce the overhead of acquiring a lock by testing the locking criterion (the "lock hint") before acquiring the lock.  Locking occurs only if the locking criterion check indicates that locking is required.
The original form of the pattern, appearing in Pattern Languages of Program Design 3, has data races, depending on the memory model in use, and it is hard to get right. Some consider it to be an anti-pattern. There are valid forms of the pattern, including the use of the volatile keyword in Java and explicit memory barriers in C++.
The pattern is typically used to reduce locking overhead when implementing "lazy initialization" in a multi-threaded environment, especially as part of the Singleton pattern. Lazy initialization avoids initializing a value until the first time it is accessed.

## Related

- [[Lock (computer science)]]
- [[Monitor (synchronization)]]
- [[Readers–writer lock]]
- [[Reentrant mutex]]
- [[Abstract factory pattern]]
- [[ACID]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Double-checked_locking