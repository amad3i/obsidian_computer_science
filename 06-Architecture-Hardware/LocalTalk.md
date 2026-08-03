---
title: "LocalTalk"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/LocalTalk"
wikipedia_categories: ["Apple Inc. hardware", "Computer network technology", "Legacy hardware", "Link protocols", "Network protocols", "Networking hardware", "Physical layer protocols"]
related: ["[[LocalTalk-to-Ethernet bridge]]", "[[Bonjour Sleep Proxy]]", "[[Dynamic synchronous transfer mode]]", "[[Encapsulation (networking)]]", "[[Frame Relay]]", "[[G.hn]]", "[[Interface Message Processor]]", "[[IP over Avian Carriers]]", "[[Link Layer Topology Discovery]]", "[[Multiple Spanning Tree Protocol]]"]
---

# LocalTalk

LocalTalk is a particular implementation of the physical layer of the AppleTalk networking system from Apple Computer. 
LocalTalk specifies a system of shielded twisted pair cabling, plugged into self-terminating transceivers, running at a rate of 230.4 kbit/s. CSMA/CA was implemented as a random multiple access method.

Networking was envisioned in the Macintosh during planning, so the Mac was given expensive RS-422 capable serial ports, first on a nine-pin D-connector, then on a mini-DIN-8 connector. The ports were driven by the Zilog SCC, which could serve as either a standard UART or handle the much more complicated HDLC protocol, which was a packet oriented protocol that incorporated addressing, bit-stuffing, and packet checksumming in hardware. Coupled together with the RS422 electrical connections, this provided a reasonably-high-speed data connection.
The 230.4 kbit/s bit rate is the highest in the series of standard serial bit rates (110, 150, 300, 600, 1200, 2400, 4800, 9600, 14400, 19200, 28800, 38400, 57600, 115200, 230400) derived from the 3.6864 MHz clock after the customary divide-by-16. This clock frequency, 3.6864 MHz, was chosen (in part) to support the common asynchronous baud rates up to 38.4 kbit/s using the SCC's internal baud-rate generator. When the SCC's internal PLL was used to lock to the clock embedded in the LocalTalk serial data stream (using its FM0 encoding method) a divide-by-16 setting on the PLL yielded the fastest rate available, namely 230.4 kbit/s.
Originally released as "AppleTalk Personal Network", LocalTalk used shielded twisted-pair cable with three-pin mini-DIN connectors. Cables were daisy-chained from transceiver to transceiver. Each transceiver had two three-pin mini-DIN ports, and a "pigtail" cable to connect to the Mac's DE-9 serial connector. Later, when the Mac Plus introduced the eight-pin mini-DIN serial connector, transceivers were updated as well.
A variation of LocalTalk called PhoneNET was introduced by Farallon Computing. It used standard unshielded side-by-side telephone wire, with six-position modular connectors (same as the popular RJ11 telephone connectors) connected to a PhoneNET transceiver, instead of the expensive, shielded, twisted-pair cable. In addition to being lower cost, PhoneNET-wired networks were more reliable due to the connections being more difficult to accidentally disconnect. In addition, because it used the "outer" pair of the modular connector, it could travel on many pre-existing phone cables and jacks where just the inner pair was in use for RJ11 telephone service. PhoneNET was also able to use an office's existing phone wire, allowing for entire floors of computers to be easily networked. Farallon introduced a 12-port hub, which made constructing star topology networks of up to 48 devices as easy as adding jacks at the workstations and some jumpers in the phone closet. These factors led to PhoneNET largely supplanting LocalTalk wiring in low-cost networking.
The useful life of PhoneNET was extended with the introduction of LocalTalk switching technology by Tribe Computer Works. Introduced in 1990, the Tribe LocalSwitch was a 16-port packet switch designed to speed up overloaded PhoneNET networks.
The widespread availability of Ethernet-based networking in the early 1990s led to the swift disappearance of both LocalTalk and PhoneNET. They remained in use for some time in low-cost applications and applications where Ethernet cannot be used. Macintosh Quadra and early models of Power Macintosh supported both 10BASE2 and 10BASE-T via the Apple Attachment Unit Interface (AAUI), and all other Ethernet media via an AAUI–AUI adapter, while still supporting LocalTalk-based networking. For older Macintosh computers that did not have built-in Ethernet, a high-speed SCSI-to-Ethernet adapter was available, and was particularly popular on PowerBooks. This enabled all but the earliest Macintosh models to access a high-speed Ethernet network.
With the release of the iMac in 1998 the traditional Mac serial port—and thus, the ability to use both LocalTalk and PhoneNET—disappeared from new models of Macintosh. LocalTalk-to-Ethernet bridges were introduced to allow legacy devices (especially printers) to function on newer networks. For very old Macintosh computers, LocalTalk remains the only option.

## Related

- [[LocalTalk-to-Ethernet bridge]]
- [[Bonjour Sleep Proxy]]
- [[Dynamic synchronous transfer mode]]
- [[Encapsulation (networking)]]
- [[Frame Relay]]
- [[G.hn]]
- [[Interface Message Processor]]
- [[IP over Avian Carriers]]
- [[Link Layer Topology Discovery]]
- [[Multiple Spanning Tree Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/LocalTalk