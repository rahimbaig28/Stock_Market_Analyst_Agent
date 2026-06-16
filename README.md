# 📈 AI Stock Market Automation (n8n + Gemini + Gmail)

![Status](https://img.shields.io/badge/status-active-success)
![AI](https://img.shields.io/badge/AI-Google%20Gemini-blue)
![Automation](https://img.shields.io/badge/n8n-workflow-orange)
![License](https://img.shields.io/badge/license-MIT-green)

This project is an **AI-powered stock market automation system** built using **n8n**, **Google Gemini AI**, and **Gmail**.  
It automatically analyzes market trends every morning and sends a curated list of promising US stocks directly to your email.

---

## 🚀 Overview

This workflow runs daily at **9:00 AM** and performs the following steps:

- Fetches latest stock/market data
- Uses **AI (Google Gemini)** to analyze trends
- Identifies potential high-growth or trending stocks
- Generates a clean email report
- Sends it directly via **Gmail automation**

---

## 🧠 Tech Stack

- ⚙️ **n8n** – Workflow automation
- 🤖 **Google Gemini AI** – Market analysis & insights
- 📊 **Stock Data API** – Yahoo Finance / Alpha Vantage / other market APIs
- 📧 **Gmail API** – Email delivery automation
- 🧩 Optional: Webhooks, Cron Trigger, JSON parsing

---

## 🔁 Workflow Architecture


---

## 📩 Sample Email Output

**Subject:** Daily Market Insights: Top 10 Promising Stocks

### Email Content Includes:
- 📊 Market summary
- 📈 Top gainers & trending stocks
- 🧠 AI reasoning for each stock
- ⚠️ Risk level (Low / Medium / High)
- 🔮 Short-term outlook

---

## 🛠️ Setup Instructions

### 1. Import Workflow
Import the `.json` workflow file into **n8n**.

---

### 2. Configure API Keys

You need to set up credentials for:

- Google Gemini API
- Stock Market Data API (Alpha Vantage / Yahoo Finance / etc.)
- Gmail OAuth2 authentication

---

### 3. Set Schedule (Cron Trigger)

Configure the Cron node:

```cron
0 9 * * *


You are a financial analyst AI.

Analyze the following stock market data and identify the top 10 promising US stocks for short-term growth.

Return in structured format:
- Stock Name
- Ticker Symbol
- Reason for selection (1–2 lines)
- Risk Level (Low / Medium / High)

Data:
{{stock_data}}
---
```


✔ Runs every day at 9:00 AM automatically.


4. Enable Workflow

Turn ON the workflow inside the **n8n dashboard** to start automation.

---

## 📩 Sample AI Email Output

**Subject:** Daily Market Insights: Top 10 Promising Stocks

### Email Content Includes:

- 📊 Market summary of overall market conditions  
- 📈 Top gainers and trending stocks  
- 🧠 AI reasoning for each stock selection  
- ⚠️ Risk level classification (Low / Medium / High)  
- 🔮 Short-term outlook and momentum insights  

---

## 🧪 AI Agent Prompt (Gemini)

You are a financial analyst AI.

Analyze the following stock market data and identify the top 10 promising US stocks for short-term growth.

Return in structured format:
- Stock Name
- Ticker Symbol
- Reason for selection (1–2 lines)
- Risk Level (Low / Medium / High)

Data:
{{stock_data}}

---

## 📊 Features

- ✅ Fully automated daily stock insights system  
- 🤖 AI-powered financial reasoning using Google Gemini  
- 📧 Automated email delivery via Gmail  
- ⚡ No manual intervention required after setup  
- 🔌 Easily extendable (crypto, news sentiment, indicators, etc.)  

---

---

## 🔮 Future Improvements

- 🔔 Real-time stock alerts via Telegram / Slack  
- 📰 News sentiment analysis integration  
- 💼 Portfolio tracking dashboard  
- 📊 Backtesting AI-generated stock picks  
- 🌐 Web dashboard using Streamlit / React  

---

## ⚠️ Disclaimer

This project is built for **educational and informational purposes only**.  
It does **not constitute financial advice**. Always do your own research before making investment decisions.

---

## 👨‍💻 Author

**Rahim Baig**  
GitHub: https://github.com/rahimbaig28

---

⭐ If you like this project, consider giving it a star on GitHub!

