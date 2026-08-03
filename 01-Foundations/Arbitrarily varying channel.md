---
title: "Arbitrarily varying channel"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Arbitrarily_varying_channel"
wikipedia_categories: ["Coding theory"]
related: ["[[Algebraic geometry code]]", "[[Alternant code]]", "[[Bar product]]", "[[Barker code]]", "[[BCH code]]", "[[Belief propagation]]", "[[Berger code]]", "[[Berlekamp switching game]]", "[[Berlekamp–Welch algorithm]]", "[[Binary erasure channel]]"]
---

# Arbitrarily varying channel

An arbitrarily varying channel (AVC) is a communication channel model used in coding theory, and was first introduced by Blackwell, Breiman, and Thomasian.  This particular channel has unknown parameters that can change over time and these changes may not have a uniform pattern during the transmission of a codeword. 
  
    
      
        
          n
        
      
    
    
  
 uses of this channel can be described using a stochastic matrix 
  
    
      
        
          
            W
            
              n
            
          
          :
          
            X
            
              n
            
          
        
      
    
    
  
 
  
    
      
        
          
            S
            
              n
            
          
          →
          
            Y
            
              n
            
          
        
      
    
    
  
, where 
  
    
      
        
          X
        
      
    
    
  
 is the input alphabet, 
  
    
      
        
          Y
        
      
    
    
  
 is the output alphabet, and 
  
    
      
        
          
            W
            
              n
            
          
          y
          
            |
          
          x
          ,
          s
        
      
    
    
  
 is the probability over a given set of states 
  
    
      
        
          S
        
      
    
    
  
, that the transmitted input 
  
    
      
        
          x
          (
          
            x
            
              1
            
          
          ,
          …
          ,
          
            x
            
              n
            
          
        
      
    
    
  
 leads to the received output 
  
    
      
        
          y
          (
          
            y
            
              1
            
          
          ,
          …
          ,
          
            y
            
              n
            
          
        
      
    
    
  
.  The state 
  
    
      
        
          
            s
            
              i
            
          
        
      
    
    
  
 in set 
  
    
      
        
          S
        
      
    
    
  
 can vary arbitrarily at each time unit 
  
    
      
        
          i
        
      
    
    
  
.  This channel was developed as an alternative to Shannon's Binary Symmetric Channel (BSC), where the entire nature of the channel is known, to be more realistic to actual network channel situations.

## Related

- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Bar product]]
- [[Barker code]]
- [[BCH code]]
- [[Belief propagation]]
- [[Berger code]]
- [[Berlekamp switching game]]
- [[Berlekamp–Welch algorithm]]
- [[Binary erasure channel]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Arbitrarily_varying_channel