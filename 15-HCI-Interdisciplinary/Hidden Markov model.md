---
title: "Hidden Markov model"
tags: ["cs", "hci-interdisciplinary", "intermediate"]
domain: HCI & Interdisciplinary
level: intermediate
source: "https://en.wikipedia.org/wiki/Hidden_Markov_model"
wikipedia_categories: ["Bioinformatics", "Hidden Markov models", "Markov models"]
related: ["[[Adaptive sampling]]", "[[Folding@home]]", "[[Gene prediction]]", "[[Models of DNA evolution]]", "[[Multiple sequence alignment]]", "[[100,000 Genomes Project]]", "[[1000 Genomes Project]]", "[[3D-Jury]]", "[[ABCD Schema]]", "[[Accession number (bioinformatics)]]"]
---

# Hidden Markov model

In probability theory, a hidden Markov model (HMM) is a Markov model in which the observations are dependent on a latent (or hidden) Markov process (referred to as 
  
    
      
        X
      
    
    
  
). An HMM requires that there be an observable process 
  
    
      
        Y
      
    
    
  
 whose outcomes depend on the outcomes of 
  
    
      
        X
      
    
    
  
 in a known way. Since 
  
    
      
        X
      
    
    
  
 cannot be observed directly, the goal is to learn about state of 
  
    
      
        X
      
    
    
  
 by observing 
  
    
      
        Y
      
    
    
  
. By definition of being a Markov model, an HMM has an additional requirement that the outcome of 
  
    
      
        Y
      
    
    
  
 at time 
  
    
      
        t
        
          t
          
            0
          
        
      
    
    
  
 must be "influenced" exclusively by the outcome of 
  
    
      
        X
      
    
    
  
 at 
  
    
      
        t
        
          t
          
            0
          
        
      
    
    
  
 and that the outcomes of 
  
    
      
        X
      
    
    
  
 and 
  
    
      
        Y
      
    
    
  
 at 
  
    
      
        t
        
          t
          
            0
          
        
      
    
    
  
 must be conditionally independent of 
  
    
      
        Y
      
    
    
  
 at 
  
    
      
        t
        
          t
          
            0
          
        
      
    
    
  
 given 
  
    
      
        X
      
    
    
  
 at time 
  
    
      
        t
        
          t
          
            0
          
        
      
    
    
  
. Estimation of the parameters in an HMM can be performed using maximum likelihood estimation. For linear chain HMMs, the Baum–Welch algorithm can be used to estimate parameters.
Hidden Markov models are known for their applications to thermodynamics, statistical mechanics, physics, chemistry, economics, finance, signal processing, information theory, pattern recognition—such as speech recognition, handwriting recognition, gesture recognition, part-of-speech tagging, musical score following, partial discharges and bioinformatics.

## Related

- [[Adaptive sampling]]
- [[Folding@home]]
- [[Gene prediction]]
- [[Models of DNA evolution]]
- [[Multiple sequence alignment]]
- [[100,000 Genomes Project]]
- [[1000 Genomes Project]]
- [[3D-Jury]]
- [[ABCD Schema]]
- [[Accession number (bioinformatics)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Hidden_Markov_model