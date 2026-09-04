# Rossmann Store Sales Forecasting

A machine learning and time-series analysis project designed to analyze and predict daily store sales across various retail locations using Python, Pandas, Seaborn, and Prophet/FBProphet.

## 📌 Overview

Retail stores often face challenges in accurately forecasting daily sales due to seasonal variations, promotional activities, regional holidays, and local competition. This repository contains data exploration, exploratory data analysis (EDA), and time-series modeling using historical sales data to predict future store performance.

## 📊 Dataset

The project utilizes two main datasets:
- **`train.csv`**: Daily historical sales data including features like `Store`, `DayOfWeek`, `Date`, `Sales`, `Customers`, `Open`, `Promo`, `StateHoliday`, and `SchoolHoliday`.
- **`store.csv`**: Supplemental information about individual stores, such as `StoreType`, `Assortment`, `CompetitionDistance`, `CompetitionOpenSince[Month/Year]`, and `Promo2` details.

## 🛠️ Tech Stack & Dependencies

- **Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`
- **Time-Series / Machine Learning:** `FBProphet` / `prophet`
- **Environment:** Jupyter Notebook / Anaconda

## 🚀 Key Features & Workflow

1. **Exploratory Data Analysis (EDA):**
   - Summary statistics and missing value detection across store and sales data.
   - Analysis of sales patterns influenced by promotions (`Promo`), school holidays, and state holidays.
   - Visualizing missing data distributions using heatmaps.

2. **Data Preprocessing & Feature Engineering:**
   - Handling missing values in store competition distances and promotional intervals.
   - Merging daily sales records with store metadata.
   - Date feature extraction and conversion to datetime formats.

3. **Time-Series Forecasting:**
   - Building store-level sales forecasting models using Prophet.
   - Analyzing holiday trends and promotional impacts on sales performance.

## ⚙️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/rossmann-sales-forecasting.git](https://github.com/your-username/rossmann-sales-forecasting.git)
   cd rossmann-sales-forecasting
