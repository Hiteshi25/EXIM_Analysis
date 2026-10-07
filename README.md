# 🌍 EXIM Trade Intelligence Dashboard

An interactive Streamlit dashboard for analyzing global import-export trade data, identifying trade trends, understanding country and commodity-wise performance, and generating data-driven business insights.

---

## 📌 Project Overview

This project analyzes international trade data to identify import-export patterns, country-wise trade performance, commodity trends, and overall trade behavior.

The project uses Python for data processing and analysis and Streamlit to build an interactive dashboard. Users can filter trade data by country, partner, and commodity and explore key trade indicators, trends, distributions, and predictions.

---

## 🚀 Features

- Interactive Trade Dashboard
- Country-wise Trade Analysis
- Partner-wise Trade Analysis
- Commodity-wise Trade Analysis
- Import & Export Analysis
- Trade Balance Calculation
- KPI Cards
- Monthly Trade Trends
- Seasonal Trade Analysis
- Country vs Partner Heatmap
- Top 5 Trading Partners/Countries
- Top 5 Commodities
- Interactive Filters
- Trade Value Prediction
- Downloadable Trade Data

---

## 🛠 Tech Stack

### Programming & Data Analysis
- Python
- Pandas
- NumPy

### Dashboard & Visualization
- Streamlit
- Plotly

### Machine Learning
- Scikit-learn
- Random Forest Regressor

### Development
- VS Code

---

## 📊 Dashboard Analysis

The dashboard provides multiple analytical sections:

### 1. Trade Overview
Displays:
- Total Trade
- Export Value
- Import Value
- Trade Balance
- Import vs Export Distribution

### 2. Trade Trends
Analyzes trade values over time using monthly trade data.

### 3. Country & Partner Analysis
Allows users to explore trade relationships between reporting countries and their trading partners.

### 4. Commodity Analysis
Provides commodity-level analysis with filters for:
- Country
- Partner
- Commodity

### 5. Top Trading Analysis
Identifies the top trading countries and partners based on trade value.

### 6. Prediction
Uses a Random Forest Regressor to generate predicted trade values based on a time index.

---

## 📂 Repository Structure

```text
EXIM_Analysis/
│
├── CODE.zip
├── DATA/
│   ├── trade_data_10k.csv
│   └── trade_data_100k.csv
│
├── exim dashboard.pdf
└── README.md
