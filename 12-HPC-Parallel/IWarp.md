---
title: "IWarp"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/IWarp"
wikipedia_categories: ["Massively parallel computers", "Parallel computing", "Supercomputers"]
related: ["[[Connection Machine]]", "[[Finite element machine]]", "[[ILLIAC IV]]", "[[Parsytec]]", "[[SUPRENUM]]", "[[Thinking Machines Corporation]]", "[[WARP (systolic array)]]", "[[Computer cluster]]", "[[Heterogeneous Element Processor]]", "[[Parallel Element Processing Ensemble]]"]
---

# IWarp

iWarp was an experimental parallel supercomputer architecture developed as a joint project by Intel and Carnegie Mellon University. The project started in 1988, as a follow-up to CMU's previous WARP research project, in order to explore building an entire parallel-computing "node" in a single microprocessor, complete with memory and communications links. In this respect the iWarp is very similar to the INMOS transputer and nCUBE.
Intel announced iWarp in 1989. The first iWarp prototype was delivered to Carnegie Mellon in summer of 1990, and in fall they received the first 64-cell production systems, followed by two more in 1991. With the creation of the Intel Supercomputing Systems Division in the summer of 1992, the iWarp was merged into the iPSC product line. Intel kept iWarp as a product but stopped actively marketing it.
Each iWarp CPU included a 32-bit ALU with a 64-bit FPU running at 20 MHz. It was purely scalar and completed one instruction per cycle, so the performance was 20 MIPS or 20 megaflops for single precision and 10 MFLOPS for double. The communications were handled by a separate unit on the CPU that drove four serial channels at 40 MB/s, and included networking support in hardware that allowed for up to 20 virtual channels (similar to the system added to the INMOS T9000).
iWarp processors were combined onto boards along with memory, but unlike other systems Intel chose the faster, but more expensive, static RAM for use on the iWarp. Boards typically included four CPUs and anywhere from 512 kB to 4 MB of SRAM.

Another difference in the iWarp was that the systems were connected together as a n-by-m torus, instead of the more common hypercube. A typical system included 64 CPUs connected as an 8×8 torus, which could deliver 1.2 gigaflops peak.
George Cox was the lead architect of the iWarp project. Steven McGeady (later an Intel Vice-president and witness in the Microsoft antitrust case) wrote an innovative development environment that allowed software to be written for the array before it was completed.  Each node of the array was represented by a different Sun workstation on a LAN, with the iWarp's unique inter-node communication protocol simulated over sockets.  Unlike the chip-level simulator, which could not simulate a multi-node array, and which ran very slowly, this environment allowed in-depth development of array software to begin.
The production compiler for iWarp was a C and Fortran compiler based on the AT&T pcc compiler for UNIX, ported under contract for Intel by the Canadian firm HCR Corporation and then extensively modified and extended by Intel.

## Related

- [[Connection Machine]]
- [[Finite element machine]]
- [[ILLIAC IV]]
- [[Parsytec]]
- [[SUPRENUM]]
- [[Thinking Machines Corporation]]
- [[WARP (systolic array)]]
- [[Computer cluster]]
- [[Heterogeneous Element Processor]]
- [[Parallel Element Processing Ensemble]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IWarp