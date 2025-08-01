# ChatGPT Micro-Cap Trading Bot

This repo contains a lightweight Python project that logs a micro-cap stock portfolio and generates daily reports. It was originally part of an experiment but has been cleaned for a fresh start.

## Quick start

1. Install Python 3.10+ and the required packages:
   ```bash
   pip install -r requirements.txt
   ```
2. Open `Scripts and CSV Files/Trading_Script.py` and edit the bottom section if you want to start with any positions. By default the script starts with an empty portfolio and `$500` in cash.
3. Run the trading script:
   ```bash
   python "Scripts and CSV Files/Trading_Script.py"
   ```
   This creates `chatgpt_portfolio_update.csv` and `chatgpt_trade_log.csv` inside the same folder.
4. (Optional) Run `Generate_Graph.py` after you have some history to see a simple performance chart.

To keep the bot running indefinitely you can schedule the trading script using `cron` or your operating system's task scheduler.

## Disclaimer

This project is provided for educational purposes only. It does **not** constitute financial or investment advice. Use it at your own risk.
