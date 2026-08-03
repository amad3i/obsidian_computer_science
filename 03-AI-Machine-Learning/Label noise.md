---
title: "Label noise"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Label_noise"
wikipedia_categories: ["Artificial intelligence stubs", "Classification algorithms", "Data quality", "Machine learning", "Supervised learning"]
related: ["[[Co-training]]", "[[Dataset shift]]", "[[Evolving classification function]]", "[[Few-shot learning]]", "[[Representation collapse]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]"]
---

# Label noise

Label noise refers to errors or inaccuracies in the class labels of data instances. This is a widespread issue in machine learning datasets, arising from human annotator mistakes, unclear labeling instructions, automated labeling methods, or adversarial attacks in supervised learning. Label noise can be roughly divided into random noise, where labels are flipped independently of input features, and systematic noise, where mislabeling is dependent on certain patterns or biases in the data. Label noise can be damaging to model performance, especially for complex models that may overfit to noisy labels rather than generalizable patterns.
Many approaches have been proposed to deal with the effects of label noise, including robust loss functions, noise-tolerant algorithms, data cleaning methods, and semi-supervised learning approaches. To reduce the impact of wrong labels during training, techniques like label smoothing, sample reweighting and using trusted validation sets are used. The role of noise-robust training paradigms and curriculum learning strategies to improve resilience against mislabeled data is also explored in recent research.

## Related

- [[Co-training]]
- [[Dataset shift]]
- [[Evolving classification function]]
- [[Few-shot learning]]
- [[Representation collapse]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Label_noise