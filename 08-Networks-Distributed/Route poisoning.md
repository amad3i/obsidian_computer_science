---
title: "Route poisoning"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Route_poisoning"
wikipedia_categories: ["Internet Standards", "Internet protocols", "Routing protocols"]
related: ["[[Border Gateway Multicast Protocol]]", "[[Border Gateway Protocol]]", "[[Exterior Gateway Protocol]]", "[[Exterior gateway protocol]]", "[[IS-IS]]", "[[Open Shortest Path First]]", "[[Routing Information Protocol]]", "[[Split horizon route advertisement]]", "[[Berkeley r-commands]]", "[[Bidirectional Forwarding Detection]]"]
---

# Route poisoning

Route poisoning is a method to prevent a router from sending packets through a route that has become invalid within computer networks. Distance-vector routing protocols in computer networks use route poisoning to indicate to other routers that a route is no longer reachable and should not be considered from their routing tables. Unlike the split horizon with poison reverse, route poisoning provides for sending updates with unreachable hop counts immediately to all the nodes in the network.
When the protocol detects an invalid route, all of the routers in the network are informed that the bad route has an infinite (∞) route metric. This makes all nodes on the invalid route seem infinitely distant, preventing any of the routers from sending packets over the invalid route.
Some distance-vector routing protocols, such as RIP, use a maximum hop count to determine how many routers the traffic must go through to reach the destination. Each route has a hop count number assigned to it which is incremented as the routing information is passed from router to router. A route is considered unreachable if the hop count exceeds the maximum allowed. Route poisoning is a method of quickly forgetting outdated routing information from other router's routing tables by changing its hop count to be unreachable (higher than the maximum number of hops allowed) and sending a routing update. In the case of RIP, the maximum hop count is 15, so to perform route poisoning on a route its hop count is changed to 16, deeming it unreachable, and a routing update is sent.
If these updates are lost, some nodes in the network would not be informed that a route is invalid, so they could attempt to send packets over the bad route and cause a problem known as a routing loop. Therefore, route poisoning is used in conjunction with holddowns to keep update messages from falsely reinstating the validity of a bad route. This prevents routing loops, improving the overall efficiency of the network.

## Related

- [[Border Gateway Multicast Protocol]]
- [[Border Gateway Protocol]]
- [[Exterior Gateway Protocol]]
- [[Exterior gateway protocol]]
- [[IS-IS]]
- [[Open Shortest Path First]]
- [[Routing Information Protocol]]
- [[Split horizon route advertisement]]
- [[Berkeley r-commands]]
- [[Bidirectional Forwarding Detection]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Route_poisoning