# n8n Lead Capture CRM System

A production-style Lead Capture & CRM Automation workflow built with n8n.

## Workflow Preview

![Workflow Overview](docs/screenshots/workflow-overview.png)

---

# Features

- Lead Capture via Webhook
- Data Normalization
- CRM Storage using Google Sheets
- Lead Scoring System
- Telegram Notifications
- Automated Email Replies

---

# Workflow Architecture

Webhook Trigger
→ Normalize Lead Data
→ Store Lead in CRM
→ Calculate Lead Score
→ Send Lead Alert
→ Send Auto Reply

---

# Folder Structure

```text
n8n-lead-capture-crm/
├── workflows/
│   └── lead-capture-crm.workflow.json
├── docs/
│   └── screenshots/
│       └── workflow-overview.png
├── sample-data/
├── templates/
├── README.md
├── .env.example
└── LICENSE
```

---

# Setup Guide

## 1. Import Workflow

Import:
`workflows/lead-capture-crm.workflow.json`

into your n8n instance.

## 2. Configure Credentials

Connect:
- Google Sheets OAuth
- Telegram Bot API
- Gmail OAuth

## 3. Activate Workflow

Enable the workflow and use the webhook endpoint for lead intake.

---

# License

MIT
