---
title: "General protection fault"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/General_protection_fault"
wikipedia_categories: ["Computer errors", "Operating system technology"]
related: ["[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Binary Application Markup Language]]", "[[Burst error-correcting code]]", "[[Busdma]]", "[[Chain loading]]", "[[Computer multitasking]]"]
---

# General protection fault

A general protection fault (GPF) in the x86 instruction set architectures (ISAs) is a fault (a type of interrupt) initiated by ISA-defined protection mechanisms in response to an access violation caused by some running code, either in the kernel or a user program. The mechanism is first described in Intel manuals and datasheets for the Intel 80286 CPU, which was introduced in 1983; it is also described in section 9.8.13 in the Intel 80386 programmer's reference manual from 1986. A general protection fault is implemented as an interrupt (vector number 13 (0Dh)). Some operating systems may also classify some exceptions not related to access violations, such as illegal opcode exceptions, as general protection faults, even though they have nothing to do with memory protection. If a CPU detects a protection violation, it stops executing the code and sends a GPF interrupt. In most cases, the operating system removes the failing process from the execution queue, signals the user, and continues executing other processes. If, however, the operating system fails to catch the general protection fault, i.e. another protection violation occurs before the operating system returns from the previous GPF interrupt, the CPU signals a double fault, stopping the operating system. If yet another failure (triple fault) occurs, the CPU is unable to recover; since 80286, the CPU enters a special halt state called "Shutdown", which can only be exited through a hardware reset. The IBM PC AT, the first PC-compatible system to contain an 80286, has hardware that detects the Shutdown state and automatically resets the CPU when it occurs. All descendants of the PC AT do the same, so in a PC, a triple fault causes an immediate system reset.

## Related

- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Binary Application Markup Language]]
- [[Burst error-correcting code]]
- [[Busdma]]
- [[Chain loading]]
- [[Computer multitasking]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/General_protection_fault