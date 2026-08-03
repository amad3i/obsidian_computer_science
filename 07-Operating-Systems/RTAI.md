---
title: "RTAI"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/RTAI"
wikipedia_categories: ["Linux kernel", "Real-time operating systems"]
related: ["[[PREEMPT RT]]", "[[BogoMips]]", "[[Boot folder]]", "[[Booting process of Linux]]", "[[Configuration Menu Language]]", "[[Copy Fail]]", "[[Cryptoloop]]", "[[Debugfs]]", "[[Dirty COW]]", "[[Dprobes]]"]
---

# RTAI

Real-time application interface (RTAI) is a real-time extension for the Linux kernel, which lets users write applications with strict timing constraints for Linux.  Like Linux itself the RTAI software is a community effort.  RTAI provides deterministic response to interrupts, POSIX-compliant and native RTAI real-time tasks. RTAI supports several architectures, including IA-32 (with and without FPU and TSC), x86-64, PowerPC, ARM (StrongARM and ARM7: clps711x-family, Cirrus Logic EP7xxx, CS89712, PXA25x), and MIPS.
RTAI consists mainly of two parts: an Adeos-based patch to the Linux kernel which introduces a hardware abstraction layer, and a broad variety of services which make lives of real-time programmers easier.  RTAI versions over 3.0 use an Adeos kernel patch, slightly modified in the x86 architecture case, providing additional abstraction and much lessened dependencies on the "patched" operating system. Adeos is a kernel patch comprising an Interrupt Pipeline where different operating system domains register interrupt handlers. This way, RTAI can transparently take over interrupts while leaving the processing of all others to Linux. Use of Adeos also frees RTAI from patent restrictions caused by RTLinux project.

## Related

- [[PREEMPT RT]]
- [[BogoMips]]
- [[Boot folder]]
- [[Booting process of Linux]]
- [[Configuration Menu Language]]
- [[Copy Fail]]
- [[Cryptoloop]]
- [[Debugfs]]
- [[Dirty COW]]
- [[Dprobes]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/RTAI