# Crypto Sentiment vs Trader Performance Analysis

# Project Overview

This project analyzes how **market sentiment (Fear & Greed Index)** impacts **trader behavior and profitability**.

The goal is to uncover:
- How traders perform under different market emotions
- Behavioral patterns in trading activity
- Actionable strategies based on sentiment

---

##  Business Problem

Financial markets are highly influenced by **human emotions** such as fear and greed.

Understanding:
- When traders perform best
- How sentiment affects decision-making

This can help improve trading strategies and risk management.

---

# Datasets Used

# 1. Fear & Greed Index
- Sentiment score (0–100)
- Classification: Fear, Greed, etc.

# 2. Historical Trading Data
- Trade details (PnL, size, direction)
- Trader activity

---

##  Approach

### 1. Data Cleaning
- Converted timestamps to standard format
- Checked missing values and duplicates

### 2. Data Merging
- Joined trading data with sentiment data using date

### 3. Feature Engineering
Created:
- Win Rate
- Trade Size
- Long/Short Indicator

### 4. Exploratory Data Analysis
- PnL vs Sentiment
- Win Rate vs Sentiment
- Trade Size vs Sentiment
- Trade Frequency

### 5. Behavioral Analysis
- Segmented traders by activity level
- Compared performance across segments

---

##  Key Insights

-  **Fear markets generate highest total profits**
  → Due to high volatility

-  **Extreme Greed markets have highest win rate**
  → Strong trend-following opportunities

-  **Frequent traders outperform others**
  → More exposure to market opportunities

---

##  Strategies

### Strategy 1: Fear Volatility Strategy
- Trade more during fear markets
- Focus on short-term opportunities

### Strategy 2: Greed Trend Strategy
- Follow market trend
- Increase position size carefully

---

##  Bonus: Predictive Model

A simple ML model was built to:
- Predict trade profitability

This Adds forward-looking decision-making capability

---

##  Dashboard

A Streamlit dashboard was created to:
- Visualize metrics interactively
- Filter by sentiment
- Explore trader behavior

---

##  Tech Stack

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Streamlit

---

---

## 💡 Key Takeaway

Market sentiment plays a crucial role in trading outcomes.

👉 Combining sentiment + behavior → better strategies.

---

## 👨‍💻 Author

Aadi Teja - Data Science Graduate (2025)  
Focused on Data Analytics & Business Insights
