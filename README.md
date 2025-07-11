# AI-mail-agent
An intelligent email assistant built with n8n and Gmail API, enabling automated email processing—like summarization, labeling, drafting, and replying—using AI. It leverages a Google Cloud OAuth2 or Service Account credential setup for seamless Gmail integration. 


**#Description of content**
This file contains the full JSON workflow encoded in JS, designed to run in n8n. It includes:

Trigger: Watches for new Gmail messages using the Gmail node

AI Processing: Sends message content to an AI node for summarization, labeling, or drafting

Action Nodes: Uses Gmail node operations to reply, draft, label, and archive emails

Modular Logic: Structured using functions and reusable blocks for scalability

**#Usage:**

In n8n, create a new workflow.

Click “Import” → “From file” and select this JS file.

Connect your Gmail and AI credentials.

Activate and monitor as needed.
