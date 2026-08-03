---
title: "Transfer learning"
tags: ["cs", "ai-machine-learning", "core"]
domain: AI & Machine Learning
level: core
source: "https://en.wikipedia.org/wiki/Transfer_learning"
wikipedia_categories: ["Machine learning"]
related: ["[[80 Million Tiny Images]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Accelerated Linear Algebra]]", "[[Active learning (machine learning)]]", "[[Adversarial machine learning]]", "[[AI data center]]", "[[AI observability]]", "[[AIOps]]", "[[AIXI]]", "[[Algorithm selection]]"]
---

# Transfer learning

Transfer learning (TL) is a technique in machine learning (ML) in which knowledge learned from a task is re-used in order to boost performance on a related task. For example, for image classification, knowledge gained while learning to recognize cars could be applied when trying to recognize trucks. This topic is related to the psychological literature on transfer of learning, although practical ties between the two fields are limited. Reusing or transferring information from previously learned tasks to new tasks has the potential to significantly improve learning efficiency.
Since transfer learning makes use of training with multiple objective functions it is related to cost-sensitive machine learning and multi-objective optimization.

== History ==
In 1976, Bozinovski and Fulgosi published a paper addressing transfer learning in neural network training. The paper gives a mathematical and geometrical model of the topic. In 1981, a report considered the application of transfer learning to a dataset of images representing letters of computer terminals, experimentally demonstrating positive and negative transfer learning.
In 1992, Lorien Pratt formulated the discriminability-based transfer (DBT) algorithm.
By 1998, the field had advanced to include multi-task learning, along with more formal theoretical foundations. Influential publications on transfer learning include the book Learning to Learn in 1998, a 2009 survey and a 2019 survey.
Ng said in his NIPS 2016 tutorial that TL would become the next driver of machine learning commercial success after supervised learning.
In the 2020 paper, "Rethinking Pre-Training and self-training", Zoph et al. reported that pre-training can hurt accuracy, and advocate self-training instead.

== Definition ==
The definition of transfer learning is given in terms of domains and tasks. A domain 
  
    
      
        
          
            D
          
        
      
    
    
  
 consists of: a feature space 
  
    
      
        
          
            X
          
        
      
    
    
  
 and a marginal probability distribution 
  
    
      
        P
        X
      
    
    
  
, where 
  
    
      
        X
        {
        
          x
          
            1
          
        
        ,
        .
        .
        .
        ,
        
          x
          
            n
          
        
        ∈
        
          
            X
          
        
      
    
    
  
. Given a specific domain, 
  
    
      
        
          
            D
          
        
        {
        
          
            X
          
        
        ,
        P
        X
        }
      
    
    
  
, a task consists of two components: a label space 
  
    
      
        
          
            Y
          
        
      
    
    
  
 and an objective predictive function 
  
    
      
        f
        :
        
          
            X
          
        
        →
        
          
            Y
          
        
      
    
    
  
. The function 
  
    
      
        f
      
    
    
  
 is used to predict the corresponding label 
  
    
      
        f
        x
      
    
    
  
 of a new instance 
  
    
      
        x
      
    
    
  
. This task, denoted by 
  
    
      
        
          
            T
          
        
        {
        
          
            Y
          
        
        ,
        f
        x
        }
      
    
    
  
, is learned from the training data consisting of pairs 
  
    
      
        
          x
          
            i
          
        
        ,
        
          y
          
            i
          
        
      
    
    
  
, where 
  
    
      
        
          x
          
            i
          
        
        ∈
        
          
            X
          
        
      
    
    
  
 and 
  
    
      
        
          y
          
            i
          
        
        ∈
        
          
            Y
          
        
      
    
    
  
.
Given a source domain 
  
    
      
        
          
            
              D
            
          
          
            S
          
        
      
    
    
  
 and learning task 
  
    
      
        
          
            
              T
            
          
          
            S
          
        
      
    
    
  
, a target domain 
  
    
      
        
          
            
              D
            
          
          
            T
          
        
      
    
    
  
 and learning task 
  
    
      
        
          
            
              T
            
          
          
            T
          
        
      
    
    
  
, where 
  
    
      
        
          
            
              D
            
          
          
            S
          
        
        ≠
        
          
            
              D
            
          
          
            T
          
        
      
    
    
  
, or 
  
    
      
        
          
            
              T
            
          
          
            S
          
        
        ≠
        
          
            
              T
            
          
          
            T
          
        
      
    
    
  
, transfer learning aims to help improve the learning of the target predictive function 
  
    
      
        
          f
          
            T
          
        
        ⋅
      
    
    
  
 in 
  
    
      
        
          
            
              D
            
          
          
            T
          
        
      
    
    
  
 using the knowledge in 
  
    
      
        
          
            
              D
            
          
          
            S
          
        
      
    
    
  
 and 
  
    
      
        
          
            
              T
            
          
          
            S
          
        
      
    
    
  
.

== Applications ==
Algorithms for transfer learning are available in Markov logic networks and Bayesian networks. Transfer learning has been applied to cancer subtype discovery, building utilization, general game playing, text classification, digit recognition, medical imaging and spam filtering.
In 2020, it was discovered that, due to their similar physical natures, transfer learning is possible between electromyographic (EMG) signals from the muscles and classifying the behaviors of electroencephalographic (EEG) brainwaves, from the gesture recognition domain to the mental state recognition domain. It was noted that this relationship worked in both directions, showing that EEG brainwaves can likewise be used to classify EMG signals. The experiments noted that the accuracy of neural networks and convolutional neural networks were improved through transfer learning both prior to any learning (compared to standard random weight distribution) and at the end of the learning process (asymptote). That is, results are improved by exposure to another domain. Moreover, the end-user of a pre-trained model can change the structure of fully-connected layers to improve performance.

== See also ==
Crossover (genetic algorithm)
Domain adaptation
General game playing
Multi-task learning
Multitask optimization
Transfer of learning
Zero-shot learning
Few-shot learning
Feature learning
external validity

== References ==

== Sources ==
Thrun, Sebastian; Pratt, Lorien (6 December 2012). Learning to Learn. Springer Science & Business Media. ISBN 978-1-4615-5529-2.

## Related

- [[80 Million Tiny Images]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Accelerated Linear Algebra]]
- [[Active learning (machine learning)]]
- [[Adversarial machine learning]]
- [[AI data center]]
- [[AI observability]]
- [[AIOps]]
- [[AIXI]]
- [[Algorithm selection]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Transfer_learning