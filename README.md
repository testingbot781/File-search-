# Serena Auto File Forwarder Bot

A Telegram bot that fetches files from any added channel and sends them to users, with a 10-second delay to avoid bans.  
Uses MongoDB for data storage, and logs all activities in a specified channel.

### ✨ Features:
- Fetch files from channels with safe sending (10-second delay)
- Admin features: Broadcast, Ban, Unban, Stats
- MongoDB storage for users, banned users, and logs
- Notify owner when the bot starts
- Fully configurable with environment variables

---

## 🚀 Deploy on Render

### 1. Upload these files:
- bot.py
- requirements.txt
- README.md

### 2. Go to **Environment Variables** in Render and add the following:
