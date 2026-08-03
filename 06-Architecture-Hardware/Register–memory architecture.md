---
title: "Register–memory architecture"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Register–memory_architecture"
wikipedia_categories: ["Computer architecture"]
related: ["[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[Aperture (computer memory)]]", "[[Approximate computing]]", "[[Arithmetic logic unit]]", "[[Autonomous decentralized system]]", "[[Berkeley IRAM project]]", "[[Branch queue]]", "[[Bridging model]]"]
---

# Register–memory architecture

In computer engineering, a register–memory architecture is an instruction set architecture that allows operations to be performed on (or from) memory, as well as registers. If the architecture allows all operands to be in memory or in registers, or in combinations, it is called a "register plus memory" architecture.
In a register–memory approach one of the operands for operations such as the ADD operation may be in memory, while the other is in a register. This differs from a load–store architecture (used by RISC designs such as MIPS) in which both operands for an ADD operation must be in registers before the ADD.
Example of Load-Store (RISC)

;Add mem1 to mem2
mov r1, [mem1]       ; Load first value into register
mov r2, [mem2]       ; Load second value into register
add r2, r1, r2       ; r2 = r1 + r2
mov [mem2],r2        ; Store result

Example of register-memory (CISC)
Some register-memory machines cannot write ALU results to memory, only their registers. This is like an accumulator machine with multiple accumulators:

;Add mem1 to mem2, if add-register-to-memory instructions are not supported
mov r1, [mem1]       ; Load first value into register
add r1, [mem2]       ; Add second value into register
mov [mem2], r1       ; Store result

Some register-memory machines are able to write ALU results directly to memory, saving an instruction:

;Add mem1 to mem2, if add-register-to-memory instructions are supported
mov r1, [mem1]       ; Load first value into register
add [mem2],r1        ; Add it to second value

Example of register plus memory (CISC)

;Add mem1 to mem2
add [mem2],[mem1]       ; Add first to second value

An example of register-memory architecture that can write ALU results to memory is the Intel x86.
Examples of register plus memory architecture are:

IBM System/360 and its successors, which support memory-to-memory fixed-point decimal arithmetic operations, but not binary integer or floating-point arithmetic operations;
PDP-11, which supports memory (or register) source and destination operands for most two-operand integer operations;
VAX, which supports memory or (or register) source and destination operands for binary integer and floating-point arithmetic;
Texas Instruments MSP430 is a rare microcontroller that supports memory (or register) source and destination operands for all 24 of its two-operand operations.
Motorola 68000 series can move data memory-to-memory with nearly all addressing modes. All other integer arithmetic/logic operations require at least one parameter to reside in a register, making it primarily a register-memory machine.

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

- Wikipedia: https://en.wikipedia.org/wiki/Register–memory_architecture