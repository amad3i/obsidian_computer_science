---
title: "Blackman's theorem"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Blackman's_theorem"
wikipedia_categories: ["Control engineering", "Electronic amplifiers", "Electronic feedback", "Engineering stubs", "Signal processing"]
related: ["[[Asymptotic gain model]]", "[[Bode plot]]", "[[Phase margin]]", "[[Routh–Hurwitz stability criterion]]", "[[Masreliez's theorem]]", "[[Parasitic oscillation]]", "[[Return ratio]]", "[[Self-tuning]]", "[[Step response]]", "[[Transfer function matrix]]"]
---

# Blackman's theorem

Blackman's theorem is a general procedure for calculating the change in an impedance due to feedback in a circuit. It was published by Ralph Beebe Blackman in 1943, was connected to signal-flow analysis by John Choma, and was made popular in the extra element theorem by R. D. Middlebrook and the asymptotic gain model of Solomon Rosenstark. Blackman's approach leads to the formula for the impedance Z between two selected terminals of a negative feedback amplifier as Blackman's formula:

  
    
      
        Z
        
          Z
          
            D
          
        
        
          
            
              1
              
                T
                
                  S
                  C
                
              
            
            
              1
              
                T
                
                  O
                  C
                
              
            
          
        
         
        ,
      
    
    
  

where ZD = impedance with the feedback disabled, TSC = loop transmission with a small-signal short across the selected terminal pair, and TOC = loop transmission with an open circuit across the terminal pair. The loop transmission also is referred to as the return ratio. Blackman's formula can be compared with Middlebrook's result for the input impedance Zin of a circuit based upon the extra-element theorem:

  
    
      
        
          Z
          
            i
            n
          
        
        
          Z
          
            i
            n
          
          
            ∞
          
        
        
          
            
              
                1
                
                  Z
                  
                    e
                  
                  
                    0
                  
                
                
                  /
                
                Z
              
              
                1
                
                  Z
                  
                    e
                  
                  
                    ∞
                  
                
                
                  /
                
                Z
              
            
          
        
      
    
    
  

where:

  
    
      
        Z
         
      
    
    
  
 is the impedance of the extra element; 
  
    
      
        
          Z
          
            i
            n
          
          
            ∞
          
        
      
    
    
  
 is the input impedance with 
  
    
      
        Z
         
      
    
    
  
 removed (or made infinite); 
  
    
      
        
          Z
          
            e
          
          
            0
          
        
      
    
    
  
 is the impedance seen by the extra element 
  
    
      
        Z
         
      
    
    
  
 with the input shorted (or made zero); 
  
    
      
        
          Z
          
            e
          
          
            ∞
          
        
      
    
    
  
 is the impedance seen by the extra element 
  
    
      
        Z
         
      
    
    
  
 with the input open (or made infinite).
Blackman's formula also can be compared with Choma's signal-flow result:

  
    
      
        
          Z
          
            S
            S
          
        
        
          Z
          
            S
            0
          
        
        
          
            
              
                1
                
                  T
                  
                    I
                  
                
              
              
                1
                
                  T
                  
                    Z
                  
                
              
            
          
        
         
        ,
      
    
    
  

where 
  
    
      
        
          Z
          
            S
            0
          
        
         
      
    
    
  
 is the value of 
  
    
      
        
          Z
          
            S
            S
          
        
         
      
    
    
  
 under the condition that a selected parameter P is set to zero, return ratio 
  
    
      
        
          T
          
            Z
          
        
         
      
    
    
  
 is evaluated with zero excitation and 
  
    
      
        
          T
          
            I
          
        
         
      
    
    
  
 is 
  
    
      
        
          T
          
            Z
          
        
         
      
    
    
  
 for the case of short-circuited source resistance. As with the extra-element result, differences are in the perspective leading to the formula.

## Related

- [[Asymptotic gain model]]
- [[Bode plot]]
- [[Phase margin]]
- [[Routh–Hurwitz stability criterion]]
- [[Masreliez's theorem]]
- [[Parasitic oscillation]]
- [[Return ratio]]
- [[Self-tuning]]
- [[Step response]]
- [[Transfer function matrix]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Blackman's_theorem