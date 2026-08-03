---
title: "WAN optimization"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/WAN_optimization"
wikipedia_categories: ["Internet protocols", "Network performance", "Network protocols", "WAN optimization", "Wide area networks"]
related: ["[[BEEP]]", "[[Coloured Book protocols]]", "[[Connection-oriented communication]]", "[[Connectionless communication]]", "[[Constrained Shortest Path First]]", "[[Domain Name System]]", "[[Forward-confirmed reverse DNS]]", "[[GPSoverIP]]", "[[Internet Fibre Channel Protocol]]", "[[InterPlanetary File System]]"]
---

# WAN optimization

WAN optimization is a collection of techniques for improving data transfer across wide area networks (WANs).  In 2008, the WAN optimization market was estimated to be $1 billion, and was to grow to $4.4 billion by 2014 according to Gartner, a technology research firm. In 2015, Gartner estimated the WAN optimization market to be a $1.1 billion market.
The most common measures of TCP data-transfer efficiencies (i.e., optimization) are throughput, bandwidth requirements, latency, protocol optimization, and congestion, as manifested in dropped packets. In addition, the WAN itself can be classified with regard to the distance between endpoints and the amount of data transferred. Two common business WAN topologies are branch to headquarters and  data center to data center (DC2DC). In general, "branch" WAN links are closer, use less bandwidth, support more simultaneous connections, support smaller connections and more short-lived connections, and handle a greater variety of protocols. They are used for business applications such as email, content management systems, database applications, and Web delivery. In comparison, DC2DC WAN links tend to require more bandwidth, are more distant, and involve fewer connections, but those connections are bigger (100 Mbit/s to 1 Gbit/s flows) and of longer duration. Traffic on a DC2DC WAN may include replication, backup, data migration, virtualization, and other Business Continuity/Disaster Recovery (BC/DR) flows.
WAN optimization has been the subject of extensive academic research almost since the advent of the WAN. In the early 2000s, research in both the private and public sectors turned to improving the end-to-end throughput of TCP, and the target of the first proprietary WAN optimization solutions was the branch WAN. In recent years, however, the rapid growth of digital data and the concomitant need to store and protect it have presented a need for DC2DC WAN optimization. For example, such optimizations can be performed to increase overall network capacity utilization, meet inter-datacenter transfer deadlines, or minimize average completion times of data transfers. As another example, private inter-datacenter WANs can benefit optimizations for fast and efficient geo-replication of data and content, such as newly computed machine learning models or multimedia content.
Component techniques of branch WAN optimization include deduplication, wide area file services (WAFS), SMB proxy, HTTPS proxy, media multicasting, web caching, and bandwidth management. Requirements for DC2DC WAN Optimization also center around deduplication and TCP acceleration; however, these must occur in the context of multi-gigabit data transfer rates.

## Related

- [[BEEP]]
- [[Coloured Book protocols]]
- [[Connection-oriented communication]]
- [[Connectionless communication]]
- [[Constrained Shortest Path First]]
- [[Domain Name System]]
- [[Forward-confirmed reverse DNS]]
- [[GPSoverIP]]
- [[Internet Fibre Channel Protocol]]
- [[InterPlanetary File System]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/WAN_optimization