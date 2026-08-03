---
title: "Site isolation"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Site_isolation"
wikipedia_categories: ["Browsers", "Client-side web security exploits", "Internet privacy", "Internet security"]
related: ["[[2014 celebrity nude photo leak]]", "[[Cookie syncing]]", "[[Cross-site leaks]]", "[[DNS hijacking]]", "[[DNS over HTTPS]]", "[[DNSChanger]]", "[[History sniffing]]", "[[Internet censorship circumvention]]", "[[2010 Duke University faux sex thesis controversy]]", "[[2017 Equifax data breach]]"]
---

# Site isolation

Site isolation is a web browser security feature that groups websites into sandboxed processes by their associated origins. This technique enables the process sandbox to block cross-origin bypasses that would otherwise be exposed by exploitable vulnerabilities in the sandboxed process.
The feature was first proposed publicly by Charles Reis and others, although Microsoft was independently working on implementation in the Gazelle research browser at the same time. The approach initially failed to gain traction due to the large engineering effort required to implement it in a fully featured browser, and concerns around the real-world performance impact of potentially unbounded process use. In 2018, following the discovery of the Spectre and Meltdown vulnerabilities to the public, Google accelerated the work, culminating in a 2019 release of the feature. In 2021, Firefox also launched their own version of site isolation which they had been working on under the codename Project Fission.
Despite the security benefits of this feature, it does have limitations and tradeoffs. While it provides a baseline protection against side channel attacks such as Spectre and Meltdown, full protection against such attacks requires developers to explicitly enable certain advanced browser protections. The main tradeoff of site isolation involves the added resource consumption necessitated by the additional processes it requires. This limits its effectiveness on some classes of devices, and can be abused in some cases to enable resource exhaustion attacks.

## Related

- [[2014 celebrity nude photo leak]]
- [[Cookie syncing]]
- [[Cross-site leaks]]
- [[DNS hijacking]]
- [[DNS over HTTPS]]
- [[DNSChanger]]
- [[History sniffing]]
- [[Internet censorship circumvention]]
- [[2010 Duke University faux sex thesis controversy]]
- [[2017 Equifax data breach]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Site_isolation