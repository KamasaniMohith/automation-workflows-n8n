# 📰 BBC News → Google Sheets → Twitter

> Automatically fetches BBC News, avoids duplicates using Google Sheets, and posts to Twitter on a schedule!

---

## ✨ What It Does

This workflow runs every few hours and:
- Reads the latest BBC News RSS feed
- Checks Google Sheets to avoid posting duplicate articles
- Filters only new, unposted articles
- Auto-posts each new article as a tweet
- Saves posted articles back to Google Sheets

Smart deduplication means you'll never tweet the same story twice!

---

## 🛠️ Tools & Tech

| Tool | Purpose |
|------|---------|
| n8n | Workflow automation |
| BBC RSS Feed | News source |
| Google Sheets | Duplicate tracking |
| JavaScript (Code node) | Filter logic |
| Twitter / X API | Auto-posting |



## 🚀 How to Use

1. Import `workflow.json` into your n8n instance
2. Connect your Twitter/X API credentials
3. Connect your Google Sheets account and set your Sheet ID
4. Activate the workflow — it auto-runs every 6 hours!

---

## 💡 Key Highlight

> Uses Google Sheets as a smart memory layer to prevent duplicate tweets — no database needed!
