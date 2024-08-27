---
title: "AWS Workshop for temporal.io customers"
weight: 0
---


### What will customers learn from this workshop.
 ##### 1. What is Durable Execution?
Durable Execution is a new abstraction.
It is a fault-oblivious development model that preserves full application state in the case of any host or software failure.
It ensures your apps and end-to-end services are correct and reliable.

 ##### 2. How failures affect Normal process execution?
If you application is built for High availability (HA), your program will be rehydrated on another server in the exact state at time of failure. Response comes (seconds or days later) and the function returns.

 ##### 3. How failures are handled in Durable execution?
You do not need to code for failure scenarios.
You can run a function or wait for an API for a year.
You don't need a db, because variables are durable.

##### 4. Getting started with temporal platform workshop. 
- Write a Temporal Workflow in your language using a Temporal SDK - Using Python
- Write activities to hold the failure-prone parts of your code that can be automatically retried upon some failure.
- Deploy your application on your infrastructure in your environment using all your standard deployment methods.
- Your application coordinates with a Temporal Service which retains state and manages the completion of your activities.
      - If your app crashes or sleeps, the service can rehydrate any process, anywhere.
      - You can self-host or use Temporal Cloud