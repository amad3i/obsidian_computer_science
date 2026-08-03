---
title: "Parallel Redundancy Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Parallel_Redundancy_Protocol"
wikipedia_categories: ["Network protocols", "Networking standards"]
related: ["[[G.9963]]", "[[G.9970]]", "[[G.9972]]", "[[G.hn]]", "[[IEC-IEEE 61850-9-3]]", "[[Precision Time Protocol Industry Profile]]", "[[PXE boot]]", "[[Segmentation and reassembly]]", "[[Trivial File Transfer Protocol]]", "[[Access stratum]]"]
---

# Parallel Redundancy Protocol

Parallel Redundancy Protocol (PRP) is a network protocol standard for Ethernet that provides seamless failover against failure of any network component. This redundancy is invisible to the application.
PRP nodes have two ports and are attached to two separated networks of similar topology. PRP can be implemented entirely in software, i.e. integrated in the network driver. Nodes with single attachment can be attached to one network only. This is in contrast to the companion standard HSR (IEC 62439-3 Clause 5), with which PRP shares the operating principle. 
PRP and HSR are independent of the application-protocol and can be used by most Industrial Ethernet protocols in the IEC 61784 suite. PRP and HSR are standardized by the IEC 62439-3:2016). They have been adopted for substation automation in the framework of IEC 61850.
PRP and HSR are suited for applications that request high availability and short switchover time, such as: protection for electrical substation, synchronized drives, for instance in printing machines or high power inverters. For such applications, the recovery time of commonly used protocols such as the Rapid Spanning Tree Protocol (RSTP) is too long.
The cost of PRP is a duplication of all network elements that require it. Cost impact is low since it makes little difference if the spares lie on the shelf or are actually working in the plant. The maintenance interval is shortened since more components can fail in use, but such outage will remain invisible to the application.
PRP does not cover end node failures, but redundant nodes may be connected via a PRP network.

## Related

- [[G.9963]]
- [[G.9970]]
- [[G.9972]]
- [[G.hn]]
- [[IEC-IEEE 61850-9-3]]
- [[Precision Time Protocol Industry Profile]]
- [[PXE boot]]
- [[Segmentation and reassembly]]
- [[Trivial File Transfer Protocol]]
- [[Access stratum]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Parallel_Redundancy_Protocol