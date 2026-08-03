---
title: "Successor cardinal"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Successor_cardinal"
wikipedia_categories: ["Cardinal numbers", "Set theory"]
related: ["[[Cantor's diagonal argument]]", "[[Cantor's theorem]]", "[[Cardinality of the continuum]]", "[[Cofinality]]", "[[Easton's theorem]]", "[[Hartogs number]]", "[[Limit cardinal]]", "[[Tarski's theorem about choice]]", "[[Admissible set]]", "[[Almost]]"]
---

# Successor cardinal

In set theory, one can define a successor operation on cardinal numbers in a similar way to the successor operation on the ordinal numbers. The cardinal successor coincides with the ordinal successor for finite cardinals, but in the infinite case they diverge because every infinite ordinal and its successor have the same cardinality (a bijection can be set up between the two by simply sending the last element of the successor to 0, 0 to 1, etc., and fixing ω and all the elements above; in the style of Hilbert's Hotel Infinity). Using the von Neumann cardinal assignment and the axiom of choice (AC), this successor operation is easy to define: for a cardinal number κ we have

  
    
      
        
          κ
          
          
        
        
          |
          
            inf
            λ
            ∈
            
              O
              n
            
             
            :
             
            κ
            
              |
              λ
              |
            
          
          |
        
      
    
    
  
 ,
where ON is the class of ordinals.  That is, the successor cardinal is the cardinality of the least ordinal into which a set of the given cardinality can be mapped one-to-one, but which cannot be mapped one-to-one back into that set.
That the set above is nonempty follows from  Hartogs' theorem, which says that for any well-orderable cardinal, a larger such cardinal is constructible. The minimum actually exists because the ordinals are well-ordered. It is therefore immediate that there is no cardinal number in between κ and κ+. A successor cardinal is a cardinal that is κ+ for some cardinal κ. In the infinite case, the successor operation skips over many ordinal numbers; in fact, every infinite cardinal is a limit ordinal. Therefore, the successor operation on cardinals gains a lot of power in the infinite case (relative the ordinal successorship operation), and consequently the cardinal numbers are a very "sparse" subclass of the ordinals. We define the sequence of alephs (via the axiom of replacement) via this operation, through all the ordinal numbers as follows:

  
    
      
        
          ℵ
          
            0
          
        
        ω
      
    
    
  

  
    
      
        
          ℵ
          
            α
            1
          
        
        
          ℵ
          
            α
          
          
          
        
      
    
    
  

and for λ an infinite limit ordinal,

  
    
      
        
          ℵ
          
            λ
          
        
        
          ⋃
          
            β
            λ
          
        
        
          ℵ
          
            β
          
        
      
    
    
  

If β is a successor ordinal, then 
  
    
      
        
          ℵ
          
            β
          
        
      
    
    
  
 is  a successor cardinal. Cardinals that are not successor cardinals are called limit cardinals; and by the above definition, if λ is a limit ordinal, then 
  
    
      
        
          ℵ
          
            λ
          
        
      
    
    
  
 is a limit cardinal.
The standard definition above is restricted to the case when the cardinal can be well-ordered, i.e. is finite or an aleph.  Without the axiom of choice, there are cardinals that cannot be well-ordered.  Some mathematicians have defined the successor of such a cardinal as the cardinality of the least ordinal that cannot be mapped one-to-one into a set of the given cardinality.  That is:

  
    
      
        
          κ
          
          
        
        
          |
          
            inf
            λ
            ∈
            
              O
              N
            
             
            :
             
            
              |
            
            λ
            
              |
            
            ≰
            κ
          
          |
        
      
    
    
  

which is the Hartogs number of κ.

## Related

- [[Cantor's diagonal argument]]
- [[Cantor's theorem]]
- [[Cardinality of the continuum]]
- [[Cofinality]]
- [[Easton's theorem]]
- [[Hartogs number]]
- [[Limit cardinal]]
- [[Tarski's theorem about choice]]
- [[Admissible set]]
- [[Almost]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Successor_cardinal