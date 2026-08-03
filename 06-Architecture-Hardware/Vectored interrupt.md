---
title: "Vectored interrupt"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Vectored_interrupt"
wikipedia_categories: ["Computer architecture", "Interrupts"]
related: ["[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[Aperture (computer memory)]]", "[[Approximate computing]]", "[[Arithmetic logic unit]]", "[[Autonomous decentralized system]]", "[[Berkeley IRAM project]]", "[[Branch queue]]", "[[Bridging model]]"]
---

# Vectored interrupt

In computer science, a vectored interrupt is a processing technique in which the interrupting device directs the processor to the appropriate interrupt service routine. This is in contrast to a polled interrupt system, in which a single interrupt service routine must determine the source of the interrupt by checking all potential interrupt sources, a slow and relatively laborious process. Vectored interrupts are achieved by assigning each interrupting device a unique code, typically four to eight bits in length. When a device's interrupt is acknowledged, the device sends its unique code over the data bus to the processor, telling the processor which interrupt service routine to execute.

## Related

- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]
- [[Aperture (computer memory)]]
- [[Approximate computing]]
- [[Arithmetic logic unit]]
- [[Autonomous decentralized system]]
- [[Berkeley IRAM project]]
- [[Branch queue]]
- [[Bridging model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Vectored_interrupt