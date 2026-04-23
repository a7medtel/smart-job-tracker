# Smart Job Application Tracker 🎯

Automated job application tracking system with Telegram reminders built with n8n.

## What it does
- Reads job applications from Google Sheets daily
- Sends Telegram reminder 2 days before interviews
- Sends daily summary of all applications

## Tech Stack
- n8n (workflow automation)
- Google Sheets (database)
- Telegram Bot (notifications)

## Workflow

Schedule Trigger → Google Sheets → IF Condition → Telegram

## Setup
1. Import `workflow.json` into n8n
2. Add Google Sheets credentials
3. Create Telegram Bot via @BotFather
4. Add your Chat ID
5. Activate workflow

## Screenshots
_Add screenshots here_

## Author
Ahmed El-Telbani
