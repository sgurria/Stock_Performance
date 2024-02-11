# Sanofi Stock Performance Analysis 2023

This repository contains an analysis of Sanofi's stock performance throughout 2023, leveraging financial data and news event sentiment analysis. The analysis aims to identify significant stock price movements and correlate them with major news events to understand their impact on Sanofi's stock.

## Repository Structure

- `GDelt_Sanofi.ipynb`: Jupyter notebook for extracting Sanofi-related news using the GDELT database.
- `sanofi2023.csv`: CSV file generated from `GDelt_Sanofi.ipynb`, containing news data related to Sanofi in 2023.
- `README.md`: Provides an overview of the repository and instructions on how to navigate the analysis.

## Analysis Overview

The analysis is conducted through a multi-step approach:

1. **Significant Daily Returns Analysis**: Identifies days with significant stock price movements by setting a threshold for daily returns. This helps in spotting immediate market reactions to news events.

2. **Abnormal Returns Analysis**: Calculates abnormal returns as the difference between actual returns and expected (historical average) returns. This method is used to identify how specific news events deviate from normal market behavior.

3. **Stock News Sentiment Analysis**: Applies sentiment analysis on news headlines to quantify the emotional valence of news coverage. This technique distinguishes between positively and negatively framed stories and assesses their potential influence on stock price movements.
