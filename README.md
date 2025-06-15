📊 NIFTY 50 Stock Portfolio Analysis

📝 Project Overview
This project analyzes the NIFTY 50 index constituents using three distinct investment strategies:

1. Equal Weighting: Allocating equal capital to the top 10 stocks by market capitalization.

2. Value Investing: Selecting top 10 stocks based on five key financial metrics: Price, P/E Ratio, P/B Ratio, P/S Ratio, and EV/EBITDA.

3. Dividend-Based Investing: Identifying top 10 stocks with a Dividend Score that was calculated using a weighted scoring model based on Dividend Yield, Dividend Rate, Payout Ratio, and Earnings Growth.

The objective is to evaluate and compare these strategies to determine the most effective approach for investing in the NIFTY 50.

🧪 Methodology

1. Equal Weighting Strategy
- Selection Criteria: Top 10 stocks by Market Cap
- Investment Approach: Allocate equal capital to each selected stock

2. Value Investing Strategy
- Selection Critera: Top 10 stocks based on 5 key financial metrics (Price, P/E Ratio, P/B Ratio, P/S Ratio, EV/EBTDA)
- Investment Approach: Rank and select top 10 stocks based on Final Score calculated using the key metrics

3. Dividend-Based Investing Strategy
- Selection Criteria: Top 10 stocks based on the weighted scoring model
- Investment Approach: Normalise the key metrics (Dividend Yield, Dividend Rate, Payout Ratio, Earnings Growth), apply weights and calculate dividend score to rank stocks

📦 Requirements
yfinance
pandas
numpy
matplotlib (optional, for visualizations)

🚀 Usage
1. Clone this repository

2. Navigate to the respective Jupyter notebook for the strategy you wish to analyze:
-- equal_weights.ipynb
-- value_investing.ipynb
-- dividend_based_investing.ipynb

3. Open the notebook in Jupyter lab or VS Code

4. Run the cells sequentially to execute the analysis

📈 Results
Each notebook provides:
: Rankings of stocks for the respective strategy.
: Visualizations of portfolio performance.
: Insights into the effectiveness of each investment strategy.

🤝 Contributing
Contributions are welcome!

📄 License
This project is licensed under the MIT License.
