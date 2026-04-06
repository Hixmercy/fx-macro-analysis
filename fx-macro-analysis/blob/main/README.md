# 📊 Central Bank Policy vs Forex Market Behavior

## 📌 Overview

This project presents a data-driven analysis of the relationship between central bank interest rates and foreign exchange market behavior, using EURUSD and GBPUSD currency pairs as case studies.

## 🎯 Objective

To evaluate the extent to which interest rate movements influence FX market dynamics, and to determine whether monetary policy alone can explain currency behavior.


## 🧰 Tools & Technologies

* Python (pandas, matplotlib, seaborn, statsmodels)
* yfinance (market data sourcing)


## 📊 Methodology

### 1. Data Collection

Historical FX price data was obtained and aligned with macroeconomic indicators, specifically interest rates.

### 2. Data Transformation

Price data was converted into returns to accurately reflect market behavior and enable statistical analysis.

### 3. Volatility Analysis

Rolling standard deviation was used to identify periods of heightened market risk and instability.

### 4. Correlation Analysis

Relationships between FX pairs and interest rates were measured to identify dependencies.

### 5. Regression Analysis

Statistical models were applied to quantify the influence of interest rates on currency movements.

## 📈 Key Findings

* EURUSD and GBPUSD are strongly correlated, reflecting shared exposure to USD movements
* US interest rates exhibit an inverse relationship with EURUSD, consistent with macroeconomic expectations
* The relationship between interest rates and FX is present but not consistently strong, indicating additional influencing factors
* Market volatility increases during periods of monetary policy adjustment, reflecting uncertainty
* Global monetary policy exerts significantly more influence on FX markets than local policy

## 📂 Project Structure

id="211934"
outputs/
   charts/
      fx_price_trends.png
      fx_returns.png
      fx_volatility.png
      correlation_matrix.png
      eurusd_vs_rates.png
## 📊 Conclusion

The analysis demonstrates that while interest rates are an important driver of foreign exchange markets, they do not operate in isolation. Currency behavior is shaped by a combination of monetary policy, global liquidity conditions, and market sentiment.

A comprehensive understanding of FX markets therefore requires both quantitative analysis and macroeconomic interpretation.
