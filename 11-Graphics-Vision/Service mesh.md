---
title: "Service mesh"
tags: ["cs", "graphics-vision", "intermediate"]
domain: Graphics & Vision
level: intermediate
source: "https://en.wikipedia.org/wiki/Service_mesh"
wikipedia_categories: ["Software architecture", "Software engineering stubs"]
related: ["[[Active reviews for intermediate designs]]", "[[Common Component Architecture]]", "[[Connection broker]]", "[[Darwin (ADL)]]", "[[Monolithic application]]", "[[Presentation logic]]", "[[Reference architecture]]", "[[SAP Enterprise Architecture Framework]]", "[[Semantic architecture]]", "[[Software architecture analysis method]]"]
---

# Service mesh

In software architecture, a service mesh is a dedicated infrastructure layer for facilitating service-to-service communications between services or microservices using a proxy.
A dedicated communication layer can provide numerous benefits, such as providing observability into communications, providing secure connections, and automating retries and backoff for failed requests.
A service mesh consists of network proxies paired with each service in an application and a set of task-management processes. The proxies are called the data plane and the management processes are called the control plane. The data plane intercepts calls between different services and processes them; the control plane is the brain of the mesh that coordinates the behavior of proxies and provides APIs for operations and maintenance personnel to manipulate and observe the entire network.
The service mesh architecture is implemented by software products such as Istio, Cilium, Linkerd, Consul, AWS App Mesh, Kuma, Traefik Mesh, and Greymatter.io. Many service meshes use the Envoy proxy on the data plane.

## Related

- [[Active reviews for intermediate designs]]
- [[Common Component Architecture]]
- [[Connection broker]]
- [[Darwin (ADL)]]
- [[Monolithic application]]
- [[Presentation logic]]
- [[Reference architecture]]
- [[SAP Enterprise Architecture Framework]]
- [[Semantic architecture]]
- [[Software architecture analysis method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Service_mesh