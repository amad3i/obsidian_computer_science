---
title: "Application binary interface"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Application_binary_interface"
wikipedia_categories: ["Application programming interfaces", "Operating system technology"]
related: ["[[Binary Application Markup Language]]", "[[Busdma]]", "[[Sysctl]]", "[[System call]]", "[[ALTQ]]", "[[API]]", "[[Apptainer]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[C3D Toolkit]]"]
---

# Application binary interface

An application binary interface (ABI) is an interface exposed by software that is defined for in-process machine code access. Often, the exposing software is a library, and the consumer is a program.
An ABI is at a relatively low level of abstraction. Interface compatibility depends on the target hardware and the software build toolchain. In contrast, an application programming interface (API) defines access in source code, which is a relatively high-level, hardware-independent, and human-readable format. An API defines an interface at the source code level, before compilation, whereas an ABI defines an interface to compiled code.
API compatibility is generally the concern for system design and of the toolchain. However, a programmer may have to deal with an ABI directly when writing a program in multiple languages or when using multiple compilers for the same language.
A complete ABI enables a program that supports an ABI to run without modification on multiple operating systems that provide the ABI. The target system must provide any required libraries (that implement the ABI), and there may be other prerequisites.

## Related

- [[Binary Application Markup Language]]
- [[Busdma]]
- [[Sysctl]]
- [[System call]]
- [[ALTQ]]
- [[API]]
- [[Apptainer]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[C3D Toolkit]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Application_binary_interface