# YT-DLP Telegram Bot

A Telegram bot that downloads audio/video from various platforms using yt-dlp.

## Features
- 📥 Download videos from 1000+ sites
- 🎵 Audio extraction in multiple formats
- 📊 Quality selection
- 🆓 Free hosting on Render.com

## Setup

### 1. Create a Telegram Bot
1. Open Telegram and search for @BotFather
2. Send `/newbot` and follow instructions
3. Copy your bot token

### 2. Local Development
```bash
# Clone and navigate to project
git clone https://github.com/sinharzs2k26/ytdlp-telegram-bot.git
cd ytdlp-telegram-bot

# Install dependencies
pip install -r requirements.txt

# Configure environment
cp .env.example .env
# Edit .env and add your bot token

# Run the bot
python bot.py