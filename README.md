# 🏠 Real Estate Price Analysis – Exploratory Data Analysis

## 📌 Overview
This project performs Exploratory Data Analysis (EDA) on a real estate dataset to understand the factors affecting house prices. Visualizations were created using Matplotlib and Seaborn to identify patterns, trends, and correlations between housing features and price per unit area.

---

## 📊 Dataset Description
The dataset includes:

- Transaction date  
- House age  
- Distance to the nearest MRT station  
- Number of convenience stores  
- Latitude  
- Longitude  
- House price of unit area  

The target variable is **House price of unit area**.

---

## 🎯 Objective
- Explore relationships between housing features and prices  
- Analyze distributions of key variables  
- Identify correlations between numerical features  
- Prepare data for future machine learning modeling  

---

## 🛠 Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 🔍 Methodology

### 1️⃣ Data Exploration
- Checked data types and summary statistics  
- Selected numeric columns for correlation analysis  

### 2️⃣ Data Visualization
- Scatter plots (Age vs Price, Distance vs Price)  
- Histograms (Price distribution)  
- Boxplots & Violin plots (Stores vs Price)  
- Pairplot (Feature relationships)  
- Correlation Heatmap  

### 3️⃣ Analysis
- Examined how distance to MRT affects price  
- Analyzed impact of convenience stores  
- Interpreted correlation matrix  

---

## 📈 Key Findings
- Property prices generally decrease as distance from MRT increases.  
- More nearby convenience stores tend to increase property value.  
- Some numerical features show moderate correlation with price.  

---

## ▶️ How to Run

1. Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn
