---
title: "Instruction window"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Instruction_window"
wikipedia_categories: ["Computer architecture", "Instruction processing"]
related: ["[[Branch queue]]", "[[Transport triggered architecture]]", "[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[Aperture (computer memory)]]", "[[Approximate computing]]", "[[Arithmetic logic unit]]", "[[Autonomous decentralized system]]", "[[Berkeley IRAM project]]"]
---

# Instruction window

An instruction window in computer architecture refers to the set of instructions which can execute out-of-order in a speculative processor.
In particular, in a conventional design, the instruction window consists of all instructions which are in the re-order buffer (ROB). In such a processor, any instruction within the instruction window can be executed when its operands are ready. Out-of-order processors derive their name because this may occur out-of-order (if operands to a younger instruction are ready before those of an older instruction).
The instruction window has a finite size, and new instructions can enter the window (usually called dispatch or allocate) only when other instructions leave the window (usually called retire or commit). Instructions enter and leave the instruction window in program order, and an instruction can only leave the window when it is the oldest instruction in the window, and it has been completed. Hence, the instruction window can be seen as a sliding window in which the instructions can become out-of-order. All execution within the window is speculative (i.e., side-effects are not applied outside the CPU) until it is committed in order to support asynchronous exception handling like interrupts.
This paradigm is also known as restricted dataflow because instructions within the window execute in dataflow order (not necessarily in program order) but the window in which this occurs is restricted (of finite size).
The instruction window is distinct from pipelining: instructions in an in-order pipeline are not in an instruction window in the conventionally understood sense, because they cannot execute out of order with respect to one another. Out-of-order processors are usually built around pipelines, but many of the pipeline stages (e.g., front-end instruction fetch and decode stages) are not considered to be part of the instruction window.

## Related

- [[Branch queue]]
- [[Transport triggered architecture]]
- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]
- [[Aperture (computer memory)]]
- [[Approximate computing]]
- [[Arithmetic logic unit]]
- [[Autonomous decentralized system]]
- [[Berkeley IRAM project]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Instruction_window