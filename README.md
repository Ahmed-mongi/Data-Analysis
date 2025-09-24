# 📊 Data Dashboards in Colab

This repository contains three interactive data analysis dashboards implemented in **Google Colab** using **Dash** and **Plotly**.

Each project demonstrates **Exploratory Data Analysis (EDA)** with interactive visualizations, accessible directly from a Colab environment or by running locally.

---

## 1. 🎬 IMDb / Netflix Titles EDA Dashboard

### Dataset
- Source: [Netflix Titles dataset on Kaggle](https://www.kaggle.com/shivamb/netflix-shows)  
- Contains metadata about Netflix movies and TV shows including type, release year, country, date added, and rating.

### Features
- Movies vs TV Shows distribution  
- Additions by month (overall trends)  
- Movies added per month (seasonality analysis)  
- Heatmap of movies added by **month vs year** (seasonal patterns over time)  
- Top 10 producing countries for movies  
- Integration-ready with IMDb ratings file for:
  - Top rated movies  
  - Top producing countries among top rated titles  

### Usage
Run the notebook in Colab. The dashboard is hosted with **Colab integration for Dash** and displays inline.

---

## 2. 📈 Stock Market Analysis Dashboard

### Dataset
- Stock price data retrieved via **Yahoo Finance API** (`yfinance`)  
- Contains open, close, high, low prices, and trading volume.

### Features
- Interactive stock price trends with range selectors  
- Daily returns analysis  
- Moving averages (e.g., 20-day, 50-day)  
- Volatility visualization  
- Comparison of multiple stocks in one view  

### Usage
Run the notebook in Colab. Input stock ticker symbols to visualize trends and metrics.

---

## 3. 🚖 Uber Trips EDA Dashboard

### Dataset
- Provided in **`Uber Data Analysis.zip`**  
- Contains Uber trip logs including date, category, miles, and trip purpose.

### Features
✅ Filter trips by **Purpose** and **Category**  
✅ Interactive **charts & plots**  
✅ Pre-built **insights section**  

#### Visualizations:
- 📊 **Purpose Distribution** → Most common trip reasons  
- 📈 **Mileage Trends** → Average miles by hour & purpose  
- 📦 **Box Plot** → Trip length comparison (Business vs Personal)  

### Example Insights
- Business trips (Meetings, Meals) dominate overall usage.  
- Mileage is higher during **commuting hours** for business trips.  
- Business trips are **longer & more variable**, while personal trips are **shorter & consistent**.  

### Usage
Run `uber_dashboard.py` locally or inside Colab with Colab-Dash integration.  
Default local URL: 👉 `http://127.0.0.1:8050/`

---

## 🛠️ Tech Stack
- **Python 3.12+**  
- **Dash**  
- **Plotly Express**  
- **Dash Bootstrap Components**  
- **Pandas**  
- **yfinance** (for Stock Market Dashboard)  
- **Colab Dash integration** for inline display  

---

## 🚀 How to Run
1. Open the corresponding Colab notebook or run locally.  
2. Install dependencies:
   ```bash
   pip install dash dash-bootstrap-components plotly pandas yfinance
