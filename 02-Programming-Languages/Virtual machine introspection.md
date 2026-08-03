---
title: "Virtual machine introspection"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Virtual_machine_introspection"
wikipedia_categories: ["Operating system technology", "Virtual machines"]
related: ["[[System virtual machine]]", "[[Virtual machine]]", "[[Vkernel]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Binary Application Markup Language]]", "[[Busdma]]"]
---

# Virtual machine introspection

In computing, virtual machine introspection (VMI) is a technique "for monitoring the runtime state of a system-level virtual machine (VM)", which is helpful for debugging or forensic analysis.
The term introspection in application to the virtual machines was introduced by Garfinkel and Rosenblum. They invented an approach for "protecting a security application from attack by malicious software" and called it VMI. Now VMI is a common term for different virtual machine forensics and analysis methods. VMI-based approaches are widely used for security applications, software debugging, and systems management.
VMI tools may be located inside or outside the virtual machine and act by tracking the events (interrupts, memory writes, and so on) or sending the requests to the virtual machine. Virtual machine monitor usually provides low-level information like raw bytes of the memory. Converting this low-level view into something meaningful for the user is known as the semantic gap problem. Solving this problem requires analysis and understanding of the systems being monitored.

## Related

- [[System virtual machine]]
- [[Virtual machine]]
- [[Vkernel]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Binary Application Markup Language]]
- [[Busdma]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Virtual_machine_introspection