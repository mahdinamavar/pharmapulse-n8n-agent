# 🚀 PharmaPulse — AI Pharma Intelligence Agent

PharmaPulse is an AI-powered automation agent built with **n8n** that continuously monitors pharmaceutical data sources and turns raw information into **high-signal, actionable insights**.

It aggregates data from:
- 🏥 FDA (drug updates & approvals)
- 🔬 PubMed (latest research)
- 💊 BioPharma news

Then uses AI to **filter noise, normalize data, and generate concise summaries** — so you only see what actually matters.

---

## ✨ Features

- ⚡ Real-time data aggregation from multiple pharma sources  
- 🧠 AI-powered filtering & summarization (GPT-based)  
- 🔄 Deduplication & normalization pipeline  
- 📊 Clean, structured output ready for publishing or analysis  
- 🔌 Built entirely with n8n (low-code / automation-first)

---

## 🧱 Workflow Overview

```
Sources (FDA / PubMed / BioPharma)
        ↓
Normalization & Cleaning
        ↓
Deduplication
        ↓
AI Filtering (GPT)
        ↓
Summarization
        ↓
Final Output / Publishing
```

---

## 🛠 Tech Stack

- **n8n** — workflow automation  
- **OpenAI / GPT** — content filtering & summarization  
- **RSS / APIs** — data ingestion  
- **JavaScript (Function Nodes)** — data processing  

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/mahdinamavar/pharmapulse-n8n-agent.git
cd pharmapulse-n8n-agent
```

### 2. Import workflow into n8n
- Open n8n  
- Go to **Workflows**  
- Click **Import**  
- Upload the workflow JSON file  

### 3. Configure credentials
Set up:
- OpenAI API key  
- Any required API/RSS endpoints  

### 4. Run the workflow
Execute manually or set a trigger (cron/webhook)

---

## ⚠️ Known Challenges

- ⚖️ AI filtering may drop some valid items (tunable via prompt/limits)  
- 📉 Rate limits depending on API usage  
- 🔍 Data variability across sources  

---

## 🎯 Use Cases

- Pharma market monitoring  
- Research trend tracking  
- Drug intelligence dashboards  
- Automated content pipelines  

---

## 🧠 Vision

PharmaPulse aims to become a **real-time pharma intelligence layer** — helping researchers, analysts, and teams stay ahead without drowning in data.
