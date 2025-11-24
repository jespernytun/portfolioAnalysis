# Portfolio Analysis
A quantitative finance tool focused on beta calculation, with future plans for full portfolio metrics (P/E ratios, sharpe ratio, etc...)

## Overview
This project is a work-in-progress quantitative finance tool designed to analyse individual stocks and, eventually, complete investment portfolios.
The current version focuses on beta calculation, while later versions will support portfolio-level metrics such as weighted P/E, aggregated beta, Sharpe ratio, and custom portfolio imports.

## Current state
The project currently calculates the beta of one or more stocks relative to a chosen market index. <br>
**This includes:** <br>
Downloading historical price data <br>
Computing daily returns <br>
Performing a linear regression against benchmark returns <br>
Extracting the stock’s beta value <br>

## Future plans
**CSV Import from Nordnet**<br>
Ability to upload/export your actual Nordnet portfolio<br>
Automatic extraction of tickers, weights, and quantities <br>

**Weighted Portfolio Calculations**<br>
Weighted average P/E ratio, beta and other metrics

**Sharpe Ratio Calculation**<br>
Sharpe ratio for both single assets and full portfolio

**Additional Metrics**<br>
Correlation matrix
Portfolio variance
Cumulative returns
Visualisations (risk/return plots, heatmaps)

## Purpose of this project
This project was started to build hands-on experience in quantitative finance.
