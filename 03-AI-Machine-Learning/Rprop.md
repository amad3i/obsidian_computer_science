---
title: "Rprop"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Rprop"
wikipedia_categories: ["Artificial neural networks", "Machine learning algorithms"]
related: ["[[Backpropagation]]", "[[Dehaene–Changeux model]]", "[[Growing self-organizing map]]", "[[Hyper basis function network]]", "[[Leabra]]", "[[Linde–Buzo–Gray algorithm]]", "[[LoRA (machine learning)]]", "[[Quickprop]]", "[[Self-organizing map]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]"]
---

# Rprop

Rprop, short for resilient backpropagation, is a learning heuristic for supervised learning in feedforward artificial neural networks. This is a first-order optimization algorithm. This algorithm was created by Martin Riedmiller and Heinrich Braun in 1992.
Similarly to the Manhattan update rule, Rprop takes into account only the sign of the partial derivative over all patterns (not the magnitude), and acts independently on each "weight".  For each weight, if there was a sign change of the partial derivative of the total error function compared to the last iteration, the update value for that weight is multiplied by a factor η−, where η− < 1. If the last iteration produced the same sign, the update value is multiplied by a factor of η+, where η+ > 1. The update values are calculated for each weight in the above manner, and finally each weight is changed by its own update value, in the opposite direction of that weight's partial derivative, so as to minimise the total error function.  η+ is empirically set to 1.2 and η− to 0.5.
Rprop can result in very large weight increments or decrements if the gradients are large, which is a problem when using mini-batches as opposed to full batches. RMSprop addresses this problem by keeping the moving average of the squared gradients for each weight and dividing the gradient by the square root of the mean square.
RPROP is a batch update algorithm. Next to the cascade correlation algorithm and the Levenberg–Marquardt algorithm, Rprop is one of the fastest weight update mechanisms.

## Related

- [[Backpropagation]]
- [[Dehaene–Changeux model]]
- [[Growing self-organizing map]]
- [[Hyper basis function network]]
- [[Leabra]]
- [[Linde–Buzo–Gray algorithm]]
- [[LoRA (machine learning)]]
- [[Quickprop]]
- [[Self-organizing map]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rprop