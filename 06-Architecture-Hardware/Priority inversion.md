---
title: "Priority inversion"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Priority_inversion"
wikipedia_categories: ["Concurrency control", "Embedded systems", "Software bugs"]
related: ["[[ACID]]", "[[Adesto Technologies]]", "[[Advanced Synchronization Facility]]", "[[ADvantage Framework]]", "[[Anti-hijack system]]", "[[Apache Celix]]", "[[Assembly language]]", "[[ATM]]", "[[Automatic system recovery]]", "[[Background debug mode interface]]"]
---

# Priority inversion

In computer science, priority inversion is a scenario in scheduling in which a high-priority task is indirectly superseded by a lower-priority task, effectively inverting the assigned priorities of the tasks. This violates the priority model that every task can only be prevented from running by a higher-priority task. Inversion occurs when there is a resource contention with a (low-priority) task that is then preempted by a higher-priority task.

## Related

- [[ACID]]
- [[Adesto Technologies]]
- [[Advanced Synchronization Facility]]
- [[ADvantage Framework]]
- [[Anti-hijack system]]
- [[Apache Celix]]
- [[Assembly language]]
- [[ATM]]
- [[Automatic system recovery]]
- [[Background debug mode interface]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Priority_inversion