# Tele2Sheets

Tele2Sheets is a simple yet powerful automation pipeline that lets you send manually-entered stock data from Telegram, process it inside Google Colab, and store it neatly in Google Sheets.

This project is designed as an accessible first step toward a complete quantitative research toolkit — including data ingestion, backtesting, experimentation, and automated strategy testing.

🚀 Features

✔ Send stock messages directly from Telegram
✔ Fetch messages inside Google Colab
✔ Parse & clean structured stock inputs
✔ Automatically upload to Google Sheets
✔ Zero hosting needed — runs fully in Colab
✔ Safe token handling (no secrets stored in code)
✔ Modular design: easy to extend and scale
✔ Ideal for beginners building their first real automation pipeline

🔧 How It Works 

Telegram Message → Google Colab → Python Parsing → Google Sheets

Write message in Telegram bot in given format below:

"
STOCK NAME

ENTRY RANGE

TARGET1
TARGET2
TARGET3

STOPLOSS

SOURCE OF CALL

PERIOD OF HOLDING
"
and done, the data will automatically stored in new cell on your google sheet in clean format

Note:
Create Telegram Bot using Bot_Father
Store API Key into google colabe Secrets

🛣️ Roadmap

✔ Stage 1 — Current (Mini-Project)
Telegram → Colab → Sheets pipeline
Basic parsing
Manual or semi-automated message import

🔜 Stage 2 — Automation
Telegram bot integration
Auto-cleaning and rule-based processing
Error handling + logging

🔥 Stage 3 — Quant + Analysis
Fetch data from multiple sources
Strategy backtesting module
Paper/live testing interface
Dashboard for signals

🚀 Stage 4 — Full Quant Suite
Portfolio optimizer
Position sizing models
ML-based prediction modules
Broker/API integrations

📝 License
Released under the MIT License for maximum openness and flexibility.
