# 📰 AI News Summarizer using n8n + Google Gemini

An automated AI-powered news summarization workflow built with **n8n** and **Google Gemini**. The workflow fetches news from multiple RSS feeds, combines them, summarizes the latest articles using Gemini AI, and delivers the summarized news directly to Gmail.

---

## 🚀 Features

- ⏰ Runs automatically on a schedule
- 📰 Fetches AI news and Tech news from RSS feeds
- 🔄 Merges multiple news sources
- 📊 Aggregates articles into a single dataset
- 🤖 Generates concise summaries using Google Gemini
- 📧 Sends summarized news directly to Gmail
- ⚡ Fully automated with n8n

---

## 🛠️ Tech Stack

- **n8n**
- **Google Gemini API**
- **RSS Feed Reader**
- **Gmail**
- **Data Aggregator Node**

---

## 📌 Workflow Architecture

```text
Schedule Trigger
      │
      ├── AI News Feed
      │
      └── Tech News Feed
               │
            Merge
               │
        Data Aggregator
               │
       Google Gemini AI
               │
          Gmail Node
```

---

## 📷 Workflow Screenshot

<img width="1307" height="528" alt="image" src="https://github.com/user-attachments/assets/32b158ec-443a-4d44-89e0-e3bce02f1b28" />
<img width="1397" height="753" alt="image" src="https://github.com/user-attachments/assets/6b136a7a-25f4-476c-8b04-f27a34a8ad4d" />
<img width="1531" height="870" alt="image" src="https://github.com/user-attachments/assets/17f75240-c908-49ee-986d-0a53d7197768" />




---

## ⚙️ How It Works

### 1. Schedule Trigger
The workflow starts automatically at predefined intervals.

### 2. RSS Feed Nodes
- AI News Feed
- Tech News Feed

These nodes fetch the latest articles.

### 3. Merge Node
Combines articles from multiple RSS feeds.

### 4. Data Aggregator
Aggregates all fetched articles into a single input.

### 5. AI Summarizer
Uses **Google Gemini** to generate a concise summary of the news.

### 6. Gmail Node
Sends the summarized news to the configured email address.

---

## 📂 Project Structure

```
AI-News-Summarizer/
│
├── workflows/
│   └── ai-news-summarizer.json
│
├── images/
│   └── workflow.png
│
├── README.md
└── .env.example
```

---



## 📥 Importing the Workflow

1. Download `ai-news-summarizer.json`.
2. Open n8n.
3. Click **Import Workflow**.
4. Upload the JSON file.
5. Configure your credentials.
6. Activate the workflow.

---

## Example Output

```
📰 AI News Summary

• OpenAI announced new updates to ChatGPT.
• Google introduced improvements to Gemini.
• Major advancements were reported in robotics and AI agents.
• Several tech companies unveiled new AI-powered tools.

Generated using Google Gemini.
```

---

## Future Improvements

- Telegram Notifications
- Discord Integration
- Slack Notifications
- Daily Digest
- Database Storage
- Multi-language Summaries
- Web Dashboard

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

---

## ⭐ Support

If you found this project useful, consider giving it a star ⭐ on GitHub.

---

