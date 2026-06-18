# Agentic Email Manager

An AI-powered email assistant built in n8n that can read emails, send messages, and maintain conversation memory.

## Business Problem

Professionals spend hours every week managing email communications.

Common challenges include:

* Inbox overload
* Repetitive email tasks
* Slow response times
* Lack of context between conversations

This workflow creates an AI email assistant capable of handling common email management tasks.

---

## Workflow Architecture

```text
Chat Interface
      │
      ▼
AI Agent
      │
 ┌────┴─────┐
 ▼          ▼
Read Email  Send Email
  Tool       Tool
      │
      ▼
Conversation Memory
```

---

## Integrations Used

### OpenAI GPT

Understands requests and determines actions.

### Gmail

Reads inbox messages and sends emails.

### n8n Chat Trigger

Provides a conversational interface.

### Memory Buffer

Maintains conversation context.

---

## Expected Outcomes

✅ Read recent emails

✅ Retrieve unread messages

✅ Send emails using natural language

✅ Maintain conversation history

✅ Improve productivity

✅ Reduce inbox management effort

---

## Setup Instructions

### 1. Import Workflow

Import:

```text
Agentic Email Manager.json
```

### 2. Connect OpenAI

Add your OpenAI API credentials.

### 3. Connect Gmail

Authorize Gmail using OAuth2.

### 4. Test Workflow

Try prompts such as:

```text
Show me my latest emails

Read unread emails

Send an email to john@example.com
```

---

## Download

[Agentic Email Manager.json](./Agentic%20Email%20Manager.json)

---

## Author

Kenneth Soriano

Sales & AI Automation Specialist

Built with n8n, OpenAI, LangChain, and Gmail.
