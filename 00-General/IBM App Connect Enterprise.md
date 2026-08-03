---
title: "IBM App Connect Enterprise"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/IBM_App_Connect_Enterprise"
wikipedia_categories: ["IBM WebSphere", "Middleware"]
related: ["[[ActiveVOS]]", "[[Advanced Message Queuing Protocol]]", "[[Advanced Resource Connector]]", "[[Akka.io]]", "[[Asynchrony (computer programming)]]", "[[Audiokinetic Wwise]]", "[[Ayotle]]", "[[Base One Foundation Component Library]]", "[[Candle Corporation]]", "[[CICS]]"]
---

# IBM App Connect Enterprise

IBM App Connect Enterprise (abbreviated as IBM ACE, formerly known as IBM Integration Bus (IIB), WebSphere Message Broker (WMB), WebSphere Business Integration Message Broker (WBIMB), WebSphere MQSeries Integrator (WMQI) and started life as MQSeries Systems Integrator (MQSI). App Connect IBM's integration software offering, allowing business information to flow between disparate applications across multiple hardware and software platforms. Rules can be applied to the data flowing through user-authored integrations to route and transform the information. The product can be used as an Enterprise Service Bus supplying a communication channel between applications and services in a service-oriented architecture. App Connect from V11 supports container native deployments with highly optimised container start-up times.
IBM ACE provides capabilities to build integration flows needed to support diverse integration requirements through a set of connectors to a range of data sources, including packaged applications, files, mobile devices, messaging systems, and databases. A benefit of using IBM ACE is that the tool enables existing applications for Web Services without costly legacy application rewrites. IBM ACE avoids the point-to-point strain on development resources by connecting any application or service over multiple protocols, including SOAP, HTTP and JMS. Modern secure authentication mechanisms, including the ability to perform actions on behalf of masquerading or delegate users, through MQ, HTTP and SOAP nodes are supported such as LDAP, X-AUTH, O-AUTH, and two-way SSL.
A major focus of IBM ACE in its recent releases has been the capability of the product's runtime to be fully hosted in a cloud. Hosting the runtime in the cloud provides certain advantages and potential cost savings compared to hosting the runtime on premises as it simplifies the maintenance and application of OS-level patches which can sometimes be disruptive to business continuity. Also, cloud hosting of IBM ACE runtime allows easy expansion of capacity by adding more horsepower to the CPU configuration of a cloud environment or by adding additional nodes in an Active-Active configuration. An additional advantage of maintaining IBM ACE runtime in the cloud is the ability to configure access to your IBM ACE functionality separate and apart from your internal network using DataPower or API Connect devices. This allows people or services on the public internet to access your Enterprise Service Bus without passing through your internal network, which can be a more secure configuration than if your ESB was deployed to your internal on premises network.
IBM ACE embeds a Common Language Runtime to invoke any .NET logic as part of an integration. It also includes full support for the Visual Studio development environment, including the integrated debugger and code templates. IBM Integration Bus includes a comprehensive set of patterns and samples that demonstrate bi-directional connectivity with both Microsoft Dynamics CRM and MSMQ. Several improvements have been made to this current release, among them the ability to configure runtime parameters using a property file that is part of the deployed artifacts contained in the BAR ('broker archive') file. Previously, the only way to configure runtime parameters was to run an MQSI command on the command line. This new way of configuration is referred to as a policy document and can be created with the new Policy Editor. Policy documents can be stored in a source code control system and a different policy can exist for different environments (DEV, INT, QA, PROD).
IBM ACE is compatible with several virtualization platforms right out-of-the-box, Docker being a prime example. With IBM ACE, you can download from the global Docker repository a runtime of IBM ACE and run it locally. Because IBM ACE has its administrative console built right into the runtime, once the Docker image is active on your local, you can do all the configuration and administration commands needed to fully activate any message flow or deploy any BAR file. In fact, you can construct message flows that are microservices and package these microservices into a Docker deployable object directly. Because message flows and BAR files can contain Policy files, this node configuration can be automatic and no or little human intervention is needed to complete the application deployment.

## Related

- [[ActiveVOS]]
- [[Advanced Message Queuing Protocol]]
- [[Advanced Resource Connector]]
- [[Akka.io]]
- [[Asynchrony (computer programming)]]
- [[Audiokinetic Wwise]]
- [[Ayotle]]
- [[Base One Foundation Component Library]]
- [[Candle Corporation]]
- [[CICS]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/IBM_App_Connect_Enterprise