# chatbot-extended-vendor-dashboard
# 💬 Vendor Invoice Chatbot

![Status](https://img.shields.io/badge/status-active-brightgreen)
![PHP](https://img.shields.io/badge/built%20with-PHP-blue)
![MySQL](https://img.shields.io/badge/database-MySQL-blue)
![Dialogflow](https://img.shields.io/badge/NLP-Dialogflow-orange)



This chatbot allows vendors to check their invoice details through a Dialogflow-powered assistant, connected to a MySQL database via a PHP webhook.
# 💬 Vendor Invoice Chatbot (Dialogflow + PHP + MySQL)

This chatbot allows vendors to check their invoice details through a Dialogflow-powered assistant, connected to a MySQL database via a PHP webhook.

## 🔧 Tech Stack
- Dialogflow CX (Intent handling)
- PHP (Webhook logic)
- MySQL (Invoice database)
- Replit (Hosting)

## 🚀 Features
- Fetches the **latest invoice** for a specific vendor
- Hosted PHP webhook integration with Dialogflow
- Uses real-time SQL queries to pull invoice data

## 📁 Files
- `dialogflow_webhook.php` — Receives request from Dialogflow, returns invoice info
- `db.php` — Database connection file (use dummy creds if public)
- `index.php` — Optional homepage for Replit

  
![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red)


