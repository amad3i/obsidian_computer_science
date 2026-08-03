---
title: "IEBus"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/IEBus"
wikipedia_categories: ["Computer networks", "Industrial automation", "Industrial computing", "Serial buses"]
related: ["[[Highway Addressable Remote Transducer Protocol]]", "[[Hilscher netx network controller]]", "[[CANaerospace]]", "[[Common Industrial Protocol]]", "[[ControlNet]]", "[[Fourth Industrial Revolution]]", "[[InfiniBand]]", "[[List of network buses]]", "[[Manufacturing Automation Protocol]]", "[[Nondestructive Evaluation 4.0]]"]
---

# IEBus

IEBus (Inter Equipment Bus) is a communication bus specification "between equipments within a vehicle or a chassis" of Renesas Electronics. It defines OSI model layer 1 and layer 2 specification. IEBus is mainly used for car audio and car navigations, which established de facto standard in Japan, though SAE J1850 is major in United States.

IEBus is also used in some vending machines, which major customer is Fuji Electric.
Each button on the vending machine has an IEBus ID, i.e. has a controller.

Detailed specification is disclosed to licensees only, but protocol analyzers are provided from some test equipment vendors.
Its modulation method is PWM (Pulse-Width Modulation) with 6.00 MHz base clock originally, but most of automotive customers use 6.291 MHz, and physical layer is a pair of differential signalling harness. Its physical layer adopts half-duplex, asynchronous, and multi-master communication with carrier-sense multiple access with collision detection (CSMA/CD) for medium access control. It allows for up to fifty units on one bus over a maximum length of 150 meters. Two differential signalling lines are used with Bus+ / Bus− naming, sometimes labeled as Data(+) / Data(−).
It is sometimes described as "IE-BUS", "IE-Bus," or "IE Bus," but these are incorrect. In formal, it is "IEBus."
IEBus® and Inter Equipment Bus® are registered trademark symbols of Renesas Electronics Corporation, formerly NEC Electronics Corporation, (JPO: Reg. No.2552418
and 2552419, respectively).

## Related

- [[Highway Addressable Remote Transducer Protocol]]
- [[Hilscher netx network controller]]
- [[CANaerospace]]
- [[Common Industrial Protocol]]
- [[ControlNet]]
- [[Fourth Industrial Revolution]]
- [[InfiniBand]]
- [[List of network buses]]
- [[Manufacturing Automation Protocol]]
- [[Nondestructive Evaluation 4.0]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IEBus