# 📊 Household Demographics Analysis Project

## 📁 Project Overview

This project presents a comprehensive analysis of household demographic data using Python. The goal is to derive insights from a real-world-like dataset by applying various statistical techniques such as central tendency, dispersion, data visualization, and distribution analysis.

---

## 📂 Dataset: `Household_Data.xlsx`

This Excel file contains detailed records of households, with the following columns:

- `Household_ID`: Unique identifier for each household
- `Age_of_Household_Head`: Age of the head of the household
- `Household_Income`: Monthly income of the household
- `Education_Level`: Education qualification of the household head
- `Family_Size`: Number of family members
- `Owns_House`: Whether the household owns their house (Yes/No)
- `Urban_Rural`: Type of area (Urban or Rural)

The dataset serves as the foundation for all analysis done in the notebook and summarized in the final report.

---

## 📒 Jupyter Notebook: `Household demographics.ipynb`

This notebook performs the following steps:

1. **Data Loading & Inspection**  
   - Uses `pandas` to read and preview the dataset  
   - Identifies types of data: categorical vs numerical

2. **Central Tendency (Manual Calculation)**  
   - Calculates **Mean**, **Median**, and **Mode** for Age and Income  
   - All calculations are done manually (without `.mean()`, `.median()`, `.mode()`)

3. **Dispersion Measures**  
   - Range, Variance, Standard Deviation, and Interquartile Range (IQR) for Income

4. **Distribution Analysis**  
   - Histogram of Income  
   - Skewness and Kurtosis  
   - Fitting of Gaussian (normal distribution) curve

5. **Data Categorization and Visualization**  
   - KDE and histogram plots  
   - Family size by education level  
   - Age vs Income distribution plots
---