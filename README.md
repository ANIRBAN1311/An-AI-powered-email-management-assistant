# 🤖 Email Agent

An AI-powered email management assistant workflow built with **n8n** and **OpenAI GPT-4o**.

## Overview

The **Email Agent** automates email management by understanding natural language commands and performing tasks such as sending emails, creating drafts, retrieving emails, replying, labeling, and marking emails unread. All emails are formatted professionally in HTML and signed off as "Nate."

---

## Features

- Send professionally formatted HTML emails  
- Create email drafts on demand  
- Retrieve emails with filters (sender, limit, etc.)  
- Reply to emails intelligently  
- Label and organize emails  
- Mark emails as unread  
- Powered by OpenAI GPT-4o for natural language understanding  
- Integrates with Gmail API using OAuth2  
- Built using n8n workflow automation platform  

---

## How It Works

1. User inputs a natural language email-related request.  
2. OpenAI GPT-4o interprets the request and generates instructions.  
3. The workflow executes Gmail operations accordingly (send, reply, draft, label, etc.).  
4. Success or error responses are provided.

---

## Tech Stack

- **n8n**: Workflow automation tool  
- **OpenAI GPT-4o**: Language model for AI understanding and generation  
- **Gmail API (OAuth2)**: For sending and managing emails  

---

## Getting Started

### Prerequisites

- n8n instance (cloud or self-hosted)  
- OpenAI API key (with GPT-4o access)  
- Gmail account with OAuth2 configured in n8n  

### Installation

1. Import the workflow JSON file into your n8n instance.  
2. Configure OpenAI and Gmail OAuth2 credentials.  
3. Activate the workflow.  
4. Use natural language commands to manage emails.

---

## Example Commands

- "Send an email to anirban@example.com confirming tomorrow's meeting."
- "Create a draft to my manager about project updates."  
- "Reply to the latest email from Alex thanking them for the report."  
- "Label all unread emails from marketing as 'Marketing'."  
- "Mark the last email from finance as unread."

