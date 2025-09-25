 📬 Motivational Quotes & Daily Message Automation (n8n + AI)

This project is an **automation workflow** built with [n8n](https://n8n.io/) that sends **daily motivational quotes (or any scheduled messages)** automatically at **7 a.m.**.

## 🚀 Features

* ⏰ **Schedule Trigger** → Runs every day at 7 a.m.
* 🤖 **AI Integration (LLM Chain)** → Generates or personalizes quotes/messages
* 📊 **Google Sheets Integration** → Stores and manages recipient emails
* 📧 **Gmail Node** → Sends automated messages to all recipients
* 🔄 **Flexible Content** → Not limited to motivation; can send business updates, announcements, reminders, or learning tips

## 🛠️ Tech Stack

* **n8n** (workflow automation)
* **OpenAI GPT-4 mini** (content generation)
* **Google Sheets** (recipient management)
* **Gmail** (email delivery)

## 🎯 Use Cases

* Daily motivational quotes for teams or audiences
* Automated company announcements
* Daily learning/knowledge sharing
* Newsletters without manual effort
* Personalized reminders for clients or employees

## 📸 Workflow Overview

1. Trigger → Runs daily at 7 a.m.
2. AI Node → Generates a motivational quote or message
3. Google Sheets → Fetches recipient list
4. Gmail Node → Sends email to each recipient

## ⚡ Impact

* Saves time ⏳ (no manual sending)
* Increases consistency 📈
* Keeps audiences engaged 💬

## 🔧 How to Use

1. Clone this workflow into your n8n instance.
2. Connect OpenAI, Gmail, and Google Sheets credentials.
3. Update recipient emails in your Google Sheet.
4. Activate workflow → Done! 🎉


Would you like me to also draft the **`project.json` workflow export description** (so people can import your n8n workflow directly from GitHub)?
