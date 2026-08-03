---
title: "Erlang (unit)"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Erlang_(unit)"
wikipedia_categories: ["Network performance", "Queueing theory", "Teletraffic", "Units of measurement"]
related: ["[[Adaptive quality of service multi-hop routing]]", "[[Layered queueing network]]", "[[Palm–Khintchine theorem]]", "[[Quality of service]]", "[[Queueing theory]]", "[[Teletraffic engineering]]", "[[Traffic generation model]]", "[[Adversarial queueing network]]", "[[AiScaler]]", "[[ALTQ]]"]
---

# Erlang (unit)

The erlang (symbol E) is a dimensionless unit that is used in telephony as a measure of offered load or carried load on service-providing elements such as telephone circuits or telephone switching equipment. A single cord circuit has the capacity to be used for 60 minutes in one hour. Full utilization of that capacity, 60 minutes of traffic, constitutes 1 erlang.
Carried traffic in erlangs is the average number of concurrent calls measured over a given period (often one hour), while offered traffic is the traffic that would be carried if all call-attempts succeeded. How much offered traffic is carried in practice will depend on what happens to unanswered calls when all servers are busy.
The CCITT named the international unit of telephone traffic the erlang in 1946 in honor of Agner Krarup Erlang. In Erlang's analysis of efficient telephone line usage, he derived the formulae for two important cases, Erlang-B and Erlang-C, which became foundational results in teletraffic engineering and queueing theory. His results, which are still used today, relate quality of service to the number of available servers. Both formulae take offered load as one of their main inputs (in erlangs), which is often expressed as call arrival rate times average call length.
A distinguishing assumption behind the Erlang B formula is that there is no queue, so that if all service elements are already in use then a newly arriving call will be blocked and subsequently lost. The formula gives the probability of this occurring. In contrast, the Erlang C formula provides for the possibility of an unlimited queue and it gives the probability that a new call will need to wait in the queue due to all servers being in use. Erlang's formulae apply quite widely, but they may fail when congestion is especially high causing unsuccessful traffic to repeatedly retry. One way of accounting for retries when no queue is available is the Extended Erlang B method.

## Related

- [[Adaptive quality of service multi-hop routing]]
- [[Layered queueing network]]
- [[Palm–Khintchine theorem]]
- [[Quality of service]]
- [[Queueing theory]]
- [[Teletraffic engineering]]
- [[Traffic generation model]]
- [[Adversarial queueing network]]
- [[AiScaler]]
- [[ALTQ]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Erlang_(unit)