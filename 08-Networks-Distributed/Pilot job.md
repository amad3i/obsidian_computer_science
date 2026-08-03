---
title: "Pilot job"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Pilot_job"
wikipedia_categories: ["Distributed computing", "Grid computing", "Job scheduling", "Parallel computing"]
related: ["[[HTCondor]]", "[[Oracle Grid Engine]]", "[[Slurm Workload Manager]]", "[[Beowulf cluster]]", "[[Collective operation]]", "[[Data-centric programming language]]", "[[Grid MP]]", "[[HPCC]]", "[[IBM Spectrum LSF]]", "[[MOSIX]]"]
---

# Pilot job

In computer science, a pilot job is a type of multilevel scheduling, in which a resource is acquired by an application so that the application can schedule work into that resource directly, rather than going through a local job scheduler, which might lead to queue waits for each work unit.  This term comes from the Condor High-Throughput Computing System, in which Condor GlideIns provides this functionality.  Other examples of pilot jobs are: the BigJob implemented in SAGA, Swift Coasters as part of the Swift parallel scripting system,  the Falkon lightweight task execution framework, and HTCaaS.
Pilot jobs are most often used on systems that have queues, as part of their purpose is, in some sense, to avoid multiple waits in these queues.  These are most often found in parallel computing systems, but pilot jobs are usually part of a distributed application, and are many times associated with Many-task computing. Pilot-Job systems play a significant role in distributed scientific computing, enabling the execution of millions of tasks across multiple cyberinfrastructures and supporting large-scale task-level parallelism in high-performance computing environments.

## Related

- [[HTCondor]]
- [[Oracle Grid Engine]]
- [[Slurm Workload Manager]]
- [[Beowulf cluster]]
- [[Collective operation]]
- [[Data-centric programming language]]
- [[Grid MP]]
- [[HPCC]]
- [[IBM Spectrum LSF]]
- [[MOSIX]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pilot_job