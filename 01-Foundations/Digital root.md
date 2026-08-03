---
title: "Digital root"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Digital_root"
wikipedia_categories: ["Algebra", "Arithmetic dynamics", "Base-dependent integer sequences", "Number theory"]
related: ["[[Multiplicative digital root]]", "[[Automorphic number]]", "[[Digit sum]]", "[[Kaprekar number]]", "[[3x + 1 semigroup]]", "[[AWM–Microsoft Research Prize in Algebra and Number Theory]]", "[[Cole Prize]]", "[[Cyclotomic polynomial]]", "[[Euler's totient function]]", "[[Hundred Fowls Problem]]"]
---

# Digital root

The digital root (also repeated digital sum) of a natural number in a given radix is the (single digit) value obtained by an iterative process of summing digits, on each iteration using the result from the previous iteration to compute a digit sum. The process continues until a single-digit number is reached. For example, in base 10, the digital root of the number 12345 is 6 because the sum of the digits in the number is 1 + 2 + 3 + 4 + 5 = 15, then the addition process is repeated again for the resulting number 15, so that the sum of 1 + 5 equals 6, which is the digital root of that number. In base 10, this is equivalent to taking the remainder upon division by 9 (except when the digital root is 9, where the remainder upon division by 9 will be 0), which allows it to be used as a divisibility rule. The formula for the function 
  
    
      
        
          
            d
            r
          
          
            b
          
        
        :
        
          N
        
        →
        
          
            ⋃
          
          
            k
            0
          
          
            b
            1
          
        
         
        k
        ,
        
        b
        ∈
        
          
            N
          
          
            ⩾
            2
          
        
      
    
    
  
 is expressed as:

  
    
      
        
          
            d
            r
          
          
            b
          
        
        n
        :=
        
          
            
              
                
                  0
                
                
                  n
                  0
                
              
              
                
                  1
                  (
                  n
                  1
                  
                    mod
                    
                    
                  
                  b
                  1
                  )
                
                
                  n
                  0
                
              
            
            
          
        
      
    
    
  
.

## Related

- [[Multiplicative digital root]]
- [[Automorphic number]]
- [[Digit sum]]
- [[Kaprekar number]]
- [[3x + 1 semigroup]]
- [[AWM–Microsoft Research Prize in Algebra and Number Theory]]
- [[Cole Prize]]
- [[Cyclotomic polynomial]]
- [[Euler's totient function]]
- [[Hundred Fowls Problem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Digital_root