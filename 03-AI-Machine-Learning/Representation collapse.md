---
title: "Representation collapse"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Representation_collapse"
wikipedia_categories: ["Artificial intelligence", "Artificial intelligence stubs", "Machine learning"]
related: ["[[Dataset shift]]", "[[AI data center]]", "[[AI observability]]", "[[AIOps]]", "[[Artificial intelligence in spirituality]]", "[[Attributional calculus]]", "[[Automated machine learning]]", "[[Automated negotiation]]", "[[Belief–desire–intention model]]", "[[Data-centric AI]]"]
---

# Representation collapse

Representation collapse is a phenomenon in machine learning and representation learning where a model maps different inputs to the same or very similar embeddings, which means it loses important information about how the data is spread out. It is frequently encountered in self-supervised learning, especially within contrastive and non-contrastive frameworks, when training objectives or model architectures do not maintain variance across representations. Collapse results in degenerate solutions characterized by uninformative learned features, significantly impairing downstream task performance. Various techniques have been proposed to mitigate representation collapse, including the use of negative samples, architectural asymmetry, stop-gradient operations, variance regularization, and redundancy reduction objectives, as seen in methods such as SimCLR, BYOL, and VICReg. Comprehending and averting representation collapse is regarded as a fundamental challenge in the advancement of stable and efficient self-supervised learning systems.

## Related

- [[Dataset shift]]
- [[AI data center]]
- [[AI observability]]
- [[AIOps]]
- [[Artificial intelligence in spirituality]]
- [[Attributional calculus]]
- [[Automated machine learning]]
- [[Automated negotiation]]
- [[Belief–desire–intention model]]
- [[Data-centric AI]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Representation_collapse