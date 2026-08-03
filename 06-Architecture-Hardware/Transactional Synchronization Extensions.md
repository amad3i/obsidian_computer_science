---
title: "Transactional Synchronization Extensions"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Transactional_Synchronization_Extensions"
wikipedia_categories: ["Computer-related introductions in 2012", "Concurrency control", "Hardware bugs", "Instruction set extensions", "Parallel computing", "Transaction processing", "Transactional memory", "X86 instructions"]
related: ["[[Advanced Synchronization Facility]]", "[[ACID]]", "[[Barrier (computer science)]]", "[[Commitment ordering]]", "[[Concurrency control]]", "[[Database transaction schedule]]", "[[Distributed concurrency control]]", "[[Global serializability]]", "[[Graphics Core Next]]", "[[IBM Blue Gene]]"]
---

# Transactional Synchronization Extensions

Transactional Synchronization Extensions (TSX), also called Transactional Synchronization Extensions New Instructions (TSX-NI), is an extension to the x86 instruction set architecture (ISA) that adds hardware transactional memory support, speeding up execution of multi-threaded software through lock elision.  According to different benchmarks, TSX/TSX-NI can provide around 40% faster applications execution in specific workloads, and 4–5 times more database transactions per second (TPS).
TSX/TSX-NI was documented by Intel in February 2012, and debuted in June 2013 on selected Intel microprocessors based on the Haswell microarchitecture.  Haswell processors below 45xx as well as R-series and K-series (with unlocked multiplier) SKUs do not support TSX/TSX-NI. In August 2014, Intel announced a bug in the TSX/TSX-NI implementation on current steppings of Haswell, Haswell-E, Haswell-EP and early Broadwell CPUs, which resulted in disabling the TSX/TSX-NI feature on affected CPUs via a microcode update.
In 2016, a side-channel timing attack was found by abusing the way TSX/TSX-NI handles transactional faults (i.e. page faults) in order to break kernel address space layout randomization (KASLR) on all major operating systems.  In 2021, Intel released a microcode update that disabled the TSX/TSX-NI feature on CPU generations from Skylake to Coffee Lake, as a mitigation for discovered security issues.
While TSX/TSX-NI is not supported anymore in desktop-class processors, it remains supported in the Xeon line of processors (at least on specific models, as of the 6th generation).
Support for TSX/TSX-NI emulation is provided as part of the Intel Software Development Emulator.  There is also experimental support for TSX/TSX-NI emulation in a QEMU fork.

## Related

- [[Advanced Synchronization Facility]]
- [[ACID]]
- [[Barrier (computer science)]]
- [[Commitment ordering]]
- [[Concurrency control]]
- [[Database transaction schedule]]
- [[Distributed concurrency control]]
- [[Global serializability]]
- [[Graphics Core Next]]
- [[IBM Blue Gene]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Transactional_Synchronization_Extensions