---
title: "End node problem"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/End_node_problem"
wikipedia_categories: ["Computer network security", "Operating system security"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-level gateway]]", "[[Apptainer]]", "[[Attack tree]]", "[[Authentication server]]"]
---

# End node problem

The end node problem arises when individual computers are used for sensitive work and/or temporarily become part of a trusted, well-managed network/cloud and then are used for more risky activities and/or join untrusted networks. (Individual computers on the periphery of networks/clouds are called end nodes.) End nodes often are not managed to the trusted network‘s high computer security standards. End nodes often have weak/outdated software, weak security tools, excessive permissions, mis-configurations, questionable content and apps, and covert exploitations. Cross contamination and unauthorized release of data from within a computer system becomes the problem.
Within the vast cyber-ecosystem, these end nodes often attach transiently to one or more clouds/networks, some trustworthy and others not.  A few examples: a corporate desktop browsing the Internet, a corporate laptop checking company webmail via a coffee shop's open Wi-Fi access point, a personal computer used to telecommute during the day and gaming at night, or app within a smartphone/tablet (or any of the previous use/device combinations).  Even if fully updated and tightly locked down, these nodes may ferry malware from one network (e.g. a corrupted webpage or an infected email message) into another, sensitive network.  Likewise, the end nodes may exfiltrate sensitive data (e.g. log keystrokes or screen-capture).  Assuming the device is fully trustworthy, the end node must provide the means to properly authenticate the user.  Other nodes may impersonate trusted computers, thus requiring device authentication. The device and user may be trusted but within an untrustworthy environment (as determined by inboard sensors' feedback). Collectively, these risks are called the end node problem.  There are several remedies but all require instilling trust in the end node and conveying that trust to the network/cloud.

## Related

- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Anomaly-based intrusion detection system]]
- [[Application Defined Network]]
- [[Application-level gateway]]
- [[Apptainer]]
- [[Attack tree]]
- [[Authentication server]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/End_node_problem