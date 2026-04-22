# BigMart Sales - Exploratory Data Analysis (EDA)

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the BigMart Sales dataset to understand the key factors affecting product sales across different outlets.

The analysis focuses on:

- Data cleaning & preprocessing
- Univariate analysis
- Bivariate analysis
- Feature relationships affecting sales
- Visualization using subplots for comparative insights

---

## Dataset Information

The dataset contains historical sales data for products sold across multiple BigMart outlets, including:

- Product details (MRP, weight, visibility, etc.)
- Outlet information (type, size, location)
- Sales data (target variable: `Item_Outlet_Sales`)

---

## Data Cleaning & Preprocessing

Performed essential preprocessing steps:

- Handled missing values in categorical and numerical columns
- Replaced null values using mode/median strategies
- Standardized inconsistent categorical values
- Removed or treated duplicate/invalid entries
- Encoded categorical variables for analysis

---

## Exploratory Data Analysis

### Univariate Analysis

- Distribution of numerical features (MRP, Sales, Item Visibility)
- Frequency analysis of categorical variables (Outlet Type, Item Type, etc.)
- Sales distribution using histograms

**Key Insight:**

- Sales data is slightly right-skewed, indicating most products have lower to moderate sales.

---

### Bivariate Analysis

Analyzed relationships between features and **Item_Outlet_Sales**:

#### Key Factors Affecting Sales:

- **MRP (Maximum Retail Price)** → Higher MRP generally leads to higher sales
- **Outlet Type** → Supermarket Type outlets perform better than grocery stores
- **Outlet Location Type** → Tier 1/Urban locations show stronger sales
- **Item Type** → Some product categories consistently outperform others
- **Item Visibility** → Lower visibility sometimes correlates with higher sales (unexpected pattern)

---

## Visualizations

Used Matplotlib for insights:

- Histograms for distribution analysis
- Bar plots for categorical comparisons
- Box plots for outlier detection
- Subplots dashboard to compare multiple features in a single view

### Subplots Dashboard

Combined multiple graphs to compare:

- MRP vs Sales
- Outlet Type vs Sales
- Location vs Sales
- Item Type vs Sales

---

## Key Insights

- Supermarket outlets generate significantly higher sales than grocery outlets
- Medium visibility products perform better than highly visible ones in some cases
- Tier 3 outlets show lower performance compared to Tier 1 and Tier 2
- Product pricing (MRP) is a strong predictor of sales

---

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib

---

## Future Improvements

- Apply Seaborn for advanced visualization
- Build predictive ML model for sales forecasting
- Feature engineering for better accuracy
- Dashboard using Power BI / Streamlit

---
