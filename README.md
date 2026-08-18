# n8n Workflow

This directory contains the sanitized n8n workflow used as the automation layer for the AI Receptionist.

## Workflow Responsibilities

The workflow can be used to:

1. Receive data from the AI agent
2. Validate incoming information
3. Process customer data
4. Call external APIs or tools
5. Store or retrieve information
6. Execute business logic
7. Return structured results

## Example Flow

```text
Webhook
   ↓
Input Validation
   ↓
Data Processing
   ↓
Business Logic
   ↓
External API / Tool
   ↓
Result Processing
   ↓
Response
```

## Importing into n8n

1. Open your n8n instance.
2. Create a new workflow.
3. Import the JSON workflow.
4. Configure the required credentials.
5. Update environment-specific URLs.
6. Test using demo data.

> The included workflow is sanitized and does not contain production credentials.
