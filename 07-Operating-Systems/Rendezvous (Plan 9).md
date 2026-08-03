---
title: "Rendezvous (Plan 9)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Rendezvous_(Plan_9)"
wikipedia_categories: ["Inter-process communication", "Operating system stubs", "Parallel computing", "Plan 9 from Bell Labs"]
related: ["[[Blocking (computing)]]", "[[Parallel Virtual Machine]]", "[[ABIT BP6]]", "[[Advanced Message Queuing Protocol]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alef (programming language)]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]"]
---

# Rendezvous (Plan 9)

Rendezvous is a data synchronization mechanism in Plan 9 from Bell Labs. It is a system call that allows two processes to exchange a single datum while synchronizing.
The rendezvous call takes a tag and a value as its arguments. The tag is typically an address in memory shared by both processes. Calling rendezvous causes a process to sleep until a second rendezvous call with a matching tag occurs. Then, the values are exchanged and both processes are awakened.
More complex synchronization mechanisms can be created from this primitive operation. See also mutual exclusion.

## Related

- [[Blocking (computing)]]
- [[Parallel Virtual Machine]]
- [[ABIT BP6]]
- [[Advanced Message Queuing Protocol]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alef (programming language)]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rendezvous_(Plan_9)