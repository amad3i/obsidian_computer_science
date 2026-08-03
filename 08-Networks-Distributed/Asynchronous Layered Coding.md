---
title: "Asynchronous Layered Coding"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Asynchronous_Layered_Coding"
wikipedia_categories: ["Internet protocols", "Internet stubs"]
related: ["[[Border Gateway Multicast Protocol]]", "[[Endpoint Handlespace Redundancy Protocol]]", "[[Extensible Name Service]]", "[[High Frequency Internet Protocol]]", "[[Internet Imaging Protocol]]", "[[Internet Open Trading Protocol]]", "[[IPFC]]", "[[IPv9 (China)]]", "[[Network Data Representation]]", "[[QOTD]]"]
---

# Asynchronous Layered Coding

Asynchronous Layered Coding (ALC) is an Internet protocol for content delivery in a reliable, massively scalable, multiple-rate, and congestion-controlled manner.  Specified in RFC 5775, it is an IETF proposed standard.
The protocol
is specifically designed to provide massive scalability using IP
multicast as the underlying network service.  Massive scalability in
this context means the number of concurrent receivers for an object
is potentially in the millions, the aggregate size of objects to be
delivered in a session ranges from hundreds of kilobytes to hundreds
of gigabytes, each receiver can initiate reception of an object
asynchronously, the reception rate of each receiver in the session is
the maximum fair bandwidth available between that receiver and the
sender, and all of this can be supported using a single sender.
Because ALC is focused on reliable content delivery, the goal is to
deliver objects as quickly as possible to each receiver while at the
same time remaining network friendly to competing traffic.  Thus, the
congestion control used in conjunction with ALC should strive to
maximize use of available bandwidth between receivers and the sender
while at the same time backing off aggressively in the face of
competing traffic.
The sender side of ALC consists of generating packets based on
objects to be delivered within the session and sending the
appropriately formatted packets at the appropriate rates to the
channels associated with the session.  The receiver side of ALC
consists of joining appropriate channels associated with the session,
performing congestion control by adjusting the set of joined channels
associated with the session in response to detected congestion, and
using the packets to reliably reconstruct objects.  All information
flow in an ALC session is in the form of data packets sent by a
single sender to channels that receivers join to receive data.
ALC does specify the Session Description needed by receivers before
they join a session, but the mechanisms by which receivers obtain
this required information is outside the scope of ALC.  An
application that uses ALC may require that receivers report
statistics on their reception experience back to the sender, but the
mechanisms by which receivers report back statistics is outside the
scope of ALC.  In general, ALC is designed to be a minimal protocol
instantiation that provides reliable content delivery without
unnecessary limitations to the scalability of the basic protocol.

## Related

- [[Border Gateway Multicast Protocol]]
- [[Endpoint Handlespace Redundancy Protocol]]
- [[Extensible Name Service]]
- [[High Frequency Internet Protocol]]
- [[Internet Imaging Protocol]]
- [[Internet Open Trading Protocol]]
- [[IPFC]]
- [[IPv9 (China)]]
- [[Network Data Representation]]
- [[QOTD]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Asynchronous_Layered_Coding