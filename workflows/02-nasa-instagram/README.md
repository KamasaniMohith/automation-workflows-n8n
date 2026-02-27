# 🚀 NASA Images → Instagram (Fully Automated)

> Fetches NASA's daily space photo, generates an AI caption, and posts to Instagram — zero manual work!

---

## ✨ What It Does

Every single day, this workflow:
- Fetches NASA's Astronomy Picture of the Day (APOD) via API
- Filters to ensure it's an image (not a video)
- Downloads and uploads the image to Cloudinary
- Generates a creative AI-powered caption using Gemini
- Publishes the post directly to Instagram
- Logs everything to Google Sheets

---

## 🛠️ Tools & Tech

| Tool | Purpose |
|------|---------|
| n8n | Workflow automation |
| NASA APOD API | Daily space images |
| Cloudinary | Image hosting |
| Gemini AI | Caption generation |
| Instagram Graph API | Auto-posting |
| Google Sheets | Activity log |


## 🚀 How to Use

1. Import `workflow.json` into your n8n instance
2. Add credentials: NASA API key, Cloudinary, Gemini API key, Instagram access token, Google Sheets
3. Set your Instagram User ID and Google Sheet ID in the nodes
4. Activate — it runs daily automatically!

---

## 💡 Key Highlight

> End-to-end pipeline: API fetch → AI caption → Instagram post, fully hands-free!
