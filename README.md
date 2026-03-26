# 🎙️ Telegram Voice AI Bot (n8n)

This project is an automation workflow built using n8n that processes Telegram voice messages using AI.

## 🚀 Features

- 🔒 User AllowList security
- 🎧 Voice message detection
- 📥 Automatic voice file download
- 🧠 AI-based speech-to-text processing
- 📤 Sends response back to Telegram

## 🛠️ Tech Stack

- n8n (Workflow Automation)
- Telegram Bot API
- OpenAI API (for transcription/processing)

## 📊 Workflow Overview

1. Listen for incoming Telegram messages
2. Check user authorization (AllowList)
3. Detect voice messages
4. Download voice file
5. Process with AI
6. Send response back

## ⚙️ Setup Instructions

1. Install n8n:
   ```bash
   npm install n8n -g
