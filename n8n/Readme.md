# 🔄 n8n Workflows

Ready-made n8n workflows for AI + automation.

## 📂 Workflows

- `workflows/Fullstack.json` – Connect n8n with Lovable/Bolt/etc
- `workflows/email_classifier.json` – Decluttering emails into segments or deleting depending on the email category

## 🧪 Import into n8n

1. Open your n8n instance.
2. Create a new workflow.
3. Use **Import from file** and select the JSON from `workflows/`.
4. Set credentials for:
   - OpenAI / Anthropic (or your model provider)
   - Google Sheets / Notion / etc.
5. Activate the workflow.

Each JSON has a short comment block at the top describing nodes and variables.

## 🛠️ Customizing

- Change trigger nodes (cron, webhook, app events).
- Swap LLM providers by editing the LLM node.
- Add extra branches for notifications (Slack, Discord, email).
