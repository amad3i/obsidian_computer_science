---
title: "Megahertz myth"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Megahertz_myth"
wikipedia_categories: ["Clock signal", "Computer performance", "Microprocessors", "Misconceptions"]
related: ["[[Microprocessor chronology]]", "[[Asynchronous circuit]]", "[[Circuit Layer Operations per Second]]", "[[CleanMyMac]]", "[[Code motion]]", "[[European Processor Initiative]]", "[[Instruction set architecture]]", "[[Interconnect bottleneck]]", "[[Latency oriented processor architecture]]", "[[List of microprocessors]]"]
---

# Megahertz myth

The megahertz myth, or in more recent cases the gigahertz myth, refers to the misconception of only using clock rate (for example measured in megahertz or gigahertz) to compare the performance of different microprocessors. While clock rates are a valid way of comparing the performance of different speeds of the same model and type of processor, other factors such as an amount of execution units, pipeline depth, cache hierarchy, branch prediction, and instruction sets can greatly affect the performance when considering different processors. For example, one processor may take two clock cycles to add two numbers and another clock cycle to multiply by a third number, whereas another processor may do the same calculation in two clock cycles. Comparisons between different types of processors are difficult because performance varies depending on the type of task. A benchmark is a more thorough way of measuring and comparing computer performance.
The myth started around 1984 when comparing the Apple II with the IBM PC. The argument was that the IBM computer was five times faster than the Apple II, as its Intel 8088 processor had a clock speed roughly 4.7 times the clock speed of the MOS Technology 6502 used in the latter. However, what really matters is not how finely divided a machine's instructions are, but how long it takes to complete a given task. Consider the LDA # (Load Accumulator Immediate) instruction. On a 6502 that instruction requires two clock cycles, or 2 μs at 1 MHz. Although the 4.77 MHz 8088's clock cycles are shorter, the LDA # needs at least 4 of them, so it takes 4 / 4.77 MHz = 0.84 μs at least. So, at best, that instruction runs only a little more than 2 times as fast on the original IBM PC than on the Apple II.

## Related

- [[Microprocessor chronology]]
- [[Asynchronous circuit]]
- [[Circuit Layer Operations per Second]]
- [[CleanMyMac]]
- [[Code motion]]
- [[European Processor Initiative]]
- [[Instruction set architecture]]
- [[Interconnect bottleneck]]
- [[Latency oriented processor architecture]]
- [[List of microprocessors]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Megahertz_myth