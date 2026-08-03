---
title: "Hamming scheme"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Hamming_scheme"
wikipedia_categories: ["Coding theory"]
related: ["[[Algebraic geometry code]]", "[[Alternant code]]", "[[Arbitrarily varying channel]]", "[[Bar product]]", "[[Barker code]]", "[[BCH code]]", "[[Belief propagation]]", "[[Berger code]]", "[[Berlekamp switching game]]", "[[Berlekamp–Welch algorithm]]"]
---

# Hamming scheme

The Hamming scheme, named after Richard Hamming, is also known as the hyper-cubic association scheme, and it is the most important example for coding theory. In this scheme 
  
    
      
        X
        
          
            
              F
            
          
          
            n
          
        
        ,
      
    
    
  
 the set of binary vectors of length 
  
    
      
        n
        ,
      
    
    
  
 and two vectors 
  
    
      
        x
        ,
        y
        ∈
        
          
            
              F
            
          
          
            n
          
        
      
    
    
  
 are 
  
    
      
        i
      
    
    
  
-th associates if they are Hamming distance 
  
    
      
        i
      
    
    
  
 apart.
Recall that an association scheme is visualized as a complete graph with labeled edges. The graph has 
  
    
      
        v
      
    
    
  
 vertices, one for each point of 
  
    
      
        X
        ,
      
    
    
  
 and the edge joining vertices 
  
    
      
        x
      
    
    
  
 and 
  
    
      
        y
      
    
    
  
 is labeled 
  
    
      
        i
      
    
    
  
 if 
  
    
      
        x
      
    
    
  
 and 
  
    
      
        y
      
    
    
  
 are 
  
    
      
        i
      
    
    
  
-th associates. Each edge has a unique label, and the number of triangles with a fixed base labeled 
  
    
      
        k
      
    
    
  
 having the other edges labeled 
  
    
      
        i
      
    
    
  
 and 
  
    
      
        j
      
    
    
  
 is a constant 
  
    
      
        
          c
          
            i
            j
            k
          
        
        ,
      
    
    
  
 depending on 
  
    
      
        i
        ,
        j
        ,
        k
      
    
    
  
 but not on the choice of the base. In particular, each vertex is incident with exactly 
  
    
      
        
          c
          
            i
            i
            0
          
        
        
          v
          
            i
          
        
      
    
    
  
 edges labeled 
  
    
      
        i
      
    
    
  
; 
  
    
      
        
          v
          
            i
          
        
      
    
    
  
 is the valency of the relation 
  
    
      
        
          R
          
            i
          
        
        .
      
    
    
  
 The 
  
    
      
        
          c
          
            i
            j
            k
          
        
      
    
    
  
 in a Hamming scheme are given by

  
    
      
        
          c
          
            i
            j
            k
          
        
        
          
            
              
                
                  
                    
                      
                        
                        
                        
                          k
                          
                            
                              
                                1
                                2
                              
                            
                            i
                            j
                            k
                          
                        
                        
                        
                      
                    
                  
                  
                    
                      
                        
                        
                        
                          
                            n
                            k
                          
                          
                            
                              
                                1
                                2
                              
                            
                            i
                            j
                            k
                          
                        
                        
                        
                      
                    
                  
                
                
                  i
                  j
                  k
                  ≡
                  0
                  
                    
                    mod
                    
                    2
                  
                
              
              
                
              
              
                
                  0
                
                
                  i
                  j
                  k
                  ≡
                  1
                  
                    
                    mod
                    
                    2
                  
                
              
            
            
          
        
      
    
    
  

Here, 
  
    
      
        v
        
          |
        
        X
        
          |
        
        
          2
          
            n
          
        
      
    
    
  
 and 
  
    
      
        
          v
          
            i
          
        
        
          
            
              
              
              
                n
                i
              
              
              
            
          
        
        .
      
    
    
  
 The matrices in the Bose-Mesner algebra are 
  
    
      
        
          2
          
            n
          
        
        
          2
          
            n
          
        
      
    
    
  
 matrices, with rows and columns labeled by vectors 
  
    
      
        x
        ∈
        
          
            
              F
            
          
          
            n
          
        
        .
      
    
    
  
 In particular the 
  
    
      
        x
        ,
        y
      
    
    
  
-th entry of 
  
    
      
        
          D
          
            k
          
        
      
    
    
  
 is 
  
    
      
        1
      
    
    
  
 if and only if 
  
    
      
        
          d
          
            H
          
        
        x
        ,
        y
        =
        k
        .
      
    
    

## Related

- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Arbitrarily varying channel]]
- [[Bar product]]
- [[Barker code]]
- [[BCH code]]
- [[Belief propagation]]
- [[Berger code]]
- [[Berlekamp switching game]]
- [[Berlekamp–Welch algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hamming_scheme