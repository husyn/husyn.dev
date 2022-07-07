---
layout: post
author: husyn
title:  "DevOps / Systems Engineering Tools"
categories: [ devops, cloud, tools, systems-engineering ]
tags: []
---

Originally posted at [iHusyn](https://ihusyn.wordpress.com/2018/09/09/devops-tools/)

These are some of the tools which I have used or considered for my projects as DevOps practitioner / SRE implementer

## CI Tools

- [TeamCity](https://www.jetbrains.com/teamcity/) Open source, free 3 agent & 100 Build Configs    
- [BuildKite](https://buildkite.com/) Simpler then old 
school CI Servers. UI as SaaS. Agents are loosly coupled
- [TravisCI](https://travis-ci.org/) / [CircleCI](https://circleci.com/)
- [Bamboo](https://www.atlassian.com/software/bamboo) Atlassian product. Gels well with Bitbucket and JIRA
- [Jenkins](https://jenkins.io/) Would not use this if absolute necessary!

## CD Tools
- [CodeDeploy](https://aws.amazon.com/codedeploy/) Deployment on AWS Cloud
- [Spinnaker](https://www.spinnaker.io/) Continuous Delivery for Enterprise (same as CodeDeploy). Fits in K8s eco system

## (Code) Quality
- [SonarQube](https://www.sonarqube.org) Source Code scanning (Continuous Inspection)
- [VeraCode](https://www.veracode.com) Focused on security
- [SNYK](https://snyk.io)

## Monitoring
- [Aplas](https://aplas.com/public) Maps software applications on Map like canvas
- [Graphite](http://hostedgraphite.com/) Dashboard (visualisation) tool
- Dynatrace
- AppDynamics

## Infrastructure as Code
- [Terraform](https://www.terraform.io/) create and maintain infrastructure as a code. (multi-cloud, external CDN & DNS)
- [AWS CDK](https://aws.amazon.com/cdk/) Programming language based CloudFormation abstraction

## Practices
DevOps is a set of practices and/or mindset which demands more than tools and their automated usage. Some of the practices which I follow or plan to follow is below:

- [Versioning](https://semver.org/) how to version software releases
- [TechRadar](https://github.com/thoughtworks/build-your-own-radar) A library that generates an interactive radar, inspired by http://thoughtworks.com/radar/ It's more of a communication tool in an organisation.
- CNCF (Cloud Native Computing Foundation)’s [trail map](https://github.com/cncf/trailmap) for companies starting on Cloud

## BigData
- [Presto](https://prestodb.io/) Distributed SQL Query Engine for Big Data
- [Apache Avro](https://avro.apache.org/) Apache Avro™ is a data serialization system

## Data format

- [Apache Parquet](https://parquet.apache.org/)
- YML
- KDL

## Microservices
- [Docker](http://docker.io/)
- [Kubernetes](https://kubernetes.io/)
- [Istio](https://istio.io) 
- [Eureka](https://github.com/Netflix/eureka)Netflix’s Service registry/discovery
- [Linkerd](https://linkerd.io/) Ultralight service mesh for Kubernetes and beyond

## Feature Toggle
- [Unleash](https://unleash.github.io/)
- [Launch Darkly](https://launchdarkly.com)

## Secrets Management
- [SOPS](https://github.com/mozilla/sops) Created by Mozilla, uses AWS KMS for the master key to encrypt files based on yml configurations
- [Hashicorp Vault](https://www.vaultproject.io/) 
- [Shush](https://github.com/realestate-com-au/shush) AWS KMS based encryption and command shim

## Performance Measure
- [GTmetrix](https://gtmetrix.com/) 
- [Pingdom](https://www.pingdom.com/) 
- [WebPageTest](https://www.webpagetest.org/) 

## Documentation
- [Mermaid](https://github.com/mermaid-js/mermaid) Generation of diagram and flowchart from text in a similar manner as markdown
- [Diagram As Code](https://github.com/mingrammer/diagrams) Python based tool to create cloud diagrams

## Specialised Tools
- [ProxySQL](https://www.proxysql.com/) layer 7 SQL-aware load balancer for MySQL
- [Reliability Calculator](https://www.gremlin.com/reliability-calculator/) a simple calculator which shows the rating of Reliability of a System
- [DevOps Calculator](https://www.devops-research.com/quickcheck.html) Google Cloud based calculator which is based on DORA
