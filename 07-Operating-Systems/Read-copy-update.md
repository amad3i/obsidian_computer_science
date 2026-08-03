---
title: "Read-copy-update"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Read-copy-update"
wikipedia_categories: ["Concurrency control", "Operating system technology"]
related: ["[[ACID]]", "[[Advanced Synchronization Facility]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Barrier (computer science)]]", "[[Binary Application Markup Language]]", "[[Busdma]]"]
---

# Read-copy-update

In computer science, read-copy-update (RCU) is a synchronization mechanism that avoids the use of lock primitives while multiple threads concurrently read and update elements that are linked through pointers and that belong to shared data structures (e.g., linked lists, trees, hash tables).
Whenever a thread is inserting or deleting elements of data structures in shared memory, all readers are guaranteed to see and traverse either the older or the new structure, therefore avoiding inconsistencies (e.g., dereferencing null pointers).
It is used when performance of reads is crucial and is an example of space–time tradeoff, enabling fast operations at the cost of more space. This makes all readers proceed as if there were no synchronization involved, hence they will be fast, but also making updates more difficult.

## Related

- [[ACID]]
- [[Advanced Synchronization Facility]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Barrier (computer science)]]
- [[Binary Application Markup Language]]
- [[Busdma]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Read-copy-update