---
title: "Stochastic matrix"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Stochastic_matrix"
wikipedia_categories: ["Markov models", "Matrices (mathematics)"]
related: ["[[Bartels–Stewart algorithm]]", "[[Baum–Welch algorithm]]", "[[Bernoulli scheme]]", "[[Birkhoff algorithm]]", "[[BLOSUM]]", "[[Brandt matrix]]", "[[Burst error]]", "[[Centrosymmetric matrix]]", "[[CLAWS (linguistics)]]", "[[Column groups and row groups]]"]
---

# Stochastic matrix

In mathematics, a stochastic matrix is a square matrix used to describe the transitions of a Markov chain. Each of its entries is a nonnegative real number representing a probability. It is also called a probability matrix, transition matrix, substitution matrix, or Markov matrix. The stochastic matrix was first developed by Andrey Markov at the beginning of the 20th century, and has found use throughout a wide variety of scientific fields, including probability theory, statistics, mathematical finance and linear algebra, as well as computer science and population genetics. There are several different definitions and types of stochastic matrices:

A right stochastic matrix is a square matrix of nonnegative real numbers, with each row summing to 1 (so it is also called a row stochastic matrix).
A left stochastic matrix is a square matrix of nonnegative real numbers, with each column summing to 1 (so it is also called a column stochastic matrix).
A doubly stochastic matrix is a square matrix of nonnegative real numbers with each row and column summing to 1.
A substochastic matrix is a real square matrix whose row sums are all 
  
    
      
        ≤
        1.
      
    
    
  

In the same vein, one may define a probability vector as a vector whose elements are nonnegative real numbers which sum to 1. Thus, each row of a right stochastic matrix (or column of a left stochastic matrix) is a probability vector.  Right stochastic matrices act upon row vectors of probabilities by multiplication from the right (hence their name) and the matrix entry in the i-th row and j-th column is the probability of transition from state i to state j.  Left stochastic matrices act upon column vectors of probabilities by multiplication from the left (hence their name) and the matrix entry in the i-th row and j-th column is the probability of transition from state j to state i. 
This article uses the right/row stochastic matrix convention.

## Related

- [[Bartels–Stewart algorithm]]
- [[Baum–Welch algorithm]]
- [[Bernoulli scheme]]
- [[Birkhoff algorithm]]
- [[BLOSUM]]
- [[Brandt matrix]]
- [[Burst error]]
- [[Centrosymmetric matrix]]
- [[CLAWS (linguistics)]]
- [[Column groups and row groups]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stochastic_matrix