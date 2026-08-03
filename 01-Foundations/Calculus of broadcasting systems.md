---
title: "Calculus of broadcasting systems"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Calculus_of_broadcasting_systems"
wikipedia_categories: ["Parallel computing", "Process calculi"]
related: ["[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]", "[[Apache Samza]]"]
---

# Calculus of broadcasting systems

Calculus of broadcasting systems (CBS) is a CCS-like calculus where processes speak one at a time and each is heard instantaneously by all others. Speech is autonomous, contention between speakers being resolved nondeterministically, but hearing only happens when someone else speaks. Observationally meaningful laws differ from those of CCS. The handshake communication of CCS is changed to broadcast communication in CBS. This allows several additional features:

Priority, which attaches only to autonomous actions, is simply added to CBS in contrast to CCS, where such actions are the result of communication.
A CBS simulator runs a process by returning a list of values it broadcasts. This permits a powerful combination, CBS with the host language. It yields several elegant algorithms. Only processes with a unique response to each input are needed in practice, so weak bi simulation is a congruence.
CBS subsystems are interfaced by translators; by mapping messages to silence, these can restrict hearing and hide speech. Reversing a translator turns its scope inside out. This permits a new specification for a communication link – the environment of each user should behave like the other user.

## Related

- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]
- [[AMD Instinct]]
- [[Amorphous computing]]
- [[Apache Samza]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Calculus_of_broadcasting_systems