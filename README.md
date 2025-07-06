# Breakeven Inflation Monitor

A Python-based tool that calculates and visualizes the 5-year and 10-year breakeven inflation rates using nominal U.S. Treasury yields and TIPS data from the Federal Reserve Economic Data (FRED) API. This project helps track market expectations of inflation and is relevant to discretionary macro trading and rates strategy.

## Features

- Pulls historical daily data from FRED via `fredapi`
- Computes breakeven inflation as the yield spread between nominal Treasuries and TIPS (5s & 10s)
- Outputs real-time 5Y and 10Y breakeven values
- Plots historical time series
- Useful for rates desks, macro strategy teams, and inflation traders
