# Team Bitantics: Crash Course in Cryptocurrencies

### Team Members
- Blake
- Kelly
- Tony
- April 

## Description
Compare the data & trading movement of the cryptocurrencies asset class. Determine intra/cross similarities and differences between crypto and other asset classes (global indices) and determine nature of realtionships.

## Research Questions
- How many different cryptocurrencies are out in the market?
- What is the relationship between cryptocurrencies?
- What similarities and differences can we draw between cryptocurrencies and other asset classes?
- What fiat currencies are accepted for buying/selling cryptocurrencies? How often is one fiat currency used compared to another?
- Is crypto a viable asset class? Who are the winners and laggards?

## Datasets used
- Cryptocurrency pricing & volume datsets from Coinbase and CoinMarketCap
- Global World, Regional & Country Indices from Investing.com

## APIs & new Python package used
- Coinbase REST API - cryptocurrency historical data (volume)
- Dealing with rate limits and amount of data returned
- CoinMarketCap - cryptocurrency historical prices
- Investing.com - global indices data using investpy Python package

## Features Delivered
- Data Ingestion of trading information about cryptocurrencies and global indices
- Data Cleaning & Shaping
- Exploratory Data Analysis (EDA)
- Reports/Dashboards
- Presentation

## Key Assets
- Combined Data Prep Notebook ([data_processing.ipynb](notebooks/data_processing.ipynb))
- Combined Analysis & Dashboard Notebook ([final_analysis.ipynb](notebooks/final_analysis.ipynb))
- Various notebooks used per analysis domain
- Saved data sources & dataframes via CSV [files](data)
- Saved visualization PNG [images](images)

## Findings

### How many different cryptocurrencies are out in the market?

*Answer here.* Coinbase, one of the most well known exchanges, supports trading over 40 cryptocurrencies.

### What is the relationship between cryptocurrencies?
*Answer here.*

### What similarities and differences can we draw between cryptocurrencies and other asset classes?
*Answer here.*

### What fiat currencies are accepted for buying/selling cryptocurrencies?

The US dollar, Pound Sterling and Euro are widely accepted across the exchanges. Also accepted are the Japanese yen, the Russian ruble, the Australian dollar, the Singapore dollar, and the Canadian dollar. Coinbase accepts: USD, GBP, EUR, AUD, SGD, and CAD.

### How often is one fiat currency used compared to another?

The USD is the most popular fiat currency used to buy cryptocurrencies. Coinbase's historical data shows the US dollar (USD) is more popular by volume (total # of coins/token) than the Pound Sterling (GBP) and Euro (EUR).

![Daily Volume of Trading Activity by Fiat Currency](images/trading_volume_by_fiat_plot.png)

Additionally, the USD is also used to buy more cryptocurrencies than the other fiat currencies.

![Daily Count of Unique Cryptocurrencies Traded](images/unique_cryptocurrency_count.png)

### Is crypto a viable asset class? Who are the winners and laggards?
*Answer here.*