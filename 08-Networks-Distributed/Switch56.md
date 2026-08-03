---
title: "Switch56"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Switch56"
wikipedia_categories: ["Network protocols", "Telephone exchange equipment"]
related: ["[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]", "[[ATM Adaptation Layer 2]]", "[[ATM Adaptation Layer 5]]"]
---

# Switch56

Nortel's Switch56 was a networking protocol built on top of the telephone cabling hardware of their Digital Multiplex System and other telephone switches. It was also offered by most other digital telephony suppliers, despite there being no official standards. Service was widely resold under a number of names by telecommunications companies that had large investments in digital backbones. Bell Atlantic called their version "Switched 56", while Southwestern Bell called theirs "MicroLink 1", for instance. The term switched 56 became common to refer to the concept in general.
The name is in two parts. The "switched" refers to the fact that the system uses on-demand dial-up connections, which are routed through the public telephone switching system. The 56 refers to the fact that it carried 56 kbit/s of data on its 64 kbit/s lines, as opposed to most systems, including ISDN, where the entire 64 kbit/s bandwidth was available for data. This particular speed was a side effect of Nortel using an early 2-wire protocol to carry both voice and switching commands, as opposed to other systems like AT&T's Signalling System No. 7 where the command data was carried on a separate set of low-speed lines. Switch56 "folded" the two sources of data into one, placing a single bit from the command channel onto the end of every 7 bits of data, similar to the original T-carrier supervision scheme. This data was split out at the far end of the connection as 56 kbit/s and 8 kbit/s subchannels.
Switch56 services were offered by many hardware vendors, and was implemented by installing custom central distribution units (CDU) at the central office (CO) that acted as a protocol adapter, in US use, the CDU side was normally on a AT&T 4EES. This was then connected to the physical line using a data service unit (DSU), which ran over the public lines to the customer site where it was turned back into network data using a customer unit from Nortel.
Switch56 was not high-performance even by the standards of contemporary systems, and was used mostly where traffic was "sporadic and relatively small". However, it was also very inexpensive, often much less than the corresponding ISDN service which was only marginally faster. Around the same time Switch56 was being offered, a similar on-demand service using frame relay over T-1 lines was also being offered, which was much faster but also much more expensive. This gave Switch56 a cost advantage and was common among companies that had large Nortel investments, especially between branch offices that were connected using a Nortel PBX like the Meridian Norstar. 
For the LAN role new telephone terminals were produced with a RS-232C port on the back, which were then plugged into the user's computer and used with custom software. It appears Switch56 saw little use in this role, and the system was normally used with routers that bridged the Switch56 data onto other LAN systems like Ethernet. The system was commonly used as the basis for videoconferencing systems in the era when these required custom hardware and "high speed" lines, in which case it was common to bond two Switch56 lines into a 112 kbps channel.

## Related

- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]
- [[ATA over Ethernet]]
- [[ATM Adaptation Layer 2]]
- [[ATM Adaptation Layer 5]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Switch56