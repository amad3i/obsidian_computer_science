---
title: "Frame-bursting"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Frame-bursting"
wikipedia_categories: ["Wireless networking"]
related: ["[[2016 United States wireless spectrum auction]]", "[[Ad hoc wireless distribution service]]", "[[Air2Web]]", "[[AirHop Communications]]", "[[Andrea Goldsmith (engineer)]]", "[[Augmented tree-based routing]]", "[[Backhaul (telecommunications)]]", "[[Barker code]]", "[[Base station]]", "[[Base transceiver station]]"]
---

# Frame-bursting

Frame-bursting is a communication protocol feature used at the link layer in communication networks to alter the transmission characteristics in order to benefit from higher throughput. It is a technique sometimes used in communication protocols for shared mediums to achieve higher throughput by allowing the transmitter to send a series of frames in succession without relinquishing control of the transmission medium. Related techniques used to achieve the same goal include fast frames wherein the inter-frame wait interval is reduced, and jumbo frames wherein the size of the frame is increased. Frame bursting may also benefit from packet aggregation. Communication protocols for shared mediums are designed to relinquish the medium and wait for a while after the transmission of a MAC layer frame in order to facilitate the fair use of the medium by multiple users. Frame bursting may be permissible in certain scenarios such as when the link is point-to-point or when the signal from other users is indistinguishable from noise. Frame bursting allows for more data packets per time interval at the cost of wait time for other users.
In the case of wireless technology, the draft 802.11e quality of service specification allows frame bursting under some situations. Frame bursting may increase the throughput of any (point-to-point) 802.11a, b, g or n link connection under certain conditions. This is done by reducing the overhead associated with the wireless session in either of the following two modes:

Access point to client and vice versa
Client to client in ad hoc mode
Frame bursting and fast framing allow a wireless client to upload data at higher throughputs by using the inter-frame wait intervals to "burst" a sequence of up to three packets before waiting the required period. This allows more data to be sent with less waiting.  However, their use can also result in unbalanced allocation of airtime where there are a mix of clients with and without Frame-Bursting.  In such cases, the inter-frame wait periods cause unsupported stations to wait longer for service availability, and to receive less data transfer throughput. Therefore, it is not recommended for more than 2-3 wireless clients to use frame-bursting as the negative effects can adversely affect the throughput for all clients.
Proprietary extensions that have added frame bursting to the wireless standards include Nitro from Intersil, Super G from Atheros, Xpress from Broadcom and Xtreme G from D-Link.

## Related

- [[2016 United States wireless spectrum auction]]
- [[Ad hoc wireless distribution service]]
- [[Air2Web]]
- [[AirHop Communications]]
- [[Andrea Goldsmith (engineer)]]
- [[Augmented tree-based routing]]
- [[Backhaul (telecommunications)]]
- [[Barker code]]
- [[Base station]]
- [[Base transceiver station]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Frame-bursting