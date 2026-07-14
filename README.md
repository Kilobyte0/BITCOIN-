# ₿ Bitcoin Price Forecasting & Market Analysis (2014–2026)

> **Forecasting Bitcoin prices using Time Series Analysis, SARIMAX Forecasting, Monte Carlo Simulation, and Power BI Dashboarding.**

---

# Executive Summary

Bitcoin is one of the world's most volatile financial assets, making accurate price forecasting both challenging and valuable for investors, analysts, and financial institutions.

This project presents an end-to-end financial analytics solution that combines **Python**, **SARIMAX Time Series Forecasting**, **Monte Carlo Simulation**, and **Power BI** to analyze more than a decade of historical Bitcoin market data and forecast potential price movements through **December 2026**.

By integrating statistical forecasting with probabilistic simulation, the project estimates both the expected future price and the uncertainty surrounding that prediction. The accompanying Power BI dashboard transforms complex financial data into an interactive business intelligence solution for market analysis and decision-making.

Forecasting cryptocurrency prices is inherently challenging due to high volatility, rapid shifts in market sentiment, and uncertain future conditions. Traditional forecasting methods typically estimate a single future price while providing limited insight into the uncertainty surrounding that prediction. This project addresses these challenges by combining statistical forecasting with probability-based simulation to provide a more comprehensive view of future market behaviour and support informed investment decision-making.

---

# Project Objectives

This project was developed to:

- Analyze Bitcoin's historical market performance.
- Forecast future Bitcoin prices using SARIMAX.
- Simulate thousands of possible future market outcomes using Monte Carlo Simulation.
- Compare deterministic and probabilistic forecasting techniques.
- Build an interactive Power BI dashboard for financial reporting.
- Generate actionable business insights to support investment decision-making.

---

# Key Performance Indicators (KPIs)

| Metric | Value |
|---------|-------:|
| **Analysis Period** | **2014 – 2026** |
| **Total Trading Days** | **4.28K** |
| **Current Bitcoin Price** | **$60.923K** |
| **All-Time High** | **$126.20K** |
| **All-Time Low** | **$171.51** |
| **Distance from ATH** | **-51.72%** |
| **Average Closing Price** | **$28.64K** |
| **Total Trading Volume** | **$95.46T** |
| **Annual Return** | **13,221.26%** |
| **Average Monthly Return** | **6.14%** |
| **Latest Monthly Return** | **-17.20%** |
| **Market Phase** | **Bull Market** |
| **Trend Signal** | **Bearish** |
| **Forecasting Models** | **SARIMAX & Monte Carlo Simulation** |
| **Visualization Tool** | **Power BI** |

---

# Dataset Overview

The analysis uses historical Bitcoin market data spanning **2014–2026**, consisting of daily observations for:

- Date
- Open Price
- High Price
- Low Price
- Close Price
- Trading Volume

Daily observations were aggregated into monthly closing prices to improve forecasting stability and reduce short-term market noise.

---

# Methodology

### Data Preparation

Historical Bitcoin market data was cleaned, validated, and transformed into monthly time-series observations before modelling.

### Exploratory Data Analysis

Historical price behaviour was analysed to identify:

- Long-term market trends
- Bull and bear market cycles
- Historical volatility
- Trading volume behaviour
- Monthly returns
- Major market corrections

### Feature Engineering

Additional financial features were created to improve forecasting performance, including:

- Monthly Closing Price
- Monthly Log Close
- Monthly Log Returns

### Forecasting Models

#### SARIMAX

A Seasonal AutoRegressive Integrated Moving Average (SARIMAX) model was trained on historical monthly closing prices to generate long-term forecasts through **December 2026**, including forecast trends and **80% confidence intervals**.

#### Monte Carlo Simulation

Historical monthly returns were used to generate thousands of possible future price paths, producing:

- Median Forecast
- 10th Percentile Scenario
- 90th Percentile Scenario
- Future Price Distribution
- Investment Risk Scenarios

---

# Analytical Insights

## Historical Market Performance

- Bitcoin generated a cumulative return of **13,221.26%**, making it one of the highest-performing financial assets of the past decade.
- The analysis covers approximately **4.28K trading days**, during which Bitcoin maintained an average closing price of **$28.64K**.
- Bitcoin appreciated from an all-time low of **$171.51** to a record high of **$126.20K**, demonstrating exceptional long-term growth.
- Total trading volume exceeded **$95.46 trillion**, reflecting strong and sustained market participation.

---

## Trend Analysis

### Moving Average Indicators

| Indicator | Value |
|-----------|-------:|
| **MA (20)** | **$73.19K** |
| **MA (50)** | **$76.40K** |
| **MA (100)** | **$73.10K** |
| **MA (200)** | **$78.78K** |

### Market Interpretation

- Bitcoin remains within a long-term **Bull Market**, indicating positive long-term market structure.
- The current **Bearish Trend Signal** reflects weakening short-term momentum, with prices trading below major moving averages.
- Bitcoin currently trades **51.72% below** its all-time high, highlighting both recent market corrections and potential recovery opportunities.

---

## Forecast Analysis

Two complementary forecasting techniques were implemented to improve forecasting reliability and provide a more comprehensive assessment of future Bitcoin price behaviour.

### Forecast Summary

| Model | Outcome |
|--------|----------|
| **SARIMAX** | Conservative long-term forecast based on historical trends and seasonality |
| **Monte Carlo Simulation** | Thousands of simulated price paths reflecting future market uncertainty |
| **Forecast Horizon** | December 2026 |
| **Confidence Interval** | 80% |

### Comparative Insight

- **SARIMAX** estimates the most statistically likely future price trend using historical market behaviour.
- **Monte Carlo Simulation** evaluates a wide range of potential future prices by modelling thousands of possible market scenarios.
- Combining both techniques provides a stronger analytical framework by integrating statistical forecasting with probability-based risk assessment.

---

# Power BI Dashboard

The interactive Power BI dashboard provides comprehensive insights into Bitcoin market performance through:

- Executive Overview
- Historical Price Analysis
- Moving Average Analysis
- Market Cycle Analysis
- Volatility Analysis
- Forecast Comparison

Interactive filters enable users to explore market behaviour across different periods and identify emerging trends.

---

# Key Business Insights

- Bitcoin generated a cumulative return exceeding **13,221%**, reinforcing its position as one of the highest-performing financial assets over the analysis period despite substantial market volatility.
- Historical price movements reveal recurring bull and bear market cycles, demonstrating that Bitcoin follows cyclical market behaviour rather than continuous growth.
- Forecast uncertainty increases as the prediction horizon extends, highlighting the importance of probability-based forecasting when analysing highly volatile assets.
- Combining SARIMAX Forecasting with Monte Carlo Simulation provides both an expected price trajectory and a probability distribution of future outcomes, enabling more comprehensive investment risk assessment.
- Interactive Power BI dashboards transform complex analytical outputs into intuitive business intelligence, making financial insights more accessible to both technical and non-technical stakeholders.

---

# Business Recommendations

- Combine statistical forecasting with scenario-based simulation when evaluating cryptocurrency investments.
- Monitor market volatility and technical indicators alongside forecast models before making investment decisions.
- Continuously retrain forecasting models using recent market data to improve predictive performance.
- Incorporate macroeconomic variables such as inflation, interest rates, institutional adoption, and market sentiment into future forecasting models.

---

# Conclusion

This project demonstrates how advanced time series forecasting, probabilistic simulation, and interactive business intelligence can be combined to analyse cryptocurrency markets and support data-driven investment decisions.

Using over **4.28K trading days** of historical Bitcoin market data, the analysis identified exceptional long-term growth, significant market volatility, and recurring market cycles. The integration of **SARIMAX Forecasting**, **Monte Carlo Simulation**, and **Power BI** provides a comprehensive financial analytics framework capable of forecasting future price behaviour while quantifying investment uncertainty.

Overall, this project showcases the practical application of data analytics, predictive modelling, and business intelligence to transform complex financial data into meaningful insights for strategic financial decision-making.

---

# Skills Demonstrated

### Data Analytics

- Exploratory Data Analysis (EDA)
- Financial Data Analysis
- Data Cleaning
- Feature Engineering
- Business Intelligence
- Data Storytelling

### Time Series & Forecasting

- Time Series Analysis
- SARIMAX Forecasting
- Monte Carlo Simulation
- Forecast Validation
- Trend Analysis
- Market Cycle Analysis

### Data Visualization

- Interactive Dashboard Development
- Executive KPI Design
- Financial Reporting
- Business Insight Generation

---

# About the Author

## Muhydeen Abdulrazaq

**Data Analyst | Python | SQL | Power BI | Excel**

Specializing in financial analytics, predictive modelling, business intelligence, dashboard development, and statistical analysis.

Feel free to explore this repository, connect with me, or share your feedback.
