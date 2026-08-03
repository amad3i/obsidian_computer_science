---
title: "FDR (software)"
tags: ["cs", "hpc-parallel", "advanced"]
domain: HPC & Parallel
level: advanced
source: "https://en.wikipedia.org/wiki/FDR_(software)"
wikipedia_categories: ["Computer programming tool stubs", "Concurrent computing", "Model checkers", "Oxford University Computing Laboratory"]
related: ["[[Actor model]]", "[[Cache coherence]]", "[[Choreographic programming]]", "[[CiMPLE]]", "[[Communicating sequential processes]]", "[[CompCert]]", "[[Computer cluster]]", "[[Computer multitasking]]", "[[Concurrency pattern]]", "[[Concurrent computing]]"]
---

# FDR (software)

FDR (Failures-Divergences Refinement) and subsequently FDR2, FDR3 and FDR4 are refinement checking software tools, designed to check formal models expressed in communicating sequential processes (CSP). The tools were originally developed by Formal Systems (Europe) Ltd. Bill Roscoe of the Department of Computer Science, University of Oxford devised many of the algorithms used by the tool and Michael Goldsmith was instrumental in the implementation. 
FDR2 was developed by Department of Computer Science, University of Oxford from where it was freely available
for academic and other non-commercial use.
FDR is often described as a model checker, but is technically a refinement checker, in that it converts two CSP process expressions into Labelled Transition Systems (LTSs), and then determines whether one of the processes is a refinement of the other within some specified semantic model (traces, failures, failures/divergence and some other alternatives). FDR2 applies various state-space compression algorithms to the process LTSs in order to reduce the size of the state-space that must be explored during a refinement check.
FDR2 has gone through many releases, having replaced the earlier tool now referred to as FDR1 in 1995. It has been succeeded by FDR3, a completely re-written version incorporating amongst other things parallel execution and an integrated type checker. FDR3 is released by the University of Oxford, which also released FDR2 in the period 2008–12. A ProBE CSP Animator is integrated in FDR3. It now has been succeeded by FDR4. FDR4 is available from Cocotec.

## Related

- [[Actor model]]
- [[Cache coherence]]
- [[Choreographic programming]]
- [[CiMPLE]]
- [[Communicating sequential processes]]
- [[CompCert]]
- [[Computer cluster]]
- [[Computer multitasking]]
- [[Concurrency pattern]]
- [[Concurrent computing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/FDR_(software)