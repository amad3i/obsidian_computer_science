---
title: "Cross-site leaks"
tags: ["cs", "networks-distributed", "advanced"]
domain: Networks & Distributed
level: advanced
source: "https://en.wikipedia.org/wiki/Cross-site_leaks"
wikipedia_categories: ["Client-side web security exploits", "Hacking (computer security)", "Internet privacy", "Side-channel attacks", "Web browsers", "Web security exploits"]
related: ["[[Cross-site scripting]]", "[[History sniffing]]", "[[DNS hijacking]]", "[[Doxing]]", "[[HTTP cookie]]", "[[Private browsing]]", "[[Site isolation]]", "[[2010 Duke University faux sex thesis controversy]]", "[[2014 celebrity nude photo leak]]", "[[2017 Equifax data breach]]"]
---

# Cross-site leaks

In internet security, cross-site (XS) leaks are a class of attacks used to access a user's sensitive information on another website. Cross-site leaks allow an attacker to access a user's interactions with other websites. This can contain sensitive information. Web browsers normally stop other websites from seeing this information. This is enforced through a set of rules called the same-origin policy. Attackers can sometimes get around these rules, using a "cross-site leak". Attacks using a cross-site leak are often initiated by enticing users to visit the attacker's website. Upon visiting, the attacker uses malicious code on their website to interact with another website. This can be used by an attacker to learn about the user's previous actions on the other website. The information from this attack can uniquely identify the user to the attacker.
These attacks have been documented since 2000. One of the first research papers on the topic was published by researchers at Purdue University. The paper described an attack where the web cache was exploited to gather information about a website. Since then, cross-site leaks have become increasingly sophisticated. Researchers have found newer leaks targeting various web browser components. While the efficacy of some of these techniques varies, newer techniques are continually being discovered. Some older methods are blocked through updates to browsers. The introduction and removal of features on the Internet also lead to some attacks being rendered ineffective.
Cross-site leaks are a diverse form of attack, and there is no consistent classification of such attacks. Multiple sources classify cross-site leaks by the technique used to leak information. Among the well-known cross-site leaks are timing attacks, which depend on timing events within the web browser. For example, cache-timing attacks rely on the web cache to unveil information. Error events constitute another category, using the presence or absence of events to disclose data. Since 2023, newer attacks that use operating systems and web browser limits to leak information have also been found.
Before 2017, defending against cross-site leaks was considered to be difficult. This was because many of the information leakage issues exploited by cross-site leak attacks were inherent to the way websites worked. Most defences against this class of attacks have been introduced after 2017 in the form of extensions to the hypertext transfer protocol (HTTP). These extensions allow websites to instruct the browser to disallow or annotate certain kinds of stateful requests coming from other websites. One of the most successful approaches browsers have implemented is SameSite cookies. SameSite cookies allow websites to set a directive that prevents other websites from accessing and sending sensitive cookies. Another defence involves using HTTP headers to restrict which websites can embed a particular site. Cache partitioning also serves as a defence against cross-site leaks, preventing other websites from using the web cache to exfiltrate data.

## Related

- [[Cross-site scripting]]
- [[History sniffing]]
- [[DNS hijacking]]
- [[Doxing]]
- [[HTTP cookie]]
- [[Private browsing]]
- [[Site isolation]]
- [[2010 Duke University faux sex thesis controversy]]
- [[2014 celebrity nude photo leak]]
- [[2017 Equifax data breach]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cross-site_leaks