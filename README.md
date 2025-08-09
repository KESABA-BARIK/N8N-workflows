# N8N Workflows

A curated collection of **ready-to-use automation workflows** for [n8n](https://n8n.io/).  
These workflows cover email outreach, CRM automation, recruitment tasks, social media, and more.  
All files have been **sanitized** — no credentials are included.

---

## 📂 Included Workflows

| File | Description |
|------|-------------|
| `ai-crm-automation-hubspot.json` | Automates CRM tasks in HubSpot, including data sync and follow-ups. |
| `ai-outreach-bot.json` | AI-powered Gmail outreach bot with personalized follow-ups. |
| `linkedin_candidate_search_public_serpapi.json` | Searches LinkedIn for candidates using SERP API and compiles results. |
| `n8n-ai-followup-bot.json` | Waits a set period after an event, then sends an AI-personalized follow-up email. |
| `recruitment-automation.json` | End-to-end recruitment workflow from candidate sourcing to follow-up emails. |
| `resume_parser_ats_hr_template.json` | Parses resumes into a structured ATS-friendly format. |
| `social-post-to-image.json` | Converts social media posts into shareable images using AI and image generation APIs. |

---

## 🚀 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/KESABA-BARIK/N8N-workflows.git
   ```
2. **Import into n8n**  
   - Go to **Workflows → Import from File** in n8n.  
   - Select the `.json` file you want to use.  
3. **Configure credentials**  
   - Each workflow may require credentials (Gmail, OpenRouter, HubSpot, SERP API, etc.).  
   - Add these via **n8n Credentials Manager**.  
4. **Activate & customize**  
   - Modify nodes, messages, and triggers to fit your needs.  
   - Activate the workflow in n8n.  

---

## 🔒 Security Notes

- No credentials are stored in this repo.  
- Always keep your `.env` or credential exports private.  
- Regenerate API keys if they were ever exposed.  

---

## 💡 Example Use Cases

- Automate sales follow-ups with AI-personalized messages.  
- Recruitment pipelines that source, parse, and email candidates.  
- CRM synchronization between HubSpot and other tools.  
- Create AI-generated visuals from text or social posts.  

---

## 📜 License

MIT License – Free to use and modify.  
Contributions and new workflows are welcome!

---

## 🤝 Contributions

If you have an automation idea:  
- Open an Issue  
- Submit a Pull Request  
- Share your own n8n workflow  
