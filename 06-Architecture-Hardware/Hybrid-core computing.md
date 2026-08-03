---
title: "Hybrid-core computing"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Hybrid-core_computing"
wikipedia_categories: ["Computer architecture", "Computer hardware stubs"]
related: ["[[Cellular architecture]]", "[[Machine Check Architecture]]", "[[SpiNNaker]]", "[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[Aperture (computer memory)]]", "[[Approximate computing]]", "[[Arithmetic logic unit]]", "[[Autonomous decentralized system]]"]
---

# Hybrid-core computing

Hybrid-core computing is the technique of extending a commodity instruction set architecture (e.g. x86) with application-specific instructions to accelerate application performance. It is a form of heterogeneous computing wherein asymmetric computational units coexist with a "commodity" processor.
Hybrid-core processing differs from general heterogeneous computing in that the computational units share a common logical address space, and an executable is composed of a single instruction stream—in essence a contemporary coprocessor. The instruction set of a hybrid-core computing system contains instructions that can be dispatched either to the host instruction set or to the application-specific hardware.
Typically, hybrid-core computing is best deployed where the predominance of computational cycles are spent in a few identifiable kernels, as is often seen in high-performance computing applications. Acceleration is especially pronounced when the kernel's logic maps poorly to a sequence of commodity processor instructions, and/or maps well to the application-specific hardware.
Hybrid-core computing is used to accelerate applications beyond what is currently physically possible with off-the-shelf processors, or to lower power & cooling costs in a data center by reducing computational footprint. (i.e., to circumvent obstacles such as the power/density challenges faced with today's commodity processors).

## Related

- [[Cellular architecture]]
- [[Machine Check Architecture]]
- [[SpiNNaker]]
- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]
- [[Aperture (computer memory)]]
- [[Approximate computing]]
- [[Arithmetic logic unit]]
- [[Autonomous decentralized system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hybrid-core_computing