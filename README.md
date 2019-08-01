# python-telegram-bot
Telegram bot compatible with Python 3.7. Webhooks with ngrok to Telegram bot message stream, conditional responses.

Currently under development - 4/13/2019

## Instructions For Use:
configure nginx proxy for port to expose

Navigate the the root directory in terminal, run:


Add your telegram bot token to the TOKEN variable in config.py

Add your ngrok https url to the NGROK_URL variable in config.py

Configure conditional actions based on Telegram message text in telegram_bot.py TelegramBot.action class method

Run the app server however you have python3.7 set to PATH:
> $ python3.7 app.py
