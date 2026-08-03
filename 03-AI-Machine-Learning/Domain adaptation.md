---
title: "Domain adaptation"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Domain_adaptation"
wikipedia_categories: ["Machine learning"]
related: ["[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]", "[[AIOps]]", "[[AIXI]]", "[[Algorithm selection]]"]
---

# Domain adaptation

Domain adaptation is a field associated with machine learning and transfer learning. It addresses the challenge of training a model on one data distribution (the source domain) and applying it to a related but different data distribution (the target domain).
A common example is spam filtering, where a model trained on emails from one user (source domain) is adapted to handle emails for another user with significantly different patterns (target domain).
Domain adaptation techniques can also leverage unrelated data sources to improve learning. When multiple source distributions are involved, the problem extends to multi-source domain adaptation.
Domain adaptation is a specific type of transfer learning. According to the taxonomy laid out by Pan and Yang (2010), it falls into the category of transductive transfer learning. In this setting, the source and target tasks are the same (e.g., both are object recognition), but the domains differ (different marginal distributions). This distinguishes it from inductive transfer learning (where labeled data is available for the target task) and unsupervised transfer learning (where labels are unavailable in both domains).

## Related

- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]
- [[Adversarial machine learning]]
- [[AI data center]]
- [[AI observability]]
- [[AIOps]]
- [[AIXI]]
- [[Algorithm selection]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Domain_adaptation