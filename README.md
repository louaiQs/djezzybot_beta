# Djezzy Bot Usage Guide

## Features
- Allows users to request a gift every **24 hours**.
- Uses **OTP verification** to authenticate Djezzy phone numbers.
- Securely stores user data in a JSON file.
- Provides a simple **Telegram bot interface** for user interaction.
- Error handling and response messages for better user experience.

## Setup Instructions
### 1. Install Dependencies
Ensure you have Python installed on your system. Then, install the required Python libraries:
```bash
pip install pyTelegramBotAPI requests
```

### 2. Configure the Bot
Edit the following fields in the script:
- Replace `TOKEN` with your **Telegram Bot Token**.
- Replace `ADMIN_ID` with your **Telegram User ID**.

```python
TOKEN = 'YOUR_TELEGRAM_BOT_TOKEN'
ADMIN_ID = 'YOUR_TELEGRAM_USER_ID'
```

### 3. Run the Bot

## Hosting on Bot Hosting Net
1. Sign up on [Bot Hosting Net](https://www.bot-hosting.net/).
2. Upload your `bot.py` script.
3. Configure the bot’s environment variables with your **TOKEN** and **ADMIN_ID**.
4. Start the bot using their **hosting dashboard**.

## Notes
- The bot must remain **online** for continuous operation.
- For security reasons, never expose your bot token or API credentials publicly.
- Due to the way Djezzy servers operate, the bot will not work in 90% of cases. You need to keep trying repeatedly for it to work.

