---
title: "BIBO stability"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/BIBO_stability"
wikipedia_categories: ["Digital signal processing", "Signal processing", "Stability theory"]
related: ["[[Aliasing]]", "[[Beta encoder]]", "[[Bistritz stability criterion]]", "[[Delay equalization]]", "[[Digital down converter]]", "[[Downsampling (signal processing)]]", "[[First-order hold]]", "[[Half-band filter]]", "[[Instantaneous phase and frequency]]", "[[Least-squares spectral analysis]]"]
---

# BIBO stability

In signal processing, specifically control theory, bounded-input, bounded-output (BIBO) stability is a form of stability for signals and systems that take inputs. If a system is BIBO stable, then the output will be bounded for every input to the system that is bounded.
A signal is bounded if there is a finite value 
  
    
      
        B
        0
      
    
    
  
 such that the signal magnitude never exceeds 
  
    
      
        B
      
    
    
  
, that is

For discrete-time signals: 
  
    
      
        ∃
        B
        ∀
        n
         
        
          |
        
        y
        n
        
          |
        
        ≤
        B
        
        n
        ∈
        
          Z
        
      
    
    
  

For continuous-time signals: 
  
    
      
        ∃
        B
        ∀
        t
         
        
          |
        
        y
        t
        
          |
        
        ≤
        B
        
        t
        ∈
        
          R
        
      
    
    

## Related

- [[Aliasing]]
- [[Beta encoder]]
- [[Bistritz stability criterion]]
- [[Delay equalization]]
- [[Digital down converter]]
- [[Downsampling (signal processing)]]
- [[First-order hold]]
- [[Half-band filter]]
- [[Instantaneous phase and frequency]]
- [[Least-squares spectral analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/BIBO_stability