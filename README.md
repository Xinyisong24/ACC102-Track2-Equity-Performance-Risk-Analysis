# Equity Performance & Risk Analysis

## 1. Problem & User
- This project analyzes stock performance and risk to help investors make more informed decisions.
- The target users are individual investors or analysts who want to understand both returns and downside risks.

## 2. Data (source + access date + key fields)
- Data is collected from CRSP via WRDS and accessed in April 2026.
- Key fields include date, stock price, daily return, and market index return.

## 3. Methods & Python Workflow
- Data extraction from WRDS
- Data cleaning and time filtering
- Normalized price comparison
- Cumulative return calculation
- 30‑day rolling volatility
- Drawdown analysis
- Return correlation heatmap
- Sharpe ratio & rolling Sharpe ratio
- Maximum drawdown
- CAPM regression (alpha & beta) using statsmodels

## 4. Key Findings
- Some stocks outperform others but with higher volatility
- Higher returns are often associated with higher risk
- Maximum drawdown reveals significant downside exposure
- Correlation analysis suggests diversification opportunities
- Sharpe ratio provides a clearer view of risk-adjusted performance

## 5. How to run
- Clone or download this repository to your local computer
- Install all required dependencies by running: `pip install -r requirements.txt`
- Open the Jupyter Notebook file (`.ipynb`) in your preferred environment
- Run the notebook cells in order from top to bottom
- A valid WRDS account is required to connect and retrieve stock data
- All charts, metrics, and regression results will be generated automatically

## 6. Demo link
- https://video.xjtlu.edu.cn/Mediasite/Play/9b8d022ea03d421aa08fef777f139c5a1d

## 7. Limitations & next steps
- Based only on historical data
- No transaction costs included
- Limited number of stocks analyzed
- Future work could include more assets, longer time periods, and advanced risk models