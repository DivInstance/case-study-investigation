# Cab Case Study Investigation

**By Divyaranjan Sahoo**

> **Background Context:** This project was assigned by the Nebula Space Organisation as part of their selection criteria for potential candidates. For this task, I conducted a case study to develop an investment strategy for cab companies, leveraging data analysis and statistical methods to generate actionable insights.


[![Project Notebook Preview](./assets/preview.png)](https://colab.research.google.com/drive/16tYZf6WxRYRQNSWQxT_dfQzLpCk2uYuj?usp=sharing)

#### Live Notebook

Explore the full **project analysis** in an interactive Google Colab notebook.  
📓 [Open Notebook](https://colab.research.google.com/drive/16tYZf6WxRYRQNSWQxT_dfQzLpCk2uYuj?usp=sharing)


## Project Overview
This project analyzes the US cab industry to identify investment opportunities for XYZ, a private equity firm. Using transaction, customer, and city-level data for two cab companies, the study derives actionable insights to guide investment decisions.

## Objective
- Analyze customer behavior, city-wise cab usage, and payment patterns.  
- Evaluate company performance and profitability.  
- Identify trends, preferences, and potential growth areas in the cab sector.  

## Datasets
- **Cab_Data.csv** – Cab transactions (Transaction ID, Date, Company, City, KM, Price, Cost).  
- **Customer_ID.csv** – Customer demographics (ID, Gender, Age, Income).  
- **Transaction_ID.csv** – Mapping of transactions to customers and payment modes.  
- **City.csv** – City-level data (Population, Users).  

## Methodology
- Data cleaning and missing value handling.  
- Merging datasets for unified analysis.  
- Statistical analysis, hypothesis testing, and visualization including:  
  - City-wise cab activity  
  - Gender-based preferences  
  - Seasonal trends  
  - Payment mode dependence  
  - Customer segmentation and margins  

## Key Insights
- **Top cities:** New York and Chicago have the highest number of trips.  
- **Cab preference:** Yellow cabs dominate overall; young users (18–24) prefer yellow cabs.  
- **Seasonality:** Yellow cabs are more popular during winter months.  
- **Profitability:** Margin tends to increase with the number of customers.  
- **Payment mode:** Users show company-dependent payment preferences.  

## Tools & Technologies
- **Python:** pandas, numpy, matplotlib, seaborn, scipy  
- **Jupyter Notebook** for analysis and visualization  

## Conclusion
The analysis provides actionable insights to support XYZ’s investment strategy in the US cab market, highlighting customer trends, city-wise cab activity, and profitability metrics.
