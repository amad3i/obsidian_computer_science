---
title: "Normalization (machine learning)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Normalization_(machine_learning)"
wikipedia_categories: ["Deep learning", "Machine learning", "Neural networks", "Statistical data transformation"]
related: ["[[AI data center]]", "[[Audio inpainting]]", "[[Circuit (neural network)]]", "[[Compute (machine learning)]]", "[[Feature scaling]]", "[[Fine-tuning (deep learning)]]", "[[Generative AI]]", "[[Hallucination (artificial intelligence)]]", "[[Hidden layer]]", "[[Kolmogorov–Arnold Networks]]"]
---

# Normalization (machine learning)

In machine learning, normalization is a statistical technique with various applications. There are two main forms of normalization, namely data normalization and activation normalization. Data normalization (or feature scaling) includes methods that rescale input data so that the features have the same range, mean, variance, or other statistical properties. For instance, a popular choice of feature scaling method is min-max normalization, where each feature is transformed to have the same range (typically 
  
    
      
        0
        ,
        1
      
    
    
  
 or 
  
    
      
        −
        1
        ,
        1
      
    
    
  
). This solves the problem of different features having vastly different scales, for example if one feature is measured in kilometers and another in nanometers.
Activation normalization, on the other hand, is specific to deep learning, and includes methods that rescale the activation of hidden neurons inside neural networks.
Normalization is often used to:

increase the speed of training convergence,
reduce sensitivity to variations and feature scales in input data,
reduce overfitting,
and produce better model generalization to unseen data.
Normalization techniques are often theoretically justified as reducing covariance shift, smoothing optimization landscapes, and increasing regularization, though they are mainly justified by empirical success.

## Related

- [[AI data center]]
- [[Audio inpainting]]
- [[Circuit (neural network)]]
- [[Compute (machine learning)]]
- [[Feature scaling]]
- [[Fine-tuning (deep learning)]]
- [[Generative AI]]
- [[Hallucination (artificial intelligence)]]
- [[Hidden layer]]
- [[Kolmogorov–Arnold Networks]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Normalization_(machine_learning)