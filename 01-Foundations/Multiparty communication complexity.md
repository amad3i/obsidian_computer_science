---
title: "Multiparty communication complexity"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Multiparty_communication_complexity"
wikipedia_categories: ["Applied mathematics", "Information theory"]
related: ["[[A Symbolic Analysis of Relay and Switching Circuits]]", "[[3G MIMO]]", "[[A Mathematical Theory of Communication]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Adjusted mutual information]]", "[[Algorithmic information theory]]", "[[Ascendency]]", "[[Asymptotic equipartition property]]", "[[Bandwidth (computing)]]"]
---

# Multiparty communication complexity

In theoretical computer science, multiparty communication complexity is the study of communication complexity in the setting where there are more than two players.
In the traditional two-party communication game, introduced by Yao (1979), two players, P1 and P2 attempt to compute a Boolean function 

  
    
      
        f
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        :
        0
        ,
        1
        
          
            n
          
        
        →
        0
        ,
        1
        ,
         
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ∈
        0
        ,
        1
        
          
            
              n
              ′
            
          
        
        ,
         
        2
        
          n
          ′
        
        n
      
    
    
  

Player P1 knows the value of x2, P2 knows the value of x1, but Pi does not know the value of xi, for i = 1, 2. 
In other words, the players know the other's variables, but not their own. The minimum number of bits that must be communicated by the players to compute f is the communication complexity of f, denoted by κ(f).
The multiparty communication game, defined in 1983, is a powerful generalization of the two-party case: Here the players know all the others' input, except their own. Because of this property, sometimes this model is called "numbers on the forehead" model, since if the players were seated around a round table, each wearing their own input on the forehead, then every player would see all the others' input, except their own.
The formal definition is as follows: 
  
    
      
        k
      
    
    
  
 players: 
  
    
      
        
          P
          
            1
          
        
        ,
        
          P
          
            2
          
        
        ,
        .
        .
        .
        ,
        
          P
          
            k
          
        
      
    
    
  
 intend to compute a Boolean function 

  
    
      
        f
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        …
        ,
        
          x
          
            n
          
        
        :
        0
        ,
        1
        
          
            n
          
        
        →
        0
        ,
        1
      
    
    
  

On set 
  
    
      
        S
        {
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        .
        .
        .
        ,
        
          x
          
            n
          
        
      
    
    
  
 of variables there is a fixed partition 
  
    
      
        A
      
    
    
  
 of 
  
    
      
        k
      
    
    
  
 classes 
  
    
      
        
          A
          
            1
          
        
        ,
        
          A
          
            2
          
        
        ,
        .
        .
        .
        ,
        
          A
          
            k
          
        
      
    
    
  
, and player 
  
    
      
        
          P
          
            i
          
        
      
    
    
  
 knows every variable, except those in 
  
    
      
        
          A
          
            i
          
        
      
    
    
  
, for 
  
    
      
        i
        1
        ,
        2
        ,
        .
        .
        .
        ,
        k
      
    
    
  
. The players have unlimited computational power, and they  communicate with the help of a blackboard, viewed by all players.
The aim is to compute 
  
    
      
        f
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        .
        .
        .
        ,
        
          x
          
            n
          
        
      
    
    
  
), such  that at the end of the computation, every player knows this value. The cost of the computation is the number of bits written onto the blackboard for the given input  
  
    
      
        x
        (
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        .
        .
        .
        ,
        
          x
          
            n
          
        
      
    
    
  
 and partition 
  
    
      
        A
        (
        
          A
          
            1
          
        
        ,
        
          A
          
            2
          
        
        ,
        .
        .
        .
        ,
        
          A
          
            n
          
        
      
    
    
  
. The cost of a multiparty protocol is the maximum number of bits communicated for any 
  
    
      
        x
      
    
    
  
 from the set {0,1}n and the given partition 
  
    
      
        A
      
    
    
  
. The 
  
    
      
        k
      
    
    
  
-party communication complexity, 
  
    
      
        
          C
          
            A
          
          
            k
          
        
        f
      
    
    
  
 of a function 
  
    
      
        f
      
    
    
  
, with respect to partition 
  
    
      
        A
      
    
    
  
, is the minimum of costs of those 
  
    
      
        k
      
    
    
  
-party protocols which compute 
  
    
      
        f
      
    
    
  
. The 
  
    
      
        k
      
    
    
  
-party symmetric communication complexity of 
  
    
      
        f
      
    
    
  
 is defined as 

  
    
      
        
          C
          
            k
          
        
        f
        =
        
          max
          
            A
          
        
        
          C
          
            A
          
          
            k
          
        
        f
      
    
    
  

where the maximum is taken over all k-partitions of set 
  
    
      
        x
        (
        
          x
          
            1
          
        
        ,
        
          x
          
            2
          
        
        ,
        .
        .
        .
        ,
        
          x
          
            n
          
        
      
    
    
  
.

## Related

- [[A Symbolic Analysis of Relay and Switching Circuits]]
- [[3G MIMO]]
- [[A Mathematical Theory of Communication]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Adjusted mutual information]]
- [[Algorithmic information theory]]
- [[Ascendency]]
- [[Asymptotic equipartition property]]
- [[Bandwidth (computing)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multiparty_communication_complexity