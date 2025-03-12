# COVID-19 Data Analysis Project

## 📌 Overview
This project focuses on analyzing COVID-19 global data using **Pandas, Matplotlib, and Jupyter Notebook**. The goal is to **clean, process, and visualize** the dataset to identify trends and insights about the pandemic.

## 📊 Dataset
- **Source:** WHO COVID-19 Global Data
- **Format:** CSV
- **Columns Include:**
  - Date
  - Country
  - WHO Region
  - New Cases
  - New Deaths
  - Cumulative Cases
  - Cumulative Deaths

## 🛠 Tools & Libraries
- **Pandas** (for data cleaning & manipulation)
- **Matplotlib** (for visualization)
- **Jupyter Notebook** (for interactive analysis)

## 🔍 Steps Performed
1. **Importing the Dataset**
   - Loaded data using Pandas.
2. **Exploratory Data Analysis (EDA)**
   - Checked missing values, data types, and inconsistencies.
3. **Data Cleaning**
   - Filled missing values.
   - Clipped negative values to zero.
4. **Filtering Data**
   - Selected major countries for meaningful visualization.
   - Aggregated data by month for better trend analysis.
5. **Data Visualization**
   - Created line plots to track new cases & deaths over time.
   - Used boxplots to detect outliers.
   - Applied rolling averages to smoothen trends.

## 📈 Key Insights
- Major peaks in new cases and deaths observed during specific waves.
- Significant variation in trends across different countries.
- Data cleaning improved accuracy and readability of visualizations.

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install pandas matplotlib jupyter
   ```
2. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Run the notebook cells step by step.

## 📌 Future Improvements
- Add interactive visualizations using **Plotly**.
- Perform **sentiment analysis** on pandemic-related tweets.
- Use **machine learning** to predict future cases.

---
**Author:** Muhammad Omer Ansar 
**Date:** 2025-02-27

