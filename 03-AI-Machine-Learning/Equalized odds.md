---
title: "Equalized odds"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Equalized_odds"
wikipedia_categories: ["Bias", "Computing and society", "Discrimination", "Ethics stubs", "Information ethics", "Machine learning", "Machine learning stubs", "Philosophy of artificial intelligence"]
related: ["[[Algorithmic bias]]", "[[Fairness (machine learning)]]", "[[Toronto Declaration]]", "[[Astrostatistics]]", "[[Bayesian learning mechanisms]]", "[[Cost-sensitive machine learning]]", "[[Decision list]]", "[[Discrimination against robots]]", "[[Eager learning]]", "[[Expectation propagation]]"]
---

# Equalized odds

Equalized odds, also referred to as conditional procedure accuracy equality and disparate mistreatment, is a measure of fairness in machine learning. A classifier satisfies this definition if the subjects in the protected and unprotected groups have equal true positive rate and equal false positive rate, satisfying the formula:

  
    
      
        P
        R
        +
        
          |
        
        Y
        y
        ,
        A
        a
        =
        P
        R
        +
        
          |
        
        Y
        y
        ,
        A
        b
        
        y
        ∈
        +
        ,
        }
        
        ∀
        a
        ,
        b
        ∈
        A
      
    
    
  

For example, 
  
    
      
        A
      
    
    
  
 could be gender, race, or any other characteristics that we want to be free of bias, while 
  
    
      
        Y
      
    
    
  
 would be whether the person is qualified for the degree, and the output 
  
    
      
        R
      
    
    
  
 would be the school's decision whether to offer the person to study for the degree. In this context, higher university enrollment rates of African Americans compared to whites with similar test scores might be necessary to fulfill the condition of equalized odds, if the "base rate" of 
  
    
      
        Y
      
    
    
  
 differs between the groups.
The concept was originally defined for binary-valued 
  
    
      
        Y
      
    
    
  
. In 2017, Woodworth et al. generalized the concept further for multiple classes.

## Related

- [[Algorithmic bias]]
- [[Fairness (machine learning)]]
- [[Toronto Declaration]]
- [[Astrostatistics]]
- [[Bayesian learning mechanisms]]
- [[Cost-sensitive machine learning]]
- [[Decision list]]
- [[Discrimination against robots]]
- [[Eager learning]]
- [[Expectation propagation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Equalized_odds