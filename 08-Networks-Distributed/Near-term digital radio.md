---
title: "Near-term digital radio"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Near-term_digital_radio"
wikipedia_categories: ["Wireless networking"]
related: ["[[2016 United States wireless spectrum auction]]", "[[Ad hoc wireless distribution service]]", "[[Air2Web]]", "[[AirHop Communications]]", "[[Andrea Goldsmith (engineer)]]", "[[Augmented tree-based routing]]", "[[Backhaul (telecommunications)]]", "[[Barker code]]", "[[Base station]]", "[[Base transceiver station]]"]
---

# Near-term digital radio

The Near-term digital radio (NTDR) program provided a prototype mobile ad hoc network (MANET) radio system to the United States Army, starting in the 1990s. The MANET protocols were provided by Bolt, Beranek and Newman; the radio hardware was supplied by ITT. These systems have been fielded by the United Kingdom as the High-capacity data radio (HCDR) and by the Israelis as the Israeli data radio. They have also been purchased by a number of other countries for experimentation.
The NTDR protocols consist of two components: clustering and routing. The clustering algorithms dynamically organize a given network into cluster heads and cluster members. The cluster heads create a backbone; the cluster members use the services of this backbone to send and receive packets. The cluster heads use a link-state routing algorithm to maintain the integrity of their backbone and to track the locations of cluster members.
The NTDR routers also use a variant of Open Shortest Path First (OSPF) that is called Radio-OSPF (ROSPF). ROSPF does not use the OSPF hello protocol for link discovery, etc. Instead, OSPF adjacencies are created and destroyed as a function of MANET information that is distributed by the NTDR routers, both cluster heads and cluster members. It also supported multicasting.

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

- Wikipedia: https://en.wikipedia.org/wiki/Near-term_digital_radio