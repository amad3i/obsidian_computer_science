---
title: "Lift (data mining)"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Lift_(data_mining)"
wikipedia_categories: ["Data mining"]
related: ["[[Action model learning]]", "[[Adamic–Adar index]]", "[[Affinity analysis]]", "[[Agent mining]]", "[[AMiner (database)]]", "[[Anomaly detection]]", "[[Archetypal analysis]]", "[[Argument mining]]", "[[Association rule learning]]", "[[Astrostatistics]]"]
---

# Lift (data mining)

In data mining and association rule learning, lift is a measure of the performance of a targeting model (association rule) at predicting or classifying cases as having an enhanced response (with respect to the population as a whole), measured against a random choice targeting model. A targeting model is doing a good job if the response 
  
    
      
        P
        B
        ∣
        T
      
    
    
  
 within the target (
  
    
      
        T
      
    
    
  
) is much better than the baseline (
  
    
      
        P
        B
      
    
    
  
) average for the population as a whole. Lift is simply the ratio of these values: target response divided by average response. Mathematically,

  
    
      
        lift
        
          
            
              P
              B
              ∣
              T
            
            
              P
              B
            
          
        
        
          
            
              P
              T
              ∧
              B
            
            
              P
              T
              P
              B
            
          
        
      
    
    
  

For example, suppose a population has an average response rate of 5%, but a certain model (or rule) has identified a segment with a response rate of 20%. Then that segment would have a lift of 4.0 (20%/5%).
Lift is also the ratio of precision and prevalence as shown in this chart:

Because lift is the ratio of precision and prevalence, and prevalence does not change with target set selection, lift is proportional to precision. Thus the lift curve, which plots lift vs recall (i.e., capture) is identical in shape to the precision-recall curve. The lift curve will always end at the point (1, 1) or (100%, 1) in the bottom-right corner, just as the precision-recall curve ends at the point (1/P(B), 1). This point corresponds to selecting the entire population as the target set.
Like the precision-recall curve, the lift curve shows a similar tradeoff as the receiver operating characteristic (ROC) curve. It is also similar to the curve known in econometrics as the Lorenz or power curve.

## Related

- [[Action model learning]]
- [[Adamic–Adar index]]
- [[Affinity analysis]]
- [[Agent mining]]
- [[AMiner (database)]]
- [[Anomaly detection]]
- [[Archetypal analysis]]
- [[Argument mining]]
- [[Association rule learning]]
- [[Astrostatistics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Lift_(data_mining)