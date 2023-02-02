---
{"created":"2022-12-31T23:15:52-06:00","updated":"2023-02-02T16:39:27-06:00","title":"Microservices","zettelgarden":true,"zettelType":"concept","dg-publish":true,"permalink":"/z/notes/microservices/","dgPassFrontmatter":true}
---

# Microservices
#office/technology

Monolithic Architecture vs Microservices

Monolithic has all components dependent on each other. All are assembled tog4ether and tightly packaged. In order to scale, multiple instances of the application can be spun up behind a load balancer. Simple to deploy.

Monolithic is difficult for large and complex applications due to complexity of change, quality of code will decline, there are difficulties upsizing the application. It also has slow development due to multiple teams working on it and the size of the application. In order to update one component the entire application must be redeployed, which can interrupt background tasks, dependencies, etc.

Does not handle memory management and CPU usage very well due to scalability requiring full deployment of the application for each instance.

Monolithic is inflexible, unreliable, and unscalable. Huge barrier to adopting new technologies.

Microservices is an architectural style that structures an application as a collection of small autonomous services, modelled around a business domain.

Micro each service is responsible for its own data model -- a federated data model. Each service has its own codebase, which is managed by a team. A team can update an existing service without having to redeploy the entire application. They do not need to share the same technology stack or libraries or frameworks. They have their own database.

In micro, the API gateway controls the communication between individual services and the client.

Features of Micro:
1: Small Focused
2: Loosely Coupled
3: Language Neutral
4: Bounded Context