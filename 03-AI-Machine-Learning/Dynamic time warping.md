---
title: "Dynamic time warping"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Dynamic_time_warping"
wikipedia_categories: ["Dynamic programming", "Machine learning algorithms", "Multivariate time series"]
related: ["[[Forward–backward algorithm]]", "[[Actor-critic algorithm]]", "[[AdaBoost]]", "[[Algorithms of Oppression]]", "[[Almeida–Pineda recurrent backpropagation]]", "[[Augmented Analytics]]", "[[Backpropagation]]", "[[Backward induction]]", "[[Bellman equation]]", "[[Bellman–Ford algorithm]]"]
---

# Dynamic time warping

In time series analysis, dynamic time warping (DTW) is an algorithm for measuring similarity between two temporal sequences, which may vary in speed.  For instance, similarities in walking could be detected using DTW, even if one person was walking faster than the other, or if there were accelerations and decelerations during the course of an observation. DTW has been applied to temporal sequences of video, audio, and graphics data — indeed, any data that can be turned into a one-dimensional sequence can be analyzed with DTW. A well-known application has been automatic speech recognition, to cope with different speaking speeds. Other applications include speaker recognition and online signature recognition. It can also be used in partial shape matching applications.
In general, DTW is a method that calculates an optimal match between two given sequences (e.g. time series) with certain restriction and rules:

Every index from the first sequence must be matched with one or more indices from the other sequence, and vice versa
The first index from the first sequence must be matched with the first index from the other sequence (but it does not have to be its only match)
The last index from the first sequence must be matched with the last index from the other sequence (but it does not have to be its only match)
The mapping of the indices from the first sequence to indices from the other sequence must be monotonically increasing, and vice versa, i.e. if 
  
    
      
        j
        i
      
    
    
  
 are indices from the first sequence, then there must not be two indices 
  
    
      
        l
        k
      
    
    
  
 in the other sequence, such that index 
  
    
      
        i
      
    
    
  
 is matched with index 
  
    
      
        l
      
    
    
  
 and index 
  
    
      
        j
      
    
    
  
 is matched with index 
  
    
      
        k
      
    
    
  
, and vice versa
We can plot each match between the sequences 
  
    
      
        1
        :
        M
      
    
    
  
 and 
  
    
      
        1
        :
        N
      
    
    
  
 as a path in a 
  
    
      
        M
        N
      
    
    
  
 matrix from 
  
    
      
        1
        ,
        1
      
    
    
  
 to 
  
    
      
        M
        ,
        N
      
    
    
  
, such that each step is one of 
  
    
      
        0
        ,
        1
        ,
        1
        ,
        0
        ,
        1
        ,
        1
      
    
    
  
. In this formulation, we see that the number of possible matches is the Delannoy number.
The optimal match is denoted by the match that satisfies all the restrictions and the rules and that has the minimal cost, where the cost is computed as the sum of absolute differences, for each matched pair of indices, between their values.
The sequences are "warped" non-linearly in the time dimension to determine a measure of their similarity independent of certain non-linear variations in the time dimension. This sequence alignment method is often used in time series classification. Although DTW measures a distance-like quantity between two given sequences, it doesn't guarantee the triangle inequality to hold.
In addition to a similarity measure between the two sequences (a so called "warping path" is produced), by warping according to this path the two signals may be aligned in time. The signal with an original set of points X(original), Y(original) is transformed to X(warped), Y(warped). This finds applications in genetic sequence and audio synchronisation. In a related technique sequences of varying speed may be averaged using this technique see the average sequence section.
This is conceptually very similar to the Needleman–Wunsch algorithm.

## Related

- [[Forward–backward algorithm]]
- [[Actor-critic algorithm]]
- [[AdaBoost]]
- [[Algorithms of Oppression]]
- [[Almeida–Pineda recurrent backpropagation]]
- [[Augmented Analytics]]
- [[Backpropagation]]
- [[Backward induction]]
- [[Bellman equation]]
- [[Bellman–Ford algorithm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dynamic_time_warping