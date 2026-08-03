---
title: "TSIG"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/TSIG"
wikipedia_categories: ["Domain Name System", "Internet Standards", "Internet protocols"]
related: ["[[Domain Name System]]", "[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[Clearinghouse for Networked Information Discovery and Retrieval]]", "[[Diameter Credit-Control Application]]"]
---

# TSIG

TSIG (transaction signature) is a  computer-networking protocol defined
in RFC 2845. Primarily it enables the Domain Name System (DNS) to authenticate updates to a DNS database. It is most commonly used to update Dynamic DNS or a secondary/slave DNS server. TSIG uses shared secret keys and one-way hashing to provide a cryptographically secure means of authenticating each endpoint of a connection as being allowed to make or respond to a DNS update.
Although queries to DNS may usually be made without authentication, updates to DNS must be authenticated, since they make lasting changes to the structure of the Internet naming system.  As the update request may arrive via an insecure channel (the Internet), one must take measures to ensure the authenticity and integrity of the request. The use of a key shared by the client making the update and the DNS server helps to ensure the authenticity and integrity of the update request.  A one-way hashing function serves to prevent malicious observers from modifying the update and forwarding on to the destination, thus ensuring integrity of the message from source to destination.
A timestamp is included in the TSIG protocol to prevent recorded responses from being reused, which would allow an attacker to breach the security of TSIG.  This places a requirement on dynamic DNS servers and TSIG clients to contain an accurate clock.  Since DNS servers are connected to a network, the Network Time Protocol can provide an accurate time source.
DNS updates, like queries, are normally transported via UDP since it requires lower overhead than TCP.  However, DNS servers support both UDP and TCP requests.

## Related

- [[Domain Name System]]
- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]
- [[Clearinghouse for Networked Information Discovery and Retrieval]]
- [[Diameter Credit-Control Application]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/TSIG