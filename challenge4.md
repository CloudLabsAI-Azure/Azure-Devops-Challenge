## Day 04

# Challenge 4: Traceability & Operational Validation

## Goal

Introduce traceability, and operational visibility to ensure that the delivery system is production-ready, auditable, and controlled.

This challenge focuses on integrating pipelines with work tracking, enforcing failure visibility, enabling cost awareness, and validating the complete end-to-end workflow.

---

## Challenge Overview

A successful CI/CD implementation is not complete without traceability.

In this challenge, you will:

- Integrate Azure DevOps Pipelines with Azure Boards.
- Automatically generate work items upon pipeline failures.
- Configure subscription-level budgets and notifications.

The objective is to ensure visibility, accountability, and operational control across the entire delivery process.

---

## Objectives

### 1. Azure Boards Integration

- Configure integration between Azure Repos, Pipelines, and Azure Boards.
- Ensure commits can be linked to work items.
- Enable traceability from work item - commit - pipeline - deployment.

Outcome:
Clear linkage exists between development activities and delivery outcomes.

---

### 2. Automatic Work Item Creation on Pipeline Failure

- Configure pipeline behavior so that failures result in automatic work item creation.
- Ensure failure details are captured clearly.
- Validate that the generated work item references the pipeline execution.

Outcome:
Pipeline failures trigger traceable and actionable work items.

---

### 3. End-to-End Traceability Validation

Demonstrate that:

- A work item is linked to a commit.
- The commit triggers a pipeline.
- The pipeline execution result is traceable.
- Deployment outcome is visible.

Outcome:
Full lifecycle traceability is established and verifiable.

---

### 4. Subscription-Level Governance

- Configure a budget at the subscription or resource group level.
- Enable cost threshold alerts.
- Configure notification mechanisms for budget limits.
- Validate alert configuration.

Outcome:
Cost governance and operational awareness are established.

---

## Expected Outcomes

By the end of Challenge 4:

- Azure Boards is integrated with repositories and pipelines.
- Pipeline failures automatically generate work items.
- Traceability exists across work items, commits, pipelines, and deployments.
- Subscription-level budgets and notifications are configured.

---

## Completion Criteria

Please use the instructions provided below and follow the submission steps carefully:

Once you complete this challenge, you must:

1. Keep the below artifact ready to be uploaded:

   - A screenshot showing work item creation triggered by a pipeline failure.
   - A screenshot of configured budget and alert notification.

1. Name the screenshot using the below naming convention:

   - `<Your_Name>_<Challenge04>_<file01>_<Time_Stamp(HH:MM)>`
   - `<Your_Name>_<Challenge04>_<file02>_<Time_Stamp(HH:MM)>`

1. Navigate back to **Hackathon Portal** where you registered for the hackathon.

1. In the hackathon portal, select **Learning Resources** page.

   ![](./media/hackportalv2.png)

1. Scroll down to bottom, under **Upload Your Certificate**, click **upload Certificate** and upload the artifact that you have prepared earlier.

   ![](./media/hack2.png)

This submission is mandatory.

Failure to submit these artifacts will result in the challenge being marked as incomplete.

## Congratulations! You have successfully completed Challenge 4