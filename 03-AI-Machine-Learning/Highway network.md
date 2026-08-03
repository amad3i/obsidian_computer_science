---
title: "Highway network"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Highway_network"
wikipedia_categories: ["2015 in artificial intelligence", "Machine learning", "Neural network architectures"]
related: ["[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]", "[[AIOps]]", "[[AIXI]]", "[[AlexNet]]"]
---

# Highway network

In machine learning, the Highway Network was the first working very deep feedforward neural network with hundreds of layers, much deeper than previous neural networks.
It uses skip connections modulated by learned gating mechanisms to regulate information flow, inspired by long short-term memory (LSTM) recurrent neural networks.
The advantage of the Highway Network over other deep learning architectures is its ability to overcome or partially prevent the vanishing gradient problem, thus improving its optimization. Gating mechanisms are used to facilitate information flow across the many layers ("information highways").
Highway Networks have found use in text sequence labeling and speech recognition tasks.
In 2014, the state of the art was training deep neural networks with 20 to 30 layers. Stacking too many layers led to a steep reduction in training accuracy, known as the "degradation" problem. In 2015, two techniques were developed to train such networks: the Highway Network (published in May), and the residual neural network, or ResNet (December). ResNet behaves like an open-gated Highway Net.

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
- [[AlexNet]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Highway_network