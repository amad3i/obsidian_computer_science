---
title: "Dynamic timing verification"
tags: ["cs", "architecture-hardware", "advanced"]
domain: Architecture & Hardware
level: advanced
source: "https://en.wikipedia.org/wiki/Dynamic_timing_verification"
wikipedia_categories: ["Formal methods", "Timing in electronic circuits"]
related: ["[[Retiming]]", "[[Static timing analysis]]", "[[Statistical static timing analysis]]", "[[1-in-3-SAT]]", "[[Abstract state machine]]", "[[Agent verification]]", "[[Algebraic semantics (computer science)]]", "[[Algebraic specification]]", "[[Algorithm characterizations]]", "[[And-inverter graph]]"]
---

# Dynamic timing verification

Dynamic timing verification is a verification that an ASIC design is fast enough to run without errors at the targeted clock rate.  This is accomplished by simulating the design files used to synthesize the integrated circuit (IC) design.  This is in contrast to static timing analysis, which has a similar goal as dynamic timing verification except it does not require simulating the real functionality of the IC.
Hobbyists often perform a type of dynamic timing verification when they over-clock the CPUs in their computers in order to find the fastest clock rate at which they can run the CPU without errors.  This is a type of dynamic timing verification that is performed after the silicon is manufactured.  In the field of ASIC design, this timing verification is preferably performed before manufacturing the IC in order to make sure that IC works under the required conditions before mass production of the IC.

## Related

- [[Retiming]]
- [[Static timing analysis]]
- [[Statistical static timing analysis]]
- [[1-in-3-SAT]]
- [[Abstract state machine]]
- [[Agent verification]]
- [[Algebraic semantics (computer science)]]
- [[Algebraic specification]]
- [[Algorithm characterizations]]
- [[And-inverter graph]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dynamic_timing_verification