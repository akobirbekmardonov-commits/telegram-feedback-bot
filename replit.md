# Telegram Feedback Bot

## Overview
A Telegram bot for collecting suggestions and complaints ("Taklif va e'tirozlar"). Users can submit feedback either anonymously or with their contact information. The admin receives all submissions and can reply directly to users.

## Project Structure
- `bot.py` - Main bot application using aiogram library
- `requirements.txt` - Python dependencies

## Dependencies
- Python 3.11
- aiogram 2.25.1 (Telegram Bot API framework)

## Environment Variables Required
- `API_TOKEN` - Telegram Bot API token (get from @BotFather)
- `ADMIN_ID` - Telegram user ID of the admin who receives feedback

## Running the Bot
The bot runs as a long-polling Telegram bot. It will continuously listen for messages once started.

## Bot Features
1. Users start with `/start` command
2. Choose category: Suggestion or Complaint
3. Choose identity: With phone number or Anonymous
4. Submit their message
5. Admin receives the message and can reply
