---
title: "Fate-sharing"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Fate-sharing"
wikipedia_categories: ["Computer network stubs", "Internet architecture", "Programming paradigms"]
related: ["[[Application-layer framing]]", "[[Circuit-level gateway]]", "[[DIMES]]", "[[Echo (communications protocol)]]", "[[End-to-end principle]]", "[[Global network positioning]]", "[[Identifier-Locator Network Protocol]]", "[[IP aliasing]]", "[[Management plane]]", "[[Per-hop behaviour]]"]
---

# Fate-sharing

Fate-sharing is an engineering design philosophy where related parts of a system are yoked together, so that they either fail together or not at all. Fate-sharing is an example of the end-to-end principle. The term "fate-sharing" was defined by David D. Clark in his 1988 paper "The Design Philosophy of the DARPA Internet Protocols" as follows:

The fate-sharing model suggests that it is acceptable to lose the state information associated with an entity if, at the same time, the entity itself is lost. Specifically, information about transport level synchronization is stored in the host which is attached to the net and using its communication service.
Since the connection between two parties should fail if either party fails, it is acceptable to lose any state associated with the connection when one of them fails. Hence, fate sharing suggests that connection state should be stored directly on the two communicating parties, rather than on any other node within the network.

## Related

- [[Application-layer framing]]
- [[Circuit-level gateway]]
- [[DIMES]]
- [[Echo (communications protocol)]]
- [[End-to-end principle]]
- [[Global network positioning]]
- [[Identifier-Locator Network Protocol]]
- [[IP aliasing]]
- [[Management plane]]
- [[Per-hop behaviour]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Fate-sharing