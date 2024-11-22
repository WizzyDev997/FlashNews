# FlashNews
Scrap 90'000 sources with 1 search, in the format: 'query, page_size'.

# Telegram News Search Bot

This is a simple Telegram bot that allows users to search for news articles using the NewsCatcher API. The bot processes queries sent in the format `query,page_size` and returns a list of articles matching the query.

---

## Features
- `/start`: Welcomes the user and provides instructions.
- **Search News**: Users send a query in the format `query,page_size` (e.g., `technology,5`) to fetch news articles.
- `/user_ids` (optional): Tracks user IDs that have interacted with the bot (restricted to an authorized user).

---

## Prerequisites
- Python 3.10 or later
- A Telegram bot token from BotFather
- A NewsCatcher API key (sign up at [NewsCatcher API](https://www.newscatcherapi.com/docs/v3/documentation/get-started/quickstart))

---------------

# Install Dependencies

## bash

pip install -r requirements.txt
Set Up Environment Variables Create a .env file in the root directory and add your credentials:


## env

API_KEY=your_newscatcher_api_key
TELEGRAM_TOKEN=your_telegram_bot_token
NEWS_API_URL=https://v3-api.newscatcherapi.com/api/search
Run the Bot


## bash

python3 <script_name>.py


## Usage
Create a Telegram Bot

Go to Telegram and search for "BotFather".
Use the /newbot command to create a bot and get your bot token.
Get a NewsCatcher API Key

Sign up at NewsCatcher API.
Generate an API key for your application.
Interact with the Bot

Use /start to get started.
Send queries in the format query,page_size (e.g., sports,5).

# License
This project is open source and available under the MIT License.

