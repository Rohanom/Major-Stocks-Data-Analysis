# 📈 Major Stock Analysis & Technical Indicator Visualization

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

This project is a comprehensive stock data analysis tool built using Python and Jupyter Notebook. It enables you to fetch historical market data, compute key technical indicators, and visualize trends, aiding in better trading or investment decisions.

---

## 📁 Project Structure

- **Stock_Analysis.ipynb** – Main notebook for data loading, visualization, and technical indicator computation.
- **data/** – *(Optional)* Folder to store any downloaded CSV files or backups.
- **charts/** – *(Optional)* Output directory for saved plots.

## 📌 Features

- 🗓️ Fetch stock data using Yahoo Finance (`yfinance`)
- 📊 Compute technical indicators like:
  - Simple Moving Average (SMA)
  - Exponential Moving Average (EMA)
  - Relative Strength Index (RSI)
  - Moving Average Convergence Divergence (MACD)
- 🖼️ Plot price charts with indicators and signals
- 🧠 Perform trend and momentum analysis
- 🧾 Simple signal generation (Buy/Sell zones)

## 🚀 How to Run

1. **Install Dependencies**

   Run the following command to install all required Python packages:

   ```bash
   pip install pandas numpy matplotlib seaborn yfinance ta

## 📌 Features

- ✅ **Stock Data Download** via `yfinance`
- ✅ **Interactive Charting** with price overlays
- ✅ **Built-in Indicators**: 
  - Moving Averages (SMA, EMA)
  - MACD & Signal Line
  - Relative Strength Index (RSI)
- ✅ **Buy/Sell Signal Zones** (based on RSI thresholds or MA crossovers)
- ✅ **Modular Codebase** for easy customization
- ✅ **No API key required** (free public data)

---

## 🧰 Tech Stack

### 🖥️ Programming Language
- Python 3.7+

### 📦 Libraries & Tools
| Library       | Purpose                             |
|---------------|-------------------------------------|
| `pandas`      | Data wrangling and time series      |
| `numpy`       | Numerical computations              |
| `matplotlib`  | Basic visualization                 |
| `seaborn`     | Statistical & styled visualizations |
| `yfinance`    | Fetching historical stock data      |
| `ta`          | Pre-built technical indicators      |
| `jupyter`     | Notebook for interactive workflows  |

---
