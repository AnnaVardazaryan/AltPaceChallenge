**Product Demand Prediction Project**

**Overview**
This repository contains a machine learning project aimed at predicting the sales (Units Sold) of products based on various features.
The dataset provides insights into the impact of product pricing, discounts, and store locations on sales volumes.

**Dataset**
The dataset comprises several features, each providing insights into different aspects of sales:
**1.ID**: A unique identifier for each sale record.
**2.Store ID**: An identifier representing different store locations.
**3.Total Price**: The final price of the product, accounting for any discounts.
**4.Base Price**: The original price of the product before any discounts.
**5.Units Sold**: The number of units of the product sold.

**Workflow**
**Data Loading**: Data was fetched directly from a provided URL and loaded into a DataFrame.
**Data Exploration**: Undertook preliminary data exploration to understand the nature and structure of the data.
**Data Cleaning**: Identified and treated missing values and checked for duplicates.
**Data Visualization**: Used histogram plots to understand the distribution of features. Additionally, scatter plots were utilized to analyze relationships between features.
**Feature Engineering**: Derived new features (like 'Discount_per_Unit') based on existing data.
**Modeling**: Trained both Linear Regression and Decision Tree Regression models.
**Evaluation**: Assessed model performance using metrics such as MAE, MSE, and R-squared.
**Conclusion**: Summarized key findings and determined the best performing model based on the evaluation metrics.

**Key Findings**
Initial data exploration revealed missing values which were treated accordingly.
Correlation analysis was conducted to determine the relationship between the features.
Histograms and scatter plots highlighted the distribution of features and their relationship with the target variable, "Units Sold."
Linear regression and decision tree regression models were trained to predict "Units Sold."
The decision tree regressor substantially outperformed the linear regression model in predicting "Units Sold."
