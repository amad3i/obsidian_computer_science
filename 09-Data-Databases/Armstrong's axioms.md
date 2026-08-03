---
title: "Armstrong's axioms"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Armstrong's_axioms"
wikipedia_categories: ["Data modeling", "Database management systems", "Database normalization"]
related: ["[[Database normalization]]", "[[Anchor modeling]]", "[[Bitemporal modeling]]", "[[Candidate key]]", "[[Column (database)]]", "[[Data control language]]", "[[Data query language]]", "[[Database object]]", "[[Foreign key]]", "[[Lossless join decomposition]]"]
---

# Armstrong's axioms

Armstrong's axioms are a set of axioms (or, more precisely, inference rules) used to infer all the functional dependencies on a relational database. They were developed by William W. Armstrong in his 1974 paper. The axioms are sound in generating only functional dependencies in the closure of a set of functional dependencies (denoted as  
  
    
      
        
          F
          
          
        
      
    
    
  
) when applied to that set (denoted as 
  
    
      
        F
      
    
    
  
). They are also complete in that repeated application of these rules will generate all functional dependencies in the closure 
  
    
      
        
          F
          
          
        
      
    
    
  
.
More formally, let 
  
    
      
        ⟨
        R
        U
        ,
        F
        ⟩
      
    
    
  
 denote a relational scheme over the set of attributes 
  
    
      
        U
      
    
    
  
 with a set of functional dependencies 
  
    
      
        F
      
    
    
  
. We say that a functional dependency 
  
    
      
        f
      
    
    
  
 is logically implied by 
  
    
      
        F
      
    
    
  
, and denote it with 
  
    
      
        F
        ⊨
        f
      
    
    
  
 if and only if for every instance 
  
    
      
        r
      
    
    
  
 of 
  
    
      
        R
      
    
    
  
 that satisfies the functional dependencies in 
  
    
      
        F
      
    
    
  
, 
  
    
      
        r
      
    
    
  
 also satisfies 
  
    
      
        f
      
    
    
  
. We denote by 
  
    
      
        
          F
          
          
        
      
    
    
  
 the set of all functional dependencies that are logically implied by 
  
    
      
        F
      
    
    
  
.
Furthermore, with respect to a set of inference rules 
  
    
      
        A
      
    
    
  
, we say that a functional dependency 
  
    
      
        f
      
    
    
  
 is derivable from the functional dependencies in 
  
    
      
        F
      
    
    
  
 by the set of inference rules 
  
    
      
        A
      
    
    
  
, and we denote it by 
  
    
      
        F
        
          ⊢
          
            A
          
        
        f
      
    
    
  
 if and only if 
  
    
      
        f
      
    
    
  
 is obtainable by means of repeatedly applying the inference rules in 
  
    
      
        A
      
    
    
  
 to functional dependencies in 
  
    
      
        F
      
    
    
  
. We denote by 
  
    
      
        
          F
          
            A
          
          
          
        
      
    
    
  
 the set of all functional dependencies that are derivable from 
  
    
      
        F
      
    
    
  
 by inference rules in 
  
    
      
        A
      
    
    
  
.
Then, a set of inference rules 
  
    
      
        A
      
    
    
  
 is sound if and only if the following holds:

  
    
      
        
          F
          
            A
          
          
          
        
        ⊆
        
          F
          
          
        
      
    
    
  

that is to say, we cannot derive by means of 
  
    
      
        A
      
    
    
  
 functional dependencies that are not logically implied by 
  
    
      
        F
      
    
    
  
.
The set of inference rules 
  
    
      
        A
      
    
    
  
 is said to be complete if the following holds:

  
    
      
        
          F
          
          
        
        ⊆
        
          F
          
            A
          
          
          
        
      
    
    
  

more simply put, we are able to derive by 
  
    
      
        A
      
    
    
  
 all the functional dependencies that are logically implied by 
  
    
      
        F
      
    
    
  
.

## Related

- [[Database normalization]]
- [[Anchor modeling]]
- [[Bitemporal modeling]]
- [[Candidate key]]
- [[Column (database)]]
- [[Data control language]]
- [[Data query language]]
- [[Database object]]
- [[Foreign key]]
- [[Lossless join decomposition]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Armstrong's_axioms