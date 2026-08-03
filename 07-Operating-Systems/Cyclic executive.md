---
title: "Cyclic executive"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Cyclic_executive"
wikipedia_categories: ["Concurrent computing", "Operating system technology"]
related: ["[[Computer multitasking]]", "[[Concurrent computing]]", "[[Preemption (computing)]]", "[[Process (computing)]]", "[[Yield (multithreading)]]", "[[Actor model]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]"]
---

# Cyclic executive

A cyclic executive is an alternative to a real-time operating system.  It is a form of cooperative multitasking, in which there is only one task.  The sole task is typically realized as an infinite loop in main(), e.g. in C.
The basic scheme is to cycle through a repeating sequence of activities, at a set frequency (a.k.a. time-triggered cyclic executive).  For example, consider the example of an embedded system designed to monitor a temperature sensor and update an LCD. The LCD may need to be written twenty times a second (i.e., every 50 ms).  If the temperature sensor must be read every 100 ms for other reasons, we might construct a loop of the following appearance:

The outer 100 ms cycle is called the major cycle.  In this case, there is also an inner minor cycle of 50 ms. In this first example the outer versus inner cycles aren't obvious. We can use a counting mechanism to clarify the major and minor cycles.

## Related

- [[Computer multitasking]]
- [[Concurrent computing]]
- [[Preemption (computing)]]
- [[Process (computing)]]
- [[Yield (multithreading)]]
- [[Actor model]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cyclic_executive