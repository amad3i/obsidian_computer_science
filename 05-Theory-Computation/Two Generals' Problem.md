---
title: "Two Generals' Problem"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Two_Generals'_Problem"
wikipedia_categories: ["Distributed computing problems", "Theory of computation", "Thought experiments"]
related: ["[[Brooks–Iyengar algorithm]]", "[[Byzantine fault]]", "[[Quantum Byzantine agreement]]", "[[Ackermann function]]", "[[Admissible numbering]]", "[[Andreas Brandstädt]]", "[[Automatic vectorization]]", "[[Big memory]]", "[[Blockhead (thought experiment)]]", "[[Bremermann's limit]]"]
---

# Two Generals' Problem

In computing, the Two Generals' Problem (or Chinese Generals Problem) is a thought experiment meant to illustrate the pitfalls and design challenges of attempting to coordinate an action by communicating over an unreliable link. In the experiment, two generals are only able to communicate with one another by sending a messenger through enemy territory. The experiment asks how they might reach an agreement on the time to launch an attack, while knowing that any messenger they send could be captured.
The Two Generals' Problem appears often as an introduction to the more general Byzantine Generals problem in introductory classes about computer networking (particularly with regard to the Transmission Control Protocol, where it shows that TCP cannot guarantee state consistency between endpoints and why this is the case), though it applies to any type of two-party communication where failures of communication are possible. A key concept in epistemic logic, this problem highlights the importance of common knowledge. Some authors also refer to this as the Two Generals' Paradox, the Two Armies Problem, or the Coordinated Attack Problem.  The Two Generals' Problem was the first computer communication problem to be proven to be unsolvable. An important consequence of this proof is that generalizations such as the Byzantine Generals problem are also unsolvable in the face of arbitrary communication failures, thus providing a base of realistic expectations for any distributed consistency protocols.

## Related

- [[Brooks–Iyengar algorithm]]
- [[Byzantine fault]]
- [[Quantum Byzantine agreement]]
- [[Ackermann function]]
- [[Admissible numbering]]
- [[Andreas Brandstädt]]
- [[Automatic vectorization]]
- [[Big memory]]
- [[Blockhead (thought experiment)]]
- [[Bremermann's limit]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Two_Generals'_Problem