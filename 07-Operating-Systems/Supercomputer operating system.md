---
title: "Supercomputer operating system"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Supercomputer_operating_system"
wikipedia_categories: ["Operating systems", "Supercomputer operating systems"]
related: ["[[Bare machine]]", "[[Comparison of operating systems]]", "[[Comparison of user features of operating systems]]", "[[DBOS]]", "[[Distributed operating system]]", "[[Glossary of operating systems terms]]", "[[History of operating systems]]", "[[History of RISC OS]]", "[[Holborn 9100]]", "[[Internet OS]]"]
---

# Supercomputer operating system

A supercomputer operating system is an operating system intended for supercomputers. Since the end of the 20th century, supercomputer operating systems have undergone major transformations, as fundamental changes have occurred in supercomputer architecture. While early operating systems were custom tailored to each supercomputer to gain speed, the trend has been moving away from in-house operating systems and toward some form of Linux, with it running all the supercomputers on the TOP500 list in November 2017. In 2021, top 10 computers run for instance Red Hat Enterprise Linux (RHEL), or some variant of it or other Linux distribution e.g. Ubuntu.
Given that modern massively parallel supercomputers typically separate computations from other services by using multiple types of nodes, they usually run different operating systems on different nodes, e.g., using a small and efficient lightweight kernel such as Compute Node Kernel (CNK) or Compute Node Linux (CNL) on compute nodes, but a larger system such as a Linux distribution on server and input/output (I/O) nodes.
While in a traditional multi-user computer system job scheduling is in effect a tasking problem for processing and peripheral resources, in a massively parallel system, the job management system needs to manage the allocation of both computational and communication resources, as well as gracefully dealing with inevitable hardware failures when tens of thousands of processors are present.
Although most modern supercomputers use the Linux operating system, each manufacturer has made its own specific changes to the Linux distribution they use, and no industry standard exists, partly because the differences in hardware architectures require changes to optimize the operating system to each hardware design.

## Related

- [[Bare machine]]
- [[Comparison of operating systems]]
- [[Comparison of user features of operating systems]]
- [[DBOS]]
- [[Distributed operating system]]
- [[Glossary of operating systems terms]]
- [[History of operating systems]]
- [[History of RISC OS]]
- [[Holborn 9100]]
- [[Internet OS]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Supercomputer_operating_system