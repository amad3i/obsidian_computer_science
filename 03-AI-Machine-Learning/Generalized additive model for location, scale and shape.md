---
title: "Generalized additive model for location, scale and shape"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Generalized_additive_model_for_location,_scale_and_shape"
wikipedia_categories: ["Generalized linear models", "Machine learning", "Semi-parametric models"]
related: ["[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]", "[[AIOps]]", "[[AIXI]]", "[[Algorithm selection]]"]
---

# Generalized additive model for location, scale and shape

The  generalized additive model for location, scale and shape (GAMLSS) is a distributional regression model in which a parametric statistical distribution is assumed for the response (target) variable but the parameters of this distribution can vary according to explanatory variables. Therefore the shape of this distribution for the target variable can change with explanatory variables.
GAMLSS is an input output model, i.e. 
  
    
      
        X
        →
        Y
      
    
    
  
  but differs from the classical model in that the input X  affects the distribution of the target variable as a whole  not just the mean, i.e. 
  
    
      
        X
        →
        D
        Y
        
          |
        
        X
      
    
    
  
.
GAMLSS allows flexible regression by using smoothing or machine learning techniques to model the parameters of the target variable (response). GAMLSS assumes the response variable could follows any theoretical parametric distribution, which might be heavy or light-tailed, and positively or negatively skewed. In addition, all the parameters of the distribution which often are location (e.g., mean), scale (e.g., variance) and shape (skewness and kurtosis) – can be modelled as linear, nonlinear or using algorithm modelling functions of the explanatory variables. The distributional assumption for the target variables can be checked through diagnostic plots like Q–Q plot or worm plot. GAMLSS is a supervised machine learning model since the target value (the output) is always present.

## Related

- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]
- [[Adversarial machine learning]]
- [[AI data center]]
- [[AI observability]]
- [[AIOps]]
- [[AIXI]]
- [[Algorithm selection]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Generalized_additive_model_for_location,_scale_and_shape