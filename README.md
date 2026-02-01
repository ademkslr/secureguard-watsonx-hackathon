# SecureGuard - Intelligent Compliance Guardian

**Team Submission for IBM watsonx Orchestrate Hackathon**

## 🛡️ Project Overview
SecureGuard is an agentic AI solution designed to prevent data leakage in banking communications. Built on **IBM watsonx Orchestrate**, it acts as a proactive compliance officer embedded directly within Slack.

## 🚀 Key Features
* **Real-time Intent Analysis:** Detects risky behavior (e.g., sharing IBANs or PII) using LLM reasoning.
* **RAG (Retrieval Augmented Generation):** Answers policy questions based on the "2024 Bank Policy" PDF.
* **Automated Auditing:** Uses custom Tool-Calling to log security violations directly into an **IBM Cloudant** NoSQL database.

## 🛠️ Technology Stack
* **Platform:** IBM watsonx Orchestrate
* **Model:** Llama 3 (via watsonx.ai)
* **Integration:** Slack (Frontend), IBM Cloudant (Backend Database)
* **Tools:** Custom OpenAPI Extension for database logging

## 📂 Repository Structure
* `prompts/` - Contains the system instructions used to govern the agent's behavior.
* `extensions/` - The OpenAPI specification used to connect the agent to IBM Cloudant (Sanitized).
* `data/` - The sample policy document used for the Knowledge Base.

## 🎥 Demo Video
https://youtu.be/E_BGD0klwNM

---
*Created by Adem Köseler*
