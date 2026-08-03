---
title: "Typing environment"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Typing_environment"
wikipedia_categories: ["Data types", "Program analysis", "Programming language theory stubs", "Type theory"]
related: ["[[Typing rule]]", "[[Flow-sensitive typing]]", "[[Type system]]", "[[Abstract data type]]", "[[Algebraic data type]]", "[[Any type]]", "[[Bottom type]]", "[[Composite data type]]", "[[Container (type theory)]]", "[[Effect system]]"]
---

# Typing environment

In type theory, a typing environment (or typing context) represents the association between variable names and data types.
More formally, an environment 
  
    
      
        Γ
      
    
    
  
 is a set or ordered list of pairs 
  
    
      
        ⟨
        x
        ,
        τ
        ⟩
      
    
    
  
, usually written as 
  
    
      
        x
        :
        τ
      
    
    
  
, where 
  
    
      
        x
      
    
    
  
 is a variable and 
  
    
      
        τ
      
    
    
  
 its type.
The judgement

  
    
      
        Γ
        ⊢
        e
        :
        τ
      
    
    
  

is read as "
  
    
      
        e
      
    
    
  
 has type 
  
    
      
        τ
      
    
    
  
 in context 
  
    
      
        Γ
      
    
    
  
 ".
For each function body type checks:

  
    
      
        Γ
        {
        f
        ,
        
          τ
          
            1
          
        
        .
        .
        .
        
          τ
          
            n
          
        
        →
        
          τ
          
            0
          
        
        
          |
        
        f
        ,
        x
        s
        ,
        
          τ
          
            1
          
        
        ,
        .
        .
        .
        ,
        
          τ
          
            n
          
        
        ,
        
          t
          
            f
          
        
        ,
        
          τ
          
            0
          
        
        ∈
        e
      
    
    
  

Typing Rules Example:

  
    
      
        
          
            
              
                Γ
                ⊢
                b
                :
                B
                o
                o
                l
                ,
                Γ
                ⊢
                
                  t
                  
                    1
                  
                
                :
                τ
                ,
                Γ
                ⊢
                
                  t
                  
                    2
                  
                
                :
                τ
              
            
            
              
                Γ
                ⊢
                
                  if
                
                b
                
                  t
                  
                    1
                  
                
                
                  else
                
                
                  t
                  
                    2
                  
                
                :
                τ
              
            
          
        
      
    
    
  

In statically typed programming languages, these environments are used and maintained by typing rules to type check a given program or expression.

## Related

- [[Typing rule]]
- [[Flow-sensitive typing]]
- [[Type system]]
- [[Abstract data type]]
- [[Algebraic data type]]
- [[Any type]]
- [[Bottom type]]
- [[Composite data type]]
- [[Container (type theory)]]
- [[Effect system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Typing_environment