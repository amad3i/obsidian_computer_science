---
title: "Neural network quantum states"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Neural_network_quantum_states"
wikipedia_categories: ["Machine learning", "Quantum Monte Carlo", "Quantum states"]
related: ["[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Absolutely maximally entangled state]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]", "[[AIOps]]", "[[AIXI]]"]
---

# Neural network quantum states

Neural Network Quantum States (NQS or NNQS) is a general class of variational quantum states parameterized in terms of an artificial neural network. It was first introduced in 2017 by the physicists Giuseppe Carleo and Matthias Troyer to approximate wave functions of many-body quantum systems.
Given a many-body quantum state 
  
    
      
        
          |
        
        Ψ
        ⟩
      
    
    
  
 comprising 
  
    
      
        N
      
    
    
  
 degrees of freedom and a choice of associated quantum numbers 
  
    
      
        
          s
          
            1
          
        
        …
        
          s
          
            N
          
        
      
    
    
  
, then an NQS parameterizes the wave-function amplitudes

  
    
      
        ⟨
        
          s
          
            1
          
        
        …
        
          s
          
            N
          
        
        
          |
        
        Ψ
        ;
        W
        ⟩
        F
        
          s
          
            1
          
        
        …
        
          s
          
            N
          
        
        ;
        W
        ,
      
    
    
  

where 
  
    
      
        F
        
          s
          
            1
          
        
        …
        
          s
          
            N
          
        
        ;
        W
      
    
    
  
 is an artificial neural network of parameters (weights) 
  
    
      
        W
      
    
    
  
, 
  
    
      
        N
      
    
    
  
 input variables (
  
    
      
        
          s
          
            1
          
        
        …
        
          s
          
            N
          
        
      
    
    
  
) and one complex-valued output corresponding to the wave-function amplitude.
This variational form is used in conjunction with specific stochastic learning approaches to approximate quantum states of interest.

## Related

- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Absolutely maximally entangled state]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]
- [[Adversarial machine learning]]
- [[AI data center]]
- [[AI observability]]
- [[AIOps]]
- [[AIXI]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Neural_network_quantum_states