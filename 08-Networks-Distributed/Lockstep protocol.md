---
title: "Lockstep protocol"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Lockstep_protocol"
wikipedia_categories: ["Cheating in video games", "Network protocols"]
related: ["[[Access stratum]]", "[[Acknowledgement (data networks)]]", "[[Alternating bit protocol]]", "[[AMX192]]", "[[Apple Filing Protocol]]", "[[AppleTalk]]", "[[ARCNET]]", "[[ATA over Ethernet]]", "[[ATM Adaptation Layer 2]]", "[[ATM Adaptation Layer 5]]"]
---

# Lockstep protocol

The lockstep protocol is a partial solution to the look-ahead cheating problem in peer-to-peer architecture multiplayer games, in which a cheating client delays their own actions to await the messages of other players. A client can do so by acting as if they're suffering from high latency; the outgoing packet is forged by attaching a time stamp that is prior to the actual moment the packet is sent.
To avoid this method of cheating, the lockstep protocol requires each player to first announce a "commitment" (e.g. hash value of the action); this commitment is a representation of an action that:

Cannot be used to infer the action; and
Easily compares whether an action corresponds with a commitment.
Once all players have received the commitments, they reveal their actions, which are compared with the corresponding commitments to ensure that the commitment is indeed the sent action.

## Related

- [[Access stratum]]
- [[Acknowledgement (data networks)]]
- [[Alternating bit protocol]]
- [[AMX192]]
- [[Apple Filing Protocol]]
- [[AppleTalk]]
- [[ARCNET]]
- [[ATA over Ethernet]]
- [[ATM Adaptation Layer 2]]
- [[ATM Adaptation Layer 5]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Lockstep_protocol