---
title: "Local case-control sampling"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Local_case-control_sampling"
wikipedia_categories: ["Logistic regression", "Machine learning"]
related: ["[[Bradley–Terry model]]", "[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]", "[[AIOps]]", "[[AIXI]]"]
---

# Local case-control sampling

In machine learning, local case-control sampling  is an algorithm used to reduce the complexity of training a logistic regression classifier. The algorithm reduces the training complexity by selecting a small subsample of the original dataset for training. It assumes the availability of an (unreliable) pilot estimation of the parameters. It then performs a single pass over the entire dataset using the pilot estimation to identify the most "surprising" samples. In practice, the pilot may come from prior knowledge or training using a subsample of the dataset. The algorithm is most effective when the underlying dataset is imbalanced. It exploits the structures of conditional imbalanced datasets more efficiently than alternative methods, such as case control sampling and weighted case control sampling.

## Related

- [[Bradley–Terry model]]
- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]
- [[Adversarial machine learning]]
- [[AI data center]]
- [[AI observability]]
- [[AIOps]]
- [[AIXI]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Local_case-control_sampling