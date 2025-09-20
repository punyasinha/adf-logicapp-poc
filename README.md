# adf-logicapp-poc
This project is a Proof of Concept (POC) that demonstrates how to integrate Azure Data Factory (ADF) with Azure Logic Apps for automated failure notifications.

The solution simulates a failing pipeline in ADF and triggers a Logic App workflow that sends an email alert when the pipeline fails. This showcases how cloud-native orchestration and monitoring can be combined to improve data pipeline reliability and incident response times.

Key Features:

Built an ADF pipeline to simulate data ingestion and processing.

Configured a failure scenario to test monitoring.

Integrated Logic App to capture ADF pipeline run status via trigger.

Automated email notifications with pipeline details upon failure.


Tech Stack:

Azure Data Factory (Pipeline Orchestration)

Azure Logic Apps (Event-driven automation)

Use Cases:

Real-time alerting for failed data pipelines.

Improved monitoring and observability in data platforms.
