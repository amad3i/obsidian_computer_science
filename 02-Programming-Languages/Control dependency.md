---
title: "Control dependency"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Control_dependency"
wikipedia_categories: ["Compilers"]
related: ["[[Absoft]]", "[[Accelerated Linear Algebra]]", "[[Ahead-of-time compilation]]", "[[Apple Dylan]]", "[[Arden2ByteCode]]", "[[Ark Compiler]]", "[[Banerjee test]]", "[[Binary optimizer]]", "[[Binary recompiler]]", "[[Bootstrapping (compilers)]]"]
---

# Control dependency

Control dependency is a situation in which a program instruction executes if the previous instruction evaluates in a way that allows its execution.
An instruction B has a control dependency on a preceding instruction A if the outcome of A determines whether B should be executed or not. In the following example, the instruction 
  
    
      
        
          S
          
            2
          
        
      
    
    
  
 has a control dependency on instruction 
  
    
      
        
          S
          
            1
          
        
      
    
    
  
. However, 
  
    
      
        
          S
          
            3
          
        
      
    
    
  
 does not depend on 
  
    
      
        
          S
          
            1
          
        
      
    
    
  
 because 
  
    
      
        
          S
          
            3
          
        
      
    
    
  
 is always executed irrespective of the outcome of 
  
    
      
        
          S
          
            1
          
        
      
    
    
  
.

S1.         if (a == b)
S2.             a = a + b
S3.         b = a + b

Intuitively, there is control dependence between two statements A and B if

B could be possibly executed after A
The outcome of the execution of A will determine whether B will be executed or not.
A typical example is that there are control dependences between the condition part of an if statement and the statements in its true/false bodies.
A formal definition of control dependence can be presented as follows:
A statement 
  
    
      
        
          S
          
            2
          
        
      
    
    
  
 is said to be control dependent on another statement 
  
    
      
        
          S
          
            1
          
        
      
    
    
  
 iff

there exists a path 
  
    
      
        P
      
    
    
  
 from 
  
    
      
        
          S
          
            1
          
        
      
    
    
  
 to 
  
    
      
        
          S
          
            2
          
        
      
    
    
  
 such that every statement 
  
    
      
        
          S
          
            i
          
        
      
    
    
  
 ≠ 
  
    
      
        
          S
          
            1
          
        
      
    
    
  
 within 
  
    
      
        P
      
    
    
  
 will be followed by 
  
    
      
        
          S
          
            2
          
        
      
    
    
  
 in each possible path to the end of the program and

  
    
      
        
          S
          
            1
          
        
      
    
    
  
 will not necessarily be followed by 
  
    
      
        
          S
          
            2
          
        
      
    
    
  
, i.e. there is an execution path from 
  
    
      
        
          S
          
            1
          
        
      
    
    
  
 to the end of the program that does not go through 
  
    
      
        
          S
          
            2
          
        
      
    
    
  
.
Expressed with the help of (post-)dominance the two conditions are equivalent to

  
    
      
        
          S
          
            2
          
        
      
    
    
  
 post-dominates all 
  
    
      
        
          S
          
            i
          
        
      
    
    
  

  
    
      
        
          S
          
            2
          
        
      
    
    
  
 does not post-dominate 
  
    
      
        
          S
          
            1
          
        
      
    
    

## Related

- [[Absoft]]
- [[Accelerated Linear Algebra]]
- [[Ahead-of-time compilation]]
- [[Apple Dylan]]
- [[Arden2ByteCode]]
- [[Ark Compiler]]
- [[Banerjee test]]
- [[Binary optimizer]]
- [[Binary recompiler]]
- [[Bootstrapping (compilers)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Control_dependency