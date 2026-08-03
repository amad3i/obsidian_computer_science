---
title: "Authenticated Received Chain"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Authenticated_Received_Chain"
wikipedia_categories: ["Anti-spam", "Email authentication", "Internet architecture", "Internet governance", "Network addressing"]
related: ["[[DomainKeys Identified Mail]]", "[[Sender Policy Framework]]", "[[Routing Assets Database]]", "[[6bone]]", "[[Adaptive quality of service multi-hop routing]]", "[[Address pool]]", "[[AiScaler]]", "[[Any-source multicast]]", "[[Anycast]]", "[[Application-layer framing]]"]
---

# Authenticated Received Chain

Authenticated Received Chain (ARC) is an email authentication system designed to allow an intermediate mail server like a mailing list or forwarding service to sign an email's original authentication results. This allows a receiving service to validate an email when the email's SPF and DKIM records are rendered invalid by an intermediate server's processing.
ARC is defined in RFC 8617, published in July 2019, as "Experimental".
It has been suggested by the IETF that ARC should no longer be used. ARC did not solve the problems with email reputation. Some parts might be incorporated into DKIMv2.

## Related

- [[DomainKeys Identified Mail]]
- [[Sender Policy Framework]]
- [[Routing Assets Database]]
- [[6bone]]
- [[Adaptive quality of service multi-hop routing]]
- [[Address pool]]
- [[AiScaler]]
- [[Any-source multicast]]
- [[Anycast]]
- [[Application-layer framing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Authenticated_Received_Chain