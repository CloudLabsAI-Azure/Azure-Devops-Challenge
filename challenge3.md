## Day 03

# Challenge 3 – CI/CD Enablement for Microservices Application 

## Goal

Design and provision a microservices-ready backend platform using Infrastructure as Code, implement independent service-level pipelines that consume pre-built container images, enforce vulnerability scanning, and validate successful deployment.

This challenge focuses on architectural planning, container image management, and controlled service-level delivery.

---

## Challenge Overview

In this phase, you will transition from a monolithic delivery model to a microservices-based architecture.

Pre-built container images will be available in a public container registry.

Your responsibility is to:

- Plan the microservices deployment architecture in Azure.
- Provision the required backend platform using Infrastructure as Code.
- Consume and manage container images appropriately.
- Implement vulnerability scanning within service pipelines.
- Deploy services to your chosen endpoint.
- Validate successful service execution.

The emphasis is on platform readiness, secure image handling, and independent pipeline execution.

---

## Objectives

### 1. Microservices Architecture Planning

Before implementation, you must:

- Define the backend architecture required to support a microservices model.
- Identify required platform components such as:
  - Container hosting environment
  - Container registry
  - Networking configuration
  - Load distribution mechanism
- Consider high availability and service isolation in your design.

Outcome:
A clearly defined microservices deployment architecture prepared for provisioning.

---

### 2. Platform Provisioning Using Infrastructure as Code

- Create Infrastructure as Code templates (e.g., Terraform) to provision the backend platform.
- Deploy required Azure resources to host containerized services.
- Ensure configurations are parameterized and repeatable.
- Validate successful infrastructure provisioning.

Infrastructure must be:

- Declarative  
- Repeatable  
- Idempotent  

Outcome:
A provisioned backend platform capable of hosting microservices.

---

### 3. Independent Service-Level Pipelines

- Create separate pipelines for individual services.
- Configure pipelines to reference the container images.
- Integrate vulnerability scanning for container images within the pipeline.
- Enforce threshold-based progression (e.g., block deployment on critical vulnerabilities).
- Ensure pipelines execute independently.

You may design multiple stages per service as needed, provided progression is controlled.

Outcome:
Each service has a secure and independently controlled delivery workflow.

---

### 4. Deployment to Selected Endpoint

- Deploy services to your provisioned backend environment.
- Configure load distribution as part of your architecture.
- Validate deployment success.
- Ensure services are accessible via the defined endpoint.

Outcome:
Microservices are successfully deployed and reachable.

---

### 5. High Availability & Disaster Recovery Consideration

- Consider load balancing or traffic management mechanisms.
- Application Gateway with WAF may be included as an optional best practice.

Outcome:
Your architecture demonstrates resilience and operational awareness.

---

### 6. Functional Endpoint Validation

Once pipelines execute successfully:

- Access the deployed application endpoint.
- Validate basic functionality.
- Perform a simple user action such as adding a product to the cart.
- Confirm service integration and responsiveness.

Outcome:
Microservices deployment is functionally verified.

---

## Expected Outcomes

By the end of Challenge 3:

- Microservices architecture is defined.
- Backend platform is provisioned using Infrastructure as Code.
- Independent service pipelines are implemented.
- Vulnerability scanning is integrated and enforced.
- Services are deployed successfully.
- High availability and disaster recovery considerations are documented.
- Application endpoint is validated and functional.

---

## Completion Criteria

Please use the SharePoint endpoint provided below and follow the submission steps carefully:

```
will be added soon
```

Once you complete this challenge, you must:

1. Inside the folder created earlier with your name, create one more folder for challenge 03:

   `<challenge03>_<Timestamp>`

1. Upload the following artifacts:
   - Infrastructure as Code templates used to provision the backend platform.
   - YAML pipeline definitions for at least two services.
   - A screenshot showing successful service pipeline execution.
   - A screenshot showing functional validation (e.g., adding a product to the cart).

#### Platform provisioning, secure image handling, and functional validation are mandatory criteria for successful completion of this challenge.

## Congratulations! You have successfully completed Challenge 3