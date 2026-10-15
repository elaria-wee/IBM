# IBM Account Opening Workflow

This repository documents an **Account Opening** business process designed in IBM Automation Workflow. The workflow guides a customer account request from submission through validation, review, account creation, and customer notification.

## Workflow overview

1. A customer enters an account-opening request.
2. The request is submitted and validated.
3. If validation fails, the customer is asked to correct the information and submit it again.
4. A valid request is sent for identity verification and compliance review.
5. When the review is approved, the account is created.
6. Confirmation and internal account-opening activities run in parallel.
7. The customer is notified when the process is complete.

## Main process elements

- Customer-facing tasks for entering requests and correcting submitted data
- Service activities for request submission, validation, status return, account creation, and notification
- Exclusive gateways to route valid and invalid requests
- Parallel gateways for compliance, confirmation, and internal account-opening work
- Events for coordinating the end of workflow stages

## Prerequisites

To open or modify the process, use an environment with IBM Automation Workflow Designer (or the corresponding IBM Business Automation Workflow tools) and access to the target workflow application.

## Getting started

1. Open the workflow application in IBM Automation Workflow Designer.
2. Locate the `AccountOpening` process definition.
3. Review or update its variables, user interface, service integrations, and task assignments for your environment.
4. Validate and deploy the workflow following your organization's IBM Automation Workflow release process.

## Notes

This repository currently provides project documentation. Exported workflow artifacts and environment-specific configuration are not included.

## License

No license has been specified for this project.
