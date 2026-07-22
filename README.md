# 🚀 AI Lead Intelligence & Scoring Agent

An automated, real-time lead qualification pipeline built using **n8n**, **Groq Cloud API (LLMs)**, and **Discord Webhooks**. 

This system ingests incoming sales leads, evaluates their company profile, calculates a **Fit Score (0-100)** with clear reasoning, drafts a personalized cold email pitch, and dispatches real-time alerts to Discord—all in **under 3 seconds**.

---

## 💡 The Problem Solved

Sales and outreach teams often lose high-ticket opportunities due to slow lead qualification. Manually reviewing company domains, scoring fit, and writing custom outreach emails takes **15-20 minutes per lead**. 

**This AI Agent reduces that time to 0 manual minutes.**

---

## ⚡ Key Features

- **Instant Ingestion:** Webhook-driven trigger that captures lead data (Name, Email, Company, Website).
- **AI Qualification Engine:** Uses Groq Cloud's fast LLM inference to score lead fit (0-100) based on industry relevance and company size.
- **Automated Personalization:** Generates a custom cold email pitch tailored specifically to the lead's domain/niche.
- **Real-Time Discord Alerts:** Formats and dispatches organized alert cards to sales channels for immediate action.

---

## 🛠️ Tech Stack & Integration

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Orchestrator** | `n8n` | Workflow automation engine |
| **AI Model** | `Groq Cloud API` | High-speed LLM evaluation & email generation |
| **Logic Layer** | `JavaScript / JSON` | Data formatting and prompt engineering |
| **Alerting** | `Discord API` | Real-time sales team notification |

---

## 🚀 How to Import and Run

1. Clone this repository.
2. Import the `My workflow 11.json` file directly into your **n8n** instance.
3. Add your **Groq API Key** in the HTTP Request / AI node credentials.
4. Replace the Discord Webhook URL with your own channel webhook endpoint.
5. Activate the workflow and send a test POST payload!

---

*Building AI Automations in Public | Day 4/30* 🚀
