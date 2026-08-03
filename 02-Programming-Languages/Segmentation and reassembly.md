---
title: "Segmentation and reassembly"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Segmentation_and_reassembly"
wikipedia_categories: ["Network protocols", "Networking standards"]
related: ["[[G.9963]]", "[[G.9970]]", "[[G.9972]]", "[[G.hn]]", "[[IEC-IEEE 61850-9-3]]", "[[Parallel Redundancy Protocol]]", "[[Precision Time Protocol Industry Profile]]", "[[PXE boot]]", "[[Trivial File Transfer Protocol]]", "[[Access stratum]]"]
---

# Segmentation and reassembly

Segmentation and reassembly (SAR) is the process used to fragment and reassemble variable length packets into fixed length cells so as to allow them to be transported across Asynchronous Transfer Mode (ATM) networks or other cell based infrastructures. Since ATM's payload is only 48 bytes, nearly every packet from any other protocol has to be processed in this way. Thus, it is an essential process for any ATM node. It is usually handled by a dedicated chip, called the SAR.
The process is conceptually simple: an incoming packet from another protocol to be transmitted across the ATM network is chopped up into segments that fit into 48-byte chunks carried as ATM cell payloads. At the far end, these chunks are fitted back together to reconstitute the original packet.
The process is analogous to the fragmentation of IP packets on reaching an interface with a maximum transmission unit (MTU) less than the packet size and the subsequent reassembly of the original packet  once the fragments have reached the original packet's destination.
Since different types of data are encapsulated in different ways, the details of the segmentation process vary according to the type of data being handled. There are several different schemes, referred to as ATM adaptation layers (AALs). The schemes are:

AAL0 – Raw cells with no special format
AAL1 – Constant bitrate, circuit emulation (T1, E1, etc.)
AAL2 – Variable bitrate synchronous traffic, eous traffic, e.g. Frame Relay transport
AAL5 – Used for most data traffic, such as IP

## Related

- [[G.9963]]
- [[G.9970]]
- [[G.9972]]
- [[G.hn]]
- [[IEC-IEEE 61850-9-3]]
- [[Parallel Redundancy Protocol]]
- [[Precision Time Protocol Industry Profile]]
- [[PXE boot]]
- [[Trivial File Transfer Protocol]]
- [[Access stratum]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Segmentation_and_reassembly