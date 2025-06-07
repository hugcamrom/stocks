# 📈 Stock Data Analysis & Visualisation

---

## 🧭 Overview

This project collects and visualises real-time stock data (MSFT, AAPL, GOOG) using `yfinance`, generating line plots, moving averages, histograms of returns, and interactive candlestick charts. It updates daily and saves snapshots as CSV files for continuous tracking.

---

## 🎯 Objectives

- Automatically fetch minute-level stock data using Yahoo Finance.
- Generate insightful visualisations including candlestick charts.
- Save an interactive HTML version of the candlestick chart.
- Maintain a historical record of market activity using timestamped CSVs.

---

## ✨ Features

- 📊 Line chart of real-time close prices (1-minute interval).
- 📈 5-period moving average visualisation.
- 📉 Histogram of minute-by-minute returns.
- 🕯️ Interactive candlestick chart for MSFT (saved as HTML).
- 🗂️ Auto-saved data with daily GitHub Actions support.

---

## 🧪 Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/hugcamrom/stocks.git
   cd stocks
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook stocks_visualisation.ipynb
   ```

4. View the interactive candlestick chart:
   - Open the file `msft_candlestick.html` in your browser.

---

## 🗂️ Project Structure

```
stocks/
│
├── data/                     # Daily timestamped CSV files
├── stocks.py                 # Script to fetch and save stock data
├── stocks_visualisation.ipynb  # Main Jupyter notebook
├── msft_candlestick.html     # Saved interactive chart
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

Requires Python 3.8+  
Recommended: Use a virtual environment

```bash
pip install -r requirements.txt
```

---

## 🛠️ Tools and Libraries

- [Python](https://www.python.org/)
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [plotly](https://plotly.com/)
- [yfinance](https://pypi.org/project/yfinance/)
- [GitHub Actions](https://docs.github.com/en/actions)

---

## 📚 Documentation and Insights

- The `stocks.py` script is scheduled to run daily via GitHub Actions and push new data files.
- The Jupyter notebook allows visual inspection and analysis of trends using various statistical and charting techniques.
- All data is resampled to 5-minute windows for candlestick plotting.

---

## 📡 Sources and References

- Yahoo Finance via [yfinance](https://pypi.org/project/yfinance/)
- Plotly documentation: https://plotly.com/python/candlestick-charts/
- pandas resampling: https://pandas.pydata.org/docs/user_guide/timeseries.html

---

## 🪪 Licence

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 🔖 Tags

`stocks` `python` `finance` `jupyter-notebook` `visualisation` `candlestick` `plotly` `automation` `yfinance`

---

**Author:** Hugo Camacho Romero  

**Student at:** [ATU](https://www.atu.ie/)

**Course:** Computer Infrastructure
