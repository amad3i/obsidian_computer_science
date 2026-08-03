---
title: "Zero trust architecture"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Zero_trust_architecture"
wikipedia_categories: ["Computer network security", "Information technology"]
related: ["[[3-subset meet-in-the-middle attack]]", "[[ACARM-ng]]", "[[Adaptive redaction]]", "[[Administrative domain]]", "[[AEGIS SecureConnect]]", "[[Anomaly-based intrusion detection system]]", "[[Application Defined Network]]", "[[Application-level gateway]]", "[[Attack tree]]", "[[Authentication server]]"]
---

# Zero trust architecture

Zero trust architecture (ZTA) is a design and implementation strategy of IT systems. The principle is that users and devices should not be trusted by default, even if they are connected to a privileged network such as a corporate LAN and even if they were previously verified. The principle is also known as perimeterless security or formerly de-perimeterization.
ZTA is implemented by establishing identity verification, validating device compliance prior to granting access, and ensuring least privilege access to only explicitly-authorized resources. Most modern corporate networks consist of many interconnected zones, cloud services and infrastructure, connections to remote and mobile environments, and connections to non-conventional IT, such as IoT devices. 
The traditional approach by trusting users and devices within a notional "corporate perimeter" or via a VPN connection is commonly not sufficient in the complex environment of a corporate network. The zero trust approach advocates mutual authentication, including checking the identity and integrity of users and devices without respect to location, and providing access to applications and services based on the confidence of user and device identity and device status in combination with user authentication. The zero trust architecture has been proposed for use in specific areas such as supply chains.
The principles of zero trust can be applied to data access, and to the management of data. This brings about zero trust data security where every request to access the data needs to be authenticated dynamically and ensure least privileged access to resources. In order to determine if access can be granted, policies can be applied based on the attributes of the data, who the user is, and the type of environment using attribute-based access control (ABAC). This zero trust data security approach can protect access to the data.

## Related

- [[3-subset meet-in-the-middle attack]]
- [[ACARM-ng]]
- [[Adaptive redaction]]
- [[Administrative domain]]
- [[AEGIS SecureConnect]]
- [[Anomaly-based intrusion detection system]]
- [[Application Defined Network]]
- [[Application-level gateway]]
- [[Attack tree]]
- [[Authentication server]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Zero_trust_architecture