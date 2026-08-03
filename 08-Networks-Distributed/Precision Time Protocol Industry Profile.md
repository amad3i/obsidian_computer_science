---
title: "Precision Time Protocol Industry Profile"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Precision_Time_Protocol_Industry_Profile"
wikipedia_categories: ["Network protocols", "Networking standards"]
related: ["[[G.9963]]", "[[G.9970]]", "[[G.9972]]", "[[G.hn]]", "[[IEC-IEEE 61850-9-3]]", "[[Parallel Redundancy Protocol]]", "[[PXE boot]]", "[[Segmentation and reassembly]]", "[[Trivial File Transfer Protocol]]", "[[Access stratum]]"]
---

# Precision Time Protocol Industry Profile

Industrial automation systems consisting of several distributed controllers need a precise synchronization for commands, events and process data.  
For instance, motors for newspaper printing are synchronized within some 5 microseconds to ensure that the color pixels in the different cylinders come within 0.1 mm at a paper speed of some 20 m/s. Similar requirements exist in high-power semiconductors (e.g. for converting between AC and DC grids) and in drive-by-wire vehicles (e.g. cars with no mechanical steering wheel). 
This synchronisation is provided by the communication network, in most cases Industrial Ethernet.
Many ad-hoc synchronization schemes exist, so IEEE published a standard Precision Time Protocol IEEE 1588 or "PTP", which allows sub-microsecond synchronization of clocks.
PTP is formulated generally, so concrete applications need a stricter profile. In particular, PTP does not specify how the clocks should operate when the network is duplicated for better resilience to failures.
The PTP Industrial Profile (PIP) is a standard of the IEC 62439-3  that specifies in its Annex C two Precision Time Protocol IEEE 1588 / IEC 61588 profiles, L3E2E and L2P2P, to synchronize network clocks with an accuracy of 1 μs and provide fault-tolerance against clock failures.
The IEC 62439-3 PTP profiles are applicable to most Industrial Ethernet networks, for synchronized drives, robotics, vehicular technology and other applications that require precise time distribution, not necessarily using redundant networks.
The IEC 62439-3 profile L2P2P has been adopted as IEC/IEEE 61850-9-3 by the power utility industry to support precise time stamping of voltage and current measurement for differential protection, wide area monitoring and protection, busbar protection and event recording.

The IEC 62439-3 PTP profiles can be used to ensure deterministic operation of critical functions in the automation system itself, for instance precise starting of tasks, resource reservation and deadline supervision. 
The IEC 62439-3 Annexes belongs to the Parallel Redundancy Protocol and High-availability Seamless Redundancy standard suite for high availability automation networks. However, this specification also applies to networks that have no redundancy and do not use PRP or HSR.

## Related

- [[G.9963]]
- [[G.9970]]
- [[G.9972]]
- [[G.hn]]
- [[IEC-IEEE 61850-9-3]]
- [[Parallel Redundancy Protocol]]
- [[PXE boot]]
- [[Segmentation and reassembly]]
- [[Trivial File Transfer Protocol]]
- [[Access stratum]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Precision_Time_Protocol_Industry_Profile