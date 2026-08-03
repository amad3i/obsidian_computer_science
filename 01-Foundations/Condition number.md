---
title: "Condition number"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Condition_number"
wikipedia_categories: ["Matrices (mathematics)", "Numerical analysis"]
related: ["[[Levinson recursion]]", "[[Matrix analysis]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]"]
---

# Condition number

In numerical analysis, the condition number of a function measures how much the output value of the function can change for a small change in the input argument. This is used to measure how sensitive a function is to changes or errors in the input, and how much error in the output results from an error in the input. Very frequently, one is solving the inverse problem: given 
  
    
      
        f
        x
        =
        y
        ,
      
    
    
  
 one is solving for x, and thus the condition number of the (local) inverse must be used.
The condition number is derived from the theory of propagation of uncertainty, and is formally defined as the value of the asymptotic worst-case relative change in output for a relative change in input. The "function" is the solution of a problem and the "arguments" are the data in the problem. The condition number is frequently applied to questions in linear algebra, in which case the derivative is straightforward but the error could be in many different directions, and is thus computed from the geometry of the matrix. More generally, condition numbers can be defined for non-linear functions in several variables.
A problem with a low condition number is said to be well-conditioned, while a problem with a high condition number is said to be ill-conditioned. In non-mathematical terms, an ill-conditioned problem is one where, for a small change in the inputs (the independent variables) there is a large change in the answer or dependent variable. This means that the correct solution/answer to the equation becomes hard to find. The condition number is a property of the problem.  Paired with the problem are any number of algorithms that can be used to solve the problem, that is, to calculate the solution.  Some algorithms have a property called backward stability; in general, a backward stable algorithm can be expected to accurately solve well-conditioned problems. Numerical analysis textbooks give formulas for the condition numbers of problems and identify known backward stable algorithms.
As a rule of thumb, if the condition number 
  
    
      
        κ
        A
        =
        
          10
          
            k
          
        
      
    
    
  
, then up to 
  
    
      
        k
      
    
    
  
 digits of accuracy may be lost on top of what would be lost to the numerical method due to loss of precision from arithmetic methods. However, the condition number does not give the exact value of the maximum inaccuracy that may occur in the algorithm. It generally just bounds it with an estimate (whose computed value depends on the choice of the norm to measure the inaccuracy).

## Related

- [[Levinson recursion]]
- [[Matrix analysis]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]
- [[Approximation error]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Condition_number