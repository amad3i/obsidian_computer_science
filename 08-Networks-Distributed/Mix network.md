---
title: "Mix network"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Mix_network"
wikipedia_categories: ["Anonymity networks", "Cryptographic primitives", "Cryptographic protocols", "Internet privacy", "Mix networks", "Routing"]
related: ["[[Data haven]]", "[[Degree of anonymity]]", "[[Flash proxy]]", "[[Friend-to-friend]]", "[[Public-key cryptography]]", "[[2010 Duke University faux sex thesis controversy]]", "[[2014 celebrity nude photo leak]]", "[[2017 Equifax data breach]]", "[[2023 Bangladesh Government website data breach]]", "[[AiScaler]]"]
---

# Mix network

Mix networks are routing protocols that create hard-to-trace communications by using a chain of proxy servers known as mixes which take in messages from multiple senders, shuffle them, and send them back out in random order to the next destination (possibly another mix node). This breaks the link between the source of the request and the destination, making it harder for eavesdroppers to trace end-to-end communications. Furthermore, mixes only know the node that it immediately received the message from, and the immediate destination to send the shuffled messages to, making the network resistant to malicious mix nodes.
Each message is encrypted to each proxy using public key cryptography; the resulting encryption is layered like a Russian doll (except that each "doll" is of the same size) with the message as the innermost layer.  Each proxy server strips off its own layer of encryption to reveal where to send the message next.  If all but one of the proxy servers are compromised by the tracer, untraceability can still be achieved against some weaker adversaries.
The concept of a mix "cryptosystem" in the context of electronic mail was first described by David Chaum in 1981 because of the "traffic analysis problem" (traffic analysis).  Applications that are based on this concept include anonymous remailers (such as Mixmaster), onion routing, garlic routing, and key-based routing (including  Tor, I2P, and Freenet). Large-scale implementations of the mix network concept began to emerge in the 2020s, driven by advancements in privacy-preserving technologies and decentralized infrastructure.

## Related

- [[Data haven]]
- [[Degree of anonymity]]
- [[Flash proxy]]
- [[Friend-to-friend]]
- [[Public-key cryptography]]
- [[2010 Duke University faux sex thesis controversy]]
- [[2014 celebrity nude photo leak]]
- [[2017 Equifax data breach]]
- [[2023 Bangladesh Government website data breach]]
- [[AiScaler]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Mix_network