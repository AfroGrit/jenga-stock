### Project Overview

This project aims to automate Forex trading by leveraging data scraping, modeling, simulation, and automation techniques. It involves collecting real-time and historical Forex data, developing predictive models, simulating trading scenarios, and automating trading decisions based on the models.

### Design Document

#### 1. Data Scraping
- **Objective:** Collect real-time and historical Forex data from various online sources.
- **Implementation:**
  - Use web scraping libraries like BeautifulSoup or Scrapy to fetch Forex data.
  - Extract currency pair prices, economic indicators, and external market data (e.g., gold prices, stock indices).
  - Ensure data integrity and update frequency to maintain accuracy in trading strategies.

#### 2. Modeling
- **Objective:** Develop predictive models to analyze Forex market trends and movements.
- **Implementation:**
  - Utilize machine learning algorithms (e.g., linear regression, random forest) to predict currency pair movements.
  - Feature engineering to enhance model performance with technical indicators, sentiment analysis, and economic indicators.
  - Train models on historical data and validate using cross-validation techniques to ensure robustness.

#### 3. Simulation
- **Objective:** Create simulations to test trading strategies based on predictive models.
- **Implementation:**
  - Design simulation environments that replicate real-world market conditions.
  - Implement trading algorithms based on model predictions and risk management strategies.
  - Evaluate performance metrics such as profit and loss, Sharpe ratio, and drawdown to assess strategy effectiveness.

#### 4. Automated Trading
- **Objective:** Automate Forex trading decisions based on simulation results and model predictions.
- **Implementation:**
  - Integrate trading APIs (e.g., MetaTrader, OANDA API) for executing trades programmatically.
  - Implement decision-making logic based on real-time data feeds and model updates.
  - Monitor and optimize trading strategies continuously based on performance metrics and market conditions.


#### Contents

1. **Forex Currency Pairs (Daily Data)**
2. **African Currency Pairs (Daily Data)**
3. **External Indicators (Daily Data)**
4. **Economic Indicators (Monthly Data)**

#### Usage

To use these dictionaries in your Python project, simply import the dictionaries and utilize them as needed.


#### Dictionaries

##### 1. Forex Currency Pairs (Daily Data)
```python
forex_currency_pairs_daily = {
    'EUR/USD': 'Euro / US Dollar',
    'USD/CAD': 'US Dollar / Canadian Dollar',
    ...
}
```

##### 2. African Currency Pairs (Daily Data)
```python
african_currency_pairs_daily = {
    'USD/ZAR': 'US Dollar / South African Rand',
    'EUR/ZAR': 'Euro / South African Rand',
    ...
}
```

##### 3. External Indicators and Economic Indicators (Daily Data)
```python
external_indicators_daily = {
    'XAU/USD': 'Gold / US Dollar',
    'XAG/USD': 'Silver / US Dollar',
    'WTI': 'West Texas Intermediate Crude Oil',
    'Brent': 'Brent Crude Oil',
    'VIX': 'Volatility Index',
    'SPX': 'S&P 500 Index',
    'DXY': 'US Dollar Index',
    'US10Y': 'US 10-Year Treasury Yield',
    'HG': 'Copper Futures',
    'CNY/USD': 'Chinese Yuan / US Dollar',
    'BTC/USD': 'Bitcoin / US Dollar'
}
```

##### 4. Economic Indicators (Monthly Data)
```python
economic_indicators_monthly = {
    'US GDP': 'US Gross Domestic Product',
    'US CPI': 'US Consumer Price Index',
    ...
}
```

