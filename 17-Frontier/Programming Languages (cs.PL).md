---
title: "Programming Languages"
tags: [cs, frontier, arxiv]
domain: Frontier
level: frontier
source: "https://arxiv.org/list/cs.PL/recent"
---

# Programming Languages (cs.PL)

Frontier research area. Live listing: https://arxiv.org/list/cs.PL/recent

## Recent papers (real, from arXiv)

### High-Level Big Integer Arithmetic in Futhark for GPUs

We report on GPU implementations of block-level addition, subtraction, multiplication and division for midsize integers, with operands of $2^{15}$ to $2^{19}$ bits using the high-level functional language Futhark. Comparing with hand-written C++/CUDA versions and CGBN, we identify which functional constructs compile well, where memory placement and sequentialization are effective, and what compiler support is needed. The results show that high-level code can express the algorithms compactly while approaching competitive performance after certain compiler improvements. In particular, we find that automated placement of arrays in GPU register memory is critical for performance.

- http://arxiv.org/abs/2607.28897v1

### From C to Idiomatic Rust: A Ship-of-Theseus Agentic Translation

C underpins operating systems, embedded platforms, and network infrastructure because its abstractions map directly to machine behaviour. Its explicit memory model, predictable data representations, and minimal runtime allow compilers to generate fast, deterministic code. These properties also leave correctness and memory safety entirely to the programmer, making undefined behaviour, pointer misuse, and lifetime errors persistent sources of defects and security vulnerabilities in long-lived C codebases. Rust eliminates most of failure modes through a static ownership and borrowing model that enforces memory safety and aliasing constraints at compile time. However, mature C systems cannot be translated directly: implicit layout assumptions, aliasing patterns, and undefined behaviour must be reconstructed before safe Rust can be produced. This paper presents a migration methodology that fi

- http://arxiv.org/abs/2607.28835v1

### Formalization of security

Proof assistants are often used to validate that designs and implementations meet their expected security properties. A further motivation for using proof assistants is to support certification. This chapter focuses on their applications to system security, language-based security, secure compilation, and cryptography.

- http://arxiv.org/abs/2607.28551v1

## Sources

- https://arxiv.org/list/cs.PL/recent