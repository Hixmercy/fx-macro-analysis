#  Central Bank Policy vs FX Market Behavior

## 📌 Overview

This project investigates the relationship between U.S. Federal Reserve interest rate decisions and foreign exchange (FX) market behavior, using EUR/USD and GBP/USD as case studies.

The goal is to determine whether monetary policy actions—specifically interest rate changes—have a measurable impact on price movement, returns, and volatility in major currency pairs.

## 🎯 Objective

To test the hypothesis:

**Interest rate announcements by the Federal Reserve significantly influence FX price movements, returns, and market volatility.**
 

## ⚙️ Methodology

### 1. Data Collection

* FX data (EUR/USD, GBP/USD) retrieved using yfinance
* Federal Reserve rate decision dates compiled manually

### 2. Data Processing

* Cleaned and flattened FX dataset
* Converted time index to datetime
* Engineered features:

  * Daily returns
  * Rolling volatility (5-day window)

### 3. Event Identification

* Marked Fed rate decision dates as event days
* Created binary variable:

  * 1 → Rate event
  * 0 → No event

### 4. Event Study Analysis

For each rate decision:

* Calculated average returns before and after events
* Measured volatility shifts around events

### 5. Visualization

Generated charts to support analysis:

* Price movement with event markers
* Returns comparison (before vs after events)
* Volatility comparison (before vs after events)

## 📈 Key Visual Insights

### 1. Price Reaction to Rate Events

* Rate events do not consistently trigger immediate reversals
* Many events align with ongoing trends rather than causing new ones

**Insight:** Markets often price in expectations before the announcement

### 2. Returns Before vs After Events

* Post-event returns differ from pre-event returns in some cases
* No consistent directional bias is observed

**Insight:** Rate decisions create movement, but not reliable direction

### 3. Volatility Behavior

* Volatility tends to increase around rate decision periods
* Elevated volatility often persists shortly after events

**Insight:** Rate announcements act as volatility catalysts

## 🧠 Interpretation

### What the Data Shows

* FX markets respond to rate decisions
* The impact is stronger in volatility than in price direction
* Market behavior suggests anticipation rather than reaction

### What the Data Does NOT Support

* No consistent evidence that:

  * Rate hikes always strengthen USD
  * Rate cuts always weaken USD

**Conclusion:** The relationship is not linear or predictable

---

## ❌ Hypothesis Evaluation

**Hypothesis:** Interest rate announcements significantly influence FX behavior

**Verdict:** Partially Validated

* Valid for volatility impact
* Weak for directional price prediction


## 📊 Key Takeaways

* Markets are forward-looking
* Expectations matter more than announcements
* Volatility provides opportunity, not guaranteed direction
* Macro events require context beyond the headline

## 🚀 What This Project Demonstrates

* Financial data collection and preprocessing
* Time series analysis
* Event-driven market analysis
* Data visualization and interpretation
* Analytical thinking in financial markets

## 🔧 Tools Used

* Python
* Pandas
* Matplotlib
* yfinance
## 📌 Final Thought

**The event itself doesn’t move the market — expectations do.**
