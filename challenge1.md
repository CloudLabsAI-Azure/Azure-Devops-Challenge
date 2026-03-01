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

Please use the instructions provided below and follow the submission steps carefully:

Once you complete this challenge, you must:

1. Keep the below artifact ready to be uploaded:

   - A screenshot showing successful deployment of the provisioned resources in Azure.

1. Name the screenshot using the below naming convention:

   `<Your_Name>_<Challenge01>_<file01>_<Time_Stamp(HH:MM)>`

1. Navigate back to **Hackathon Portal** where you registered for the hackathon.

1. In the hackathon portal, select **Learning Resources** page.

   ![](./media/hackportalv2.png)

1. Scroll down to bottom, under **Upload Your Certificate**, click **upload Certificate** and upload the artifact that you have prepared earlier.

   ![](./media/hack2.png)

This submission is mandatory.

Failure to submit these artifacts will result in the challenge being marked as incomplete.

## Congratulations! You have successfully completed Challenge 1