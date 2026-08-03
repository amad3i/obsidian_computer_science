---
title: "Residual neural network"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Residual_neural_network"
wikipedia_categories: ["Deep learning", "Neural network architectures"]
related: ["[[Gating mechanism]]", "[[Neural field]]", "[[AI data center]]", "[[AlexNet]]", "[[Artificial intelligence in fraud detection]]", "[[Audio inpainting]]", "[[Circuit (neural network)]]", "[[Class activation mapping]]", "[[CLEVER score]]", "[[Compute (machine learning)]]"]
---

# Residual neural network

A residual neural network (also referred to as a residual network or ResNet) is a deep learning architecture in which the layers learn residual functions with reference to the layer inputs. It was developed in 2015 for image recognition, and won the ImageNet Large Scale Visual Recognition Challenge (ILSVRC) of that year.
As a point of terminology, "residual connection" refers to the specific architectural motif of 
  
    
      
        x
        ↦
        f
        x
        +
        x
      
    
    
  
, where 
  
    
      
        f
      
    
    
  
 is an arbitrary neural network module. The motif had been used previously (see §History for details). However, the publication of ResNet made it widely popular for feedforward networks, appearing in neural networks that are seemingly unrelated to ResNet.
The residual connection stabilizes the training and convergence of deep neural networks with hundreds of layers, and is a common motif in deep neural networks, such as transformer models (e.g., BERT, and GPT models such as ChatGPT), the AlphaGo Zero system, the AlphaStar system, and the AlphaFold system.

## Related

- [[Gating mechanism]]
- [[Neural field]]
- [[AI data center]]
- [[AlexNet]]
- [[Artificial intelligence in fraud detection]]
- [[Audio inpainting]]
- [[Circuit (neural network)]]
- [[Class activation mapping]]
- [[CLEVER score]]
- [[Compute (machine learning)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Residual_neural_network