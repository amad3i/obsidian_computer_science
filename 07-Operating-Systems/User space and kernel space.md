---
title: "User space and kernel space"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/User_space_and_kernel_space"
wikipedia_categories: ["Device drivers", "Operating system technology"]
related: ["[[Hardware abstraction]]", "[[Mode setting]]", "[[Network redirector]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Binary Application Markup Language]]", "[[Board support package]]"]
---

# User space and kernel space

A modern computer operating system usually uses virtual memory to provide separate address spaces or regions of a single address space, called user space and kernel space. This separation primarily provides memory protection and hardware protection from malicious or errant software behaviour.

Kernel space is strictly reserved for running a privileged operating system kernel, kernel extensions, and most device drivers. In contrast, user space is the memory area where application software, daemons, and some drivers execute, typically with one address space per process.
Exploits targeting the user space are colloquially referred to as "userland exploits".

## Related

- [[Hardware abstraction]]
- [[Mode setting]]
- [[Network redirector]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Binary Application Markup Language]]
- [[Board support package]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/User_space_and_kernel_space