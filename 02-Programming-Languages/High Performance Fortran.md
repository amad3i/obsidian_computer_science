---
title: "High Performance Fortran"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/High_Performance_Fortran"
wikipedia_categories: ["Concurrent programming languages", "Fortran programming language family"]
related: ["[[DAP FORTRAN]]", "[[Fortress (programming language)]]", "[[-Lisp]]", "[[Actor-Based Concurrent Language]]", "[[AgentSheets]]", "[[Alef (programming language)]]", "[[Algorithmic skeleton]]", "[[AmbientTalk]]", "[[Ateji PX]]", "[[Axum (programming language)]]"]
---

# High Performance Fortran

High Performance Fortran (HPF) is an extension of Fortran 90 designed to support parallel computing, developed by the High Performance Fortran Forum (HPFF). The HPFF was convened and chaired by Ken Kennedy of Rice University. The first version of the HPF Report was published in 1993.
Building on the array syntax introduced in Fortran 90, HPF employs a data-parallel model of computation, enabling the distribution of array computations across multiple processors. This design facilitates efficient execution on both SIMD and MIMD architectures. Key features of HPF include:

New Fortran constructs, such as FORALL, and the ability to define PURE (side-effect-free) procedures
Compiler directives for recommended array data alignment and distribution, influenced by prior efforts such as Fortran D and Vienna Fortran
Directives for specifying processor arrangements (e.g., rank, extent)
Directives for asserting loop iteration independence to enable parallel execution
An extrinsic procedure interface, allowing integration with non-HPF parallel code such as message-passing libraries
Additional library routines, including:
Environmental inquiry functions
Parallel prefix and suffix operations (e.g., scan, segmented scan)
Data scattering and gathering
Sorting operations
Some HPF capabilities were incorporated into the Fortran 95 standard. Subsequently, the HPFF reconvened and released the HPF 2.0 Report, which removed features already standardized in Fortran 95 and revised other sections based on implementation experience with HPF 1.0.
Although several vendors implemented HPF compilers in the 1990s, adoption was limited due to the complexity of implementation and limited practical benefit for some applications. Since then, most developers have transitioned to using OpenMP for parallel programming. Nonetheless, HPF has had a lasting influence on the evolution of parallel programming in Fortran. For instance, the BIT data type proposal for the Fortran 2008 standard included several intrinsic functions derived from HPF.

## Related

- [[DAP FORTRAN]]
- [[Fortress (programming language)]]
- [[-Lisp]]
- [[Actor-Based Concurrent Language]]
- [[AgentSheets]]
- [[Alef (programming language)]]
- [[Algorithmic skeleton]]
- [[AmbientTalk]]
- [[Ateji PX]]
- [[Axum (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/High_Performance_Fortran