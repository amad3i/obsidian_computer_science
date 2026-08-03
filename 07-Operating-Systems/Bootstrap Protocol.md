---
title: "Bootstrap Protocol"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Bootstrap_Protocol"
wikipedia_categories: ["Internet Standards", "Internet protocols", "Network booting"]
related: ["[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[Clearinghouse for Networked Information Discovery and Retrieval]]", "[[Diameter Credit-Control Application]]", "[[Directory information tree]]", "[[Domain Name System]]"]
---

# Bootstrap Protocol

The Bootstrap Protocol (BOOTP) is a computer networking protocol used in 
Internet Protocol networks to automatically assign an IP address to network devices from a configuration server. The BOOTP was originally defined in RFC 951 published in 1985.
While some parts of BOOTP have been effectively superseded by the Dynamic Host Configuration Protocol (DHCP), which adds the feature of leases, parts of BOOTP are used to provide service to the DHCP protocol. Some DHCP servers also provide the legacy BOOTP functionality.
When a network-connected computer boots up, its IP stack broadcasts BOOTP network messages requesting an IP address assignment. A BOOTP configuration server replies to the request by assigning an IP address from a pool of addresses, which is preconfigured by an administrator.
BOOTP is implemented using the User Datagram Protocol (UDP) for transport. Port number 67 is used by the server for receiving client requests, and port number 68 is used by the client for receiving server responses. BOOTP operates only on IPv4 networks.
Historically, BOOTP has also been used for Unix-like diskless workstations to obtain the network location of their boot image, in addition to the IP address assignment. Enterprises used it to roll out a pre-configured client (e.g., Windows) installation to newly installed PCs.
Initially requiring the use of a boot floppy disk to establish the initial network connection, manufacturers of network interfaces later embedded the protocol in the firmware of interface cards as well as system boards with on-board network interfaces, thus allowing direct network booting.

## Related

- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]
- [[Clearinghouse for Networked Information Discovery and Retrieval]]
- [[Diameter Credit-Control Application]]
- [[Directory information tree]]
- [[Domain Name System]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bootstrap_Protocol