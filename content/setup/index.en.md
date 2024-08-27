---
title : "Setup"
weight : 20
---



- Temporal is an open source platform for building highly scalable workflow automation and microservices orchestration. It was originally developed by Uber to handle large scale workflow orchestration for their ridesharing platform. 

- The main components of Temporal are the Temporal server, SDKs for various programming languages, and a web UI. The SDKs allow developers to write workflow logic that the Temporal server executes and scales. 

- It integrates with common databases like PostgreSQL, MySQL, MongoDB to persist workflow state. It also has plugins for message queues like Kafka, Redis for pub-sub. 

- Temporal provides reliable execution of workflows even in cases of machine failures, interrupts, etc. It handles work queueing, distributed coordination, fault tolerance, horizontal scalability automatically. 

- It supports various types of workflows including long-running processes, short transactions, scheduled jobs, etc. Workflows can be synchronous or asynchronous. 

- Temporal has visibility into workflow executions via auditing, metrics, and tracing. The web UI provides monitoring and visualization of workflows. 

- Use cases include order processing workflows, user onboarding flows, data processing pipelines, distributed cron jobs, and other business process automation scenarios requiring scalability and resilience. 

- Temporal is used by companies like Uber, Coinbase, Figure, Pitch, and others to run mission-critical workflows and orchestrate microservices at scale. 

#### So in summary, Temporal is a scalable open source workflow orchestration engine that reliably executes and coordinates various types of distributed workflows and microservices architectures
