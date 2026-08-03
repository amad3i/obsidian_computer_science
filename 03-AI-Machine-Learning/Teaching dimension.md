---
title: "Teaching dimension"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Teaching_dimension"
wikipedia_categories: ["Computational learning theory", "Machine learning stubs", "Theoretical computer science stubs"]
related: ["[[Sample exclusion dimension]]", "[[Unique negative dimension]]", "[[Witness set]]", "[[Algorithmic learning theory]]", "[[Almeida–Pineda recurrent backpropagation]]", "[[Archetypal analysis]]", "[[Astrostatistics]]", "[[Bayesian learning mechanisms]]", "[[Bondy's theorem]]", "[[Bridging model]]"]
---

# Teaching dimension

In computational learning theory, the teaching dimension of a concept class C is defined to be 
  
    
      
        
          max
          
            c
            ∈
            C
          
        
        
          w
          
            C
          
        
        c
        }
      
    
    
  
, where 
  
    
      
        
          
            w
            
              C
            
          
          c
        
      
    
    
  
 is the minimum size of a witness set for c in C. Intuitively, this measures the number of instances that are needed to identify a concept in the class, using supervised learning with examples provided by a helpful teacher who is trying to convey the concept as succinctly as possible. This definition was formulated in 1995 by Sally Goldman and Michael Kearns, based on earlier work by Goldman, Ron Rivest, and Robert Schapire.
The teaching dimension of a finite concept class can be used to give a lower and an upper bound on the membership query cost of the concept class.
In Stasys Jukna's book "Extremal Combinatorics", a lower bound is given for the teaching dimension in general:
Let C be a concept class over a finite domain X. If the size of C is greater than 

  
    
      
        
          2
          
            k
          
        
        
          
            
            
            
              
                
                  |
                
                X
                
                  |
                
              
              k
            
            
            
          
        
        ,
      
    
    
  

then the teaching dimension of C is greater than k.
However, there are more specific teaching models that make assumptions about teacher or learner, and can get lower values for the teaching dimension. For instance, several models are the classical teaching (CT) model, the optimal teacher (OT) model, recursive teaching (RT), preference-based teaching (PBT), and non-clashing teaching (NCT).

## Related

- [[Sample exclusion dimension]]
- [[Unique negative dimension]]
- [[Witness set]]
- [[Algorithmic learning theory]]
- [[Almeida–Pineda recurrent backpropagation]]
- [[Archetypal analysis]]
- [[Astrostatistics]]
- [[Bayesian learning mechanisms]]
- [[Bondy's theorem]]
- [[Bridging model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Teaching_dimension