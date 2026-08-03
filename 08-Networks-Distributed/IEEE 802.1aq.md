---
title: "IEEE 802.1aq"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/IEEE_802.1aq"
wikipedia_categories: ["Ethernet standards", "IEEE 802", "Internet architecture", "Link protocols", "Mesh networking", "Network architecture", "Network layer protocols", "Routing"]
related: ["[[Provider Backbone Bridge Traffic Engineering]]", "[[AiScaler]]", "[[Anonymous remailer]]", "[[Any-source multicast]]", "[[AS 7007 incident]]", "[[Classless Inter-Domain Routing]]", "[[Darknet]]", "[[Default route]]", "[[Echo (communications protocol)]]", "[[EncroChat]]"]
---

# IEEE 802.1aq

IEEE 802.1aq is an amendment to the IEEE 802.1Q  networking standard which adds support for Shortest Path Bridging (SPB). This technology is intended to simplify the creation and configuration of Ethernet networks while enabling multipath routing.
SPB is designed to replace the older Spanning Tree Protocols: IEEE 802.1D STP, IEEE 802.1w RSTP, and IEEE 802.1s MSTP. These block any redundant paths that can result in a switching loop, whereas SPB allows all paths to be active with multiple equal-cost paths, provides much larger layer-2 topologies, supports faster convergence times, and improves the efficiency by allowing traffic to load share across all paths of a mesh network. It is designed to preserve the plug-and-play nature that established Ethernet as the de facto protocol at layer 2.
The technology provides VLANs on native Ethernet infrastructures using a link-state protocol to advertise both topology and VLAN membership. Packets are encapsulated at the edge either in MAC-in-MAC per IEEE 802.1ah or tagged per IEEE 802.1Q or IEEE 802.1ad and transported only to other members of VLAN. Unicast, multicast, and broadcast are supported and all routing is on symmetric shortest paths.
The control plane is based on the Intermediate System to Intermediate System (IS-IS) routing protocol, leveraging a small number of extensions defined in RFC 6329.

## Related

- [[Provider Backbone Bridge Traffic Engineering]]
- [[AiScaler]]
- [[Anonymous remailer]]
- [[Any-source multicast]]
- [[AS 7007 incident]]
- [[Classless Inter-Domain Routing]]
- [[Darknet]]
- [[Default route]]
- [[Echo (communications protocol)]]
- [[EncroChat]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IEEE_802.1aq