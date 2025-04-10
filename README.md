# SSL Stock Volatility Prediction

This project aims to predict the stock volatility of **Sasol Limited (SSL)**, a leading South African energy and chemicals company. We use a **GARCH model** to forecast future volatility based on historical stock returns.

## Project Overview

Sasol Limited (SSL) is a major player in the global energy and chemicals industry, with operations in the production of synthetic fuels, plastics, fertilizers, and more. The model built in this project predicts volatility in the stock prices of Sasol, offering insights into the market’s risk and price fluctuations.

## Key Features

- **Stock Data Collection**: Retrieves historical stock data for Sasol from Alpha Vantage API.
- **Data Wrangling**: Prepares and cleans the data for analysis.
- **Volatility Prediction**: Uses a GARCH model to predict daily and annual volatility.
- **Exploratory Data Analysis (EDA)**: Analyzes trends, volatility patterns, and the impact of external factors (e.g., COVID-19).
- **Model Performance**: Evaluates and tunes the GARCH model to fit the data.

## Installation

To use this project, clone the repository and install the required libraries:

```bash
git clone https://github.com/HarrisTekenah/SSL-Stock-Volatility-Prediction.git
cd SSL-Stock-Volatility-Prediction
pip install -r requirements.txt
