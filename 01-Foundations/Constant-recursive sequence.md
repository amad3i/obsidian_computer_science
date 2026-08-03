---
title: "Constant-recursive sequence"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Constant-recursive_sequence"
wikipedia_categories: ["Combinatorics", "Dynamical systems", "Integer sequences", "Linear algebra", "Recurrence relations"]
related: ["[[Matrix difference equation]]", "[[Binomial coefficient]]", "[[Combinatorics and dynamical systems]]", "[[Delannoy number]]", "[[Graph dynamical system]]", "[[K-regular sequence]]", "[[Large set (combinatorics)]]", "[[Meander (mathematics)]]", "[[Primefree sequence]]", "[[Recurrence relation]]"]
---

# Constant-recursive sequence

In mathematics, an infinite sequence of numbers 
  
    
      
        
          s
          
            0
          
        
        ,
        
          s
          
            1
          
        
        ,
        
          s
          
            2
          
        
        ,
        
          s
          
            3
          
        
        ,
        …
      
    
    
  
 is called constant-recursive if it satisfies an equation of the form

  
    
      
        
          s
          
            n
          
        
        
          c
          
            1
          
        
        
          s
          
            n
            1
          
        
        
          c
          
            2
          
        
        
          s
          
            n
            2
          
        
        ⋯
        
          c
          
            d
          
        
        
          s
          
            n
            d
          
        
        ,
      
    
    
  

for all 
  
    
      
        n
        ≥
        d
      
    
    
  
, where 
  
    
      
        
          c
          
            i
          
        
      
    
    
  
 are constants. The equation is called a linear recurrence relation.
The concept is also known as a linear recurrence sequence, linear-recursive sequence, linear-recurrent sequence, or a C-finite sequence.
For example, the Fibonacci sequence

  
    
      
        0
        ,
        1
        ,
        1
        ,
        2
        ,
        3
        ,
        5
        ,
        8
        ,
        13
        ,
        …
      
    
    
  
,
is constant-recursive because it satisfies the linear recurrence 
  
    
      
        
          F
          
            n
          
        
        
          F
          
            n
            1
          
        
        
          F
          
            n
            2
          
        
      
    
    
  
: each number in the sequence is the sum of the previous two. 
Other examples include the power of two sequence 
  
    
      
        1
        ,
        2
        ,
        4
        ,
        8
        ,
        16
        ,
        …
      
    
    
  
, where each number is the sum of twice the previous number, and the square number sequence 
  
    
      
        0
        ,
        1
        ,
        4
        ,
        9
        ,
        16
        ,
        25
        ,
        …
      
    
    
  
. All arithmetic progressions, all geometric progressions, and all polynomials are constant-recursive. However, not all sequences are constant-recursive; for example, the factorial sequence 
  
    
      
        1
        ,
        1
        ,
        2
        ,
        6
        ,
        24
        ,
        120
        ,
        …
      
    
    
  
 is not constant-recursive.
Constant-recursive sequences are studied in combinatorics and the theory of finite differences. They also arise in algebraic number theory, due to the relation of the sequence to polynomial roots; in the analysis of algorithms, as the running time of simple recursive functions; and in the theory of formal languages, where they count strings up to a given length in a regular language. Constant-recursive sequences are closed under important mathematical operations such as term-wise addition, term-wise multiplication, and Cauchy product.
The Skolem–Mahler–Lech theorem states that the zeros of a constant-recursive sequence have a regularly repeating (eventually periodic) form. The Skolem problem, which asks for an algorithm to determine whether a linear recurrence has at least one zero, is an unsolved problem in mathematics.

## Related

- [[Matrix difference equation]]
- [[Binomial coefficient]]
- [[Combinatorics and dynamical systems]]
- [[Delannoy number]]
- [[Graph dynamical system]]
- [[K-regular sequence]]
- [[Large set (combinatorics)]]
- [[Meander (mathematics)]]
- [[Primefree sequence]]
- [[Recurrence relation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Constant-recursive_sequence