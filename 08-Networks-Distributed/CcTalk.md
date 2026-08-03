---
title: "CcTalk"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/CcTalk"
wikipedia_categories: ["Network protocols", "Vending"]
related: ["[[Multi-Drop Bus - Internal Communication Protocol]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]", "[[ATM Adaptation Layer 2]]"]
---

# CcTalk

ccTalk is a serial protocol in widespread use throughout the money transaction and point-of-sale industry. Peripherals such as the currency detectors for coins and banknotes found in a diverse range of automatic payment equipment such as transportation, ticketing, payphones, amusement machines, and retail cash management use ccTalk to talk to the host controller. 
The ccTalk protocol is an open standard.
ccTalk is one of 2 protocols specified by BACTA for use in all AWP machines with serial coin acceptors. (The other is the Host Intelligent Interface protocol developed by Mars Electronics International). It was developed at a company called Coin Controls (hence "cc") on the outskirts of Manchester in north-west England mainly by Engineer Andrew William Barson. The first release of the protocol was in 1996. Coin control would later be renamed Money Controls and from 2010, Crane Payment Solutions.
The protocol uses an asynchronous transfer of character frames in a similar manner to RS232. The main difference is that it uses a single two-way communication data line for half-duplex communication rather than separate transmit and receives lines. It operates at TTL voltages and is ‘multi-drop’ i.e. peripherals can be connected to a common bus and are logically separated by a device address. Each peripheral on the ccTalk bus must have a unique address. The original protocol operated at 4800 baud with subsequent releases standardising on 9600 baud. Low cost bridge chips are now available from a number of manufacturers to allow ccTalk to run over USB at baud rates of at least 1 Mbit/s.
ccTalk protocol stacks have been implemented on a range of devices from tiny Microchip microcontrollers with 512 bytes of ROM to powerful ARM7 32-bit processors. The protocol supports all standard operations for electronic devices such as flash upgrading of firmware, secure transfer of data and detailed diagnostic information.
Advantages of ccTalk include low cost UART technology, a simple-to-understand packet structure, an easily expandable command interface and no licensing requirements. The latter affords the protocol a good deal of popularity in a crowded and highly competitive field similar to open-source software.

## Related

- [[Multi-Drop Bus - Internal Communication Protocol]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]
- [[ATA over Ethernet]]
- [[ATM Adaptation Layer 2]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/CcTalk