# adf-logicapp-poc
This project is a Proof of Concept (POC) that demonstrates how to integrate Azure Data Factory (ADF) with Azure Logic Apps for automated failure notifications.

The solution simulates a failing pipeline in ADF and triggers a Logic App workflow that sends an email alert when the pipeline fails. This showcases how cloud-native orchestration and monitoring can be combined to improve data pipeline reliability and incident response times.

## Key Features:

  -Built an ADF pipeline to simulate data ingestion and processing
  
  -Configured a failure scenario to test monitoring
  
  -Integrated Logic App to capture ADF pipeline run status via trigger
  
  -Automated email notifications with pipeline details upon failure.


## Tech Stack:

Azure Data Factory (Pipeline Orchestration)\
<img width="729" height="258" alt="Screenshot 2025-09-20 at 3 20 31 pm" src="https://github.com/user-attachments/assets/db776919-eb01-48e9-a300-370d7e629193" />


Azure Logic Apps (Event-driven automation)

<img width="303" height="293" alt="Screenshot 2025-09-20 at 3 20 45 pm" src="https://github.com/user-attachments/assets/79c8d414-4b8b-4bb8-b0f9-f9070dda6b3e" />

Use Cases:

Real-time alerting for failed data pipelines.

Improved monitoring and observability in data platforms.

⚠️ Security Note: This template has been sanitized. Replace <LOGIC_APP_TRIGGER_URL> and dataset references with your actual values before deploying
⚠️ Security Note: This Logic App template has been sanitized. Replace placeholders (<YOUR_EMAIL>, <SUBSCRIPTION_ID>, <RESOURCE_GROUP>, <CONNECTION_NAME>) with your actual values before deployment.
