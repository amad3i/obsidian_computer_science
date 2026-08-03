---
title: "Varimax rotation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Varimax_rotation"
wikipedia_categories: ["Factor analysis", "Statistics stubs"]
related: ["[[Principal geodesic analysis]]", "[[Accuracy paradox]]", "[[Aggregate pattern]]", "[[Artificial precision]]", "[[Astrostatistics]]", "[[Bayesian inference using Gibbs sampling]]", "[[Biplot]]", "[[Blumenthal's zero–one law]]", "[[Canonical correspondence analysis]]", "[[Combinatorial data analysis]]"]
---

# Varimax rotation

In statistics, a varimax rotation is used to simplify the expression of a particular sub-space in terms of just a few major items each.  The actual coordinate system is unchanged, it is the orthogonal basis that is being rotated to align with those coordinates.  The sub-space found with principal component analysis or factor analysis is expressed as a dense basis with many non-zero weights which makes it hard to interpret.  Varimax is so called because it maximizes the sum of the variances of the squared loadings (squared correlations between variables and factors). Preserving orthogonality requires that it is a rotation that leaves the sub-space invariant. Intuitively, this is achieved if, (a) any given variable has a high loading on a single factor but near-zero loadings on the remaining factors and if (b) any given factor is constituted by only a few variables with very high loadings on this factor while the remaining variables have near-zero loadings on this factor.  If these conditions hold, the factor loading matrix is said to have "simple structure," and varimax rotation brings the loading matrix closer to such simple structure (as much as the data allow).  From the perspective of individuals measured on the variables, varimax seeks a basis that most economically represents each individual—that is, each individual can be well described by a linear combination of only a few basis functions.
One way of expressing the varimax criterion formally is this:

  
    
      
        
          R
          
            
              V
              A
              R
              I
              M
              A
              X
            
          
        
        arg
         
        
          max
          
            R
          
        
        
          
            
              
                1
                p
              
            
            
              ∑
              
                j
                1
              
              
                k
              
            
            
              ∑
              
                i
                1
              
              
                p
              
            
            Λ
            R
            
              
                i
                j
              
              
                4
              
            
            
              ∑
              
                j
                1
              
              
                k
              
            
            
              
                
                  
                    
                      1
                      p
                    
                  
                  
                    ∑
                    
                      i
                      1
                    
                    
                      p
                    
                  
                  Λ
                  R
                  
                    
                      i
                      j
                    
                    
                      2
                    
                  
                
              
              
                2
              
            
          
        
        .
      
    
    
  

Suggested by Henry Felix Kaiser in 1958,
it is a popular scheme for orthogonal rotation (where all factors remain uncorrelated with one another).

## Related

- [[Principal geodesic analysis]]
- [[Accuracy paradox]]
- [[Aggregate pattern]]
- [[Artificial precision]]
- [[Astrostatistics]]
- [[Bayesian inference using Gibbs sampling]]
- [[Biplot]]
- [[Blumenthal's zero–one law]]
- [[Canonical correspondence analysis]]
- [[Combinatorial data analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Varimax_rotation