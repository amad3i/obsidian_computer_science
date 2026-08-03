---
title: "Stability (learning theory)"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Stability_(learning_theory)"
wikipedia_categories: ["Learning", "Machine learning"]
related: ["[[Inferential theory of learning]]", "[[Knowledge integration]]", "[[Machine learning]]", "[[Proactive learning]]", "[[Robot learning]]", "[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]"]
---

# Stability (learning theory)

Stability, also known as algorithmic stability, is a notion in computational learning theory of how a  machine learning algorithm output is changed with small perturbations to its inputs. A stable learning algorithm is one for which the prediction does not change much when the training data is modified slightly. For instance, consider a machine learning algorithm that is being trained to recognize handwritten letters of the alphabet, using 1000 examples of handwritten letters and their labels ("A" to "Z") as a training set. One way to modify this training set is to leave out an example, so that only 999 examples of handwritten letters and their labels are available. A stable learning algorithm would produce a similar classifier with both the 1000-element and 999-element training sets.
Stability can be studied for many types of learning problems, from language learning to inverse problems in physics and engineering, as it is a property of the learning process rather than the type of information being learned. The study of stability gained importance in computational learning theory in the 2000s when it was shown to have a connection with generalization. It was shown that for large classes of learning algorithms, notably empirical risk minimization algorithms, certain types of stability ensure good generalization.

## Related

- [[Inferential theory of learning]]
- [[Knowledge integration]]
- [[Machine learning]]
- [[Proactive learning]]
- [[Robot learning]]
- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]
- [[Adversarial machine learning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stability_(learning_theory)