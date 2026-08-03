---
title: "Triangular routing"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Triangular_routing"
wikipedia_categories: ["Network protocols", "Routing"]
related: ["[[Internet Protocol Options]]", "[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[AiScaler]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Anonymous remailer]]", "[[Any-source multicast]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]"]
---

# Triangular routing

Triangular routing is a method for transmitting packets of data in communications networks. It uses a form of routing that sends a packet to a proxy system before transmission to the intended destination. Triangular routing is a problem in mobile IP; however, it finds applications in other networking situations, for instance to avoid problems associated with network address translation (NAT), implemented for example by Skype.

               2) Datagram is intercepted   3) Datagram is
                  by home agent and            detunneled and
                  is tunneled to the           delivered to the
                  care-of address.             mobile node.

                     +-----+          +-------+         +------+
                     |home | =======> |foreign| ------> |mobile|
                     |agent|          | agent | <------ | node |
                     +-----+          +-------+         +------+
    1) Datagram to    /|\         /
       mobile node     |        /   4) For datagrams sent by the
       arrives on      |      /        mobile node, standard IP
       home network    |    /          routing delivers each to its
       via standard    |  |_           destination. In this figure,
       IP routing.   +----+            the foreign agent is the
                     |host|            mobile node's default router.
                     +----+

                    Figure 1:  Operation of Mobile IPv4

## Related

- [[Internet Protocol Options]]
- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[AiScaler]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Anonymous remailer]]
- [[Any-source multicast]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Triangular_routing