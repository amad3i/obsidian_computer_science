---
title: "Capability Hardware Enhanced RISC Instructions"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Capability_Hardware_Enhanced_RISC_Instructions"
wikipedia_categories: []
related: []
---

# Capability Hardware Enhanced RISC Instructions

Capability Hardware Enhanced RISC Instructions (CHERI) is a technology designed to improve security for reduced instruction set computer (RISC) processors. CHERI aims to address the root cause of the problems caused by lack of memory safety in common implementations of programming languages such as C and C++, which are responsible for around 70% of security vulnerabilities in modern systems.
The hardware works by giving each reference to any piece of data or system resource its own access rules. This prevents programs from accessing or changing things they should not. It also makes it hard to trick a part of a program into accessing or changing something that it should be able to access, but at a different time. The same mechanism is used to implement privilege separation, dividing processes into compartments that limit the damage that a bug (security or otherwise) can do.
CHERI can be added to many different instruction set architectures including MIPS, AArch64, and RISC-V, making it usable across a wide range of platforms.
Software must be recompiled to gain fine-grained memory-safety benefits from CHERI, but most software requires few (if any) changes to the source code. CHERI's importance has been recognised by governments as a way to improve cybersecurity and protect critical systems. It is under active development by various business and academic organizations.

## Related

*(no automatic links — see MOC)*

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Capability_Hardware_Enhanced_RISC_Instructions