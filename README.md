 # 🚚 AxuRemoval Automation System

AI-powered automation suite for **removal and clearance businesses** — seamlessly integrates **Firebase**, **n8n**, and **Puppeteer** to handle lead management, instant client communication, and automatic ad posting across Facebook & Gumtree.

---

## 🌟 Overview

AxuRemoval Automation is a complete lead-generation and workflow automation platform designed to eliminate manual admin for local service businesses.  
It connects your **quote form**, **email notifications**, and **ad posting** workflows into one fully-automated system.

---

## ⚙️ Key Features

### 1. 🧾 QuoteForm Automation
Automatically handles customer quote submissions in real-time.

- Sends **instant confirmation emails** to the client.  
- Sends internal notifications to **you** and your **driver(s)**.  
- Stores quote data in **Firebase Firestore** for tracking and filtering.  
- Designed for integration with your `axuremoval.co.uk/quote` form.

---

### 2. 🤖 Facebook Auto Poster
Automates posting your ad to Facebook groups with Puppeteer.

- Opens your browser and logs into Facebook automatically.  
- Posts your pre-configured ad to selected groups.  
- Keeps browser open for manual review and verification.  
- Example group: `https://www.facebook.com/groups/1689296104623314`

---

### 3. 📢 Gumtree Ad Automation
Posts or refreshes your Gumtree ad automatically.

- Uses Puppeteer to open Gumtree’s ad creation page.  
- Fills in title, description, and category from `.env` variables.  
- Perfect for **daily posting or scheduled refreshes**.  
- Example title: `Man with a Van — Local Removals & House Clearance (Watford)`

---

### 4. ✉️ Gmail Reminder Workflow (via n8n)
Keeps your operations running even when you’re offline.

- Sends automated Gmail reminders to you and drivers when:  
  - A new lead is received  
  - A scheduled job is due  
  - A quote follow-up is pending  
- Integrated through **n8n Cloud** or self-hosted n8n instance.

---

## 🧠 Technology Stack

| Component | Purpose |
|------------|----------|
| **React + Firebase** | Handles the front-end quote system & Firestore integration |
| **n8n Automation** | Manages email triggers, lead classification & follow-ups |
| **Node.js + Puppeteer** | Runs Facebook and Gumtree posting bots |
| **.env Configuration** | Centralized control of API keys & posting details |

---

## ⚙️ Environment Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/nassirmohamoud123/axuremoval-automation.git
   cd axuremoval-automation
