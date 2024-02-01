# Trading Data Fetch and Analysis

This repository contains Python scripts for fetching historical OHLCV (Open/High/Low/Close/Volume) data from the Binance cryptocurrency exchange using the ccxt library. The data is fetched for both futures and spot markets, and a spread analysis between futures and spot prices is performed.

## Prerequisites

Before running the scripts, ensure you have the following prerequisites installed:

- Python 3.x
- ccxt library
- pandas
- matplotlib
- time
- tqdm

You can install the required Python packages using the following command:

```bash
pip install ccxt pandas matplotlib time tqdm
```
## Configuration

The API key and secret key for Binance are stored in a configuration file named config.ini. Make sure to replace the placeholder values with your actual API key and secret.

```bash
[settings]
api_key = YOUR_BINANCE_API_KEY
secret_key = YOUR_BINANCE_SECRET_KEY
```
## Usage

Run the script BTCUSDT_Spread_2023_v2.ipynb in Jupyter Notebook to fetch historical OHLCV data, calculate the spread and generate visualizations.

## Output

The fetched data is saved in CSV format with filenames containing the symbol, type, and "data.csv" (e.g., BTCUSDT_future_data.csv). 
