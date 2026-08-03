---
title: "Web Services Resource Framework"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Web_Services_Resource_Framework"
wikipedia_categories: ["Grid computing", "Web services", "Web standards"]
related: ["[[Web Services Distributed Management]]", "[[Access Grid]]", "[[Altair Engineering]]", "[[Amazon Elastic Compute Cloud]]", "[[Calais (Reuters product)]]", "[[CDDLM]]", "[[Cloud Foundry]]", "[[Co-ment]]", "[[D-Grid]]", "[[DAML-S]]"]
---

# Web Services Resource Framework

Web Services Resource Framework (WSRF) is a family of OASIS-published specifications for web services. Major contributors include the Globus Alliance and IBM.
A web service by itself is nominally stateless, i.e., it retains no data between invocations. This limits the things that can be done with web services, 
Before WSRF, no standard in the Web Services family of specifications explicitly defined how to deal with stateful interactions with remote resources. This does not mean that web services could not be stateful. Where required a web service could read from a database, or use session state by way of cookies or WS-Session.
WSRF provides a set of operations that web services can use to implement stateful interaction; web service clients communicate with resource services which allow data to be stored and retrieved. When clients talk to the web service they include the identifier of the specific resource that should be used inside the request, encapsulated within the WS-Addressing endpoint reference. This may be a simple URI address, or it may be complex XML content that helps identify or even fully describe the specific resource in question. 
Alongside the notion of an explicit resource reference comes a standardized set of web service operations to get/set resource properties. These can be used to read and perhaps write resource state, in a manner somewhat similar to having member variables of an object alongside its methods. The primary beneficiary of such a model are management tools, which can enumerate and view resources, even if they have no other knowledge of them. This is the basis for WSDM.

## Related

- [[Web Services Distributed Management]]
- [[Access Grid]]
- [[Altair Engineering]]
- [[Amazon Elastic Compute Cloud]]
- [[Calais (Reuters product)]]
- [[CDDLM]]
- [[Cloud Foundry]]
- [[Co-ment]]
- [[D-Grid]]
- [[DAML-S]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Web_Services_Resource_Framework