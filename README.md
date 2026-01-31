# 📈 Financial Data Science & ML Experiments

Welcome to this repository! Here, I explore financial markets, investment strategies, and economic indicators through the lens of **Data Science** and **Machine Learning**.

The goal of this repo is to perform backtesting, visualize market behaviors, and validate (or debunk) common investment myths using Python.

## 🚀 Repository Structure

The repository is organized by specific projects or analysis topics.

### 📂 Current Projects

#### 1. Market Sentiment Backtesting (`/fear_and_greed`)
**Objective:** Validate if the *Fear & Greed Index* can be used as a reliable signal to time the market compared to a passive strategy.

* **Scope:** S&P 500 analysis from 2011 to 2026.
* **Methodology:** A comparative backtest of 3 distinct strategies under equal conditions (same monthly contribution):
    1.  **DCA (Baseline):** Passive monthly investment.
    2.  **Buy the Fear:** Accumulate cash and only buy during "Extreme Fear" (<20).
    3.  **Fear & Greed Swing:** Buy the fear, but sell a percentage during "Extreme Greed" (>90).
* **Key Findings:**
    * **DCA** yielded the highest return (XIRR), proving that "time in the market" beats timing.
    * Active strategies suffered from **Cash Drag** (money sitting idle), significantly hurting compound interest.
    * The active strategy reduced **Max Drawdown** by nearly 50%, acting as a volatility dampener at the cost of total profit.

---

## ⚠️ Disclaimer

**This repository is for educational and research purposes only.**
Nothing in this repository constitutes financial advice. Past performance is not indicative of future results. All backtests are simulations and may not account for all real-world factors such as slippage, variable fees, or exact tax brackets.

---

**Author:** [Samuel Reyes Sanz]
*Connect with me on [LinkedIn](https://www.linkedin.com/in/samuel-reyes-sanz/)*