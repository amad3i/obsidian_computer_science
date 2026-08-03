---
title: "Red zone (computing)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Red_zone_(computing)"
wikipedia_categories: ["Compilers", "Computer programming stubs"]
related: ["[[Binary recompiler]]", "[[Absoft]]", "[[Accelerated Linear Algebra]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Aggregate pattern]]", "[[Ahead-of-time compilation]]", "[[Apple Dylan]]", "[[Arden2ByteCode]]", "[[Ark Compiler]]"]
---

# Red zone (computing)

In computing, the red zone is a fixed-size area in a function's stack frame below (for a push-down stack) the current stack pointer that is reserved and safe to use. It is most commonly used in leaf functions (functions that don't call other functions) for allocating additional stack memory, without moving the stack pointer, which saves an instruction.
Whether a red zone is present depends on the calling convention. x86-64 systems that use the System V AMD64 ABI (including Linux and macOS) use a 128-byte red zone that begins directly under the current value of the stack pointer. The OpenRISC toolchain assumes a 128-byte red zone. Microsoft Windows does not have the concept of a red zone on x86. In fact, the ABI explicitly states that the memory beyond the stack pointer is volatile and may be overwritten by debuggers or interrupt handlers. However, Microsoft Windows has a red zone of 16 bytes on IA-64, 8 bytes on AArch32, and 16 bytes on AArch64.
The red zone is safe from modification by interrupt/exception/signal handlers - the CPU is generally not aware of the red zone, however, it switches to a kernel stack in the case of an interrupt. If the kernel itself tried to use the red zone in a preemptible context, the contents would be trashed.

## Related

- [[Binary recompiler]]
- [[Absoft]]
- [[Accelerated Linear Algebra]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Aggregate pattern]]
- [[Ahead-of-time compilation]]
- [[Apple Dylan]]
- [[Arden2ByteCode]]
- [[Ark Compiler]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Red_zone_(computing)