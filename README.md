# CodeAlpha_Sales-Prediction-using-Python
# 📈 Sales Prediction & Marketing ROI Analysis

### **CodeAlpha Data Science Internship - Task 4**

## 📋 Project Overview
In the competitive landscape of marketing, understanding the Return on Investment (ROI) of advertising spend is crucial for profitability. This project involves building a **Predictive Machine Learning Model** to forecast sales revenue based on advertising budgets across multiple channels: **TV, Radio, and Newspaper**.

Acting as a Financial Data Analyst, the goal was not just to predict a number, but to provide actionable insights into which marketing channels drive the most value, enabling stakeholders to optimize their budget allocation.

## 🎯 Objectives
* **Revenue Forecasting:** Build a Linear Regression model to predict future sales with high accuracy.
* **ROI Analysis:** Identify the correlation between different ad channels and sales figures.
* **Budget Optimization:** Determine which media channels (TV vs. Radio vs. Newspaper) yield the highest return.
* **Model Evaluation:** Validate the model's performance using R-squared and RMSE metrics to ensure reliability for business decision-making.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:**
    * `Pandas`: Data manipulation and preprocessing.
    * `Scikit-Learn`: Building and training the Linear Regression model.
    * `Matplotlib` & `Seaborn`: Visualizing correlations and actual vs. predicted sales trends.
    * `NumPy`: Numerical operations and metric calculations.

## 📊 Key Findings & Insights

### 1. The Power of TV Advertising
Correlation analysis revealed that **TV advertising** has the strongest positive correlation (**0.78**) with sales. It is the primary driver of revenue in this dataset.

### 2. The "Newspaper" Trap
Newspaper advertising showed a very weak correlation (**0.23**) with sales.
* *Business Insight:* Continuing to invest heavily in newspaper ads may result in diminishing returns. Reallocating this budget to TV or Radio could improve overall ROI.

### 3. Predictive Accuracy
The Linear Regression model achieved an **R-Squared ($R^2$) score of ~0.90**.
* *Significance:* This means the model can explain **90% of the variance** in sales revenue based solely on advertising spend, making it a highly reliable tool for financial forecasting.

## 📂 Project Structure
```bash
├── data/
│   └── Advertising.csv            # Dataset containing Ad spend and Sales figures
├── visualizations/
│   ├── correlation_heatmap.png    # Heatmap showing Ad-Sales relationships
│   └── actual_vs_predicted.png    # Scatter plot of Model Performance
├── Sales_Prediction_Analysis.ipynb # Jupyter Notebook (Main Code)
└── README.md                      # Project Documentation
