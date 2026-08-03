---
title: "Process control block"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Process_control_block"
wikipedia_categories: ["Process (computing)"]
related: ["[[Background process]]", "[[Chain loading]]", "[[Child process]]", "[[Code cave]]", "[[Complex event processing]]", "[[Context (computing)]]", "[[Context switch]]", "[[Coprocess]]", "[[Daemon (computing)]]", "[[DESQview]]"]
---

# Process control block

A process control block (PCB), also sometimes called a process descriptor, is a data structure used by a computer operating system to store all the information about a  process.
When a process is created (initialized or installed), the operating system creates a corresponding process control block, which specifies and tracks the process state (i.e. new, ready, running, waiting or terminated). Since it is used to track process information, the PCB plays a key role in context switching.
An operating system kernel stores PCBs in a process table.
The current working directory of a process is one of the properties that the kernel stores in the process's PCB.

## Related

- [[Background process]]
- [[Chain loading]]
- [[Child process]]
- [[Code cave]]
- [[Complex event processing]]
- [[Context (computing)]]
- [[Context switch]]
- [[Coprocess]]
- [[Daemon (computing)]]
- [[DESQview]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Process_control_block