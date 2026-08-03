---
title: "Quickprop"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Quickprop"
wikipedia_categories: ["Algorithms and data structures stubs", "Artificial neural networks", "Computational neuroscience", "Computational neuroscience stubs", "Machine learning algorithms", "Machine learning stubs"]
related: ["[[Almeida–Pineda recurrent backpropagation]]", "[[Dehaene–Changeux model]]", "[[DexNet]]", "[[European Neural Network Society]]", "[[Hard sigmoid]]", "[[PVLV]]", "[[Backpropagation]]", "[[Circuit (neural network)]]", "[[CLEVER score]]", "[[CN2 algorithm]]"]
---

# Quickprop

Quickprop is an iterative method for determining the minimum of the loss function of an artificial neural network, following an algorithm inspired by the Newton's method. Sometimes, the algorithm is classified to the group  of the second order learning methods. It follows a quadratic approximation of the previous gradient step and the current gradient, which is expected to be close to the minimum of the loss function, under the assumption that the loss function is locally approximately square, trying to describe it by means of an upwardly open parabola. The minimum is sought in the vertex of the parabola. The procedure requires only local information of the artificial neuron to which it is applied.
The 
  
    
      
        k
      
    
    
  
-th approximation step is given by:

  
    
      
        
          Δ
          
            k
          
        
        
        
          w
          
            i
            j
          
        
        
          Δ
          
            k
            1
          
        
        
        
          w
          
            i
            j
          
        
        
          
            
              
                
                  ∇
                  
                    i
                    j
                  
                
                
                
                  E
                  
                    k
                  
                
              
              
                
                  ∇
                  
                    i
                    j
                  
                
                
                
                  E
                  
                    k
                    1
                  
                
                
                  ∇
                  
                    i
                    j
                  
                
                
                
                  E
                  
                    k
                  
                
              
            
          
        
      
    
    
  

Where 
  
    
      
        
          w
          
            i
            j
          
        
      
    
    
  
 is the weight of input 
  
    
      
        i
      
    
    
  
 of neuron 
  
    
      
        j
      
    
    
  
, and 
  
    
      
        E
      
    
    
  
 is the loss function.
The Quickprop algorithm is an implementation of the error backpropagation algorithm, but the network  can behave chaotically during the learning phase due to large step sizes.

## Related

- [[Almeida–Pineda recurrent backpropagation]]
- [[Dehaene–Changeux model]]
- [[DexNet]]
- [[European Neural Network Society]]
- [[Hard sigmoid]]
- [[PVLV]]
- [[Backpropagation]]
- [[Circuit (neural network)]]
- [[CLEVER score]]
- [[CN2 algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Quickprop