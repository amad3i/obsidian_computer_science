---
title: "Cisco Security Agent"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Cisco_Security_Agent"
wikipedia_categories: ["Cisco products", "Computer network security", "Internet Protocol based network software", "Solaris software", "Windows security software"]
related: ["[[Application-level gateway]]", "[[Bastion host]]", "[[Cisco ASA]]", "[[Cisco PIX]]", "[[Fail2ban]]", "[[NBName]]", "[[OSSEC]]", "[[PacketFence]]", "[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]"]
---

# Cisco Security Agent

Cisco Security Agent (CSA) was an endpoint intrusion prevention system software made originally by Okena (formerly named StormWatch Agent), which was bought by Cisco Systems in 2003.
The software is rule-based and it examines system activities and network traffic, determining which behaviors are normal and which may indicate an attack. CSA was offered as a replacement for Cisco IDS Host Sensor, which was announced end-of-life on 21 February 2003. This end-of-life action resulted from Cisco's acquisition of Okena, Inc., and the Cisco Security Agent product line based on the Okena technology would replace the Cisco IDS Host Sensor product line from Entercept.
As a result of this end-of-life action, Cisco offered a no-cost, one-for-one product replacement/migration program for all Cisco IDS Host Sensor customers to the new Cisco Security Agent product line. The intent of this program was to support existing IDS Host Sensor customers who chose to migrate to the new Cisco Security Agent product line.
All Cisco IDS Host Sensor customers were eligible for this migration program, whether or not the customer had purchased a Cisco Software Application Support (SAS) service contract for their Cisco IDS Host Sensor products.
CSA uses a two or three-tier client-server architecture. The Management Center (MC) (Management Console) contains the program logic. An MS SQL database backend is used to store alerts and configuration information. The MC and SQL database may be co-resident on the same system.
The agent is installed on the desktops and/or servers to be protected and communicates with the Management Center, sending logged events to the Management Center and receiving updates on rules when they occur.
A Network World article dated 17 December 2009 stated, "Cisco hinted that it will end-of-life both CSA and MARS"—full article linked below.
On 11 June 2010, Cisco announced the end-of-life and end-of-sale of CSA. Cisco did not offer any replacement products.

## Related

- [[Application-level gateway]]
- [[Bastion host]]
- [[Cisco ASA]]
- [[Cisco PIX]]
- [[Fail2ban]]
- [[NBName]]
- [[OSSEC]]
- [[PacketFence]]
- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Cisco_Security_Agent