---
title: "X86 debug register"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/X86_debug_register"
wikipedia_categories: ["Debugging", "Digital registers", "Operating system technology", "X86 instructions"]
related: ["[[Control register]]", "[[Flag (programming)]]", "[[Advanced Synchronization Facility]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Assertion (software development)]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Binary Application Markup Language]]"]
---

# X86 debug register

On the x86 architecture, a debug register is a register used by a processor for program debugging. There are six debug registers, named DR0...DR7, with DR4 and DR5 as obsolete synonyms for DR6 and DR7. The debug registers allow programmers to selectively enable various debug conditions associated with a set of four debug addresses.
Two of these registers are used to control debug features. These registers are accessed by variants of the MOV instruction. A debug register may be either the source operand or destination operand. The debug registers are privileged resources; the MOV instructions that access them can only be executed at privilege level zero. An attempt to read or write the debug registers when executing at any other privilege level causes a general protection fault.

## Related

- [[Control register]]
- [[Flag (programming)]]
- [[Advanced Synchronization Facility]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Assertion (software development)]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Binary Application Markup Language]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/X86_debug_register