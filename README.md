# Incident Triage Automation (n8n + VirusTotal)

## 📌 Project Overview
This project is an automated incident triage system built using n8n. It processes emails containing IP addresses, analyzes them using the VirusTotal API, and sends alerts for malicious activity.

## ⚙️ Workflow Components
- Email Trigger (IMAP)
- JavaScript Code Node (IP extraction)
- HTTP Request (VirusTotal API)
- IF Node (malicious detection logic)
- SMTP Email Alert

## 🔄 Workflow Flow
Email → Extract IP → VirusTotal Check → IF Condition → Email Alert

## 🧠 Key Features
- Email-based trigger system
- Real-time threat intelligence analysis
- Automated security alerting
- SOC-style incident response workflow

## 📁 Files
- incident-triage-n8n-workflow.json (n8n exported workflow)

## 🚀 Outcome
A fully automated cybersecurity workflow for detecting and responding to malicious IP addresses.
