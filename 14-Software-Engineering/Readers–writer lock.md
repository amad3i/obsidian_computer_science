---
title: "Readers–writer lock"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Readers–writer_lock"
wikipedia_categories: ["Concurrency control", "Software design patterns"]
related: ["[[Double-checked locking]]", "[[Lock (computer science)]]", "[[Monitor (synchronization)]]", "[[Reentrant mutex]]", "[[Abstract factory pattern]]", "[[ACID]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]"]
---

# Readers–writer lock

In computer science, a readers–writer (single-writer lock, a multi-reader lock, a push lock, or an MRSW lock) is a synchronization primitive that solves one of the readers–writers problems. An RW lock allows concurrent access for read-only operations, whereas write operations require exclusive access. This means that multiple threads can read the data in parallel but an exclusive lock is needed for writing or modifying data. When a writer is writing the data, all other writers and readers will be blocked until the writer is finished writing. A common use might be to control access to a data structure in memory that cannot be updated atomically and is invalid (and should not be read by another thread) until the update is complete.
Readers–writer locks are usually constructed on top of mutexes and condition variables, or on top of semaphores.

## Related

- [[Double-checked locking]]
- [[Lock (computer science)]]
- [[Monitor (synchronization)]]
- [[Reentrant mutex]]
- [[Abstract factory pattern]]
- [[ACID]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Readers–writer_lock