---
title: "Traffic indication map"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Traffic_indication_map"
wikipedia_categories: ["Local area networks", "Wireless networking"]
related: ["[[Andrea Goldsmith (engineer)]]", "[[IEEE 802.11af]]", "[[Piggybacking (Internet access)]]", "[[Wireless LAN]]", "[[2016 United States wireless spectrum auction]]", "[[Ad hoc wireless distribution service]]", "[[Air2Web]]", "[[AirHop Communications]]", "[[Augmented tree-based routing]]", "[[Backhaul (telecommunications)]]"]
---

# Traffic indication map

Traffic indication map (TIM) is a structure used in IEEE 802.11 wireless network management frames.
The traffic indication map information element is covered under section 7.3.2.6 of 802.11-1999 standard.
The IEEE 802.11 standards use a bitmap to indicate to any sleeping listening stations that the access point (AP) has buffered data waiting for it. Because stations should listen to at least one beacon during the listen interval, the AP periodically sends this bitmap in its beacons as an information element. The bit mask is called the traffic indication map and consists of 2008 bits, each bit representing the association ID (AID) of a station.
However, in most situations an AP only has data for a few stations, so only the portion of the bitmap representing those stations needs to be transmitted.
Because the bitmap is never transmitted in its entirety, it is referred to as a virtual bitmap, and the portion that is actually transmitted is referred to as a partial virtual bitmap.
The structure of the TIM is as follows:

element ID
(1 octet)
identifies a TIM element
length
(1 octet)
the size of the whole element (5 to 255)
DTIM_count
(1 octet)
the number of beacons remaining before a DTIM (including this frame, so 0 means that this frame is a DTIM)
DTIM_period
(1 octet)
A scaling factor indicating that only every nth beacon includes a TIM. Stations in low-power mode will remain asleep and only wake to listen for those beacons, to determine whether they should also remain awake to receive data frames.
bitmap_control.offset
(7 bits)
bitmap_control.broadcast
(1 bit)
1 when one or more broadcast or multicast frames are queued. This means that all stations should wake up.
partial_virtual_bitmap
(8 to 2008 bits)
This comprises (length-4)×8 bits, each representing a currently-associated station. The low-order bit of the first octet represents station with association ID (bitmap_control.offset×16). Bits outside the partial bitmap are implicitly zero.

## Related

- [[Andrea Goldsmith (engineer)]]
- [[IEEE 802.11af]]
- [[Piggybacking (Internet access)]]
- [[Wireless LAN]]
- [[2016 United States wireless spectrum auction]]
- [[Ad hoc wireless distribution service]]
- [[Air2Web]]
- [[AirHop Communications]]
- [[Augmented tree-based routing]]
- [[Backhaul (telecommunications)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Traffic_indication_map