# Equity Performance & Risk Analysis

## 1. Problem & User 
This project analyzes stock performance and risk to help investors make more informed decisions. The target users are individual investors or analysts who want to understand both returns and downside risks.

## 2. Data (source + access date + key fields)
The data consists of historical stock price data collected from public financial sources (e.g., Yahoo Finance) and accessed in April 2026. Key fields include date, closing price, and calculated daily returns.

## 3. Methods (main Python steps)
- Load and clean stock price data using pandas  
- Compute daily returns  
- Calculate rolling Sharpe ratio using a 60-day window  
- Compute cumulative returns and maximum drawdown  
- Analyze correlations between stock returns  
- Visualize results using matplotlib  

## 4. Key Findings 
- Some stocks outperform others but with higher volatility  
- Higher returns are often associated with higher risk  
- Maximum drawdown reveals significant downside exposure  
- Correlation analysis suggests diversification opportunities  
- Sharpe ratio provides a clearer view of risk-adjusted performance  

## 5. How to run 
Run the Jupyter Notebook file step by step. Ensure required libraries (pandas, numpy, matplotlib) are installed before execution.

## 6. Demo link 
Demo available via the Jupyter Notebook included in this repository.

## 7. Limitations & next steps
- Based only on historical data  
- No transaction costs included  
- Limited number of stocks analyzed  
- Future work could include more assets, longer time periods, and advanced risk models