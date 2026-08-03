---
title: "Register file"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Register_file"
wikipedia_categories: ["Computer architecture", "Digital electronics", "Digital registers"]
related: ["[[Processor register]]", "[[Shift register lookup table]]", "[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[AND gate]]", "[[Aperture (computer memory)]]", "[[Approximate computing]]", "[[Arithmetic logic unit]]", "[[Autonomous decentralized system]]"]
---

# Register file

A register file is an array of addressable registers which has two or more ports that allow concurrent reading and writing of registers in the array. Reading is nondestructive, meaning that the act of reading does not alter the stored data.
Each port is either a write port or a read port, with input and output signals relevant to the port function. All ports have address inputs that specify the register to be accessed. Write ports also have data inputs that specify the value to be written to the register, and a write enable input that allows the data to be written. Read ports have data outputs that convey the register's output value.
Register files are used in a variety of applications, including as processor registers in central processing units (CPUs), as data memory in FIFOs, and in hardware accelerators.

## Related

- [[Processor register]]
- [[Shift register lookup table]]
- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]
- [[AND gate]]
- [[Aperture (computer memory)]]
- [[Approximate computing]]
- [[Arithmetic logic unit]]
- [[Autonomous decentralized system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Register_file