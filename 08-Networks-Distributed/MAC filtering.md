---
title: "MAC filtering"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/MAC_filtering"
wikipedia_categories: ["Computer network security", "Media access control"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-level gateway]]", "[[Attack tree]]", "[[Authentication server]]", "[[Banner grabbing]]"]
---

# MAC filtering

In computer networking, MAC address filtering is a network access control method whereby the MAC address assigned to each network interface controller is used to determine access to the network.
MAC addresses are uniquely assigned to each card, so using MAC filtering on a network permits and denies network access to specific devices through the use of blacklists and whitelists. While the restriction of network access through the use of lists is straightforward, an individual person is not identified by a MAC address, rather a device only, so an authorized person will need to have a whitelist entry for each device that they would like to access the network.
While giving a network some additional protection, MAC filtering can be circumvented by using a packet analyzer to find a valid MAC and then using MAC spoofing to access the network using that address. MAC address filtering can be considered as security through obscurity because the effectiveness is based on "the secrecy of the implementation or its components".

## Related

- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Anomaly-based intrusion detection system]]
- [[Application Defined Network]]
- [[Application-level gateway]]
- [[Attack tree]]
- [[Authentication server]]
- [[Banner grabbing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/MAC_filtering