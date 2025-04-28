# stock-trends-and-returns
Stock trend and return analysis for 2023–2024 based on Yahoo Finance data.
# Stock Trends and Returns (2023–2024)
This project analyzes the daily closing prices and annual returns of major companies across different global markets between 2023 and 2024.
---

## 📈 Project Structure

Each region has its own analysis notebook:

- `US_2023_2024.ipynb`
- `Taiwan_2023_2024.ipynb`
- `Hong Kong_2023_2024.ipynb`
- `Japan_2023_2024.ipynb`
- `Singapore_2023_2024.ipynb`

Each notebook includes:

- Download daily closing prices for 2023 and 2024
- Plot stock price trends for 2023 and 2024
- Calculate annual returns for both years
- Visualize annual returns in bar charts

---
## 🚀 Future Improvements

- Extend the analysis to multiple stocks or market indices.
- Incorporate moving averages and technical indicators for trend analysis.
- Implement simple machine learning models to predict future stock trends.
- Develop interactive dashboards using Plotly, Dash, or Streamlit.

---
## 📚 Markets and Companies Analyzed

- **United States (NASDAQ/NYSE)**
  - NVIDIA Corporation (NVDA)
  - Apple Inc. (AAPL)
  - Tesla, Inc. (TSLA)
  - Amazon.com, Inc. (AMZN)
  - Microsoft Corporation (MSFT)
  - Alphabet Inc. (GOOGL)

- **Taiwan (TWSE)**
  - Taiwan Semiconductor Manufacturing Company (2330.TW)
  - Hon Hai Precision Industry Co., Ltd. (2317.TW)
  - MediaTek Inc. (2454.TW)
  - Delta Electronics, Inc. (2308.TW)
  - Evergreen Marine Corporation (2603.TW)
  - Taiwan Cement Corporation (1101.TW)

- **Hong Kong (HKEX)**
  - Hong Kong Exchanges and Clearing Limited (0388.HK)
  - AIA Group Limited (1299.HK)
  - CK Asset Holdings Limited (1113.HK)
  - Sun Hung Kai Properties Limited (0016.HK)
  - Power Assets Holdings Limited (0006.HK)
  - Link Real Estate Investment Trust (0823.HK)

- **Japan (TSE)**
  - Toyota Motor Corporation (7203.T)
  - Sony Group Corporation (6758.T)
  - Mitsubishi Corporation (8058.T)
  - Tokyo Electric Power Company Holdings (9501.T)
  - Nintendo Co., Ltd. (7974.T)
  - Nidec Corporation (6594.T)

- **Singapore (SGX)**
  - DBS Group Holdings Ltd (D05.SI)
  - Oversea-Chinese Banking Corporation (OCBC) (O39.SI)
  - United Overseas Bank Ltd (UOB) (U11.SI)
  - Singapore Telecommunications Limited (Singtel) (Z74.SI)
  - Mapletree Industrial Trust (ME8U.SI)
  - Singapore Airlines Limited (C6L.SI)

---
## 📊 Outputs

- Stock closing price trends (solid line for 2023, dashed line for 2024)
- Year-over-year return comparison bar charts
- Visualized in local currencies:
  - USD (US stocks)
  - TWD (Taiwan stocks)
  - HKD (Hong Kong stocks)
  - JPY (Japan stocks)
  - SGD (Singapore stocks)

---

## 📦 Data Source

All stock data is retrieved via the Yahoo Finance API through the `yfinance` Python library.


