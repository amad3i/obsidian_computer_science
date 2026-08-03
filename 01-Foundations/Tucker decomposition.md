---
title: "Tucker decomposition"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Tucker_decomposition"
wikipedia_categories: ["Dimension reduction", "Statistics stubs"]
related: ["[[Canonical correspondence analysis]]", "[[Generalized multidimensional scaling]]", "[[Local tangent space alignment]]", "[[Multidimensional analysis]]", "[[Sammon mapping]]", "[[Semantic mapping (statistics)]]", "[[Accuracy paradox]]", "[[Aggregate pattern]]", "[[Artificial precision]]", "[[Astrostatistics]]"]
---

# Tucker decomposition

In mathematics, Tucker decomposition decomposes a tensor into a set of matrices and one small core tensor.  It is named after Ledyard R. Tucker
although it goes back to Hitchcock in 1927.
Initially described as a three-mode extension of factor analysis and principal component analysis it may actually be generalized to higher mode analysis, which is also called higher-order singular value decomposition (HOSVD) or the  M-mode SVD.  The algorithm to which the literature typically refers when discussing the Tucker decomposition or the HOSVD is the  M-mode SVD algorithm introduced by Vasilescu and Terzopoulos, but misattributed to Tucker or De Lathauwer etal.
It may be regarded as a more flexible PARAFAC (parallel factor analysis) model.  In PARAFAC the core tensor is restricted to be "diagonal".
In practice, Tucker decomposition is used as a modelling tool. For instance, it is used to model three-way (or higher way) data by means of relatively small numbers of components for each of the three or more modes, and the components are linked to each other by a three- (or higher-) way core array. The model parameters are estimated in such a way that, given fixed numbers of components, the modelled data optimally resemble the actual data in the least squares sense. The model gives a summary of the information in the data, in the same way as principal components analysis does for two-way data.
For a 3rd-order tensor 
  
    
      
        T
        ∈
        
          F
          
            
              n
              
                1
              
            
            
              n
              
                2
              
            
            
              n
              
                3
              
            
          
        
      
    
    
  
, where 
  
    
      
        F
      
    
    
  
 is either 
  
    
      
        
          R
        
      
    
    
  
 or 
  
    
      
        
          C
        
      
    
    
  
, Tucker Decomposition can be denoted as follows, 

  
    
      
        T
        
          
            T
          
        
        
          
            1
          
        
        
          U
          
            1
          
        
        
          
            2
          
        
        
          U
          
            2
          
        
        
          
            3
          
        
        
          U
          
            3
          
        
      
    
    
  

where 
  
    
      
        
          
            T
          
        
        ∈
        
          F
          
            
              d
              
                1
              
            
            
              d
              
                2
              
            
            
              d
              
                3
              
            
          
        
      
    
    
  
 is the core tensor, a 3rd-order tensor that contains the 1-mode, 2-mode and 3-mode singular values of 
  
    
      
        T
      
    
    
  
, which are defined as the Frobenius norm of the 1-mode, 2-mode and 3-mode slices of tensor 
  
    
      
        
          
            T
          
        
      
    
    
  
 respectively. 
  
    
      
        
          U
          
            1
          
        
        ,
        
          U
          
            2
          
        
        ,
        
          U
          
            3
          
        
      
    
    
  
 are unitary matrices in 
  
    
      
        
          F
          
            
              d
              
                1
              
            
            
              n
              
                1
              
            
          
        
        ,
        
          F
          
            
              d
              
                2
              
            
            
              n
              
                2
              
            
          
        
        ,
        
          F
          
            
              d
              
                3
              
            
            
              n
              
                3
              
            
          
        
      
    
    
  
 respectively. The k-mode product (k = 1, 2, 3) of  
  
    
      
        
          
            T
          
        
      
    
    
  
 by 
  
    
      
        
          U
          
            k
          
        
      
    
    
  
 is denoted as 
  
    
      
        
          
            T
          
        
        
          U
          
            k
          
        
      
    
    
  
 with entries as 

  
    
      
        
          
            
              
                
                  
                    T
                  
                
                
                  
                    1
                  
                
                
                  U
                  
                    1
                  
                
                (
                
                  i
                  
                    1
                  
                
                ,
                
                  j
                  
                    2
                  
                
                ,
                
                  j
                  
                    3
                  
                
              
              
                
                
                  ∑
                  
                    
                      j
                      
                        1
                      
                    
                    1
                  
                  
                    
                      d
                      
                        1
                      
                    
                  
                
                
                  
                    T
                  
                
                
                  j
                  
                    1
                  
                
                ,
                
                  j
                  
                    2
                  
                
                ,
                
                  j
                  
                    3
                  
                
                
                  U
                  
                    1
                  
                
                
                  j
                  
                    1
                  
                
                ,
                
                  i
                  
                    1
                  
                
              
            
            
              
                
                  
                    T
                  
                
                
                  
                    2
                  
                
                
                  U
                  
                    2
                  
                
                (
                
                  j
                  
                    1
                  
                
                ,
                
                  i
                  
                    2
                  
                
                ,
                
                  j
                  
                    3
                  
                
              
              
                
                
                  ∑
                  
                    
                      j
                      
                        2
                      
                    
                    1
                  
                  
                    
                      d
                      
                        2
                      
                    
                  
                
                
                  
                    T
                  
                
                
                  j
                  
                    1
                  
                
                ,
                
                  j
                  
                    2
                  
                
                ,
                
                  j
                  
                    3
                  
                
                
                  U
                  
                    2
                  
                
                
                  j
                  
                    2
                  
                
                ,
                
                  i
                  
                    2
                  
                
              
            
            
              
                
                  
                    T
                  
                
                
                  
                    3
                  
                
                
                  U
                  
                    3
                  
                
                (
                
                  j
                  
                    1
                  
                
                ,
                
                  j
                  
                    2
                  
                
                ,
                
                  i
                  
                    3
                  
                
              
              
                
                
                  ∑
                  
                    
                      j
                      
                        3
                      
                    
                    1
                  
                  
                    
                      d
                      
                        3
                      
                    
                  
                
                
                  
                    T
                  
                
                
                  j
                  
                    1
                  
                
                ,
                
                  j
                  
                    2
                  
                
                ,
                
                  j
                  
                    3
                  
                
                
                  U
                  
                    3
                  
                
                
                  j
                  
                    3
                  
                
                ,
                
                  i
                  
                    3
                  
                
              
            
          
        
      
    
    
  

Altogether, the decomposition may also be written more directly as

  
    
      
        T
        
          i
          
            1
          
        
        ,
        
          i
          
            2
          
        
        ,
        
          i
          
            3
          
        
        =
        
          ∑
          
            
              j
              
                1
              
            
            1
          
          
            
              d
              
                1
              
            
          
        
        
          ∑
          
            
              j
              
                2
              
            
            1
          
          
            
              d
              
                2
              
            
          
        
        
          ∑
          
            
              j
              
                3
              
            
            1
          
          
            
              d
              
                3
              
            
          
        
        
          
            T
          
        
        
          j
          
            1
          
        
        ,
        
          j
          
            2
          
        
        ,
        
          j
          
            3
          
        
        
          U
          
            1
          
        
        
          j
          
            1
          
        
        ,
        
          i
          
            1
          
        
        
          U
          
            2
          
        
        
          j
          
            2
          
        
        ,
        
          i
          
            2
          
        
        
          U
          
            3
          
        
        
          j
          
            3
          
        
        ,
        
          i
          
            3
          
        
      
    
    
  

Taking 
  
    
      
        
          d
          
            i
          
        
        
          n
          
            i
          
        
      
    
    
  
 for all 
  
    
      
        i
      
    
    
  
 is always sufficient to represent 
  
    
      
        T
      
    
    
  
 exactly, but often 
  
    
      
        T
      
    
    
  
 can be compressed or efficiently approximately by choosing 
  
    
      
        
          d
          
            i
          
        
        
          n
          
            i
          
        
      
    
    
  
. A common choice is 
  
    
      
        
          d
          
            1
          
        
        
          d
          
            2
          
        
        
          d
          
            3
          
        
        min
        
          n
          
            1
          
        
        ,
        
          n
          
            2
          
        
        ,
        
          n
          
            3
          
        
      
    
    
  
, which can be effective when the difference in dimension sizes is large.
There are two special cases of Tucker decomposition:
Tucker1: if 
  
    
      
        
          U
          
            2
          
        
      
    
    
  
 and 
  
    
      
        
          U
          
            3
          
        
      
    
    
  
 are identity, then 
  
    
      
        T
        
          
            T
          
        
        
          
            1
          
        
        
          U
          
            1
          
        
      
    
    
  
 
Tucker2: if 
  
    
      
        
          U
          
            3
          
        
      
    
    
  
 is identity, then 
  
    
      
        T
        
          
            T
          
        
        
          
            1
          
        
        
          U
          
            1
          
        
        
          
            2
          
        
        
          U
          
            2
          
        
      
    
    
  
 .
RESCAL decomposition  can be seen as a special case of Tucker where 
  
    
      
        
          U
          
            3
          
        
      
    
    
  
 is identity and 
  
    
      
        
          U
          
            1
          
        
      
    
    
  
 is equal to 
  
    
      
        
          U
          
            2
          
        
      
    
    
  
 .

*(note truncated for size; full article at the source link below)*

## Related

- [[Canonical correspondence analysis]]
- [[Generalized multidimensional scaling]]
- [[Local tangent space alignment]]
- [[Multidimensional analysis]]
- [[Sammon mapping]]
- [[Semantic mapping (statistics)]]
- [[Accuracy paradox]]
- [[Aggregate pattern]]
- [[Artificial precision]]
- [[Astrostatistics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tucker_decomposition