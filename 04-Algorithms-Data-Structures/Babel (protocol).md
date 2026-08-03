---
title: "Babel (protocol)"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Babel_(protocol)"
wikipedia_categories: ["Ad hoc routing protocols", "Mesh networking", "Routing algorithms", "Routing protocols"]
related: ["[[Optimized Link State Routing Protocol]]", "[[Vehicular Reactive Routing protocol]]", "[[Augmented tree-based routing]]", "[[Diffusing update algorithm]]", "[[Distance-vector routing protocol]]", "[[EraMobile]]", "[[Geographic routing]]", "[[Link-state routing protocol]]", "[[MENTOR routing algorithm]]", "[[ODMRP]]"]
---

# Babel (protocol)

The Babel routing protocol is a distance-vector routing protocol for Internet Protocol packet-switched networks that is designed to be robust and efficient on both wireless mesh networks and wired networks.  Babel is described in RFC 8966.
Babel is based on the ideas in Destination-Sequenced Distance Vector routing (DSDV), Ad hoc On-Demand Distance Vector Routing (AODV), and Cisco's Enhanced Interior Gateway Routing Protocol (EIGRP), but uses different techniques for loop avoidance.  Babel has provisions for using multiple dynamically computed metrics; by default, it uses hop-count on wired networks and a variant of expected transmission count on wireless links, but can be configured to take radio diversity into account  or to automatically compute a link's latency and include it in the metric.
Babel operates on IPv4 and IPv6 networks. It has been reported to be a robust protocol and to have fast convergence properties.
In October 2015, Babel was chosen as the mandatory-to-implement protocol by the IETF Homenet working group, albeit on an Experimental basis.  In June 2016, an IETF working group was created whose main goal is to produce a standard version of Babel.  In January 2021, the working group produced a standard version of Babel, then proceeded to publish a number of extensions, including for authentication, source-specific routing, and routing of IPv4 through IPv6 routers.

## Related

- [[Optimized Link State Routing Protocol]]
- [[Vehicular Reactive Routing protocol]]
- [[Augmented tree-based routing]]
- [[Diffusing update algorithm]]
- [[Distance-vector routing protocol]]
- [[EraMobile]]
- [[Geographic routing]]
- [[Link-state routing protocol]]
- [[MENTOR routing algorithm]]
- [[ODMRP]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Babel_(protocol)