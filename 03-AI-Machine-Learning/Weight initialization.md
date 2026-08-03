---
title: "Weight initialization"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Weight_initialization"
wikipedia_categories: ["Artificial neural networks"]
related: ["[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Activation function]]", "[[ADALINE]]", "[[Adaptive neuro fuzzy inference system]]", "[[Adaptive resonance theory]]", "[[ALOPEX]]", "[[AlterEgo]]", "[[Backpropagation]]", "[[Circuit (neural network)]]", "[[Competitive learning]]"]
---

# Weight initialization

In deep learning, weight initialization or parameter initialization describes the initial step in creating a neural network. A neural network contains trainable parameters that are modified during training: weight initialization is the pre-training step of assigning initial values to these parameters.
The choice of weight initialization method affects the speed of convergence, the scale of neural activation within the network, the scale of gradient signals during backpropagation, and the quality of the final model. Proper initialization is necessary for avoiding issues such as vanishing and exploding gradients and activation function saturation.
Note that even though this article is titled "weight initialization", both weights and biases are used in a neural network as trainable parameters, so this article describes how both of these are initialized. Similarly, trainable parameters in convolutional neural networks (CNNs) are called kernels and biases, and this article also describes these.

## Related

- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Activation function]]
- [[ADALINE]]
- [[Adaptive neuro fuzzy inference system]]
- [[Adaptive resonance theory]]
- [[ALOPEX]]
- [[AlterEgo]]
- [[Backpropagation]]
- [[Circuit (neural network)]]
- [[Competitive learning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Weight_initialization