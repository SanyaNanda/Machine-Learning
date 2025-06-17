### **Phase 1: Foundations of Quant Finance & Data Handling (Beginner)**

**Goals**: Understand basics of financial markets, asset classes, and how to handle time series data.

#### Concepts:

* Stocks, ETFs, options, futures
* Time series basics: OHLCV data
* Returns: arithmetic, log, cumulative
* Risk measures: volatility, drawdown

#### Project 1: *Stock Price Forecasting with Linear Regression* [stock_price_forecasting.ipynb](stock_price_forecasting.ipynb)

* Data source: Yahoo Finance via `yfinance`
* Target: Predict next day's closing price
* Techniques: Extrapolatory Data Analysis (EDA), feature engineering, train-test split

In depth linear regression [Linear Regression]

#### Project 2: *Portfolio Returns & Risk Analysis Dashboard*

* Load multiple stock tickers
* Calculate daily returns, rolling volatility, Sharpe ratio
* Visualize portfolio evolution

---

### **Phase 2: Statistical Modeling & ML (Intermediate)**

**Goals**: Dive into ML models and apply them to trading strategies.

#### Concepts:

* Stationarity, mean reversion
* Technical indicators: RSI, MACD, Bollinger Bands
* ML models: Decision Trees, Random Forests, XGBoost
* Backtesting basics

#### Project 3: *Mean Reversion Strategy Using Bollinger Bands*

* Build trading signals using price deviation
* Backtest strategy returns vs. buy & hold

#### Project 4: *ML Classifier for Stock Movement Prediction*

* Create features (lagged returns, indicators)
* Train model to classify: up/down next day
* Evaluate with accuracy, F1, confusion matrix

---

### **Phase 3: Deep Learning & Advanced Modeling (Advanced)**

**Goals**: Apply DL to model sequences and explore modern quant tools.

#### Concepts:

* RNNs, LSTMs for time series
* Risk-adjusted optimization
* Regime detection
* Quantitative alpha factors

#### Project 5: *LSTM Model for Multi-step Stock Forecasting*

* Sequence input: past 60 days
* Output: next 5-day forecast
* Evaluation: RMSE, MAE, directional accuracy

#### Project 6: *Factor-Based Portfolio Construction (Smart Beta)*

* Build factors: value, momentum, size
* Rank and rebalance monthly
* Track portfolio turnover and performance

---

### **Phase 4: Real-World Application (Expert)**

**Goals**: Build end-to-end systems simulating real quant hedge fund workflows.

#### Concepts:

* Risk parity, Kelly Criterion
* Backtesting frameworks (bt, Zipline, Backtrader)
* API integration (Alpaca, Interactive Brokers)
* Real-time data streams

#### Capstone Project: *ML-Powered Trading Bot with Real-Time Execution*

* Connect to a paper trading API
* Run models and execute trades on live market data
* Log trades, monitor performance, track drawdowns


