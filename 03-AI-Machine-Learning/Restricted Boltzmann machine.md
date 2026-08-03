---
title: "Restricted Boltzmann machine"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Restricted_Boltzmann_machine"
wikipedia_categories: ["Neural network architectures", "Stochastic models", "Supervised learning", "Unsupervised learning"]
related: ["[[Graph neural network]]", "[[Generative adversarial network]]", "[[AlexNet]]", "[[Class activation mapping]]", "[[Cognitive computer]]", "[[Competitive learning]]", "[[Conceptual clustering]]", "[[Convolutional neural network]]", "[[Deep belief network]]", "[[Ehrenfest model]]"]
---

# Restricted Boltzmann machine

A restricted Boltzmann machine (RBM) (also called a restricted Sherrington–Kirkpatrick model with external field or restricted stochastic Ising–Lenz–Little model) is a generative stochastic artificial neural network that can learn a probability distribution over its set of inputs.
RBMs were initially proposed under the name Harmonium by Paul Smolensky in 1986, and rose to prominence after Geoffrey Hinton and collaborators used fast learning algorithms for them in the mid-2000s. RBMs have found applications in dimensionality reduction, classification, collaborative filtering, feature learning, topic modelling, immunology, and even many‑body quantum mechanics.

They can be trained in either supervised or unsupervised ways, depending on the task.
As their name implies, RBMs are a variant of Boltzmann machines, with the restriction that their neurons must form a bipartite graph:

a pair of nodes from each of the two groups of units (commonly referred to as the "visible" and "hidden" units respectively) may have a symmetric connection between them; and
there are no connections between nodes within a group.
By contrast, "unrestricted" Boltzmann machines may have connections between hidden units. This restriction allows for more efficient training algorithms than are available for the general class of Boltzmann machines, in particular the gradient-based contrastive divergence algorithm.
Restricted Boltzmann machines can also be used in deep learning networks. In particular, deep belief networks can be formed by "stacking" RBMs and optionally fine-tuning the resulting deep network with gradient descent and backpropagation.

## Related

- [[Graph neural network]]
- [[Generative adversarial network]]
- [[AlexNet]]
- [[Class activation mapping]]
- [[Cognitive computer]]
- [[Competitive learning]]
- [[Conceptual clustering]]
- [[Convolutional neural network]]
- [[Deep belief network]]
- [[Ehrenfest model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Restricted_Boltzmann_machine