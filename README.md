Klaviyo AI Campaign Intelligence Bot

AI-powered n8n workflow that analyzes Klaviyo email campaigns and automatically generates high-converting marketing content using Gemini AI and Telegram.

🚀 Features
Fetches recent Klaviyo email campaigns
Cleans and structures campaign data
Uses Gemini AI for campaign analysis
Generates:
Email subject lines
SMS hooks
CTA buttons
Urgency campaigns
VIP marketing angles
Sends formatted reports directly to Telegram
Fully automated using n8n workflows
🧠 Workflow Architecture

Telegram Trigger
→ Klaviyo API Fetch
→ Data Cleanup
→ Gemini AI Analysis
→ AI Copy Generation
→ JSON Formatting
→ Telegram Delivery

🛠️ Tech Stack
n8n
Telegram Bot API
Google Gemini AI
Klaviyo API
Docker
ngrok (for local webhook testing)

**Workflow architecture**

Telegram Trigger
   ↓
Klaviyo API fetch
   ↓
Data cleanup
   ↓
Gemini analysis
   ↓
Gemini campaign generation
   ↓
JSON cleanup
   ↓
Telegram formatting
   ↓
Send response

<img width="1632" height="601" alt="image" src="https://github.com/user-attachments/assets/09e6c9f1-af03-48b0-a0a2-14e61953aa63" />

