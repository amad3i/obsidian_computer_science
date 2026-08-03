---
title: "Thread-local storage"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Thread-local_storage"
wikipedia_categories: ["Software design patterns", "Threads (computing)", "Variable (computer science)"]
related: ["[[Asynchronous method invocation]]", "[[Reentrant mutex]]", "[[Thread pool]]", "[[Abstract factory pattern]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Active record pattern]]", "[[Adapter pattern]]", "[[Aggregate pattern]]", "[[Applicative functor]]"]
---

# Thread-local storage

In computer programming, thread-local storage (TLS) is a memory management method that uses static or global memory local to a thread. The concept allows storage of data that appears to be global in a system with separate threads.
Many systems impose restrictions on the size of the thread-local memory block, in fact often rather tight limits. On the other hand, if a system can provide at least a memory address (pointer) sized variable thread-local, then this allows the use of arbitrarily sized memory blocks in a thread-local manner, by allocating such a memory block dynamically and storing the memory address of that block in the thread-local variable. On RISC machines, the calling convention often reserves a thread pointer register for this use.

## Related

- [[Asynchronous method invocation]]
- [[Reentrant mutex]]
- [[Thread pool]]
- [[Abstract factory pattern]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Active record pattern]]
- [[Adapter pattern]]
- [[Aggregate pattern]]
- [[Applicative functor]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Thread-local_storage