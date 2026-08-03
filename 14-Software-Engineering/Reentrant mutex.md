---
title: "Reentrant mutex"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Reentrant_mutex"
wikipedia_categories: ["Concurrency control", "Software design patterns", "Threads (computing)"]
related: ["[[Asynchronous method invocation]]", "[[Double-checked locking]]", "[[Lock (computer science)]]", "[[Monitor (synchronization)]]", "[[Readers–writer lock]]", "[[Thread pool]]", "[[Thread-local storage]]", "[[Abstract factory pattern]]", "[[ACID]]", "[[Action–domain–responder]]"]
---

# Reentrant mutex

In computer science, the reentrant mutex (also known as a recursive mutex or recursive lock) is a synchronization primitive that may be locked multiple times by the same thread without causing a deadlock.
While a thread that attempts to lock a standard (non-reentrant) mutex that it already holds would block indefinitely, this operation succeeds on a reentrant mutex. This is achieved by associating the mutex with the thread that owns it and maintaining a lock count. The owning thread can acquire the lock multiple times, incrementing the count each time. The lock is only released for other threads to acquire once the owning thread has unlocked it the same number of times it was acquired, bringing the count to zero.

## Related

- [[Asynchronous method invocation]]
- [[Double-checked locking]]
- [[Lock (computer science)]]
- [[Monitor (synchronization)]]
- [[Readers–writer lock]]
- [[Thread pool]]
- [[Thread-local storage]]
- [[Abstract factory pattern]]
- [[ACID]]
- [[Action–domain–responder]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Reentrant_mutex