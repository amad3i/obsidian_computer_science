---
title: "Protection ring"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Protection_ring"
wikipedia_categories: ["Central processing unit", "Computer security models", "Operating system technology"]
related: ["[[Control register]]", "[[Dirty bit]]", "[[Flag (programming)]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Arithmetic logic unit]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Binary Application Markup Language]]"]
---

# Protection ring

In computer science, hierarchical protection domains, often called protection rings, are mechanisms to protect data and functionality from faults (by improving fault tolerance) and malicious behavior (by providing computer security).
Computer operating systems provide different levels of access to resources. A protection ring is one of two or more hierarchical levels or layers of privilege within the architecture of a computer system. This is generally hardware-enforced by some CPU architectures that provide different CPU modes at the hardware or microcode level. Rings are arranged in a hierarchy from most privileged (most trusted, usually numbered zero) to least privileged (least trusted, usually with the highest ring number). On most operating systems, Ring 0 is the level with the most privileges and interacts most directly with the physical hardware such as certain CPU functionality (e.g. the control registers) and I/O controllers. 
Special mechanisms are provided to allow an outer ring to access an inner ring's resources in a predefined manner, as opposed to allowing arbitrary usage. Correctly gating access between rings can improve security by preventing programs from one ring or privilege level from misusing resources intended for programs in another. For example, spyware running as a user program in Ring 3 should be prevented from turning on a web camera without informing the user, since hardware access should be a Ring 1 function reserved for device drivers. Programs such as web browsers running in higher numbered rings must request access to the network, a resource restricted to a lower numbered ring.
X86S, a canceled Intel architecture published in 2024, has only ring 0 and ring 3. Ring 1 and 2 were to be removed under X86S since modern operating systems never utilize them.

## Related

- [[Control register]]
- [[Dirty bit]]
- [[Flag (programming)]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Arithmetic logic unit]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Binary Application Markup Language]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Protection_ring