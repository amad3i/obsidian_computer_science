---
title: "Separation kernel"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Separation_kernel"
wikipedia_categories: ["Distributed computing", "Operating system kernels"]
related: ["[[ActivityPub]]", "[[AT Protocol]]", "[[Availability zone]]", "[[Botnet]]", "[[CAP theorem]]", "[[CockroachDB]]", "[[Collective operation]]", "[[Comparison of synchronous and asynchronous signalling]]", "[[Confidential Consortium Framework]]", "[[Consensus dynamics]]"]
---

# Separation kernel

A separation kernel is a type of security kernel used to simulate a distributed environment. The concept was introduced by John Rushby in a 1981 paper. Rushby proposed the separation kernel as a solution to the difficulties and problems that had arisen in the development and verification of large, complex security kernels that were intended to "provide multilevel secure operation on general-purpose multi-user systems." According to Rushby, "the task of a separation kernel is to create an environment which is indistinguishable from that provided by a physically distributed system: it must appear as if each regime is a separate, isolated machine and that information can only flow from one machine to another along known external communication lines. One of the properties we must prove of a separation kernel, therefore, is that there are no channels for information flow between regimes other than those explicitly provided."
A variant of the separation kernel, the partitioning kernel, has gained acceptance in the commercial aviation community as a way of consolidating multiple functions onto a single processor, perhaps of mixed criticality. Commercial real-time operating system products in this genre have been used by aircraft manufacturers for safety-critical avionics applications.
In 2007 the Information Assurance Directorate of the U.S. National Security Agency (NSA) published the Separation Kernel Protection Profile (SKPP), a security requirements specification for separation kernels suitable to be used in the most hostile threat environments. The SKPP describes, in Common Criteria parlance, a class of modern products that provide the foundational properties of Rushby's conceptual separation kernel. It defines the security functional and assurance requirements for the construction and evaluation of separation kernels while yet providing some latitude in the choices available to developers.
The SKPP defines separation kernel as "hardware and/or firmware and/or software mechanisms whose primary function is to establish, isolate and separate multiple partitions and control information flow between the subjects and exported resources allocated to those partitions." Further, the separation kernel's core functional requirements include:

Protection of all resources (including CPU, memory and devices) from unauthorized access.
Separation of internal resources used by the Target of Evaluation Security Functions (TSF) from exported resources made available to subjects.
Partitioning and isolation of exported resources.
Mediation of information flows between partitions and between exported resources.
Audit services.
The separation kernel allocates all exported resources under its control into partitions. The partitions are isolated except for explicitly allowed information flows. The actions of a subject in one partition are isolated from (viz., cannot be detected by or communicated to) subjects in another partition, unless that flow has been allowed. The partitions and flows are defined in configuration data. Note that 'partition' and 'subject' are orthogonal abstractions. 'Partition,' as indicated by its mathematical genesis, provides for a set-theoretic grouping of system entities, whereas 'subject' allows us to reason about the individual active entities of a system. Thus, a partition (a collection, containing zero or more elements) is not a subject (an active element), but may contain zero or more subjects.
The separation kernel provides to its hosted software programs high-assurance partitioning and information flow control properties that are both tamperproof and non-bypassable. These capabilities provide a configurable trusted foundation for a variety of system architectures.

## Related

- [[ActivityPub]]
- [[AT Protocol]]
- [[Availability zone]]
- [[Botnet]]
- [[CAP theorem]]
- [[CockroachDB]]
- [[Collective operation]]
- [[Comparison of synchronous and asynchronous signalling]]
- [[Confidential Consortium Framework]]
- [[Consensus dynamics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Separation_kernel