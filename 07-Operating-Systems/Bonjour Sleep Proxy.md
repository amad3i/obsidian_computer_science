---
title: "Bonjour Sleep Proxy"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Bonjour_Sleep_Proxy"
wikipedia_categories: ["Apple Inc. software", "Computer configuration", "Domain Name System", "Link protocols", "Network protocols", "Windows communication and services"]
related: ["[[Link Layer Topology Discovery]]", "[[AppleTalk]]", "[[Data Stream Interface]]", "[[Discovery and Launch]]", "[[Domain Name System]]", "[[Dynamic synchronous transfer mode]]", "[[Forward-confirmed reverse DNS]]", "[[Frame Relay]]", "[[G.hn]]", "[[Link-Local Multicast Name Resolution]]"]
---

# Bonjour Sleep Proxy

Apple's Bonjour Sleep Proxy service is an open source component of zero-configuration networking, designed to assist in reducing power consumption of networked electronic devices. It allows a device providing services, such as file sharing, printer sharing, or remote log-in, to sleep, i.e. enter a low-power mode, while its services remain available, even world-wide, by registering with a sleep proxy server on the local network. The sleep proxy server continues to both advertise the services on the local network on behalf of the sleep host and listen for incoming connections, whether the services are available only locally or across the Internet. When any device attempts to use any proxied service, the proxy server wakes the sleeping device and the service works as if the sleeping device had remained fully powered.
Any device that can act as a sleep proxy server advertises this on all LANs of which it is a part. A device providing network services, such as file sharing, when its services are not actively being used can register its services with an available sleep proxy server and sleep until one of its services is needed. The sleep proxy server continues to advertise the services in Multicast DNS (mDNS) on behalf of the sleeping host. When the sleep proxy server sees an attempt to use any such service it wakes the sleeping host and the service proceeds normally, and in the case of SSH, a server with an active session can register with a proxy, sleep, and be awakened with the next received packet, continuing the same session.
Apple refers to the service as Bonjour Sleep Proxy in its support documents. The service uses the Wake on Demand feature, first offered in Mac OS X Snow Leopard.

## Related

- [[Link Layer Topology Discovery]]
- [[AppleTalk]]
- [[Data Stream Interface]]
- [[Discovery and Launch]]
- [[Domain Name System]]
- [[Dynamic synchronous transfer mode]]
- [[Forward-confirmed reverse DNS]]
- [[Frame Relay]]
- [[G.hn]]
- [[Link-Local Multicast Name Resolution]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bonjour_Sleep_Proxy