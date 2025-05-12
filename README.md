# London Bike Sharing Data Analysis 🚲

This project explores and visualizes historical bike sharing data in London, powered by TfL Open Data.

## 📂 Dataset Overview

- **Source**: [Kaggle - London Bike Sharing Dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset/data)
- **Description**: The dataset contains daily historical records of bike shares in London along with associated weather conditions and metadata.

---

## 🧪 Tools & Libraries Used

- **Python** (in Jupyter Notebook)
- **Pandas** – data cleaning and preparation
- **Matplotlib & Seaborn** – data visualization
- **Microsoft Excel** - Interactive visualization dashboard

---

## 🔍 Analysis Highlights

The analysis focuses on how different variables affect bike-sharing usage:

- **Temporal patterns**: Year, month, and date trends 
- **Temperature effects**: Temperature vs. count of bike shares
- **Seasonal trends**: Aggregated analysis of bike usage by season

---

## 📊 Interactive Dashboard

An **Excel dashboard** is included as part of the project for quick and intuitive exploration. It provides filters and charts for the following:

- Year and month 
- Season
- Count of bike shares
- Real and feels-like temperature, categorised into:
  - Very cold: temp < 0 degree celsius
  - Cold: 0 <= temp < 10 degree celsius
  - Normal: 10 <= temp < 20 degree celsius
  - Hot: 20 <= temp < 30 degree celsius
  - Very hot: temp >= 30 degree celsius

![Screenshot 2025-05-12 at 9 05 51 PM](https://github.com/user-attachments/assets/eae15efa-2ac8-4cdc-adc2-f6d6c868056e)
 
---

## 📁 Files Included

- `bike_sharing_analysis.ipynb` – Python notebook for cleaning and visualizing the data
- `bike_dashboard.xlsx` – Interactive Excel dashboard
- `README.md` – Project description and overview

---

## ✅ Key Insights

- Bike usage peaks during warmer months and drops in colder seasons
- Bike usage peaks when temperature lies in the range (10 to 20 degree celsius), where it is not too hot nor too cold

---

## 📌 Future Work

- Analyze hourly trends instead of just daily aggregates
- Deploy visualizations to a web dashboard using Tableau


