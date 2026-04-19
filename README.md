# PharmaPulse AI Agent

An n8n workflow for monitoring:
- FDA enforcement data
- PubMed articles
- BioPharma Dive news

It normalizes data, deduplicates items, prioritizes important updates, sends selected articles to AI for summarization, and publishes the filtered output.

## Files
- `workflows/My_workflow_fixed.json` → main n8n workflow
- `assets/pharmapulse-ai-profile.png` → project avatar/logo

## Required credentials
- Google Sheets
- Gmail
- Telegram
- AvalAI / OpenAI-compatible API key

## Import into n8n
1. Download the workflow JSON
2. Import it into n8n
3. Reconnect credentials
4. Add your API key in the GPT node
5. Test before activating schedule

## Important
Do not commit API keys, OAuth secrets, or personal credentials.