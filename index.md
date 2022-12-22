---
title: My page
layout: default
---

# Damon Hayhurst

<span id="location">London, UK (+ Remote)</span>

<span id="email">damonhayhurst@gmail.com</span>
<span id="telephone">447511299645</span>
<span id="linkedin">damonhayhurst</span>
<span id="github">damonhayhurst</span>

## About Me

My technology-agnostic skillset affords me an understanding of the web that is devoid of technical context and an approach to solution engineering that is wholly creative. I pride myself on my ability to present to both technical and non-technical audiences. I thoroughly enjoy working in a team towards a common goal.

## Experience

### Elsevier

#### Software Engineer IV

2022 October - Present

#### Software Engineer III

2020 October - 2022 October

- Accessibility
- Technical Documentation
- Continuous Integration

Elsevier is a publishing company specialising in scientific, technical and medical content.

As a member of the user's team, I worked with Elsevier's federated access platform, IDPlus. IDPlus conforms to OpenID standards and, thus, so does any product wishing to integrate with it. Built upon the PingFederate framework, a set of adapters, written in Java, handle your authentication and session across Elsevier's platform of products. The logic utilises Spring-managed resources in order to yield information from third parties and also has an Elastic Search component which allows users to find and authenticate with the necessary authentication provider for their institution.

I developed new features and screens for IDPlus at every level of the stack. On the front end, I built new components that achieved accessibility standards set by the WCAG. At the adapter level, amongst iterating the code through refactoring and development of new features, I designed a newly decoupled migration flow that took advantage of the command pattern. I worked with AWS; writing improved Lambda functions that ensured cache instances were in sync and used CloudWatch to monitor the status of the available instances during monthly releases. When I worked for the client migration team, I worked in detail with Jenkins developing build pipelines. I created a python module that would bulk migrate users from an existing product to IDPlus and deployed the environment for it with Jenkins. Using unix tools like 'grep' and 'find' and creating bash scripts I was able to route out other issues facing migrating users.

Writing technical documentation was an important aspect. Documentation would be the result of spikes or the implementation of a new technology. When I implemented SASS pre-processing as part of an improvement to our front end ecosystem, I wrote documentation around setting it up and explaining the components. Another such spike, involved investigating a complete decoupling of the screen rendering engine from the backend code. I assessed the pros and cons of various technologies and solutions and considered their affordances in the context of the software development lifecycle such as whether the solution offered iterative improvements suitable for the agile workflow.

### Flox

#### Full Stack Web Developer

2019 November - 2019 April

- R&D
- Architecture
- Usability Research
- Content Upload

Flox is an agri-tech start-up company bringing computer vision and machine learning to the poultry sector.

I built software that interfaced with Flox's machine learning technology. This technology would analyse camera streams from a chicken shed, send real-time alerts and show the farmer what is going on in the sheds. I used Python and Flask to create microservices and REST APIs that would run scheduled jobs and create, update and push real time alerts to the the database, the web interface and the farmer (through text, email, Whatsapp). I worked intensively with WebRTC (including creating private TURN servers) to retrieve the camera displays and display them within a 'media player-like' interface. I utilised Vuetify and PlotlyJs to display this live and historic data. I was solely responsible for the web architecture and developed it from concept to deployed GCP production instance in an intensive three month project.

Alongside the CTO, I helped create, build and support the system architecture. I was heavily responsible for containerising the bulk of the architecture, using Docker, and automating the the build process for production deployment. I mapped out the testing framework and spec for the entire system working closely with Pytest. I communicated with the computer vision team to support them in implementing this spec and other issues related to system architecture.

### Filmdoo

#### Web Developer

2019 November - 2019 April

- R&D
- Architecture
- Usability Research
- Content Upload

FilmDoo, is a UK-based video-on-demand startup that specialises in independent and world cinema.

Member of the product development team for Filmdoo’s edutainment venture. I was responsible for the R&D on the tech stack that the new product was going to use. I took into consideration the business requirements of the product and scalability when designing the architecture of the product. I carried out the foundational full stack development for the product including developing the data structure and defining the front end component hierarchy.

I worked on the development of Filmdoo’s user upload feature that would be part of the main site. I created an endpoint that would receive chunked video data and upload it to AWS using the S3 API. The front end was developed using jQuery. A large part of the project was usability research and testing. I performed extensive research on VOD competitors to define patterns which Filmdoo could use for it’s UX all while being coherent with the rest of the site.

### Crunch

#### Web Developer

2018 July - 2019 March

- Microservices
- Continuous Integration
- Agile
- Single Sign-On

Crunch provides online accountancy services for small businesses and self-employed people.

Undertook the development of the core Spring app, developing various features intended to improve the client manager’s ability to handle issues that their client may be having with the app. I created Python scripts that would automate updating the database.

I also was a member of the team developing Crunch’s single sign on technology within a microservice architecture. Responsible for creating MySQL queries that would collate data to uncover client issues and also design MySQL procedures that would fix more widespread issues. I also introduced and implemented a unit testing framework, MyTap, for these procedures.

### Freelance

#### Web Developer

2017 August - 2018 January

- Time Management
- Requirement Building
- Client Communication

I provided development services to a variety of clients found through Gumtree.

I worked on various Laravel 5 projects. I either built or maintained AngularJs frontends for these applications. One project I built from the ground up interpreting business requirements into a technical roadmap. I also maintained Wordpress plugins for clients.

### Highwire Press

#### Java Developer

2016 January - 2017 March

- Domain Driven Design
- Agile
- Product
- Test-Driven Development
- JWT
- RESTful Services

Highwire Press is a digital publishing solutions company that provides a range of services including digital content development, access management and hosting. The software development team heavily relies on the domain driven design methodology and test driven development.

Part of the product development team for SAMSigma, a “SaaS” solution. Employing Agile principles including fast iterations (worked within sprints), the establishing of requirements as a team (regular backlog refinement meetings where future requirements were fleshed out) and daily stand ups. Acted in the role of “scrum master” which responsibilities included the organising of sprint associated meetings for the team and creating interesting methods for carrying out sprint retrospectives (where any good points or issues about the last sprint were raised). 

## Education

### Birkbeck College

#### Computation and Cognition

2022 October - Present

- Cognitive Science
- Psychology
- Computational Modelling
- Research

### University of Sussex

#### Music Informatics

2012 August - 2015 May

- Computer Science
- Digital Music
- Artificial Intelligence
- Natural Language Engineering

The course focused on the broader field of computer science with modules specializing in artificial intelligence and digital music. My dissertation combined web scraping technology with music information retrieval and a neural network model focused on semantic similarity.

## Skills

Server Side

- [x] Python
- [ ] Unix
- [ ] Java
- [ ] Node
- [ ] Rust
- [ ] PHP
- [ ] Haskell

Client-side

- [x] Vue
- [ ] Typescript
- [ ] React
- [ ] Sass
- [ ] AngularJs
- [ ] JQuery

Web Frameworks

- [x] Spring
- [ ] Laravel
- [ ] Express
- [ ] Flask

Storage Management

- [x] MySQL
- [ ] SQLAlchemy
- [ ] MongoDb
- [ ] S3
- [ ] PostgreSQL
- [ ] ElasticSearch

Deployment and Container Orchestration

- [x] AWS
- [ ] Jenkins Pipelines
- [ ] Heroku
- [ ] Docker
- [ ] RabbitMQ

Testing Frameworks

- [x] Mockito
- [ ] PyTest
- [ ] Jest

## Honours

### Certified Cloud Practitioner

### Best In Show 2010

Young Rewired State - National Hackathon Competition
