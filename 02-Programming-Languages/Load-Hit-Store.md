---
title: "Load-Hit-Store"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Load-Hit-Store"
wikipedia_categories: ["Analysis of parallel algorithms", "Compilers"]
related: ["[[Data dependency]]", "[[Absoft]]", "[[Accelerated Linear Algebra]]", "[[Ahead-of-time compilation]]", "[[Apple Dylan]]", "[[Arden2ByteCode]]", "[[Ark Compiler]]", "[[Banerjee test]]", "[[Binary optimizer]]", "[[Binary recompiler]]"]
---

# Load-Hit-Store

A Load-Hit-Store, sometimes abbreviated as LHS, is a data dependency in a CPU in which a memory location that has just been the target of a store operation is loaded from. The CPU may then need to wait until the store finishes, so that the correct value can be retrieved. This involves e.g. a L1 cache roundtrip, during which most or all of the pipeline will be stalled, causing a significant decrease in performance. For example, (C/C++):

Here, the language rules do not allow the compiler to assume that the pointers a and b refer to different memory locations. Therefore, it cannot, in general, keep the stored values in a register for the final addition (or, in this simple example, precalculate the return value to 12), but instead has to emit code that reloads at least the value from the first memory location, *a. The only realistic alternatives are a test-and-branch to see whether a and b are equal, in which case the correct return value is 14, but this adds significant overhead if the pointers are not equal, and optimizations enabled by function inlining.
Now if a call to slow is made with the same address for a and b, there is a data dependency between the memory stores and the memory load(s) in the final statement of slow. Some CPU designs (like general purpose processors for desktop or notebook computers) dedicate a significant amount of die space to complex store-to-load forwarding, which, under suitable circumstances such as native alignment of the operands, can avert having to wait for the cache roundtrip. Other CPUs (e.g. for embedded devices or video game consoles) may use a less elaborate or even minimalistic approach, and rely on the software developer to avoid frequent load-hit-stores in performance-critical code, or remove them during performance optimization. In the minimalistic approach, a store-to-load dependency forces a flush of the store buffers and stalling the pipeline. This ensures that the computation has the correct result, at a high performance cost.

## Related

- [[Data dependency]]
- [[Absoft]]
- [[Accelerated Linear Algebra]]
- [[Ahead-of-time compilation]]
- [[Apple Dylan]]
- [[Arden2ByteCode]]
- [[Ark Compiler]]
- [[Banerjee test]]
- [[Binary optimizer]]
- [[Binary recompiler]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Load-Hit-Store