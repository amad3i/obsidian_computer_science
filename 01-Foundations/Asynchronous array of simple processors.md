---
title: "Asynchronous array of simple processors"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Asynchronous_array_of_simple_processors"
wikipedia_categories: ["Digital signal processors", "Manycore processors", "Parallel computing"]
related: ["[[FR-V (microprocessor)]]", "[[Manycore processor]]", "[[Massively parallel processor array]]", "[[Milbeaut]]", "[[Multidimensional DSP with GPU acceleration]]", "[[Single-chip Cloud Computer]]", "[[Spatial architecture]]", "[[Tilera]]", "[[Xeon Phi]]", "[[ABIT BP6]]"]
---

# Asynchronous array of simple processors

The asynchronous array of simple processors (AsAP) architecture comprises a 2-D array of reduced complexity programmable processors with small scratchpad memories interconnected by a reconfigurable mesh network. AsAP was developed by researchers in the VLSI Computation Laboratory (VCL) at the University of California, Davis and achieves high performance and energy efficiency, while using a relatively small circuit area. It was made in 2006.
AsAP processors are well suited for implementation in future fabrication technologies, and are clocked in a globally asynchronous locally synchronous (GALS) fashion. Individual oscillators fully halt (leakage only) in 9 cycles when there is no work to do, and restart at full speed in less than one cycle after work is available. The chip requires no crystal oscillators, phase-locked loops, delay-locked loops, global clock signal, or any global frequency or phase-related signals whatsoever.
The multi-processor architecture makes use of task-level parallelism in many complex digital signal processor (DSP) applications, and also computes many large tasks using fine-grained parallelism.

## Related

- [[FR-V (microprocessor)]]
- [[Manycore processor]]
- [[Massively parallel processor array]]
- [[Milbeaut]]
- [[Multidimensional DSP with GPU acceleration]]
- [[Single-chip Cloud Computer]]
- [[Spatial architecture]]
- [[Tilera]]
- [[Xeon Phi]]
- [[ABIT BP6]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Asynchronous_array_of_simple_processors