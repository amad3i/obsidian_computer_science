---
title: "RadSec"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/RadSec"
wikipedia_categories: ["Application layer protocols", "Computer access control protocols", "Internet protocols"]
related: ["[[RADIUS]]", "[[Border Gateway Protocol]]", "[[DNS over HTTPS]]", "[[DNS over TLS]]", "[[Domain Name System]]", "[[GPSoverIP]]", "[[HMAC-based one-time password]]", "[[Internationalized Resource Identifier]]", "[[Internet Content Adaptation Protocol]]", "[[Internet Open Trading Protocol]]"]
---

# RadSec

RadSec is a protocol for transporting RADIUS datagrams over TCP and TLS. 
The RADIUS protocol is a widely deployed authentication and authorization protocol.  The supplementary RADIUS Accounting specification also provides accounting mechanisms, thus delivering a full AAA protocol solution.  However, RADIUS has two substantial shortcomings.  Essentially all data is sent "in the clear", which has privacy implications. MAC addresses and user names can be leaked, and users can potentially be geolocated.  The data which is obfuscated is protected via "ad hoc" constructions which use the MD5 algorithm, which has been proven to be insecure.  All packet authentication is also based on MD5.
In order to address these privacy and security issues, the "RADIUS Extensions" working group of the Internet Engineering Task Force (IETF) specified TLS transport for RADIUS, as RADIUS/TLS in RFC 6614. TCP port 2083 has been assigned to RADSEC.
The use of RadSec goes back to preliminary vendor implementations.  The standard name for RADIUS over TLS as defined in RFC 6614 is RADIUS/TLS.  There is also RADIUS/DTLS which was defined in RFC 7360.
The main focus of RADIUS/TLS is to provide a means to secure the communication between RADIUS peers on the transport layer.  The most important use of RADIUS/TLS lies in roaming environments where RADIUS packets need to be transferred through different administrative domains and untrusted, potentially hostile networks. An example for a world-wide roaming environment that uses RADIUS/TLS to secure communication is eduroam.

## Related

- [[RADIUS]]
- [[Border Gateway Protocol]]
- [[DNS over HTTPS]]
- [[DNS over TLS]]
- [[Domain Name System]]
- [[GPSoverIP]]
- [[HMAC-based one-time password]]
- [[Internationalized Resource Identifier]]
- [[Internet Content Adaptation Protocol]]
- [[Internet Open Trading Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/RadSec