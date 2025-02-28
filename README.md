# DAI-101-Assignment-1

### **Project Title:**
DAI Assignment 1 - Startup Growth Investment Dataset Analysis

### **Author:**
Aditya - 23112006

### **Project Overview:**
This project analyzes startup growth and investment trends using a dataset containing details about funding rounds, investment amounts, valuations, number of investors, industries, countries, and growth rates. The goal is to identify key factors driving startup success and investment patterns for better decision-making.

### **Dataset:**
The dataset consists of various attributes of Ford cars, including:
- Numerical Features: Funding rounds, Valuation, Investment amount, Growth rate.
- Categorical Features: Industry, Country, Year founded.

### **Workflow:**

#### **Data Cleaning:**
- Handled missing or inconsistent values in the dataset.
- Removed irrelevant columns that don't contribute to the analysis.

#### **Univariate Analysis:**
- Distribution plots for numerical columns for investment amount, valuation, growth rate.
- Count plots for categorical columns for industry, country, year founded.

#### **Outlier Detection & Handling:**
- Boxplots have been generated for numerical columns to visualize outliers.
- Extreme outliers were removed using the Z-score method (Threshold = 3).

#### **Bivariate Analysis:**
- Correlation Heatmap to visualize relationships between numerical variables.
- Pairplots to explore feature interactions.
- Boxplots to show distributions across categories.

#### **Additional Insights:**
- Investment Trends Over the Years 
- Top 10 Most Funded Industries
- Country-wise Investment Distribution
- Growth Rate vs. Investment Amount 
- Number of Investors vs. Startup Valuation
- Feature Engineering: Investment per Investor.
  
### **Results:**
The project provides comprehensive insights into startup investment trends, funding patterns, and growth metrics. Analysis of funding rounds and investment amounts over the years highlights how startup funding has evolved.

### **Dependencies:**
- numpy
- pandas
- matplotlib
- scipy
- seaborn
