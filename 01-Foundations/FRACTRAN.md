---
title: "FRACTRAN"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/FRACTRAN"
wikipedia_categories: ["Esoteric programming languages", "Models of computation", "Recreational mathematics"]
related: ["[[One-instruction set computer]]", "[[Abstract machine]]", "[[Abstract state machine]]", "[[Algorithm characterizations]]", "[[Applicative computing systems]]", "[[Beatnik (programming language)]]", "[[Befunge]]", "[[Behavior tree (artificial intelligence, robotics and control)]]", "[[BlooP and FlooP]]", "[[Brainfuck]]"]
---

# FRACTRAN

FRACTRAN is a Turing-complete esoteric programming language invented by the mathematician John Conway. A FRACTRAN program is an ordered list of positive fractions together with an initial positive integer input n. The program is run by updating the integer n as follows:

for the first fraction f in the list for which nf is an integer, replace n by nf
repeat this rule until no fraction in the list produces an integer when multiplied by n, then halt.
Conway 1987 gives the following FRACTRAN program, called PRIMEGAME, which finds successive prime numbers:

  
    
      
        
          
            
              
                17
                91
              
            
            ,
            
              
                78
                85
              
            
            ,
            
              
                19
                51
              
            
            ,
            
              
                23
                38
              
            
            ,
            
              
                29
                33
              
            
            ,
            
              
                77
                29
              
            
            ,
            
              
                95
                23
              
            
            ,
            
              
                77
                19
              
            
            ,
            
              
                1
                17
              
            
            ,
            
              
                11
                13
              
            
            ,
            
              
                13
                11
              
            
            ,
            
              
                15
                2
              
            
            ,
            
              
                1
                7
              
            
            ,
            
              
                55
                1
              
            
          
        
      
    
    
  

Starting with n=2, this FRACTRAN program generates the following sequence of integers:

2, 15, 825, 725, 1925, 2275, 425, 390, 330, 290, 770, ... (sequence A007542 in the OEIS), i.e. the sequence of PRIMEGAME numbers
After 2, this sequence contains the following powers of 2:

  
    
      
        
          2
          
            2
          
        
        4
        ,
        
        
          2
          
            3
          
        
        8
        ,
        
        
          2
          
            5
          
        
        32
        ,
        
        
          2
          
            7
          
        
        128
        ,
        
        
          2
          
            11
          
        
        2048
        ,
        
        
          2
          
            13
          
        
        8192
        ,
        
        
          2
          
            17
          
        
        131072
        ,
        
        
          2
          
            19
          
        
        524288
        ,
        
        …
      
    
    
  
 (sequence A034785 in the OEIS)
The exponent part of these powers of two are primes, 2, 3, 5, etc.

## Related

- [[One-instruction set computer]]
- [[Abstract machine]]
- [[Abstract state machine]]
- [[Algorithm characterizations]]
- [[Applicative computing systems]]
- [[Beatnik (programming language)]]
- [[Befunge]]
- [[Behavior tree (artificial intelligence, robotics and control)]]
- [[BlooP and FlooP]]
- [[Brainfuck]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/FRACTRAN