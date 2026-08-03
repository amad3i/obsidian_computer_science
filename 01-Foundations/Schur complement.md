---
title: "Schur complement"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Schur_complement"
wikipedia_categories: ["Issai Schur", "Linear algebra"]
related: ["[[3D projection]]", "[[Absolutely convex set]]", "[[Adjugate matrix]]", "[[Affine space]]", "[[Amitsur–Levitzki theorem]]", "[[Angles between flats]]", "[[Annihilating polynomial]]", "[[Antilinear map]]", "[[Antiunitary operator]]", "[[Asymmetric norm]]"]
---

# Schur complement

The Schur complement is a key tool in the fields of linear algebra, the theory of matrices, numerical analysis, and statistics.
It is defined for a block matrix. Suppose p, q are nonnegative integers such that p + q > 0, and suppose A, B, C, D are respectively p × p, p × q, q × p, and q × q matrices of complex numbers. Let

  
    
      
        M
        
          
            
              
                
                  A
                
                
                  B
                
              
              
                
                  C
                
                
                  D
                
              
            
          
        
      
    
    
  

so that M is a (p + q) × (p + q) matrix.
If D is invertible, then the Schur complement of the block D of the matrix M is the p × p matrix defined by

  
    
      
        M
        
          /
        
        D
        :=
        A
        B
        
          D
          
            1
          
        
        C
        .
      
    
    
  

If A is invertible, the Schur complement of the block A of the matrix M is the q × q matrix defined by

  
    
      
        M
        
          /
        
        A
        :=
        D
        C
        
          A
          
            1
          
        
        B
        .
      
    
    
  

In the case that A or D is singular, substituting a generalized inverse for the inverses on M/A and M/D yields the generalized Schur complement.
The Schur complement is named after Issai Schur who used it to prove Schur's lemma, although it had been used previously.  Emilie Virginia Haynsworth was the first to call it the Schur complement. The Schur complement is sometimes referred to as the Feshbach map after a physicist Herman Feshbach.

## Related

- [[3D projection]]
- [[Absolutely convex set]]
- [[Adjugate matrix]]
- [[Affine space]]
- [[Amitsur–Levitzki theorem]]
- [[Angles between flats]]
- [[Annihilating polynomial]]
- [[Antilinear map]]
- [[Antiunitary operator]]
- [[Asymmetric norm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Schur_complement