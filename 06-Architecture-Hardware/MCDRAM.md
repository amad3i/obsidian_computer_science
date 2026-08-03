---
title: "MCDRAM"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/MCDRAM"
wikipedia_categories: ["Computer-related introductions in 2016", "Computer architecture", "Computer memory", "Intel", "Parallel computing"]
related: ["[[Aperture (computer memory)]]", "[[Cache hierarchy]]", "[[Cache pollution]]", "[[Cache-only memory architecture]]", "[[Cellular architecture]]", "[[Computational RAM]]", "[[Content-addressable parallel processor]]", "[[DOPIPE]]", "[[Manycore processor]]", "[[Memory coherence]]"]
---

# MCDRAM

Multi-Channel DRAM or MCDRAM (pronounced em cee dee ram) is a 3D-stacked DRAM that is used in the Intel Xeon Phi processor codenamed Knights Landing.  It is a version of Hybrid Memory Cube developed in partnership with Micron Technology, and a competitor to High Bandwidth Memory.  
The many cores in the Xeon Phi processors, along with their associated vector processing units, enable them to consume many more gigabytes per second than traditional DRAM DIMMs can supply.  The "Multi-channel" part of the MCDRAM full name reflects the cores having many more channels available to access the MCDRAM than processors have to access their attached DIMMs.
This high channel count leads to MCDRAM's high bandwidth, up to 400+ GB/s, although the latencies are similar to a DIMM access.
Its physical placement on the processor imposes some limits on capacity – up to 16 GB at launch, although speculated to go higher in the future.

## Related

- [[Aperture (computer memory)]]
- [[Cache hierarchy]]
- [[Cache pollution]]
- [[Cache-only memory architecture]]
- [[Cellular architecture]]
- [[Computational RAM]]
- [[Content-addressable parallel processor]]
- [[DOPIPE]]
- [[Manycore processor]]
- [[Memory coherence]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MCDRAM