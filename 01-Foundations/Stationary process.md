---
title: "Stationary process"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Stationary_process"
wikipedia_categories: ["Signal processing", "Stochastic processes"]
related: ["[[Least-squares spectral analysis]]", "[[Recurrence period density entropy]]", "[[Stochastic resonance]]", "[[Adaptive beamformer]]", "[[Additive process]]", "[[Adjacent channel power ratio]]", "[[Algebraic signal processing]]", "[[Aliasing]]", "[[Ambiguity function]]", "[[Analog signal processing]]"]
---

# Stationary process

In mathematics and statistics, a stationary process (also called a strict/strictly stationary process or strong/strongly stationary process) is a stochastic process whose statistical properties, such as mean and variance, do not change over time. More formally, the joint probability distribution of the process remains the same when shifted in time. This implies that the process is statistically consistent across different time periods. Because many statistical procedures in time series analysis assume stationarity, non-stationary data are frequently transformed to achieve stationarity before analysis.
A common cause of non-stationarity is a trend in the mean, which can be due to either a unit root or a deterministic trend. In the case of a unit root, stochastic shocks have permanent effects, and the process is not mean-reverting. With a deterministic trend, the process is called trend-stationary, and shocks have only transitory effects, with the variable tending towards a deterministically evolving mean. A trend-stationary process is not strictly stationary but can be made stationary by removing the trend. Similarly, processes with unit roots can be made stationary through differencing.
Another type of non-stationary process, distinct from those with trends, is a cyclostationary process, which exhibits cyclical variations over time.
Strict stationarity, as defined above, can be too restrictive for many applications. Therefore, other forms of stationarity, such as wide-sense stationarity or ⁠
  
    
      
        N
      
    
    
  
⁠th-order stationarity, are often used. The definitions for different kinds of stationarity are not consistent among different authors (see Other terminology).

## Related

- [[Least-squares spectral analysis]]
- [[Recurrence period density entropy]]
- [[Stochastic resonance]]
- [[Adaptive beamformer]]
- [[Additive process]]
- [[Adjacent channel power ratio]]
- [[Algebraic signal processing]]
- [[Aliasing]]
- [[Ambiguity function]]
- [[Analog signal processing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stationary_process