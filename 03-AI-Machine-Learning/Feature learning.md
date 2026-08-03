---
title: "Feature learning"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Feature_learning"
wikipedia_categories: ["Machine learning"]
related: ["[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]", "[[AIOps]]", "[[AIXI]]", "[[Algorithm selection]]"]
---

# Feature learning

In machine learning (ML), feature learning or representation learning is a set of techniques that allow a system to automatically discover the representations needed for feature detection or classification from raw data. This replaces manual feature engineering and allows a machine to both learn the features and use them to perform  a specific task.
Feature learning is motivated by the fact that ML tasks such as classification often require input that is mathematically and computationally convenient to process. However, real-world data, such as image, video, and sensor data, have not yielded to attempts to algorithmically define specific features. An alternative is to discover such features or representations through examination, without relying on explicit algorithms.
Feature learning can be either supervised, unsupervised, or self-supervised:

In supervised feature learning, features are learned using labeled input data. Labeled data includes input-label pairs where the input is given to the model, and it must produce the ground truth label as the output. This can be leveraged to generate feature representations with the model which result in high label prediction accuracy. Examples include supervised neural networks, multilayer perceptrons, and dictionary learning.
In unsupervised feature learning, features are learned with unlabeled input data by analyzing the relationship between points in the dataset.  Examples include dictionary learning, independent component analysis, matrix factorization, and various forms of clustering.
In self-supervised feature learning, features are learned using unlabeled data like unsupervised learning, however input-label pairs are constructed from each data point, enabling learning the structure of the data through supervised methods such as gradient descent. Classical examples include word embeddings and autoencoders. Self-supervised learning has since been applied to many modalities through the use of deep neural network architectures such as convolutional neural networks and transformers.

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

- Wikipedia: https://en.wikipedia.org/wiki/Feature_learning