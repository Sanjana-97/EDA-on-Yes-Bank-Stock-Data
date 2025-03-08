# Yes Bank Stock Price EDA

This project performs **Exploratory Data Analysis (EDA)** on **Yes Bank’s stock prices** from **July 2005 to November 2020** to uncover **trends**, **volatility**, and **market behavior**. The analysis helps investors make **data-driven decisions** for **better market understanding**.

## Techniques Used

- **Time Series Analysis**: Identifying long-term price trends.
- **Volatility Analysis**: Using **Rolling Standard Deviation** and **Bollinger Bands** to assess risk.
- **Market Classification**: Classifying market periods as **Bullish** or **Bearish** based on daily returns.
- **Correlation Analysis**: Analyzing the relationship between stock price variables.
- **Machine Learning (Optional)**: Predicting future trends (ARIMA, LSTM, Random Forest).

## Results & Insights

- **Stock Price Trends**: The dataset shows significant **price fluctuations** in Yes Bank's stock from **July 2005 to November 2020**, with periods of **strong growth** and **sharp declines**.
- **Volatility**: The stock exhibits **high volatility** with a **standard deviation of ₹98.58** in closing prices, indicating large **price swings** over time.
- **Bullish vs Bearish Periods**: The **bullish periods** (positive returns) are more frequent, suggesting **growth opportunities** for investors during these times. **Bearish periods** (negative returns) highlight times when the stock experienced **decline**, signaling potential **exit points** for risk-averse investors.
- **Risk Management**: The **Bollinger Bands** and **Rolling Standard Deviation** analysis helped identify **overbought** and **oversold** conditions, providing clear entry and exit signals.
- **Market Sentiment**: The analysis of daily returns shows that the market sentiment is often driven by **volatility**; therefore, investors should be mindful of market conditions before making decisions.
- **Diversification Strategy**: **Correlation analysis** between stock price variables (Open, High, Low, Close) indicates a **strong relationship** between them, suggesting that diversification into different sectors could be beneficial for **risk reduction**.

## Usage

Run the **Jupyter Notebook** to see the analysis in action.

```bash
jupyter notebook YesBank_Stock_EDA.ipynb
