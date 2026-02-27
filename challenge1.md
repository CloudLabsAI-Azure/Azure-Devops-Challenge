## Day 01

# Challenge 1: Platform Setup & Infrastructure Provisioning

## Goal

Set up the delivery foundation by onboarding the provided monolithic application into Azure DevOps Repos and provisioning the required infrastructure using Infrastructure as Code.

This challenge establishes the base platform required for controlled and repeatable application delivery.

---

## Challenge Overview

You have already configured the Azure DevOps organization and project as prerequisites.

In this challenge, you will:

- Set up the repository using the provided GitHub monolithic application.
- Understand the application structure and prepare it for CI/CD integration.
- Define and provision the required infrastructure using Infrastructure as Code.
- Validate that the environment is ready for pipeline implementation.

The focus is on building a clean, repeatable, and controlled platform foundation.

## Monolithic Application Source

```
https://github.com/CloudLabsAI-Azure/contoso-electronics-monolith.git
```

---

## Objectives

### 1. Repository Setup and Application Onboarding

- Create a new repository inside the Azure DevOps project.
- Import or push the provided monolithic application from GitHub.
- Review and understand the application structure.
- Ensure the repository is organized and ready for pipeline integration.

Outcome:
The monolithic application is fully onboarded into Azure DevOps Repos and prepared for CI/CD enablement.

---

### 2. Infrastructure as Code Implementation

- Create Infrastructure as Code templates using a framework such as Terraform.
- Define the infrastructure required to support application deployment.
- Parameterize configurations to support repeatable deployments.
- Avoid hardcoded values wherever possible.
- Execute plan and apply operations to provision infrastructure.

Infrastructure provisioning must be:

- Repeatable  
- Consistent  
- Idempotent  

Outcome:
Infrastructure is provisioned successfully using IaC templates.

---

### 3. Infrastructure Validation

- Verify that all resources are successfully created in Azure.
- Confirm that the selected deployment endpoint is available.
- Ensure supporting resources required for application hosting are ready.
- Validate that the environment is prepared for CI pipeline integration in the next challenge.

Outcome:
Provisioned infrastructure is validated and confirmed ready for CI/CD implementation.

---

## Expected Outcomes

By the end of Challenge 1:

- The monolithic application is successfully onboarded into Azure DevOps Repos.
- Infrastructure as Code templates are created using Terraform (or equivalent framework).
- Infrastructure is provisioned successfully using IaC.
- The deployment environment is validated and ready.

---

## Completion Criteria (Mandatory Submission)

Please use the SharePoint endpoint provided below and follow the submission steps carefully:

```
will be added soon
```

Once you complete this challenge, you must:

1. Create a folder using the following naming convention:
   
   `<YourName>`

1. Inside the folder created earlier with your name, create one more folder for challenge 01:

   `<Challenge01>_<Timestamp>`

1. Upload the following artifacts inside that folder:
   - The Infrastructure as Code templates you created.
   - A screenshot showing successful deployment of the provisioned resources in Azure.

This submission is mandatory.

The uploaded Terraform templates and deployment screenshot will serve as the primary validation criteria for this challenge and form a major success indicator for the hackathon.

Failure to submit these artifacts will result in the challenge being marked as incomplete.

---

#### Proceed to Challenge 2 only after infrastructure provisioning has been successfully validated and submitted.

---

## Congratulations! You have successfully completed Challenge 1