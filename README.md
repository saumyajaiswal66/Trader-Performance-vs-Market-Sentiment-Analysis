# 📊 Trader Performance vs Market Sentiment Analysis

## 📌 Project Overview

This project analyzes how **market sentiment (Fear, Greed, Neutral, Extreme Greed)** impacts trader behavior and performance.

Using historical trading data and Bitcoin market sentiment data, the goal is to uncover patterns that can help design **smarter trading strategies**.

---

## 🎯 Objectives

* Analyze relationship between **market sentiment and trader profitability**
* Understand how **trader behavior changes** under different sentiment conditions
* Identify **high-performing trader segments**
* Propose **data-driven trading strategies**

---

## 📂 Dataset Description

### 1. Market Sentiment Data

* Date
* Sentiment classification (Fear / Greed / Neutral / Extreme Greed)

### 2. Trader Data

* Account
* Execution price
* Trade size
* Trade side (Long/Short)
* Closed PnL
* Timestamp

---

## ⚙️ Methodology

### 1. Data Preparation

* Cleaned missing values and removed duplicates
* Converted timestamps to daily format
* Merged datasets using time alignment

### 2. Feature Engineering

* Daily PnL per trader
* Trade frequency
* Average trade size (risk proxy)
* Win rate
* Long/Short ratio

### 3. Analysis

* Compared trader performance across sentiment categories
* Studied behavioral changes (activity, trade size, bias)
* Segmented traders:

  * High vs Low activity
  * High vs Low risk
  * Consistent vs Inconsistent performers

### 4. (Optional Enhancements)

* Clustering traders into behavioral groups
* Basic predictive modeling

---

## 📊 Key Insights

* **Higher profitability observed during Fear and Greed**
  Large sample sizes confirm this as a reliable pattern.

* **Extreme Greed reduces profitability**
  Likely due to overtrading and excessive risk-taking.

* **Trader behavior changes with sentiment**

  * Greed → higher activity & larger trade sizes
  * Fear → more cautious and selective trading

* **Win rate does not guarantee profitability**
  Larger losses during unsuccessful trades reduce overall gains.

* **Moderate sentiment conditions are more stable**
  Balanced environments outperform extreme conditions.

---

## 🚀 Strategy Recommendations

* **Reduce position size during Extreme Greed**
  Avoid aggressive trading in highly optimistic markets

* **Focus on disciplined trading during Greed**
  Use stop-loss strategies to control large losses

* **Leverage Fear periods strategically**
  Favor high-confidence trades over high-frequency trading

* **Avoid trading in Neutral markets**
  Low activity and unclear trends reduce profitability

* **Prioritize consistency over high-risk strategies**
  Stable trading behavior leads to better long-term performance

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Jupyter Notebook
* (Optional) Streamlit
* Sklearn-Kmean Clustering

---

## ▶️ How to Run

1. Clone the repository
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the notebook:

   ```bash
   jupyter notebook
   ```
4. Run all cells to reproduce results

---

## 📁 Project Structure

```
├── data/
├── notebook.ipynb
├── README.md
└── outputs/ (charts, visuals)
```

---

## 🧠 Conclusion

This project demonstrates that **trader performance is strongly influenced by market sentiment**, but more importantly by **behavioral responses to that sentiment**.

Moderate conditions (Fear & Greed) provide the most consistent opportunities, while extreme sentiment often leads to **suboptimal decision-making and reduced profitability**.

---

## 📬 Contact

If you have any questions or suggestions, feel free to connect!

---
