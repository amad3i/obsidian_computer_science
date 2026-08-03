---
title: "Geometric Arithmetic Parallel Processor"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Geometric_Arithmetic_Parallel_Processor"
wikipedia_categories: ["Computer hardware stubs", "Digital signal processing", "SIMD computing"]
related: ["[[Sensor hub]]", "[[Single instruction, multiple data]]", "[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]"]
---

# Geometric Arithmetic Parallel Processor

In parallel computing, the Geometric Arithmetic Parallel Processor (GAPP), invented by Polish mathematician Włodzimierz Holsztyński in 1981, was patented by Martin Marietta Corporation and was owned by a wide variety of companies over its lifetime, including Lockheed Martin after Martin Marietta, Co. merged with Lockheed.  The final patent assignee was Geo Semiconductor, Inc. at the time of the patent expiration in 2023.  
The GAPP's network topology is a mesh-connected array of single-bit SIMD processing elements (PEs), where each PE can communicate with its neighbor to the north, east, south, and west. Each cell has its own memory. The address-space is the same for all cells. The data travels from the cell memories to the cell registers, and in the opposite direction, in parallel. Characteristically, the cell's arithmetic logic unit (ALU) (that is, its PE) in the early versions of GAPP was nothing but a 1-bit full-adder/subtractor, which efficiently served both the complex arithmetic as well as logical functions, and with the help of shifts it also performed geometric transformations—in short, it was doing all three types of the tasks (while other designs used three separate special-purpose hardware units instead).
The 10,000-element GAPP grew to 82,944 elements by 1992. In its most recent incarnation (as of 2004), the systems by Teranex utilize GAPP arrays of up to 294,912 processing elements.
In mathematics, Holsztyński is known for the Holsztyński theorem.

## Related

- [[Sensor hub]]
- [[Single instruction, multiple data]]
- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]
- [[Adjoint filter]]
- [[Advanced process control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Geometric_Arithmetic_Parallel_Processor