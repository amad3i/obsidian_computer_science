---
title: "Science DMZ Network Architecture"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Science_DMZ_Network_Architecture"
wikipedia_categories: ["Computer network security", "Network architecture", "Network performance"]
related: ["[[Application Defined Network]]", "[[Extranet]]", "[[Jump server]]", "[[Robust random early detection]]", "[[Software-defined protection]]", "[[Split tunneling]]", "[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Adaptive quality of service multi-hop routing]]", "[[Administrative domain]]"]
---

# Science DMZ Network Architecture

The term Science DMZ refers to a computer subnetwork that is structured to be secure, but without the performance limits that would otherwise result from passing data through a stateful firewall. The Science DMZ is designed to handle high volume data transfers, typical with scientific and high-performance computing, by creating a special DMZ to accommodate those transfers. It is typically deployed at or near the local network perimeter, and is optimized for a moderate number of high-speed flows, rather than for general-purpose business systems or enterprise computing.
The term Science DMZ was coined by collaborators at the US Department of Energy's ESnet in 2010.
A number of universities and laboratories have deployed or are deploying a Science DMZ. In 2012 the National Science Foundation funded the creation or improvement of Science DMZs on several university campuses in the United 
States.
The Science DMZ
is a network architecture to support Big Data. The so-called information explosion has been discussed since the mid 1960s, and more recently the term data deluge has been used to describe the exponential growth in many types of data sets. These huge data sets, often need to be copied from one location to another using the Internet. The movement of data sets of this magnitude in a reasonable amount of time should be possible on modern networks. For example, it should only take less than 4 hours to transfer 10 Terabytes of data on a 10 Gigabit Ethernet network path, assuming disk performance is adequate The problem is that this requires networks that are free from packet loss and middleboxes such as traffic shapers or firewalls that slow network performance.

## Related

- [[Application Defined Network]]
- [[Extranet]]
- [[Jump server]]
- [[Robust random early detection]]
- [[Software-defined protection]]
- [[Split tunneling]]
- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Adaptive quality of service multi-hop routing]]
- [[Administrative domain]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Science_DMZ_Network_Architecture