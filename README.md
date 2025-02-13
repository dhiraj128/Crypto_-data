# Cryptocurrency Tracker

A Python-based application to track the top 50 cryptocurrencies in real-time using the CoinGecko API. The application fetches live data, processes it, performs analysis, and updates an Excel file with the results. The script runs periodically (every 5 minutes) to keep the data up-to-date.

## Features

- **Real-Time Data Fetching**: Fetches live data for the top 50 cryptocurrencies by market cap.
- **Data Processing**: Cleans and structures the data for analysis.
- **Analysis**:
  - Top 5 cryptocurrencies by market cap.
  - Average price of all cryptocurrencies.
  - Highest 24-hour gain and lowest 24-hour loss.
- **Excel Integration**: Updates an Excel file with live data and analysis results.
- **Error Handling**: Robust error handling with retries and logging for reliability.
- **Scheduling**: Automatically runs every 5 minutes to keep data updated.

## Prerequisites

Before running the script, ensure you have the following installed:

- Python 3.7 or higher
- Required Python libraries: `requests`, `pandas`, `schedule`, `tenacity`, `openpyxl`

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/crypto-tracker.git
   cd crypto-tracker
