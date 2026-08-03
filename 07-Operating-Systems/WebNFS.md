---
title: "WebNFS"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/WebNFS"
wikipedia_categories: ["Application layer protocols", "Internet Protocol based network software", "Internet protocols", "Network file systems", "Unix file system-related software"]
related: ["[[Network File System]]", "[[Net-SNMP]]", "[[Remote File Sharing]]", "[[Rtelnet]]", "[[Telnet]]", "[[Border Gateway Protocol]]", "[[DNS over HTTPS]]", "[[DNS over TLS]]", "[[Domain Name System]]", "[[GPSoverIP]]"]
---

# WebNFS

YANFS (Yet Another NFS), formerly WebNFS, is an extension to the Network File System (NFS) for allowing clients to access a file system over the internet using a simplified, firewall-friendly protocol.
WebNFS was developed to give Java applets and other internet enabled applications a way of accessing filesystem services over the internet. While NFS provides applications on Unix with full filesystem semantics, not all of these might be needed in a distributed, read-only web environment. Conversely, access restrictions—such as requiring the use of restricted ports for originating requests—normally used in closed environments are not usually applicable in public distributed environments.
In 2007, Sun Microsystems open-sourced its WebNFS implementation. The name was subsequently changed to YANFS (Yet Another NFS) to reflect the expanded scope of the project to include a server-side implementation.
YANFS/WebNFS makes use of a well known port (port 2049 on both UDP and TCP) thus avoiding the overhead and unpredictability of using the ONC RPC portmap protocol. WebNFS adds public filehandles and multicomponent lookups to the NFS protocol.
WebNFS has been specified by a number of RFCs:

RFC 2054: WebNFS Client
RFC 2055: WebNFS Server
RFC 2224: NFS URL Scheme
RFC 2755: Security negotiation for WebNFS

## Related

- [[Network File System]]
- [[Net-SNMP]]
- [[Remote File Sharing]]
- [[Rtelnet]]
- [[Telnet]]
- [[Border Gateway Protocol]]
- [[DNS over HTTPS]]
- [[DNS over TLS]]
- [[Domain Name System]]
- [[GPSoverIP]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/WebNFS