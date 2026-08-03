---
title: "Registration Data Access Protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Registration_Data_Access_Protocol"
wikipedia_categories: ["Internet Standards", "Internet protocols"]
related: ["[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[Clearinghouse for Networked Information Discovery and Retrieval]]", "[[Diameter Credit-Control Application]]", "[[Directory information tree]]"]
---

# Registration Data Access Protocol

The Registration Data Access Protocol (RDAP) is a computer network communications protocol standardized by a working group at the Internet Engineering Task Force in 2015, after experimental developments and thorough discussions.  It is a successor to the WHOIS protocol, used to look up relevant registration data from such Internet resources as domain names, IP addresses, and autonomous system numbers.
While WHOIS essentially retrieves free text, RDAP delivers data in a standard, machine-readable JSON format.  In order to accomplish this goal, the output of all operative WHOIS servers was analyzed, taking a census of the labels they used.  RDAP designers, many of whom are members of number or name registries, strove to keep the protocol as simple as possible, since complexity was considered one of the reasons why previous attempts, such as CRISP, failed.  RDAP is based on RESTful web services, so that error codes,  user identification, authentication, and access control can be delivered through HTTP.
The biggest delay in getting RDAP done turned out to be the bootstrap, figuring out where the server is for each top-level domain, IP range, or ASN range.  IANA agreed to host the bootstrap information in suitable registries, and publish it at a well-known location URLs in JSON format. Those registries started  empty and will be gradually populated as registrants of domains and address spaces provide RDAP server information to IANA.  For number registries, ARIN set up a public RDAP service which also features a bootstrap URL, similar to what they do for WHOIS.  For name registries, ICANN requires RDAP compliance since 2013.

## Related

- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Certificate Management over CMS]]
- [[Certificate Management Protocol]]
- [[Clearinghouse for Networked Information Discovery and Retrieval]]
- [[Diameter Credit-Control Application]]
- [[Directory information tree]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Registration_Data_Access_Protocol