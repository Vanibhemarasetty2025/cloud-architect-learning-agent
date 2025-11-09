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

## 📚 Demo Pictures

<img width="541" height="744" alt="Screenshot 2025-11-09 at 9 45 47 PM" src="https://github.com/user-attachments/assets/9b5d65a8-252f-42c9-9bef-5f3c5377ca66" />
<img width="1289" height="498" alt="Screenshot 2025-11-09 at 9 45 04 PM" src="https://github.com/user-attachments/assets/d82ddfb1-f138-4983-9c19-9e00c9c27555" />


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
