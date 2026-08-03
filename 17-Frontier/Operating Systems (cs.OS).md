---
title: "Operating Systems"
tags: [cs, frontier, arxiv]
domain: Frontier
level: frontier
source: "https://arxiv.org/list/cs.OS/recent"
---

# Operating Systems (cs.OS)

Frontier research area. Live listing: https://arxiv.org/list/cs.OS/recent

## Recent papers (real, from arXiv)

### From C to Idiomatic Rust: A Ship-of-Theseus Agentic Translation

C underpins operating systems, embedded platforms, and network infrastructure because its abstractions map directly to machine behaviour. Its explicit memory model, predictable data representations, and minimal runtime allow compilers to generate fast, deterministic code. These properties also leave correctness and memory safety entirely to the programmer, making undefined behaviour, pointer misuse, and lifetime errors persistent sources of defects and security vulnerabilities in long-lived C codebases. Rust eliminates most of failure modes through a static ownership and borrowing model that enforces memory safety and aliasing constraints at compile time. However, mature C systems cannot be translated directly: implicit layout assumptions, aliasing patterns, and undefined behaviour must be reconstructed before safe Rust can be produced. This paper presents a migration methodology that fi

- http://arxiv.org/abs/2607.28835v1

### Deductive Verification for Earliest Deadline First Scheduler Implementations

Real-Time Operating Systems (RTOSes) rely on scheduler implementations to provide predictable task execution. For safety-critical systems, it is therefore not sufficient to reason only about the abstract scheduling policy; the concrete implementation must also preserve the intended scheduling semantics. This is particularly challenging for Earliest Deadline First (EDF) scheduling, because EDF introduces dynamic, deadline-derived priorities that are often realized by reusing kernel infrastructure originally designed for fixed-priority scheduling. In this work, we formalize EDF correctness through three essential properties that any implementation of the Earliest Deadline First (EDF) scheduler must satisfy. Based on these properties, we propose a framework utilizing deductive verification, that applies to any EDF-based scheduler realization. We instantiate the framework in Frama-C/ACSL and

- http://arxiv.org/abs/2607.26927v1

### Specula: Scaling formal specifications for autonomous model checking of system code

Specula is a push-button agentic system that generates high-quality formal specifications for large, complex system code and uses the specifications for highly effective model checking and bug finding. Specula employs large language model (LLM) based coding agents to autonomously develop TLA+ specifications, including invariants that describe correctness properties of the target system and formal models that describe the system implementation with the right level of abstractions. Specula is fully autonomous and thus eliminates the barrier of applying formal methods to real-world system code (as in traditional human-centric approaches). Meanwhile, Specula addresses limitations of LLM-driven techniques like reward hacking and hallucinations through self-evolving loops that iteratively improve specification quality by enabling the agents to deepen their understanding of system code and its 

- http://arxiv.org/abs/2607.25333v1

## Sources

- https://arxiv.org/list/cs.OS/recent