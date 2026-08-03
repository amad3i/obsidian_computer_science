---
title: "G-network"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/G-network"
wikipedia_categories: ["Queueing theory"]
related: ["[[Adversarial queueing network]]", "[[Arrival theorem]]", "[[Backpressure routing]]", "[[Balance equation]]", "[[Bartlett's theorem]]", "[[BCMP network]]", "[[Beneš method]]", "[[Birth–death process]]", "[[Burke's theorem]]", "[[Buzen's algorithm]]"]
---

# G-network

In queueing theory, a discipline within the mathematical theory of probability, a G-network (generalized queueing network, often called a  Gelenbe network) is an open network of G-queues first introduced by Erol Gelenbe as a model for queueing systems with specific control functions, such as traffic re-routing or traffic destruction, as well as a model for  neural networks. A G-queue is a network of queues  with several types of novel and useful customers:

positive customers, which arrive from other queues or arrive externally as Poisson arrivals, and obey standard service and routing disciplines as in conventional network models,
negative customers, which arrive from another queue, or which arrive externally as Poisson arrivals, and remove (or 'kill') customers in a non-empty queue, representing the need to remove traffic when the network is congested, including the removal of "batches" of customers
"triggers", which arrive from other queues or from outside the network, and which displace customers and move them to other queues
A product-form solution superficially similar in form to Jackson's theorem, but which requires the solution of a system of non-linear equations for the traffic flows, exists for the stationary distribution of G-networks while the traffic equations of a G-network are in fact surprisingly non-linear, and the model does not obey partial balance. This broke previous assumptions that partial balance was a necessary condition for a product-form solution.  A powerful property of G-networks is that they are universal approximators for continuous and bounded functions, so that they can be used to approximate quite general input-output behaviours.

## Related

- [[Adversarial queueing network]]
- [[Arrival theorem]]
- [[Backpressure routing]]
- [[Balance equation]]
- [[Bartlett's theorem]]
- [[BCMP network]]
- [[Beneš method]]
- [[Birth–death process]]
- [[Burke's theorem]]
- [[Buzen's algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/G-network