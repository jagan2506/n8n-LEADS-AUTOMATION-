# n8n-LEADS-AUTOMATION-
**AI-Powered Lead Qualification & Sales Automation**


I built an AI-powered lead automation system using n8n to simplify the way businesses handle customer enquiries. It captures leads, checks for duplicates, uses Gemini to analyze and classify them as Hot, Warm, or Cold, and automatically stores the details in a sheet. For high-priority leads, it also sends Telegram alerts and personalized emails.
***what business people often face is that they miss the leads they get and the there is no proper response to the clients***

**Google Form** (CLIENT FILL THE FORM WITH THEIR REQUIREMENT)
     ↓
Google Sheets
     ↓
Duplicate Detection
     ↓
Gemini AI Analysis(Analyze the leads importance and gives a value based on this the leads is considered important or not) 
     ↓
Lead Scoring
     ↓
HOT / WARM / COLD
     ↓
Google Sheets CRM
     ↓
HOT → Telegram + Gmail





**TechStacks**
n8n
Google Forms(credential)
Google Sheets(credential)
Google Gemini API
Telegram Bot(HTTP API)
Gmail(credential)




**Future improvements**
Replace Google Sheets CRM with a dedicated database/CRM
Add WhatsApp notifications
Add follow-up reminders
Add lead analytics dashboard
Add automatic lead assignment to sales representatives
Track lead conversion status
Add follow-up scheduling
## 🔐 Security

API keys, OAuth credentials, Telegram bot tokens, and other secrets
are not included in this repository.

After importing the n8n workflow, configure your own credentials
for Gemini, Google Sheets, Gmail, and Telegram.






    
