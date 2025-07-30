
# 📈 PrimeTrade AI – Data Science Task

This repository contains a comprehensive data science workflow focused on analyzing trading performance in relation to market sentiment, particularly using the Fear & Greed Index. The project blends historical trading data with sentiment analysis to generate actionable insights and trading strategy recommendations.

---

## 📂 Project Structure

- `primetrade_ai_DS_Task.ipynb`: Main Jupyter notebook containing all data loading, preprocessing, analysis, and strategy generation logic.
- `historical_data.csv`: Contains trade-level historical data including PnL, size, and timestamps.
- `fear_greed_index.csv`: Contains market sentiment scores and classifications.

---

## 📊 Key Features

### ✅ Data Loading & Preprocessing
- Robust loading with error handling
- Timestamp parsing and feature engineering (`Hour`, `Date`, etc.)
- Sentiment classification based on Fear & Greed Index

### 🔍 Exploratory Data Analysis (EDA)
- Descriptive statistics
- PnL and trade size distributions
- Sentiment breakdowns over time
- Correlation matrix between trading metrics and sentiment

### 🧠 Sentiment-Based Performance Analysis
- PnL, win rate, and trade volume by sentiment category
- Visualization of sentiment's effect on performance
- Boxplots, bar charts, pie charts, and time-series plots

### 📌 Trader Behavior Analysis
- Trader-level metrics: total PnL, win rate, average sentiment exposure
- Insights into characteristics of top performers

### 💡 Strategy Recommendations
- Generated based on performance and behavioral insights
- Includes timing strategies, sentiment-based risk management, and contrarian plays

---

## 🚀 How to Run

1. **Upload CSVs to Colab**
   - `historical_data.csv`
   - `fear_greed_index.csv`

2. **Open and run the notebook:**
   ```python
   import pandas as pd
   import matplotlib.pyplot as plt
   import seaborn as sns
   ```

3. **Call key functions in order:**
   - `load_and_preprocess_data()`
   - `perform_eda()`
   - `merge_and_analyze()`
   - `analyze_sentiment_performance()`
   - `calculate_trader_metrics()`
   - `generate_strategy_recommendations()`

---

## 📈 Example Outputs

- Win Rate by Sentiment:
  ![Win Rate Plot](link-to-screenshot-if-applicable)

- Correlation Heatmap:
  ![Correlation Matrix](link-to-screenshot-if-applicable)

---

## 📌 Strategy Highlights

1. **Sentiment Contrarian Strategy**: Trade against extreme sentiment conditions.
2. **Optimal Timing Strategy**: Trade more during favorable sentiment windows.
3. **Risk Management by Sentiment**: Adjust trade size based on sentiment volatility.
4. **Cluster-Based Approach**: Mimic behavioral patterns of top traders.

---

## ⚠️ Disclaimer

This analysis is based on historical data and does not constitute financial advice. Past performance is not indicative of future results. Always use appropriate risk management practices.

---

## 📬 Contact

For questions or collaboration, feel free to reach out via [your_email@example.com] or open an issue.
