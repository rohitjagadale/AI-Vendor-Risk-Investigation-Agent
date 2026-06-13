# 🤖 AI Vendor Risk Investigation Agent

> Autonomous Multi-Agent Enterprise Risk Intelligence Platform for Vendor Onboarding & Compliance Verification

## 📌 Overview

AI Vendor Risk Investigation Agent is an autonomous multi-agent AI platform designed to modernize enterprise vendor onboarding and compliance verification.

The solution leverages Microsoft Copilot Studio, AI Builder, Power Automate, SharePoint, Computer Use, and GPT-powered reasoning to automate vendor investigations, risk assessments, compliance validation, and reporting.

Instead of relying on manual verification processes, multiple specialized AI agents collaborate to perform end-to-end vendor due diligence, reducing operational effort, improving accuracy, and enhancing governance.

---

## 🚀 Problem Statement

Traditional vendor onboarding processes are often:

- Manual and time-consuming
- Prone to human errors
- Vulnerable to fraud and duplicate vendors
- Difficult to audit and govern
- Slow in generating compliance reports

Organizations face risks from:

- Fake suppliers
- Fraudulent onboarding
- Compliance violations
- Poor verification processes

The need for an intelligent, scalable, and autonomous vendor verification platform inspired this solution.

---

## 💡 Solution

The AI Vendor Risk Investigation Agent autonomously investigates vendors using a collaborative multi-agent architecture.

### Supported Modes

### 1️⃣ Event-Driven Automation
Automatically triggers when a vendor onboarding email is received.

### 2️⃣ Interactive Copilot Experience
Users can directly interact with the system through Copilot Chat.

The platform generates:

- Vendor Verification Status
- AI Risk Score
- Explainable Risk Reasoning
- Investigation Summary
- Compliance Recommendations

---

## 🏗️ Architecture

```text
Vendor Email / Copilot Chat
            │
            ▼
     Intake Agent
            │
 ┌──────────┼──────────┐
 ▼          ▼          ▼
Blacklist  Document   GST
Agent      Agent      Agent
                         │
                         ▼
                   Computer Use

 ▼
Web Presence Agent
 ▼
AI Risk Scoring Agent
 ▼
Communication Agent
 ▼
Investigation Report
```

---

## 🤝 Multi-Agent Collaboration

### 📥 Intake Agent
- Receives onboarding requests
- Extracts vendor metadata
- Initializes investigations

### 🚫 Blacklist & Duplicate Detection Agent
- Detects duplicate vendors
- Identifies blacklisted entities
- Validates master records

### 📄 Document Intelligence Agent
- Reads onboarding documents
- Extracts structured data
- Performs validation checks

### 🏢 GST Verification Agent
- Uses Computer Use
- Verifies GST registrations
- Retrieves official vendor details

### 🌐 Web Presence Agent
- Analyzes vendor websites
- Validates digital credibility
- Detects suspicious online activity

### 📊 AI Risk Scoring Agent
- Aggregates findings from all agents
- Calculates risk scores
- Generates explainable reasoning

### 📢 Communication Agent
- Generates investigation summaries
- Sends notifications
- Shares final recommendations

---

## 🔍 Key Features

- Autonomous Multi-Agent Investigation
- Computer Use Automation
- AI-Powered Document Intelligence
- Duplicate Vendor Detection
- Blacklist Verification
- GST Verification
- Website Credibility Analysis
- Explainable AI Risk Scoring
- Event-Driven Workflow Automation
- Human-in-the-Loop Governance
- Enterprise Auditability

---

## 🖥️ Computer Use Integration

One of the most innovative capabilities of the platform is the use of Microsoft Copilot Studio Computer Use.

The GST Verification Agent can autonomously:

- Open browser
- Navigate to GST portal
- Enter GST number
- Retrieve official details
- Return structured results

Benefits:

✅ Reduced manual effort  
✅ Faster verification  
✅ Improved accuracy  
✅ Scalable operations  
✅ Autonomous investigations

---

## 📊 AI Risk Scoring Engine

The AI Risk Scoring Agent evaluates:

- Duplicate vendors
- Blacklist presence
- GST mismatches
- Invalid documents
- Missing information
- Suspicious web presence
- Compliance inconsistencies

### Risk Classification

| Score | Classification |
|---------|---------------|
| 0-30 | Low Risk |
| 31-70 | Medium Risk |
| 71-100 | High Risk |

### Explainable AI Example

```text
Vendor classified as High Risk due to:
- GST mismatch
- Missing website credibility
- Duplicate vendor indicators
```

---

## 🔄 End-to-End Workflow

1. Vendor onboarding email received
2. Power Automate triggers workflow
3. Documents stored in SharePoint
4. Multi-agent investigation starts
5. GST verification via Computer Use
6. Website credibility validation
7. AI risk assessment generated
8. Investigation report created
9. Human review and approval

---

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|---------|
| Microsoft Copilot Studio | AI Orchestration |
| Power Automate | Workflow Automation |
| AI Builder | Document Intelligence |
| SharePoint | Document Storage |
| Dataverse | Structured Data |
| Computer Use | Browser Automation |
| Outlook | Trigger Source |
| GPT Models | AI Reasoning |

---

## 🔐 Security & Governance

### Governance Features

- Human Approval Workflow
- Centralized Audit Trail
- Role-Based Access
- Secure Document Storage
- Traceable Investigation History

### Responsible AI

- Human-in-the-Loop Validation
- Explainable AI Decisions
- Transparent Risk Scoring
- Controlled Automation

---

## 📈 Business Impact

### Operational Benefits

- Up to 80% reduction in manual effort
- Faster vendor onboarding
- Improved fraud detection
- Enhanced compliance visibility
- Better audit readiness

### Business Value

- Reduced compliance risk
- Increased operational efficiency
- Scalable verification process
- Improved enterprise governance

---

## 🔮 Future Enhancements

- ERP Integration
- Advanced Fraud Detection Models
- Real-Time Monitoring Dashboards
- Multi-Language Vendor Support
- Predictive Risk Intelligence
- Vendor Reputation Monitoring

---

## 📷 Demo

### Vendor Investigation Lifecycle

1. Email-based onboarding trigger
2. AI-powered document analysis
3. GST verification using Computer Use
4. Website credibility assessment
5. AI risk score generation
6. Automated investigation report

---

## 🏆 Innovation Highlights

- Multi-Agent AI Architecture
- Autonomous Investigation Workflow
- Computer Use Automation
- Explainable AI
- Enterprise Governance Focus
- Human-in-the-Loop Compliance

---

## 👨‍💻 Built With

- Microsoft Copilot Studio
- Power Automate
- AI Builder
- SharePoint
- Dataverse
- GPT Models
- Computer Use

---

## 📜 License

This project was developed as part of an AI Innovation / Hackathon initiative to demonstrate autonomous enterprise risk investigation using Microsoft AI technologies.

---

### ⭐ If you found this project interesting, consider giving it a star!
