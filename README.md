# Crypto_sentiment_Analysis

## Project Overview
This project analyzes the relationship between **market sentiment (Fear & Greed Index)** and **crypto trader performance** using historical trading data.

The goal is to understand how emotional market conditions influence:
- Trader profitability
- Buy/Sell behavior
- Trade volume
- Risk-taking patterns

## Technologies used:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code

## Pipeline/Workflow:
Problem Statement: Does sentiments like Greed and Fear affect traders' behavior and profitablity?
Data Collection: Trader sentiment and Trader Data
Data Cleaning: Cleaning the columns from spaces, lowercase, PnL to numeric
Date Engineering: Extracted Month-day from dataset
Data merging: Merged the datasets so that each trade has a sentiment attached to it
EDA: Analysed which sentiment is related to more profit, which sentiment has more trade, Correlation analysis

## Some Insights from this project:

1. Traders perform differently under Fear vs Greed.
2. Buy trades dominate during Greed.
3. Extreme Fear often shows volatile profits.
4. Sentiment impacts trading behaviour.

## Dataset Limitations

During analysis, certain constraints were identified in the provided datasets:

1. The trader activity dataset and sentiment dataset had limited overlapping timestamps/dates.
2. Some records belonged to different year ranges, reducing direct one-to-one temporal matching.
3. Historical trading data contained formatting inconsistencies that required preprocessing.
4. Due to these constraints, exact causal inference between sentiment and trade profitability is limited.

Despite these challenges, exploratory analysis was successfully conducted to identify broader behavioral trends.