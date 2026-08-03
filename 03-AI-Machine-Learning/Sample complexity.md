---
title: "Sample complexity"
tags: ["cs", "ai-machine-learning", "advanced"]
domain: AI & Machine Learning
level: advanced
source: "https://en.wikipedia.org/wiki/Sample_complexity"
wikipedia_categories: ["Machine learning"]
related: ["[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]", "[[AIOps]]", "[[AIXI]]", "[[Algorithm selection]]"]
---

# Sample complexity

The sample complexity of a machine learning algorithm represents the number of training-samples that it needs in order to successfully learn a target function.
More precisely, the sample complexity is the number of training-samples that we need to supply to the algorithm, so that the function returned by the algorithm is within an arbitrarily small error of the best possible function, with probability arbitrarily close to 1.
There are two variants of sample complexity:

The weak variant fixes a particular input-output distribution;
The strong variant takes the worst-case sample complexity over all input-output distributions.
The No free lunch theorem, discussed below, proves that, in general, the strong sample complexity is infinite, i.e. that there is no algorithm that can learn the globally-optimal target function using a finite number of training samples.
However, if we are only interested in a particular class of target functions (e.g., only linear functions) then the sample complexity is finite, and it depends linearly on the VC dimension on the class of target functions.

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

- Wikipedia: https://en.wikipedia.org/wiki/Sample_complexity