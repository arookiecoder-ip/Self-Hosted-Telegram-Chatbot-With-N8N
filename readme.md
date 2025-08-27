# Telegram Chatbot AI Agent (n8n Workflow)

This repository contains an **n8n workflow** that connects a Telegram bot with an AI-powered agent using **OpenRouter (Gemini 2.0 model)**.  
It allows you to chat with an AI directly through **Telegram**, with memory support for contextual conversations.  

---

## 🗂️ Download the JSON Workflow
- First Download the below file:
[Workflow JSON](blob:https://github.com/fe2a0f68-d9b7-4325-9f40-10d6cd95bf65)
---


## ⚙️ Setup Instructions  

### 1️⃣ Prerequisites
- n8n installed (self-hosted or cloud)  
- Telegram bot (create using [@BotFather](https://t.me/botfather))  
- OpenRouter API key (for LLM access)  

### 2️⃣ Configure Credentials
- **Telegram API**: Paste the bot token inside `telegramApi` credentials in n8n.  
- **OpenRouter API**: Add your OpenRouter API key under `openRouterApi` credentials.  


### 4️⃣ Start Chatting 🎉
- Open Telegram, send messages to your bot  
- The AI will reply intelligently, remembering context within the session  


