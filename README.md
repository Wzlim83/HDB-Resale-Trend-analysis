# 🏠 HDB Resale Trend Analysis

A data analysis project examining historical HDB resale flat transactions in Singapore. This project aims to uncover pricing trends and provide visual insights to help users better understand the dynamics of the HDB resale market.

## 📌 Project Overview

This analysis focuses on:
- Average resale value of flats across towns
- Variations in resale value across selected towns
- The impact of remaining lease and floor area on resale prices

## 📂 Data Source

- HDB Resale Flat Prices dataset (2017–2020), provided by training provider

## 🛠️ Features

- ✅ Data cleaning and preprocessing
- 📈 Analysis by town, flat type, lease remaining, and floor area
- 📊 Static visualizations for key insights
- 📍 Geospatial mapping using Folium

## 🧪 Tech Stack

- Python (Pandas)
- Visualization: Matplotlib
- Mapping: Folium, HeatMap plugin, MarkerCluster plugin
- Jupyter Notebooks

## 📉 Sample Visualizations

### 🔹 Average Resale Value vs Lease Years Remaining

<img width="617" height="442" alt="Lease vs Resale Price" src="https://github.com/user-attachments/assets/6466b38f-e523-4bfa-b44a-0a30d86234d0" />

**Insight:** Resale prices tend to be higher when more lease years remain. Prices peak around the Minimum Occupation Period (MOP) of 5 years.

---

### 🔹 Floor Area vs Resale Price

<img width="576" height="444" alt="Floor Area vs Price" src="https://github.com/user-attachments/assets/37dc935c-2608-48d3-9ab6-13bb524743ef" />

**Insight:** A clear positive relationship exists — larger floor areas generally command higher resale prices.

---

### 🔹 4-Room Flat Resale Prices by Town (2017–2020)

<img width="620" height="429" alt="Towns Comparison" src="https://github.com/user-attachments/assets/5d86b575-8467-4d64-92a4-50ce9131992d" />

**Insight:** Woodlands consistently shows lower resale values, making it a potential option for budget-conscious buyers. Tampines and Punggol show similar trends, suggesting buyers may need to consider non-price factors like amenities or transport access.

---

> _Note: This notebook was completed as part of a guided project provided by a training provider. While the structure was provided, all analysis and commentary are my own._

