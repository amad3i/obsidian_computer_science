---
title: "Transport triggered architecture"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Transport_triggered_architecture"
wikipedia_categories: ["Computer architecture", "Instruction processing"]
related: ["[[Branch queue]]", "[[Instruction window]]", "[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[Aperture (computer memory)]]", "[[Approximate computing]]", "[[Arithmetic logic unit]]", "[[Autonomous decentralized system]]", "[[Berkeley IRAM project]]"]
---

# Transport triggered architecture

In computer architecture, a transport triggered architecture (TTA) is a kind of processor design in which programs directly control the internal transport buses of a processor. Computation happens as a side effect of data transports: writing data into a triggering port of a functional unit triggers the functional unit to start a computation. This is similar to what happens in a systolic array. Due to its modular structure, TTA is an ideal processor template for application-specific instruction set processors (ASIP) with customized datapath but without the inflexibility and design cost of fixed function hardware accelerators.
Typically a transport triggered processor has multiple transport buses and multiple functional units connected to the buses, which provides opportunities for instruction-level parallelism. The parallelism is statically defined by the programmer. In this respect (and obviously due to the large instruction word width), the TTA architecture resembles the very long instruction word (VLIW) architecture. A TTA instruction word is composed of multiple slots, one slot per bus, and each slot determines the data transport that takes place on the corresponding bus. The fine-grained control allows some optimizations that are not possible in a conventional processor. For example, software can transfer data directly between functional units without using registers.
Transport triggering exposes some microarchitectural details that are normally hidden from programmers. This greatly simplifies the control logic of a processor, because many decisions normally done at run time are fixed at compile time. However, it also means that a binary compiled for one TTA processor will not run on another one without recompilation if there is even a small difference in the architecture between the two. The binary incompatibility problem, in addition to the complexity of implementing a full context switch, makes TTAs more suitable for embedded systems than for general purpose computing.
Of all the one-instruction set computer architectures, the TTA architecture is one of the few that has had processors based on it built, and the only one that has processors based on it sold commercially.

## Related

- [[Branch queue]]
- [[Instruction window]]
- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]
- [[Aperture (computer memory)]]
- [[Approximate computing]]
- [[Arithmetic logic unit]]
- [[Autonomous decentralized system]]
- [[Berkeley IRAM project]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Transport_triggered_architecture