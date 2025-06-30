<h1 align="center">
  📬 Email & Phone Scraper API
</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&center=true&vCenter=true&width=600&lines=Scrape+Emails+%26+Phones+from+Websites;Export+to+Google+Sheets+Automatically;Perfect+for+Leads+%26+Data+Enrichment;Deploy+as+SaaS+%F0%9F%9A%80" alt="Typing SVG" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,100:0072ff&height=100&section=header&text=Super%20Fast%20Scraper&fontSize=30&fontColor=ffffff&animation=twinkling" />
</p>


## 🚀 What is This?

A **Node.js Express API** that:
- 🕷 Scrapes **emails and phone numbers** from any publicly available website
- 📊 Automatically **logs the data to a connected Google Sheet**
- 🔐 Built to be **hosted, extended or connected to a frontend for SaaS**

---

## 🌐 Live Demo (Optional)

```bash
GET /scrape?url=https://en.wikipedia.org/wiki/OpenAI

⚙️ Tech Stack
Feature	Technology
Server	Node.js + Express
Scraping Engine	Puppeteer (Headless Chrome)
Google Sheets Sync	Google Sheets API
Deployment Ready	✅ Railway / Render

📁 Project Structure
pgsql
Copy
Edit
📦 puppeteer-scraper
 ┣ 📄 index.js          ← Main API Server
 ┣ 📄 package.json      ← Node dependencies
 ┣ 📄 credentials.json  ← (Git-ignored) Google API key
 ┣ 📄 .gitignore        ← Ignoring secrets
🚀 How to Use (Local Setup)
Clone the repo

bash
Copy
Edit
git clone https://github.com/your-username/email-scraper-api.git
cd email-scraper-api
Install dependencies

bash
Copy
Edit
npm install
Add your credentials.json (Google Service Account with Sheets access)

Start the server

bash
Copy
Edit
node index.js
✅ Sample Output
json
Copy
Edit
{
  "message": "✅ Scraped and added to sheet",
  "url": "https://en.wikipedia.org/wiki/OpenAI",
  "emails": [],
  "phones": [
    "7000000000",
    "9022403162",
    "9810610492"
  ]
}
📊 Google Sheet Integration
Your Google Sheet should have headers like:

perl
Copy
Edit
| URL                          | Emails                     | Phones                        |
|-----------------------------|----------------------------|-------------------------------|
| https://example.com         | example@mail.com, ...      | 9876543210, 9123456789, ...   |
Bot automatically appends to next empty row using header mapping.

🛡 Permissions & Security
🔐 Make sure your Google Service Account has Editor access to the Google Sheet.

Add credentials.json safely (not in public repos)

💡 Future Plans
✨ Frontend UI (React + Tailwind)

🧠 AI-powered smart filters

🌍 Deploy as a SaaS platform

🧩 Add CSV/PDF export support


