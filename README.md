# Cryptocurrency Data Fetching and Analysis

## Overview
This project fetches live cryptocurrency data from the CoinGecko API, analyzes it (top 5 by market cap, average price, etc.), and updates a Google Sheet with the latest data.

## Requirements
- Python 3.x
- gspread
- requests
- pandas
- oauth2client

## Setup
1. Clone the repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Create a Google Cloud project and enable Sheets API.
4. Upload the credentials JSON file and update the path in the code.

## Running the Script
Run the Crypto_analysis.ipynb Script.

The script will fetch data every 5 minutes and update the Google Sheet with live cryptocurrency data.

And also Before executing the script, Create a google sheet in google cloud platform and also take the credentials.json and paste the path in the code.

