---
title: "Common Open Policy Service"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Common_Open_Policy_Service"
wikipedia_categories: ["Internet protocols", "World Wide Web stubs"]
related: ["[[Jughead (search engine)]]", "[[Asynchronous Layered Coding]]", "[[Automatic Certificate Management Environment]]", "[[BEEP]]", "[[Berkeley r-commands]]", "[[BGP Monitoring Protocol]]", "[[Bidirectional Forwarding Detection]]", "[[Binkp]]", "[[Bootstrap Protocol]]", "[[Border Gateway Multicast Protocol]]"]
---

# Common Open Policy Service

The Common Open Policy Service (COPS) Protocol is part of the internet protocol suite as defined by the RFC 2748. COPS specifies a simple client/server model for supporting policy control over quality of service (QoS) signaling protocols (e.g. RSVP). Policies are stored on servers, and acted upon by Policy Decision Points (PDP), and are enforced on clients, also known as Policy Enforcement Points (PEP). There are two models of COPS: The Outsourcing Model and the Provisioning Model, considered from the view of the client or PEP.
The Outsourcing Model is the simplest COPS implementation. In this model, all policies are stored at the PDP. Whenever the PEP needs to make a decision, it sends all relevant information to the PDP. The PDP analyzes the information, makes the decision, and relays it to the PEP. The PEP then simply enforces the decision.
In the Provisioning Model, see RFC 3084 COPS Usage for Policy Provisioning (COPS-PR), the PEP reports its decision-making capabilities to the PDP. The PDP then downloads relevant policies on to the PEP. The PEP can then make its own decisions based on these policies. The Provisioning Model uses the Policy Information Base as a repository of the policies.

## Related

- [[Jughead (search engine)]]
- [[Asynchronous Layered Coding]]
- [[Automatic Certificate Management Environment]]
- [[BEEP]]
- [[Berkeley r-commands]]
- [[BGP Monitoring Protocol]]
- [[Bidirectional Forwarding Detection]]
- [[Binkp]]
- [[Bootstrap Protocol]]
- [[Border Gateway Multicast Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Common_Open_Policy_Service