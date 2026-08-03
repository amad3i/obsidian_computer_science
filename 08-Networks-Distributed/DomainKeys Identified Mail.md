---
title: "DomainKeys Identified Mail"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/DomainKeys_Identified_Mail"
wikipedia_categories: ["Anti-spam", "Cryptographic protocols", "Email authentication", "Internet architecture", "Internet governance", "Network addressing"]
related: ["[[Authenticated Received Chain]]", "[[Sender Policy Framework]]", "[[Routing Assets Database]]", "[[6bone]]", "[[Adaptive quality of service multi-hop routing]]", "[[Address pool]]", "[[AiScaler]]", "[[Any-source multicast]]", "[[Anycast]]", "[[Application-layer framing]]"]
---

# DomainKeys Identified Mail

DomainKeys Identified Mail (DKIM) is an email authentication method that permits a person, role, or organization that owns the signing domain to claim some responsibility for a message by associating the domain with the message.
The receiver can check that an email that claimed to have come from a specific domain was indeed authorized by the owner of that domain. It achieves this by affixing a digital signature, linked to a domain name, to each outgoing email message. The recipient system can verify this by looking up the sender's public key published in the DNS. A valid signature also guarantees that some parts of the email (possibly including attachments) have not been modified since the signature was affixed. Usually, DKIM signatures are not visible to end-users, and are affixed or verified by the infrastructure rather than the message's authors and recipients.
DKIM is an Internet Standard. It is defined in RFC 6376, dated September 2011, with updates in RFC 8301, RFC 8463, RFC 8553, and RFC 8616.

## Related

- [[Authenticated Received Chain]]
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

- Wikipedia: https://en.wikipedia.org/wiki/DomainKeys_Identified_Mail