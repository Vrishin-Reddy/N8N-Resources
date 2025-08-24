# N8N-Resources 🚀

A curated collection of **n8n workflows and automation agents** for lead generation, outreach, and business process automation.  
This repo provides ready-to-use workflows, JSON exports, and zipped packages you can import directly into your n8n instance.

---

## 📂 Repository Contents

- **Cold Email.json**  
  Automated cold email outreach workflow.

- **Lead Scraper.zip**  
  End-to-end workflows for scraping and verifying leads.

- **Sales Agent (Insta, Fb).zip**  
  Social media DM automation agent for Instagram & Facebook, including CRM integration.

- **Scrape Linkedin.zip**  
  Workflows to scrape LinkedIn data, verify emails, and enrich profiles.

- **Voice Agent.zip**  
  Voice-based agent workflows (outbound caller, calendar checker, booking CRM).

- **Voice Agent github).zip**  
  Alternate / experimental version of the Voice Agent workflows.

---

## ⚡ Getting Started

1. Install [n8n](https://n8n.io) locally or on a server (Docker recommended).
   ```bash
   npm install n8n -g
   n8n start
   ```

2. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/N8N-Resources.git
   cd N8N-Resources
   ```

3. Import a workflow:

   * In the n8n Editor UI → **Import from File**
   * Select the `.json` or unzip and load the `.zip` file.

4. Configure credentials:

   * Most workflows depend on APIs (e.g., Twilio, Gmail, LinkedIn, Reoon Email Verifier).
   * Create credentials inside n8n and replace placeholder/env values.

---

## 🔑 Environment & Secrets

⚠️ Do not commit real API keys or tokens.
Use environment variables or n8n’s built-in **Credentials Manager**.

Examples:

```env
TWILIO_ACCOUNT_SID=your_account_sid
TWILIO_AUTH_TOKEN=your_auth_token
OPENAI_API_KEY=your_api_key
```

In workflows, reference them via `{{$env.TWILIO_ACCOUNT_SID}}` or Credentials.

---

## 🛠 Example Use Cases

* **Lead Generation:** Scrape LinkedIn, validate emails, enrich data.
* **Cold Outreach:** Automated email campaigns with personalization.
* **Social Media Sales:** Auto-DM prospects on Instagram & Facebook, sync to CRM.
* **Voice Agents:** Call leads, check calendars, and schedule meetings automatically.

---

## 🤝 Contributing

Contributions are welcome!
Feel free to submit pull requests with:

* New workflows
* Bug fixes
* Documentation improvements

---

## 📜 License

MIT License — free to use, modify, and share.

---

### ⭐ If you find these workflows useful, consider starring the repo!
