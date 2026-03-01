## Day 03

# Challenge 3: CI/CD Enablement for Microservices Application 

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

## Microservices Application Source

The microservices version of the application used in the previous challenge is provided as a source code repository for reference.

This repository represents the application after transitioning from a monolithic architecture to a microservices-based model. You may review it to understand service separation, architecture design, and overall application structure.

### Source Code for Reference

```
https://github.com/CloudLabsAI-Azure/contoso-electronics-microservices.git
```

You may also directly leverage the public container images provided below within your CI/CD pipelines and deployment configuration, based on your preferred approach.

---

## Public Images of Microservices

Pre-built container images for each microservice are available for direct consumption.

### Gateway Service

```
https://hub.docker.com/r/cloudlabssrv/contoso-gateway
```

### Product Service  

```
https://hub.docker.com/r/cloudlabssrv/contoso-product-service
```

### Order Service

```
https://hub.docker.com/r/cloudlabssrv/contoso-order-service
```

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

Please use the instructions provided below and follow the submission steps carefully:

Once you complete this challenge, you must:

1. Keep the below artifact ready to be uploaded:

   - A screenshot showing successful service pipeline execution of atleast two services.
   - A screenshot showing the deployment endpoint.

1. Name the screenshot using the below naming convention:

   - `<Your_Name>_<Challenge03>_<file01>_<Time_Stamp(HH:MM)>`
   - `<Your_Name>_<Challenge03>_<file02>_<Time_Stamp(HH:MM)>`
   - `<Your_Name>_<Challenge03>_<file03>_<Time_Stamp(HH:MM)>`

1. Navigate back to **Hackathon Portal** where you registered for the hackathon.

1. In the hackathon portal, select **Learning Resources** page.

   ![](./media/hackportalv2.png)

1. Scroll down to bottom, under **Upload Your Certificate**, click **upload Certificate** and upload the artifact that you have prepared earlier.

   ![](./media/hack2.png)

This submission is mandatory.

Failure to submit these artifacts will result in the challenge being marked as incomplete.

## Congratulations! You have successfully completed Challenge 3