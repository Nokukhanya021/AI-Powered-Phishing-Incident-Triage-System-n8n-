#  AI-Powered Phishing Incident Triage System

## Overview
An automated pipeline that ingests suspicious emails, analyses them using AI, and logs structured risk reports to Google Sheets.

##  Tools & Technologies
- n8n
- Claude AI
- Google Sheets API
- Python
- Webhooks

##  How It Works
1. Ingests emails via webhook
2. Parses key fields (sender, subject, URLs)
3. AI analyses content and assigns risk scores
4. Classifies severity (Low / Medium / Critical)
5. Logs results to Google Sheets automatically

 Evidence 
 1.  Workflow editor - view of the “Simple Phishing Incident Triage Workflow” with nodes for ingesting, parsing, analyzing, and logging. ![ Workflow editor](mcp_server_setup.png)
 2.  Google Sheets entry - showing the phishing email analysis (timestamp, sender, subject, risk score, severity, etc.). ![Google Sheets entry](subfinder_scan.png) 

## Skills Demonstrated
- Phishing Analysis & Incident Triage
- Workflow Automation
- AI Integration
- Data Pipeline Design
- Risk Assessment & Reporting
