---
title: "List of software reliability models"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/List_of_software_reliability_models"
wikipedia_categories: ["Software testing"]
related: ["[[-dev-full]]", "[[A-B testing]]", "[[Acceptance test-driven development]]", "[[Acceptance testing]]", "[[Ad hoc testing]]", "[[Agent verification]]", "[[Agile testing]]", "[[All-pairs testing]]", "[[Analytical Performance Modeling]]", "[[API testing]]"]
---

# List of software reliability models

Software reliability is the probability of the software causing a system failure over some specified operating time. Software does not fail due to wear out but does fail due to faulty functionality, timing, sequencing, data, and exception handling.  The software fails as a function of operating time as opposed to calendar time.  Many models have been developed since early 1970s, however, several of them have similar if not identical assumptions.  The models have two basic types - prediction modeling and estimation modeling.
1.0 Overview of Software Reliability Prediction Models
These models are derived from actual historical data from real software projects.  The user answers a list of questions which calibrate the historical data to yield a software reliability prediction.  The accuracy of the prediction depends on how many parameters (questions) and datasets are in the model, how current the data is, and how confident the user is of their inputs. One of the earliest prediction models was the Rome Laboratory TR-92-52.  It was developed in 1987 and last updated in 1992 and was geared towards software in avionics systems. The model wasn't updated after 1992.  However, the Full-scale model was deployed in 1997 which reused many of the factors in the TR-92-52 model.  New development factors were added to reflect new technologies and the empirical data included data from systems other than aircraft.
2.0 Overview of Software Reliability Growth (Estimation) Models
Software reliability growth (or estimation) models use failure data from testing to forecast the failure rate or MTBF into the future.  The models depend on the assumptions about the fault rate during testing which can either be increasing, peaking, decreasing or some combination of decreasing and increasing.  Some models assume that there is a finite and fixed number of inherent defects while others assume that it's infinite.  Some models require effort for parameter estimation while others have only a few parameters to estimate.  Some models require the exact time in between each failure found in testing, while others only need to have the number of failures found during any given time interval such as a day.

## Related

- [[-dev-full]]
- [[A-B testing]]
- [[Acceptance test-driven development]]
- [[Acceptance testing]]
- [[Ad hoc testing]]
- [[Agent verification]]
- [[Agile testing]]
- [[All-pairs testing]]
- [[Analytical Performance Modeling]]
- [[API testing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/List_of_software_reliability_models