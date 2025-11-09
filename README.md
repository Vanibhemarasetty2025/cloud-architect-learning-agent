# Cloud Architect Daily — Automated Learning Agent

This project automates Google Cloud learning using **n8n** and **OpenAI**.  
It sends one Cloud Architect concept to your Gmail daily at 11 AM — written like a mini-newsletter with links to official GCP resources.

Built by a working mom who needed to learn *on her own time.*

---

## 🧠 How It Works
- Uses an n8n Scheduled Trigger (daily at 11 AM IST)
- Pulls the next topic from a 30-day Cloud Architect syllabus
- Generates newsletter-style HTML using OpenAI
- Sends it via Gmail automatically

---

## ⚙️ Setup
1. Clone this repo.
2. Import `n8n_workflow.json` into your n8n instance.
3. Configure credentials:
   - Gmail OAuth2 (send access)
   - OpenAI API key
4. Update `startDate` in the “Select Concept” node.
5. Activate workflow.

---

## 📚 Example Email
![demo_email](./assets/demo_email_screenshot.png)

---

## 💡 Why I Built This
I wanted to keep learning while raising my daughter — but I no longer had hours for courses.  
So I built an agent that delivers one focused concept each morning.  
No dashboards. No fancy courses. Just consistent learning that fits real life.

---

## 🧩 Learn More
- [Google Cloud Professional Cloud Architect Path](https://www.skills.google/paths/12)
- [n8n Automation Platform](https://n8n.io)
- [OpenAI API](https://platform.openai.com)

---

## 🫶 Contribute
PRs are welcome! If you want to extend this to AWS, Azure, or AI-related tracks — feel free to fork and adapt.

---

## License
MIT
