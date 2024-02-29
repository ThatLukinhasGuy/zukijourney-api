# 💻 Zukijourney - Code

The not-so-incredible code for the Zukijourney API and bot. 🤖

## Requirements
- Python 3.9+ 🐍
- MongoDB Database 📚
- A Braincell 🧠

## Endpoints
This is a list of all the endpoints that are currently available, so people won't be confused on how to use our API. 🚀
### Normal Endpoints
- **Description:** Our non-RP endpoints.
- **Endpoint:** `https://zukijourney.xyzbot.net/v1/...`
***
### RP Endpoints
- **Description:** Our RP endpoints.
- **Endpoint:** `https://zukijourney.xyzbot.net/unf/...`
## How To Run
### API
```bash
# Install dependencies
pip install -r requirements.txt
# Run the server
chmod +x run.sh && screen ./run.sh
```
### Bot
```bash
# Go to the bot's folder
cd bot/
# Install dependencies
pip install -r requirements.txt
# Run the server
chmod +x run.sh && screen python3 bot.py
```