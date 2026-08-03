---
title: "Knowledge distillation"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Knowledge_distillation"
wikipedia_categories: ["Deep learning"]
related: ["[[AI data center]]", "[[Artificial intelligence in fraud detection]]", "[[Audio inpainting]]", "[[Circuit (neural network)]]", "[[CLEVER score]]", "[[Compute (machine learning)]]", "[[Conversica]]", "[[Convolutional layer]]", "[[Deep image prior]]", "[[Deep Instinct]]"]
---

# Knowledge distillation

In machine learning, knowledge distillation or model distillation is the process of transferring knowledge from a large model to a smaller one. While large models (such as very deep neural networks or ensembles of many models ) have more knowledge capacity than small models, this capacity might not be fully utilized.  It can be just as computationally expensive to evaluate a model even if it utilizes little of its knowledge capacity.  Knowledge distillation transfers knowledge from a large model to a smaller one without loss of validity.  As smaller models are less expensive to evaluate, they can be deployed on less powerful hardware (such as a mobile device).
There is also a less common technique called Reverse Knowledge Distillation, where knowledge is transferred from a smaller model to a larger one.
Model distillation is not to be confused with model compression, which describes methods to decrease the size of a large model itself, without training a new model. Model compression generally preserves the architecture and the nominal parameter count of the model, while decreasing the bits-per-parameter.
Knowledge distillation has been successfully used in several applications of machine learning such as object detection, acoustic models, and natural language processing.
Recently, it has also been introduced to graph neural networks applicable to non-grid data.

## Related

- [[AI data center]]
- [[Artificial intelligence in fraud detection]]
- [[Audio inpainting]]
- [[Circuit (neural network)]]
- [[CLEVER score]]
- [[Compute (machine learning)]]
- [[Conversica]]
- [[Convolutional layer]]
- [[Deep image prior]]
- [[Deep Instinct]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Knowledge_distillation