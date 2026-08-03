---
title: "Standalone program"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Standalone_program"
wikipedia_categories: ["Computer programming", "Legacy systems"]
related: ["[[Algorave]]", "[[Asynchronous procedure call]]", "[[Asynchrony (computer programming)]]", "[[Bayesian program synthesis]]", "[[Boolean flag]]", "[[Breakpoint]]", "[[Characterization test]]", "[[Cheat sheet]]", "[[Code Club]]", "[[Code Words]]"]
---

# Standalone program

A standalone program, also known as a freestanding program, is a computer program that does not load any external module, library function or program and that is designed to boot with the bootstrap procedure of the target processor – it runs on bare metal. In early computers like the ENIAC without the concept of an operating system, standalone programs were the only way to run a computer. Standalone programs are usually written in assembly language for a specific hardware.
Later standalone programs typically were provided for utility functions such as disk formatting. Also, computers with very limited memory may use standalone programs, i.e. most computers until the mid-1950s and later still embedded processors.
Standalone programs are now mainly limited to SoC's or microcontrollers (where battery life, price, and data space are at premiums) and critical systems. In extreme cases every possible set of inputs and errors must be tested and thus every potential output known; fully independent [separate physical suppliers and programming teams] yet fully parallel system-state monitoring; or where the attack surface must be minimized; an operating system would add unacceptable complexity and uncertainty (examples include industrial operator safety interrupts, commercial airlines, medical devices, ballistic missile launch controls and lithium-battery charge controllers in consumer devices [fire hazard and chip cost of approximately 10 cents]). Resource limited microcontrollers can also be made more tolerant of varied environmental conditions than the more powerful hardware needed for an operating system; this is possible because of the much lower clock frequency, pin spacing, lack of large data buses (e.g. DDR4 RAM modules), and limited transistor count allowance for wider design margins and thus the potential for more robust electrical and physical properties both in circuit layout and material choices.

## Related

- [[Algorave]]
- [[Asynchronous procedure call]]
- [[Asynchrony (computer programming)]]
- [[Bayesian program synthesis]]
- [[Boolean flag]]
- [[Breakpoint]]
- [[Characterization test]]
- [[Cheat sheet]]
- [[Code Club]]
- [[Code Words]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Standalone_program