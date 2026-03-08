# 🤖 n8n Workflow Automation — Indian SMB Edition

> Production-ready automation stack built for Indian businesses using **n8n**, **Telegram**, **Node.js**, **Google Sheets**, and **Razorpay** — deployed on Render & Oracle Cloud Free Tier.

---

## 🚀 What This Does

This project automates end-to-end business operations for Indian SMBs:

- 📦 **Order Management** — Customer sends order on Telegram → auto-logged in Google Sheets
- 💳 **Payment Links** — Razorpay payment link auto-generated and sent back to customer
- 🔔 **Instant Alerts** — Business owner gets Telegram notification for every new order
- 🧠 **AI-Powered Replies** — Node.js handles custom logic for edge cases

---

## 🏗️ Architecture

```
Customer (Telegram)
        ↓
  n8n Webhook Trigger
        ↓
  Node.js Custom Logic
        ↓
  Google Sheets API ──→ Log Order
        ↓
  Razorpay API ──→ Generate Payment Link
        ↓
  Telegram API ──→ Send Link to Customer + Alert Owner
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|--------|
| **n8n** | Visual workflow automation engine |
| **Node.js** | Custom business logic |
| **Telegram Bot API** | Customer & owner communication |
| **Google Sheets API** | Real-time order database |
| **Razorpay API** | Auto payment link generation |
| **Render / Oracle Cloud** | Free hosting infrastructure |

---

## 💼 Business Impact

- ✅ **Zero manual order entry** — saves 3-4 hours/day for shop owners
- ✅ **100% payment tracking** — no missed collections
- ✅ **Instant customer response** — sub-5 second reply time
- ✅ **Zero hosting cost** — runs on Oracle Cloud Free Tier

---

## 📁 Project Structure

```
n8n-tutorial/
├── package.json          # Node.js dependencies
├── workflows/            # n8n exported workflow JSONs
├── nodes/                # Custom Node.js function nodes
└── README.md
```

---

## 👨‍💻 Built By

**Mehul Jhabak** — AI Automation Architect, Jaipur 🇮🇳

Building intelligent automation systems for Indian businesses.

[![GitHub](https://img.shields.io/badge/GitHub-mehul82099-black?style=flat&logo=github)](https://github.com/mehul82099)
