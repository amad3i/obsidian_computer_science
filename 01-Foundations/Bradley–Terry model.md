---
title: "Bradley–Terry model"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Bradley–Terry_model"
wikipedia_categories: ["Logistic regression", "Machine learning", "Regression models", "Statistical models"]
related: ["[[Data-driven model]]", "[[EM algorithm and GMM model]]", "[[Energy-based model]]", "[[Flow-based generative model]]", "[[Generative model]]", "[[Local case-control sampling]]", "[[Logistic regression]]", "[[Multinomial logistic regression]]", "[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]"]
---

# Bradley–Terry model

The Bradley–Terry model is a probability model for the outcome of pairwise comparisons between items, teams, or objects. Given a pair of items i and j drawn from some population, it estimates the probability that the pairwise comparison i > j turns out true, as

where pi is a positive real-valued score assigned to individual i. The comparison i > j can be read as "i is preferred to j", "i ranks higher than j", or "i beats j", depending on the application.
For example, pi might represent the skill of a team in a sports tournament and 
  
    
      
        Pr
        i
        j
      
    
    
  
 the probability that i wins a game against j. Or pi might represent the quality or desirability of a commercial product and 
  
    
      
        Pr
        i
        j
      
    
    
  
 the probability that a consumer will prefer product i over product j.
The Bradley–Terry model can be used in the forward direction to predict outcomes, as described, but is more commonly used in reverse to infer the scores pi given an observed set of outcomes. In this type of application pi represents some measure of the strength or quality of 
  
    
      
        i
      
    
    
  
 and the model lets us estimate the strengths from a series of pairwise comparisons.  In a survey of wine preferences, for instance, it might be difficult for respondents to give a complete ranking of a large set of wines, but relatively easy for them to compare sample pairs of wines and say which they feel is better.  Based on a set of such pairwise comparisons, the Bradley–Terry model can then be used to derive a full ranking of the wines.
Once the values of the scores pi have been calculated, the model can then also be used in the forward direction, for instance to predict the likely outcome of comparisons that have not yet actually occurred.  In the wine survey example, for instance, one could calculate the probability that someone will prefer wine 
  
    
      
        i
      
    
    
  
 over wine 
  
    
      
        j
      
    
    
  
, even if no one in the survey directly compared that particular pair.

## Related

- [[Data-driven model]]
- [[EM algorithm and GMM model]]
- [[Energy-based model]]
- [[Flow-based generative model]]
- [[Generative model]]
- [[Local case-control sampling]]
- [[Logistic regression]]
- [[Multinomial logistic regression]]
- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bradley–Terry_model