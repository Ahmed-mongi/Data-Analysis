# Data-Analysis
# Data Dashboards in Colab

This repository contains two interactive data analysis dashboards implemented in **Google Colab** using **Dash** and **Plotly**.

Both projects demonstrate **Exploratory Data Analysis (EDA)** with interactive visualizations, accessible directly from a Colab environment.

---

## 1. IMDb / Netflix Titles EDA Dashboard

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

## 2. Stock Market Analysis Dashboard

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

## Tech Stack
- **Python 3**  
- **Dash**  
- **Plotly Express**  
- **Dash Bootstrap Components**  
- **Pandas**  
- **yfinance**  
- **Colab Dash integration** for inline display  

---

## How to Run
1. Open the corresponding Colab notebook.  
2. Install dependencies:
   ```bash
   pip install dash dash-bootstrap-components plotly pandas yfinance


## Requirements
The dashboard needs the following Python packages:

- dash
- dash-bootstrap-components
- plotly
- pandas
- pyngrok

---

## Installation
Run this in your Colab notebook:

```bash
!pip install dash dash-bootstrap-components pyngrok plotly pandas


# 🚖 Uber Trips EDA Dashboard

[![Python](https://img.shields.io/badge/Python-3.12%2B-blue)](https://www.python.org/)  
[![Dash](https://img.shields.io/badge/Dash-Framework-orange)](https://dash.plotly.com/)  
[![Plotly](https://img.shields.io/badge/Plotly-Visualizations-lightblue)](https://plotly.com/python/)  

## 📌 Project Overview
This project provides an **interactive dashboard** to explore Uber trip data.  
It helps analyze **trip purposes, mileage trends, and categories (Business vs Personal)** using Python, Dash, and Plotly.  

---

## 📂 Dataset
The dataset is provided in **`Uber Data Analysis.zip`**.  

Main columns:
- **START_DATE / END_DATE** → Date & time of trips  
- **CATEGORY** → Trip type (Business / Personal)  
- **MILES** → Distance traveled  
- **PURPOSE** → Reason for the trip (Meeting, Meal, Errand, Unknown)  

---

## ⚙️ Features
✅ Filter trips by **Purpose** and **Category**  
✅ Interactive **charts & plots**  
✅ Pre-built **insights** section with key observations  

### Visualizations:
- 📊 **Purpose Distribution** → Most common trip reasons  
- 📈 **Mileage Trends** → Average miles by hour & purpose  
- 📦 **Box Plot** → Trip length comparison (Business vs Personal)  

---

## 🛠️ Tech Stack
- **Python 3.12+**  
- **Pandas** → Data wrangling  
- **Plotly Express** → Interactive charts  
- **Dash** → Dashboard framework  
- **Dash Bootstrap Components** → Styling (Cyborg theme)  

---

## 🚀 How to Run Locally

### 1️⃣ Clone this repo
```bash
git clone https://github.com/your-username/uber-dashboard.git
cd uber-dashboard

```bash
pip install pandas numpy matplotlib seaborn plotly dash dash-bootstrap-components
