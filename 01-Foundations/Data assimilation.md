---
title: "Data assimilation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_assimilation"
wikipedia_categories: ["Bayesian statistics", "Climate and weather statistics", "Control theory", "Estimation theory", "Numerical climate and weather models", "Statistical forecasting", "Weather forecasting"]
related: ["[[4D-RCS Reference Model Architecture]]", "[[Abductive reasoning]]", "[[Ackermann's formula]]", "[[Active disturbance rejection control]]", "[[Adaptive control]]", "[[Advanced process control]]", "[[Affect control theory]]", "[[American Automatic Control Council]]", "[[Anticausal system]]", "[[Artstein's theorem]]"]
---

# Data assimilation

Data assimilation refers to a large group of methods that update information from numerical computer models with information from observations. Data assimilation is used to update model states, model trajectories over time, model parameters, and combinations thereof. What distinguishes data assimilation from other estimation methods is that the computer model is a dynamical model, i.e. the model describes how model variables change over time, and its firm mathematical foundation in Bayesian Inference. As such, it generalizes inverse methods and has close connections with machine learning.
Data assimilation initially developed in the field of numerical weather prediction. Numerical weather prediction models are equations describing the evolution of the atmosphere, typically coded into a computer program. When these models are used for forecasting the model output quickly deviates from the real atmosphere. Hence, we use observations of the atmosphere to keep the model on track. Data assimilation provides a very large number of practical ways to bring these observations into the models. 
Simply inserting point-wise measurements into the numerical models did not provide a satisfactory solution. Real world measurements contain errors both due to the quality of the instrument and how accurately the position of the measurement is known. These errors can cause instabilities in the models that eliminate any level of skill in a forecast. Thus, more sophisticated methods were needed in order to initialize a model using all available data while making sure to maintain stability in the numerical model. Such data typically includes the measurements as well as a previous forecast valid at the same time the measurements are made. If applied iteratively, this process begins to accumulate information from past observations into all subsequent forecasts.
Because data assimilation developed out of the field of numerical weather prediction, it initially gained popularity amongst the geosciences. In fact, one of the most cited publication in all of the geosciences is an application of data assimilation to reconstruct the observed history of the atmosphere.

## Related

- [[4D-RCS Reference Model Architecture]]
- [[Abductive reasoning]]
- [[Ackermann's formula]]
- [[Active disturbance rejection control]]
- [[Adaptive control]]
- [[Advanced process control]]
- [[Affect control theory]]
- [[American Automatic Control Council]]
- [[Anticausal system]]
- [[Artstein's theorem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data_assimilation