# customer-feedback-ai-agent

This is an AI-powered automation built with [n8n](https://n8n.io) that:

- Automatically reads user complaints or feedback
- Sends an acknowledgment email via Gmail
- Posts to Slack (if enabled)

### 🛠 Tech Used
- n8n (Self-hosted)
- Gmail API
- Slack Bot
- ngrok for public webhook URLs

### 🚀 How to Use
1. Import `feedback-acknowledgement-agent.json` into your n8n
2. Set up Gmail and Slack credentials
3. Trigger the workflow via webhook or manual input

### 🤖 Sample Output
Email:
> “Thanks for your feedback, our team has started working on it...”

Slack Message:
> “New complaint received and acknowledged automatically.”
