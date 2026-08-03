---
title: "WHOIS++"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/WHOIS++"
wikipedia_categories: ["Internet Standards", "Internet protocols"]
related: ["[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Certificate Management over CMS]]", "[[Certificate Management Protocol]]", "[[Clearinghouse for Networked Information Discovery and Retrieval]]", "[[Diameter Credit-Control Application]]", "[[Directory information tree]]"]
---

# WHOIS++

The WHOIS++ protocol is a distributed directory system, originally designed to provide a "white pages" search mechanism to find humans, but which could actually be used for arbitrary information retrieval tasks.  It was developed in the early 1990s by BUNYIP Information Systems and is documented in the IETF.
WHOIS++ was devised as an extension to the pre-existing WHOIS system.  WHOIS was an early networked directory service, originally maintained by SRI International for the Defense Data Network.  The WHOIS protocol is still widely used to allow domain ownership records in the Internet to be easily queried.
WHOIS++ attempted to address some of the short comings in the original WHOIS protocol that had become apparent over the years.  It supported multiple languages and character sets to help with I18N issues, had a more advanced query syntax, and the ability to generate "forward knowledge" in the form of 'centroid' data structures that could be used to route queries from one server to another.  The protocol was designed to be backward compatible with the older WHOIS standard, so that WHOIS++ clients could still extract meaningful information from the already deployed WHOIS servers.
Whilst WHOIS++ as a white pages directory service never really took off compared to competitors such as X.500, it did gain a notable amount of use in the United Kingdom as the underlying search and retrieval protocol of a number of subject based gateways funded as part of the Jisc Electronic library programme.  This was achieved using software called ROADS that provided WHOIS++ base and index servers and CGI based web interfaces to WHOIS++ clients.  The use of centroids to provide forward knowledge and query routing allowed a subject gateway to not only provide resources to academic users from their own database but also point them at other JISC funded subject gateways that might have useful information.
The WHOIS++ protocol is now designated by the IETF as a historic protocol and is no longer deployed in new systems or developed.

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

- Wikipedia: https://en.wikipedia.org/wiki/WHOIS++