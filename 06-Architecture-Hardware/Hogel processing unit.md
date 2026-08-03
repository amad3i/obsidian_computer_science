---
title: "Hogel processing unit"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Hogel_processing_unit"
wikipedia_categories: ["Graphics hardware", "Holography", "Human–computer interaction"]
related: ["[[10-foot user interface]]", "[[3D human–computer interaction]]", "[[3Dconnexion]]", "[[Aaron Marcus]]", "[[ACM Symposium on User Interface Software and Technology]]", "[[ACM-IEEE Virtual Reality International Conference]]", "[[Activity recognition]]", "[[Adaptation (computer science)]]", "[[Addiction by Design]]", "[[Aesthetic–usability effect]]"]
---

# Hogel processing unit

The Hogel processing unit (HPU) is a computation for rendering hogels.

HPU parallelism
Since many (possibly hundreds) HPUs would be required to drive a single light-field display, it is important that the HPU be an independent processor, requiring minimal support logic and interconnect. The HPU interconnect framework should provide scene, command and sync buffering and relay throughout the topology. Ideally, neither the host system nor the individual HPUs would have knowledge of the interconnect topology or even the depth and breadth of the system.
Hogel parallelism (multivew point rendering)
A critical component of the HPU is the rendering of multiple viewpoints (hogels) in parallel per rendering pass of the geometry to take advantage of vertex and texture cache coherency.

## Related

- [[10-foot user interface]]
- [[3D human–computer interaction]]
- [[3Dconnexion]]
- [[Aaron Marcus]]
- [[ACM Symposium on User Interface Software and Technology]]
- [[ACM-IEEE Virtual Reality International Conference]]
- [[Activity recognition]]
- [[Adaptation (computer science)]]
- [[Addiction by Design]]
- [[Aesthetic–usability effect]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hogel_processing_unit