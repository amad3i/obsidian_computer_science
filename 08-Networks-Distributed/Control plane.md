---
title: "Control plane"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Control_plane"
wikipedia_categories: ["Internet architecture", "Routers (computing)"]
related: ["[[Core router]]", "[[Data plane]]", "[[Gateway (telecommunications)]]", "[[HERMES-A-MINOTAUR]]", "[[Management plane]]", "[[Router (computing)]]", "[[6bone]]", "[[Adaptive quality of service multi-hop routing]]", "[[Address pool]]", "[[AiScaler]]"]
---

# Control plane

In network routing, the control plane is the part of the router architecture that is concerned with establishing the network topology, or the information in a routing table that defines what to do with incoming packets. Control plane functions, such as participating in routing protocols, run in the architectural control element. In most cases, the routing table contains a list of destination addresses and the outgoing interface or interfaces associated with each. Control plane logic can also identify certain packets to be discarded, as well as preferential treatment of certain packets for which a high quality of service is defined by such mechanisms as differentiated services.
Depending on the specific router implementation, there may be a separate forwarding information base that is populated by the control plane, but used by the high-speed forwarding plane to look up packets and decide how to handle them.
In computing, the control plane is the part of the software that configures and shuts down the data plane. By contrast, the data plane is the part of the software that processes the data requests. The data plane is also sometimes referred to as the forwarding plane.
The distinction has proven useful in the networking field where it originated, as it separates the concerns: the data plane is optimized for speed of processing, and for simplicity and regularity. The control plane is optimized for customizability, handling policies, handling exceptional situations, and in general facilitating and simplifying the data plane processing.

## Related

- [[Core router]]
- [[Data plane]]
- [[Gateway (telecommunications)]]
- [[HERMES-A-MINOTAUR]]
- [[Management plane]]
- [[Router (computing)]]
- [[6bone]]
- [[Adaptive quality of service multi-hop routing]]
- [[Address pool]]
- [[AiScaler]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Control_plane