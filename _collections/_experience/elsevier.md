---
company: Elsevier
role: Senior Software Engineer
past: [Software Engineer VI, Software Engineer III]
from: 2020-10-01
to: now
tags: [Identity, Access Management, User Experience]
---

Elsevier is a publishing company that specialises in scientific, technical and medical content.

As part of the user-facing team, I was responsible for developing and maintaining the authentication flows that millions use everyday to access Elsevier-licensed content. By keeping to OAuth 2.0 standards we ensure that any Elsevier-integrating product is aware of a user's identity, whether that be as an individual or as part of an organisation or both. A large proportion of my responsiblity was being able to successfully communicate this complexity on the front end. Individual products from Elsevier's sphere had their own demands for the login flows and it was important to successfully integrate them ensuring the front end maintained it's comprehendability and the back end was cohesive.

As part of a team developing a new product for administrators, I worked with UX designers highlighting key user challenges in the development of user management flows and administrative controls. I developed React components that resulted from these discussion, focusing on reuse. These were then adopted by the wider community in a shared UI Library. I also held discussions with the front end team developing Elsevier's UI primitives and provided feedback which was then adopted by the team and used to improve the primitives in development.

Across both teams, I dealt with the integration of identity systems within a Spring architecture. I worked with PingFederate in existing authentication monolith, looking at how new features could be added but remain within the framework set out by PingFederate and the contraints of OAuth standards. In the scope of the new product, I transitioned providers from our existing PingFederate setup to Keycloak. Authorisation requirements were retained across the transition by adapting Keycloak to use PingFederate as a federated provider.

<!-- As a member of the user's team, I worked with Elsevier's federated access platform, IDPlus. IDPlus conforms to OpenID standards and, thus, so does any product wishing to integrate with it. Built upon the PingFederate framework, a set of adapters, written in Java, handle your authentication and session across Elsevier's platform of products. The logic utilises Spring-managed resources in order to yield information from third parties and also has an Elastic Search component which allows users to find and authenticate with the necessary authentication provider for their institution.

I developed new features and screens for IDPlus at every level of the stack. On the front end, I built new components that achieved accessibility standards set by the WCAG. At the adapter level, amongst iterating the code through refactoring and development of new features, I designed a newly decoupled migration flow that took advantage of the command pattern. I worked with AWS; writing improved Lambda functions that ensured cache instances were in sync and used CloudWatch to monitor the status of the available instances during monthly releases. When I worked for the client migration team, I worked in detail with Jenkins developing build pipelines. I created a python module that would bulk migrate users from an existing product to IDPlus and deployed the environment for it with Jenkins. Using unix tools like 'grep' and 'find' and creating bash scripts I was able to route out other issues facing migrating users.

Writing technical documentation was an important aspect. Documentation would be the result of spikes or the implementation of a new technology. When I implemented SASS pre-processing as part of an improvement to our front end ecosystem, I wrote documentation around setting it up and explaining the components. Another such spike, involved investigating a complete decoupling of the screen rendering engine from the backend code. I assessed the pros and cons of various technologies and solutions and considered their affordances in the context of the software development lifecycle such as whether the solution offered iterative improvements suitable for the agile workflow. -->
