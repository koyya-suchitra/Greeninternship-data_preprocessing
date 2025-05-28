# 🌱 1M1B GREEN Internship - Part 1  
## Data Acquisition: Wind Data of Kakinada - Data Cleaning & Preprocessing

This repository contains the **first phase** of our data science work under the **1M1B GREEN Internship**, focusing on acquiring, cleaning, and preparing **wind and weather data for Kakinada**.

We’ve performed **data cleaning and preprocessing** using Python libraries like **Pandas**, **NumPy**, **Seaborn**, and **Matplotlib** in **VS Code (Jupyter Notebook)** to ensure the dataset is ready for further analysis and modeling.

---

## 📁 Dataset Source

The raw dataset was sourced from [meteostat.net](https://meteostat.net/en/place/in/kakinada?s=43189&t=2024-01-01/2025-05-27), covering the period from **January 1, 2024 to May 27, 2025**.

---

## 🧠 Team Members

- **Koyya Suchitra**  
  [GitHub](https://github.com/koyya-suchitra) | [LinkedIn](https://www.linkedin.com/in/suchitra-koyya-605a242b5/)

- **Jogi Rohith Kumar**  
  [GitHub](https://github.com/JogiRohithKumar) | [LinkedIn](https://www.linkedin.com/in/rohith-kumar-jogi-747a782b8/)

Team Size: **2**

---

## ✅ Workflow Steps

| Step                           | Description                                           |
|-------------------------------|-------------------------------------------------------|
| 📦 Import Libraries            | Loaded Pandas, NumPy, Seaborn, Matplotlib             |
| 📄 Load Dataset               | Read CSV and displayed the first few rows            |
| 🧼 Clean Column Names         | Renamed inconsistent column headers                  |
| 📆 Convert Date Format        | Converted 'Date' column to datetime object           |
| 🔍 Null Values Check          | Checked and handled missing values                   |
| 📉 Drop Irrelevant Columns    | Dropped columns with excessive null values           |
| ✨ Fill Missing Data          | Replaced NaNs using mean/median                      |
| 📊 Outlier Detection          | Used boxplots and IQR method to remove outliers      |
| 💾 Save Cleaned Data          | Exported cleaned data as `kakinada_cleaned_wind_data.csv` |

---

## 📊 Exploratory Data Analysis (EDA)

### 🔥 Correlation Heatmap  
Visualized correlations between numerical features to spot patterns.

### 📈 Time Series Plot  
Plotted trends of average wind speed and temperature over time.

---

## 🛠️ Tech Stack

- **Language**: Python 3  
- **Libraries Used**:
  - `pandas`
  - `numpy`
  - `seaborn`
  - `matplotlib`
- **IDE**: Visual Studio Code with Jupyter Notebook Extension

---

## 📂 Project Structure
📁 kakinada-wind-analysis/
├── kakinada_wind_data.csv # Raw dataset
├── kakinada_cleaned_wind_data.csv # Cleaned dataset
├── wind_data_cleaning_eda.ipynb # Jupyter Notebook with code
└── README.md # Project documentation

---

## 📌 Notes

This project focuses exclusively on **data cleaning and initial exploration**. Future phases will involve model-building, forecasting, and sustainability-driven decision insights for the Kakinada region.

---

> 🚀 Stay tuned for **Part 2**, where we analyze trends and forecast wind energy potential.


