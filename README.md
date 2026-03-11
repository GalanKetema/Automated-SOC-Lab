# 🛡️ AI-Enriched Automated SOC Lab

This project automates the **Detection & Analysis** phase of the NIST Incident Response framework. By connecting **TheHive** and **n8n** with **Llama/Gemini**, it reduces manual triage time from 10 minutes to 10 seconds.

## 🌟 Key Features
- **Automated Enrichment:** Pulls data from VirusTotal and MISP automatically.
- **AI Triage:** Uses LLMs to translate, summarize, and prioritize cases.
- **Privacy Focused:** Supports on-premise Llama models for data sovereignty.

## 🚀 How to Run
1. Clone the repo: `git clone [your-url]`
2. Copy `.env.example` to `.env` and add your API keys.
3. Run `docker-compose up -d`.
4. Import the `n8n-workflow.json` into your n8n instance.

## 📊 NIST Alignment
- **Detection:** Automated webhook triggers.
- **Analysis:** AI-driven synthesis of multi-source intelligence.
