# NASDAQ Stock Data Analysis

## Project Overview

This project presents an analysis of stock price data for five NASDAQ companies. The goal was to collect historical data using the Yahoo Finance API, perform basic analysis, and evaluate data quality using key performance indicators (KPIs).

The selected companies are:

* DDOG (Datadog)
* CRWD (CrowdStrike)
* ZS (Zscaler)
* MDB (MongoDB)
* OKTA (Okta)

## Source of Data

The data was collected using the Python library `yfinance`, which retrieves financial data from Yahoo Finance.

Each dataset contains:

* Date (time index)
* Open price
* High price
* Low price
* Close price
* Adjusted close price
* Volume

The data covers different one-year periods for each company.

## Data Quality KPIs

### Completeness

All datasets are complete, with no missing values in the analyzed columns. The completeness level is approximately 100%.

### Latency

Each dataset covers a clearly defined one-year period.

### Accuracy

The stock prices are realistic, with no negative values.

### Consistency

The datasets are consistent:

* no duplicated rows were found
* dates are in chronological order

## Conclusion

The datasets are suitable for basic financial analysis and visualization.
