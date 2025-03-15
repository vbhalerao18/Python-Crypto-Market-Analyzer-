# Crypto Market Analyzer 📊🚀

This Python-based application fetches real-time cryptocurrency market data from the **CoinGecko API**, identifies the **top 10 cryptocurrencies to sell** and the **bottom 10 to buy**, and sends a **daily report via email** at 8 AM.

## Features:
✅ Fetches live cryptocurrency data from **CoinGecko**  
✅ Identifies **top 10 gainers** and **top 10 losers** in the last 24 hours  
✅ Saves the data in a CSV file for record-keeping  
✅ Sends an **automated email report** with the latest market insights  
✅ **Scheduled execution** every day at 8 AM  

How It Works:

Retrieve Data: The app fetches cryptocurrency prices, market cap, and price changes.

Analyze & Rank: It identifies the top 10 best-performing and worst-performing cryptocurrencies.

Save & Send Report: The results are stored in a CSV file and emailed to a designated recipient.

Scheduled Execution: The script runs daily at 8 AM using the schedule module.


## Technologies Used:
- **Python**
- **Requests** (for API calls)
- **Pandas** (for data processing)
- **Schedule** (for task automation)
- **SMTP** (for email notifications)

