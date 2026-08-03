---
title: "IPsec cookie exchange"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/IPsec_cookie_exchange"
wikipedia_categories: ["Internet protocols"]
related: ["[[Asynchronous Layered Coding]]", "[[Automatic Certificate Management Environment]]", "[[BEEP]]", "[[Berkeley r-commands]]", "[[BGP Monitoring Protocol]]", "[[Bidirectional Forwarding Detection]]", "[[Binkp]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]"]
---

# IPsec cookie exchange

The cookie exchange in IPsec comes under the Oakley protocol, which is a protocol of key management. The cookie exchange requires that each side send a pseudorandom number, the cookie, in the initial message, which the other side acknowledges. This acknowledgement must be repeated in the first message of the Diffie–Hellman key exchange. If the source address was forged, the opponent gets no answer. Thus, an opponent can only force a user to generate acknowledgements and not to perform the Diffie–Hellman calculation. Note that "cookies" in the sense of IPsec are unrelated to HTTP cookies used by web browsers.
The recommended method for creating the cookie is to perform a fast hash (e.g. MD5) over the IP source and destination addresses, the UDP source and destination ports, and a locally generated secret value.

## Related

- [[Asynchronous Layered Coding]]
- [[Automatic Certificate Management Environment]]
- [[BEEP]]
- [[Berkeley r-commands]]
- [[BGP Monitoring Protocol]]
- [[Bidirectional Forwarding Detection]]
- [[Binkp]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IPsec_cookie_exchange