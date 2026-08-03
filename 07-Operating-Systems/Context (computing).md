---
title: "Context (computing)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Context_(computing)"
wikipedia_categories: ["Process (computing)"]
related: ["[[Background process]]", "[[Chain loading]]", "[[Child process]]", "[[Code cave]]", "[[Complex event processing]]", "[[Context switch]]", "[[Coprocess]]", "[[Daemon (computing)]]", "[[DESQview]]", "[[Divergence (computer science)]]"]
---

# Context (computing)

In computer science, a task context is the minimal set of data used by a task (which may be a process, thread, or fiber) that must be saved to allow a task to be interrupted, and later continued from the same point. The concept of context assumes significance in the case of interruptible tasks, wherein, upon being interrupted, the processor saves the context and proceeds to serve the interrupt service routine. Thus, the smaller the context is, the smaller the latency is.
The context data may be located in processor registers, memory used by the task, or in control registers used by some operating systems to directly manage the task.
The storage memory (files used by a task) is not concerned by the "task context" in the case of a context switch, even if this can be stored for some uses (checkpointing).
The context can also be viewed as a mechanism that allows a state of a program to be transferred between its components.

## Related

- [[Background process]]
- [[Chain loading]]
- [[Child process]]
- [[Code cave]]
- [[Complex event processing]]
- [[Context switch]]
- [[Coprocess]]
- [[Daemon (computing)]]
- [[DESQview]]
- [[Divergence (computer science)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Context_(computing)