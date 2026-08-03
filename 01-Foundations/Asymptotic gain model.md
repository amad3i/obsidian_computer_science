---
title: "Asymptotic gain model"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Asymptotic_gain_model"
wikipedia_categories: ["Analog circuits", "Control theory", "Electronic amplifiers", "Electronic feedback", "Signal processing"]
related: ["[[Blackman's theorem]]", "[[Bode plot]]", "[[Negative feedback]]", "[[Norator]]", "[[Nullator]]", "[[Nullor]]", "[[Parasitic oscillation]]", "[[Phase margin]]", "[[Return ratio]]", "[[Routh–Hurwitz stability criterion]]"]
---

# Asymptotic gain model

The asymptotic gain model (also known as the Rosenstark method) is a representation of the gain of negative feedback amplifiers given by the asymptotic gain relation:

  
    
      
        G
        
          G
          
            ∞
          
        
        
          
            
              T
              
                T
                1
              
            
          
        
        
          G
          
            0
          
        
        
          
            
              1
              
                T
                1
              
            
          
        
         
        ,
      
    
    
  

where 
  
    
      
        T
      
    
    
  
 is the return ratio with the input source disabled (equal to the negative of the loop gain in the case of a single-loop system composed of unilateral blocks), G∞ is the asymptotic gain and G0 is the direct transmission term. This form for the gain can provide intuitive insight into the circuit and often is easier to derive than a direct attack on the gain.

Figure 1 shows a block diagram that leads to the asymptotic gain expression. The asymptotic gain relation also can be expressed as a signal flow graph. See Figure 2. The asymptotic gain model is a special case of the extra element theorem.

As follows directly from limiting cases of the gain expression, the asymptotic gain G∞ is simply the gain of the system when the return ratio approaches infinity:

  
    
      
        
          G
          
            ∞
          
        
        G
         
        
          
            
              |
            
          
          
            T
            →
            ∞
          
        
         
        ,
      
    
    
  

while the direct transmission term G0 is the gain of the system when the return ratio is zero:

  
    
      
        
          G
          
            0
          
        
        G
         
        
          
            
              |
            
          
          
            T
            →
            0
          
        
         
        .
      
    
    

## Related

- [[Blackman's theorem]]
- [[Bode plot]]
- [[Negative feedback]]
- [[Norator]]
- [[Nullator]]
- [[Nullor]]
- [[Parasitic oscillation]]
- [[Phase margin]]
- [[Return ratio]]
- [[Routh–Hurwitz stability criterion]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Asymptotic_gain_model