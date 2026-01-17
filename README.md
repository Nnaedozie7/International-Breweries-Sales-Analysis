# International Breweries Sales Analysis

This project presents an exploratory data analysis (EDA) of **International Breweries sales data** across multiple African countries.  
The analysis focuses on **sales performance, profitability, quantity sold, and brand comparison** using Python data analysis libraries.

---

## 📌 Project Overview

The goal of this project is to analyze sales records from International Breweries in order to:
- Understand sales and profit distribution across brands
- Compare beer and malt product performance
- Identify high-performing countries, years, and sales representatives
- Extract actionable business insights from historical sales data

The dataset contains **1,047 records** covering multiple brands, countries, regions, and years.

---

## 📊 Dataset Description

**Key Columns:**
- `SALES_ID` – Unique transaction identifier  
- `SALES_REP` – Sales representative  
- `EMAILS` – Sales rep email  
- `BRANDS` – Product brand  
- `PLANT_COST` – Production cost per unit  
- `UNIT_PRICE` – Selling price per unit  
- `QUANTITY` – Units sold  
- `COST` – Total cost  
- `PROFIT` – Total profit  
- `COUNTRIES` – Country of sale  
- `REGION` – Sales region  
- `MONTHS` – Month of transaction  
- `YEARS` – Year of transaction  

**Countries Covered:**
- Ghana  
- Nigeria  
- Togo  
- Benin  
- Senegal  

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical plotting

---

## 🔍 Analysis Performed

### General Analysis
- Dataset inspection (`info`, `unique`, `min`, `max`)
- Quantity and profit distribution
- Brand-wise sales and profit comparison

### Yearly Analysis
- Sales performance for:
  - **2017**
  - **2018**
  - **2019**
- Identification of:
  - Highest and lowest profit transactions
  - Maximum and minimum quantities sold per year

### Product Category Analysis
- **Beer brands:** Trophy, Budweiser, Castle Lite, Eagle Lager, Hero  
- **Malt brands:** Beta Malt, Grand Malt  
- Comparative analysis of:
  - Profit
  - Quantity sold
  - Cost efficiency

---

## 📈 Visualizations

The project includes multiple bar charts to visualize:
- Profit by brand
- Quantity sold by brand
- Comparison between beer and malt products
- Overall brand performance across the dataset

All visualizations were created using **Seaborn bar plots** for clarity and insight.

---

## 📂 Project Structure

```text
international-breweries-analysis/
│── data/
│   └── International_Breweries.csv
│── notebooks/
│   └── analysis.ipynb
│── visuals/
│   └── charts.png
│── README.md
