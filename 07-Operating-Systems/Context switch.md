---
title: "Context switch"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Context_switch"
wikipedia_categories: ["Process (computing)"]
related: ["[[Background process]]", "[[Chain loading]]", "[[Child process]]", "[[Code cave]]", "[[Complex event processing]]", "[[Context (computing)]]", "[[Coprocess]]", "[[Daemon (computing)]]", "[[DESQview]]", "[[Divergence (computer science)]]"]
---

# Context switch

In computing, a context switch is the process of storing the state of a process or thread, so that it can be restored and resume execution at a later point, and then restoring a different, previously saved, state. This allows multiple processes to share a single central processing unit (CPU) and is an essential feature of a multiprogramming or  multitasking operating system. In a traditional CPU, each process –  a program in execution –  uses the various CPU registers to store data and hold the current state of the running process. However, in a multitasking operating system, the operating system switches between processes or threads to allow the execution of multiple processes simultaneously. For every switch, the operating system must save the state of the currently running process, followed by loading the next process state, which will run on the CPU. This sequence of operations that stores the state of the running process and loads the following running process is called a context switch.
The precise meaning of the phrase "context switch" varies. In a multitasking context, it refers to the process of storing the system state for one task, so that task can be paused and another task resumed. A context switch can also occur as the result of an interrupt, such as when a task needs to access disk storage, freeing up CPU time for other tasks. Some operating systems also require a context switch to move between user mode and kernel mode tasks. The process of context switching can have a negative impact on system performance.

## Related

- [[Background process]]
- [[Chain loading]]
- [[Child process]]
- [[Code cave]]
- [[Complex event processing]]
- [[Context (computing)]]
- [[Coprocess]]
- [[Daemon (computing)]]
- [[DESQview]]
- [[Divergence (computer science)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Context_switch