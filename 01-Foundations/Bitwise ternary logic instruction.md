---
title: "Bitwise ternary logic instruction"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Bitwise_ternary_logic_instruction"
wikipedia_categories: ["Binary arithmetic", "Boolean algebra", "Computer hardware", "Operators (programming)"]
related: ["[[Boolean function]]", "[[1-in-3-SAT]]", "[[4D vector]]", "[[AMD XDNA]]", "[[Analysis of Boolean functions]]", "[[AND gate]]", "[[ASRock M8]]", "[[B5000 instruction set]]", "[[Bent function]]", "[[Binary decision diagram]]"]
---

# Bitwise ternary logic instruction

Bitwise ternary logic instructions can logically implement all possible bitwise operations between three inputs (256 permutations). They take three registers as input and an 8-bit immediate field. Each bit in the output is generated using an 8-bit Lookup table of the three corresponding bits in the inputs to select one of the 8 positions in the 8-bit immediate. Since only 8 combinations are possible using three bits, this allows all possible 3-input bitwise operations to be performed. In mathematical terminology: each corresponding bit of the three inputs is a ternary Boolean function with a Hasse diagram of order n=8. Also known as minterms.
A full table showing all 256 possible 3-operand logical bitwise instruction may be found in the Power ISA description of xxeval . An additional insight is that if the 8-bit immediate were an operand (register) then in FPGA terminology, bitwise ternary logical instructions would implement an array of Hardware LUT3s.
One of the typical applications is an implementation bit manipulation for the symmetric cyphers.

## Related

- [[Boolean function]]
- [[1-in-3-SAT]]
- [[4D vector]]
- [[AMD XDNA]]
- [[Analysis of Boolean functions]]
- [[AND gate]]
- [[ASRock M8]]
- [[B5000 instruction set]]
- [[Bent function]]
- [[Binary decision diagram]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bitwise_ternary_logic_instruction