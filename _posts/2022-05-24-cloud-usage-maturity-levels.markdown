---
layout: post
author: husyn
title:  "Cloud usage maturity levels"
categories: [cloud, aws, devops, cloud adoption, maturity level]
tags: []
image: assets/images/cloud-usage-maturity-levels.png
---

## Introduction

From morning till night we interact with infinite things and all of them have a unit of measurement. Temperature, weight, our cars fuel tank, etc. All such units help us understand the level quantity and/or quality of something. We have to measure the level of expertise and complexity as well which is done well in higher education area. Whenever we read level **101** it is apparent that content is introductory in nature. And when something is level **400s** then it is expert level. This doesn't look like a world changing idea but it has a great deal of importance. Form [Fredonia University](https://www.fredonia.edu/apcaas/guidelines-numbering-courses-undergraduate-level) pages I found below definitions of course numberings. I'll also share the relevant Cloud trainings or courses in alignment with these levels.

### Level 100 - Introductory

Introductory courses where no pre-requisite is required. Definitions and basic knowledge is offered without application or analysis.

Training sessions are focused on providing an overview of Cloud services and features, with the assumption that attendees are new to the topic. Building blocks (Cloud Services) are introduced and their purpose is expected rather than their workings or usage. 

### Level 200 - Intermediate

Often have level 100 as pre-requisites and now the knowledge acquired should be at a level where it can be applied.

It is assumed that basic understanding of services are there. Sessions are focused on implementation of services and how to combine them in a project.

### Level 300 - Advanced

These courses teach the complex ideas in application and analysis of ideas. It is expected that anyone at this level can independently develop using what they have learned and improve it.

At this level specific area of interest is targeted like DevOps, AI, Microservices, Networking, etc. Now the topics are not generic in nature and industry best practices are discussed. Ideas like optimisations are continuous improvement live at this stage.

### Level 400 - Expert

These courses are not public in nature and are under wisdom umbrella rather than knowledge. Only knowing is not enough at this level and critical thinking is essential to compare and contrast ideas.

Trainings or discussions are for attendees who are deeply familiar with the topic, have implemented a solution on their own already, and are comfortable with how the technology works across multiple services, architectures, and implementations.

## AWS Specifics

AWS in their certifications and trainings (both classroom and on-line) categorise the content in two levels. It doesn't maps with the generic course levels but does a good job at dividing the expertise level into multiple areas. The two main levels are Fundamental and Advanced. 

### Fundamental Level
 
A developer who is new to AWS or at the fundamental level have experience in developing, testing, deploying and debugging AWS applications. A job at this level include:
 
#### Development

- Write code suited for AWS environment    
- Basic Cloud Native development

#### Deployment

- Build and manage deployment artifacts on AWS
- Use AWS continuous integration and continuous delivery (CI/CD) services for automation

#### Security

- Implement authentication and/or authorization for applications and AWS services
- Implement encryption using AWS services

#### Maintenance and Operations

- Implement observability using AWS Services
- Optimize applications using AWS services and features
 
### Advanced Level
 
At this level few years of AWS usage is recommended. All the knowledge in fundamental should be there and developers should have experience and expertise in designing and developing highly available, fault-tolerant, secure, and scalable applications on AWS. Designing a system from requirements is a must at this level. A job at this level include:
 
#### Planning and Design
- Required to understand designing a system given constraints like availability, cost, technology stack, etc.
- Determine design patterns to meet organizational or project requirements
- Select best suited AWS services to support design and non-functional requirements

#### Development & Deployment
- Select best suited tech stack with industry best practices
- Understand re-usability and modular design
- Design and manage deployment artifacts lifecycle
- Implement high cohesive and low coupled applications

#### Testing
- Develop automated unit, load, and integration tests
- Come up with scalability and multi-region requirements based on continuous testing
- Analyse results from automated tests and improve the system

#### Security

- Implement security for users and applications alike
- Implement security for data and integrations
- Define and implement run sheets for attacks and security breaches

#### Observability and Monitoring
- Instrument application code
- Implement processes like incident management
- Debug application code issues
- Troubleshoot application code, data and integration issues

## Organisational Use

Every organisation have to develop some kind of policies / rules around the competency of their employees. This competency decides career paths, promotions and compensations. How awesome it would be that every organisation clearly document this and make this public to (at least) all the employees, then a lot of debate and waste can be eliminated. Alas, our world is not perfect! 

However I love that AWS has this sorted out in their certifications. Level 100 is the practitioner certificate. Level 200 can be mapped to associate level certificates. 300 or 400 level to Professional ones and Speciality ones. There's still lot of wisdom which can't be tested or exhibit by any certification. That could be level 500s which is specialised and reserved for PhD level studies. Large Enterprises have complexities which require skillset at this 500 level. That's one of the reason that still a lot of businesses are not 100% cloud native or taking a slow route towards it.

## Update
Similar to Cloud maturity model, Dario Goldfarb from AWS shared a [Security Maturity Model](https://maturitymodel.security.aws.dev/en/). It is nice to have these basic knoledge documented and available for everyone to guage where are they in terms of security.

