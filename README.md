# ⚡ GB Electricity Market – Kriti 2025 Project

This repository presents a full-stack data science pipeline exploring the **Great Britain (GB) Electricity Market**, created for the **Kriti 2025** technical competition at IIT Guwahati. It combines live data collection, in-depth exploratory analysis, and quantitative modeling to build and backtest trading strategies on electricity price movements.

---

## 📂 Repository Structure

| File                     | Description |
|--------------------------|-------------|
| `data_collection.ipynb`  | Fetches historical and real-time electricity market data from the BMRS/Elexon APIs including wind/solar forecasts, market prices, demand, etc. |
| `data_analysis.ipynb`    | Performs comprehensive EDA and visualizations to uncover patterns, volatility clusters, and price/demand relationships. Includes **Markov Switching Model** for volatility regime detection. |
| `trading_strategy.ipynb` | Implements and evaluates multiple trading strategies including CUSUM regime-based logic, Random Forest predictive modeling, and volatility-aware timing rules. |
| `requirements.txt`       | All required Python dependencies with pinned versions for smooth reproducibility. |
| `README.md`              | You’re reading it 🙂 Contains an overview and setup guide. |
| `hostel57_the_gb_electricity_market_report.pdf` *(optional)* | Final project report (if present), summarizing key findings and methodology. |

---

## 🎯 Project Goals

- 📈 **Model the GB electricity market** using machine learning and statistical tools.
- 🔌 Analyze the impact of **renewable energy forecasts (wind, solar)** and **demand profiles** on market prices.
- 🧠 Apply **Markov Switching Models** to detect regime shifts in volatility.
- 🤖 Build **intraday trading strategies** using:
  - Net Imbalance Volume forecasts (NIV-based)
  - CUSUM-based trend regimes
  - Random Forest predictive signals
- 📊 Evaluate strategies on return, drawdown, and risk-adjusted metrics.

---

## ⚙️ Setup Instructions

### ✅ Prerequisites
- Python 3.8+
- Jupyter Notebook or JupyterLab

### 📦 Installation

Install all required dependencies with pinned versions:

```bash
pip install -r requirements.txt
