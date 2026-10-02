🌾 Global Agricultural Trade & Risk Analytics Dashboard

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Tableau](https://img.shields.io/badge/Tableau-Interactive%20Dashboard-orange)
![License](https://img.shields.io/badge/License-MIT-green)

An end-to-end Business Intelligence and Data Analytics project evaluating 10+ years of global agricultural trade flows, macroeconomic indicators, commodity price volatility, and supply chain vulnerabilities.

```

---

## 📌 Executive Summary

This project simulates a real-world BI & Strategy consultancy brief for a Global Trade Directorate. Using trade volume data across key commodities (**Wheat, Maize, Soybeans, Rice**), this analysis identifies high-risk import-dependent nations, evaluates the impact of price volatility on supply chains, and provides 2-year predictive trade forecasts.

🔗 **Interactive Tableau Dashboard:** [View Live Dashboard on Tableau Public](https://www.google.com/search?q=https%3A%2F%2Fpublic.tableau.com%2F)

---

## 🎯 Key Business & Strategy Questions Solved

1. **Supply Deficit Identification:** Which nations face severe net trade deficits and critical import dependency?
2. **Price Volatility Analysis:** How significantly does price volatility correlate with export supply disruptions?
3. **Multi-Year Forecasting:** What are the projected trade volume and pricing trends for 2026–2027?
4. **Policy Recommendations:** What strategic trade interventions can mitigate localized food security risks?

---

## 🛠️ Tech Stack & Methodologies

* **Data Processing & ETL:** Python, Pandas, NumPy
* **Data Visualization:** Tableau Desktop, Tableau Public
* **Executive Storytelling:** Markdown, Executive Briefing Memos (PDF)
* **Analytical Techniques:** Time Series Forecasting, Correlation Analysis, Geographic Trade Mapping, Descriptive & Inferential Statistics

---

## 📂 Repository Structure

```text
global-agri-trade-analytics/
│
├── data/
│   └── global_agricultural_trade.csv      # Raw & processed trade dataset
│
├── notebooks/
│   └── 01_data_preprocessing.ipynb        # Data extraction, cleaning, & formatting
│
├── reports/
│   └── Executive_Briefing_Memo.pdf        # 1-page executive summary for leadership
│
├── visuals/
│   ├── dashboard_overview.png             # Full Tableau dashboard preview
│   ├── time_series_forecast.png           # Commodity price forecast chart
│   └── geographic_trade_map.png           # Global net trade balance map
│
├── .gitignore
├── LICENSE
└── README.md

```

---

## 📊 Key Insights & Visual Deliverables

### 1. Interactive Business Intelligence Dashboard

* *Features:* Real-time filtering by commodity, dynamic KPI metrics, interactive geographic filtering, and price volatility scatter plots.

### 2. Multi-Year Commodity Price & Volume Forecast

* *Insight:* Grain prices showed a continuous upward trend over the last decade. Predictive modeling highlights ongoing market tightness for Wheat and Maize through 2027.

### 3. Regional Net Trade Surplus & Deficit Map

* *Insight:* Diverging color scales clearly differentiate key global exporter powerhouses (USA, Brazil, Argentina) from import-reliant regions in North Africa and East Asia.

---

## 📝 Executive Briefing Memo Summary

> **Headline Finding:** Global grain trade experienced a **28% increase in price volatility** over the last decade. Import-dependent regions face elevated inflationary risk without strategic reserve buffers.

### Core Strategic Recommendations:

1. **Diversify Import Corridors:** Establish bilateral trade agreements with secondary emerging exporters to reduce single-region dependency.
2. **Strategic Reserve Buffers:** Maintain a minimum 90-day physical reserve buffer for high-vulnerability grains.
3. **Futures Hedging Mechanisms:** Deploy financial hedging strategies to shield national import budgets from sudden spot market spikes.

---

## 🚀 How to Run locally

### 1. Clone the Repository

```bash
git clone [https://github.com/YOUR_USERNAME/global-agri-trade-analytics.git](https://github.com/YOUR_USERNAME/global-agri-trade-analytics.git)
cd global-agri-trade-analytics

```

### 2. Install Dependencies & Generate Data

```bash
pip install pandas numpy notebook
python notebooks/01_data_preprocessing.py

```

### 3. Open Tableau

* Launch Tableau Desktop or Tableau Public.
* Connect to `data/global_agricultural_trade.csv`.
* Load the saved `.twbx` workbook from the `visuals/` directory.

---

👤 Author & Contact
