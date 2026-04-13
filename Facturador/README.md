n8n-automation-blueprints 🚀
A professional collection of n8n workflows designed to solve real-world administrative and financial challenges through automation and AI. This repository serves as a technical portfolio showcasing scalable solutions for the modern gig economy.
📂 Featured Workflows1. Automated ARCA (AFIP) InvoicingA robust end-to-end automation for legal invoicing in Argentina.
Trigger: New row detection in Google Sheets.
Core Actions:Secure authentication with AFIP SDK.
Automatic validation of the last authorized invoice number.
Dynamic PDF generation using customized HTML/CSS templates.
Automated delivery via Gmail API.
Key Logic: Advanced JavaScript nodes for tax calculation and data sanitization.
2. AI-Powered Accounting AssistantIntelligent email parser that transforms unstructured text into structured financial data.
Mechanism: Gmail Trigger + Google Gemini (LLM) + LangChain Output Parser.
Outcome: Automatically extracts CUIT, billing periods, and amounts.
Data Integrity: Filters duplicate entries and syncs directly with Google Sheets for real-time tracking.
🛠️ Tech StackAutomation: n8n AI/LLM: Google Gemini & LangChain Storage: Google Sheets APICommunication: Gmail APIFinancial Integration: ARCA (AFIP) SDK🚀 Getting StartedImport the .json files into your n8n instance.Configure your credentials (API Keys, OAuth2).Replace placeholders (e.g., TU_CUIT, TU_SPREADSHEET_ID) with your own environment variables.
Author: Santiago Lacourrege
4th Year Computer Engineering Student at UNLP | Specialized in Backend & Automation