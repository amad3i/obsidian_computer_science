---
title: "AQuoSA"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/AQuoSA"
wikipedia_categories: ["Linux kernel features", "Real-time computing"]
related: ["[[Arthur Pollen]]", "[[CompactDAQ]]", "[[CompactRIO]]", "[[CPU shielding]]", "[[Debugfs]]", "[[Earliest deadline first scheduling]]", "[[Earliest eligible virtual deadline first scheduling]]", "[[GTFS Realtime]]", "[[JackBe]]", "[[Kim Guldstrand Larsen]]"]
---

# AQuoSA

AQuoSA (Adaptive Quality of Service Architecture)  is an open architecture for the provisioning of adaptive Quality of Service functionality into the Linux kernel. The project features a flexible, portable, lightweight and open architecture for supporting QoS related services on the top of a general-purpose operating system as Linux. The architecture is well founded on formal scheduling analysis and control theoretical results.
A key feature of AQuoSA is the Resource Reservation layer that is capable of dynamically adapting the CPU allocation for QoS aware applications based on their run-time requirements. In order to provide such functionality, AQuoSA embeds a kernel-level CPU scheduler implementing a resource reservation mechanism for the CPU based on Earliest Deadline First (EDF). This gives the ability to the Linux kernel to realize (partially) temporal isolation among the tasks running within the system.
AQuoSA is one of a few projects that provides real-time scheduling capabilities to unprivileged users on a multi-user system in a controlled way, by means of a properly designed access-control model.

## Related

- [[Arthur Pollen]]
- [[CompactDAQ]]
- [[CompactRIO]]
- [[CPU shielding]]
- [[Debugfs]]
- [[Earliest deadline first scheduling]]
- [[Earliest eligible virtual deadline first scheduling]]
- [[GTFS Realtime]]
- [[JackBe]]
- [[Kim Guldstrand Larsen]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/AQuoSA