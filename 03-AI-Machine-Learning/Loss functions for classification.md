---
title: "Loss functions for classification"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Loss_functions_for_classification"
wikipedia_categories: ["Machine learning algorithms"]
related: ["[[Actor-critic algorithm]]", "[[AdaBoost]]", "[[Algorithms of Oppression]]", "[[Almeida–Pineda recurrent backpropagation]]", "[[Augmented Analytics]]", "[[Backpropagation]]", "[[Bootstrap aggregating]]", "[[CN2 algorithm]]", "[[Co-training]]", "[[Constructing skill trees]]"]
---

# Loss functions for classification

In machine learning and mathematical optimization, loss functions for classification are computationally feasible loss functions representing the price paid for inaccuracy of predictions in classification problems (problems of identifying which category a particular observation belongs to).  Given 
  
    
      
        
          
            X
          
        
      
    
    
  
 as the space of all possible inputs (usually 
  
    
      
        
          
            X
          
        
        ⊂
        
          
            R
          
          
            d
          
        
      
    
    
  
), and 
  
    
      
        
          
            Y
          
        
        {
        1
        ,
        1
      
    
    
  
 as the set of labels (possible outputs), a typical goal of classification algorithms is to find a function 
  
    
      
        f
        :
        
          
            X
          
        
        →
        
          
            Y
          
        
      
    
    
  
 which best predicts a label 
  
    
      
        y
      
    
    
  
 for a given input 
  
    
      
        
          
            
              x
              →
            
          
        
      
    
    
  
.  However, because of incomplete information, noise in the measurement, or probabilistic components in the underlying process, it is possible for the same 
  
    
      
        
          
            
              x
              →
            
          
        
      
    
    
  
 to generate different 
  
    
      
        y
      
    
    
  
.  As a result, the goal of the learning problem is to minimize expected loss (also known as the risk), defined as

  
    
      
        I
        f
        =
        
          
            ∫
            
              
                
                  X
                
              
              
                
                  Y
                
              
            
          
          V
          f
          
            
              
                x
                →
              
            
          
          ,
          y
          
          p
          
            
              
                x
                →
              
            
          
          ,
          y
          
          d
          
            
              
                x
                →
              
            
          
          
          d
          y
        
      
    
    
  

where 
  
    
      
        V
        f
        
          
            
              x
              →
            
          
        
        ,
        y
      
    
    
  
 is a given loss function, and  
  
    
      
        p
        
          
            
              x
              →
            
          
        
        ,
        y
      
    
    
  
 is the probability density function of the process that generated the data, which can equivalently be written as

  
    
      
        p
        
          
            
              x
              →
            
          
        
        ,
        y
        =
        p
        y
        ∣
        
          
            
              x
              →
            
          
        
        p
        
          
            
              x
              →
            
          
        
        .
      
    
    
  

Within classification, several commonly used loss functions are written solely in terms of the product of the true label 
  
    
      
        y
      
    
    
  
 and the predicted label 
  
    
      
        f
        
          
            
              x
              →
            
          
        
      
    
    
  
. Therefore, they can be defined as functions of only one variable 
  
    
      
        υ
        y
        f
        
          
            
              x
              →
            
          
        
      
    
    
  
, so that 
  
    
      
        V
        f
        
          
            
              x
              →
            
          
        
        ,
        y
        =
        ϕ
        y
        f
        
          
            
              x
              →
            
          
        
        )
        ϕ
        υ
      
    
    
  
 with a suitably chosen function 
  
    
      
        ϕ
        :
        
          R
        
        →
        
          R
        
      
    
    
  
. These are called margin-based loss functions. Choosing a margin-based loss function amounts to choosing 
  
    
      
        ϕ
      
    
    
  
. Selection of a loss function within this framework impacts the optimal 
  
    
      
        
          f
          
            ϕ
          
          
          
        
      
    
    
  
 which minimizes the expected risk, see empirical risk minimization.
In the case of binary classification, it is possible to simplify the calculation of expected risk from the integral specified above.  Specifically,

  
    
      
        
          
            
              
                I
                f
              
              
                
                
                  ∫
                  
                    
                      
                        X
                      
                    
                    
                      
                        Y
                      
                    
                  
                
                V
                f
                
                  
                    
                      x
                      →
                    
                  
                
                ,
                y
                
                p
                
                  
                    
                      x
                      →
                    
                  
                
                ,
                y
                
                d
                
                  
                    
                      x
                      →
                    
                  
                
                
                d
                y
              
            
            
              
              
                
                
                  ∫
                  
                    
                      X
                    
                  
                
                
                  ∫
                  
                    
                      Y
                    
                  
                
                ϕ
                y
                f
                
                  
                    
                      x
                      →
                    
                  
                
                )
                
                p
                y
                ∣
                
                  
                    
                      x
                      →
                    
                  
                
                
                p
                
                  
                    
                      x
                      →
                    
                  
                
                
                d
                y
                
                d
                
                  
                    
                      x
                      →
                    
                  
                
              
            
            
              
              
                
                
                  ∫
                  
                    
                      X
                    
                  
                
                ϕ
                f
                
                  
                    
                      x
                      →
                    
                  
                
                )
                
                p
                1
                ∣
                
                  
                    
                      x
                      →
                    
                  
                
                +
                ϕ
                −
                f
                
                  
                    
                      x
                      →
                    
                  
                
                )
                
                p
                −
                1
                ∣
                
                  
                    
                      x
                      →
                    
                  
                
                ]
                
                p
                
                  
                    
                      x
                      →
                    
                  
                
                
                d
                
                  
                    
                      x
                      →
                    
                  
                
              
            
            
              
              
                
                
                  ∫
                  
                    
                      X
                    
                  
                
                ϕ
                f
                
                  
                    
                      x
                      →
                    
                  
                
                )
                
                p
                1
                ∣
                
                  
                    
                      x
                      →
                    
                  
                
                +
                ϕ
                −
                f
                
                  
                    
                      x
                      →
                    
                  
                
                )
                
                1
                p
                1
                ∣
                
                  
                    
                      x
                      →
                    
                  
                
                )
                
                p
                
                  
                    
                      x
                      →
                    
                  
                
                
                d
                
                  
                    
                      x
                      →
                    
                  
                
              
            
          
        
      
    
    
  

The second equality follows from the properties described above.  The third equality follows from the fact that 1 and −1 are the only possible values for 
  
    
      
        y
      
    
    
  
, and the fourth because 
  
    
      
        p
        −
        1
        ∣
        x
        =
        1
        p
        1
        ∣
        x
      
    
    
  
. The term within brackets 
  
    
      
        ϕ
        f
        
          
            
              x
              →
            
          
        
        )
        p
        1
        ∣
        
          
            
              x
              →
            
          
        
        +
        ϕ
        −
        f
        
          
            
              x
              →
            
          
        
        )
        1
        p
        1
        ∣
        
          
            
              x
              →
            
          
        
        )
      
    
    
  
 is known as the conditional risk.
One can solve for the minimizer of 
  
    
      
        I
        f
      
    
    
  
 by taking the functional derivative of the last equality with respect to 
  
    
      
        f
      
    
    
  
 and setting the derivative equal to 0.  This will result in the following equation

  
    
      
        
          
            
              ∂
              ϕ
              f
            
            
              ∂
              f
            
          
        
        η
        
          
            
              ∂
              ϕ
              −
              f
            
            
              ∂
              f
            
          
        
        1
        η
        =
        0
        ,
        
        
        
        
        
        1
      
    
    
  

where 
  
    
      
        η
        p
        y
        1
        
          |
        
        
          
            
              x
              →
            
          
        
      
    
    
  
, which is also equivalent to setting the derivative of the conditional risk equal to zero.
Given the binary nature of classification, a natural selection for a loss function (assuming equal cost for false positives and false negatives) would be the 0-1 loss function (0–1 indicator function), which takes the value of 0 if the predicted classification equals that of the true class or a 1 if the predicted classification does not match the true class. This selection is modeled by

  
    
      
        V
        f
        
          
            
              x
              →
            
          
        
        ,
        y
        =
        H
        −
        y
        f
        
          
            
              x
              →
            
          
        
        )
      
    
    
  

where 
  
    
      
        H
      
    
    
  
 indicates the Heaviside step function.
However, this loss function is non-convex and non-smooth, and solving for the optimal solution is an NP-hard combinatorial optimization problem.  As a result, it is better to substitute loss function surrogates which are tractable for commonly used learning algorithms, as they have convenient properties such as being convex and smooth.  In addition to  their computational tractability,  one can show that the solutions to the learning problem using these loss surrogates allow for the recovery of the actual solution to the original classification problem.  Some of these surrogates are described below.
In practice, the probability distribution 
  
    
      
        p
        
          
            
              x
              →
            
          
        
        ,
        y
      
    
    
  
 is unknown.  Consequently, utilizing a training set of 
  
    
      
        n
      
    
    
  
 independently and identically distributed sample points

  
    
      
        S
        {
        
          
            
              
                x
                →
              
            
          
          
            1
          
        
        ,
        
          y
          
            1
          
        
        ,
        …
        ,
        
          
            
              
                x
                →
              
            
          
          
            n
          
        
        ,
        
          y
          
            n
          
        
        }
      
    
    
  

drawn from the data sample space, one seeks to minimize empirical risk

  
    
      
        
          I
          
            S
          
        
        f
        =
        
          
            1
            n
          
        
        
          ∑
          
            i
            1
          
          
            n
          
        
        V
        f
        
          
            
              
                x
                →
              
            
          
          
            i
          
        
        ,
        
          y
          
            i
          
        
      
    
    
  

as a proxy for expected risk. (See statistical learning theory for a more detailed description.)

*(note truncated for size; full article at the source link below)*

## Related

- [[Actor-critic algorithm]]
- [[AdaBoost]]
- [[Algorithms of Oppression]]
- [[Almeida–Pineda recurrent backpropagation]]
- [[Augmented Analytics]]
- [[Backpropagation]]
- [[Bootstrap aggregating]]
- [[CN2 algorithm]]
- [[Co-training]]
- [[Constructing skill trees]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Loss_functions_for_classification