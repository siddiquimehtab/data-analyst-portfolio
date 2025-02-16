# Sales Forecasting using Time Series Analysis

## 📌 Problem Statement
Understanding sales trends is crucial for businesses to optimize inventory, improve marketing strategies, and increase revenue. In this project, we analyze historical sales data and build a time series forecasting model to predict future sales trends.

## 📊 Data Source
The dataset used in this project is downloaded form kaggle contains customer shopping transaction records from various shopping malls. The key columns include:
* Invoice Number – Unique transaction ID
* Customer ID – Anonymized customer identifier
* Gender & Age – Customer demographics
* Category – Product category (Clothing, Shoes, Books, etc.)
* Invoice price – Purchase amount per unit
* Payment Method – Cash, Credit Card, or Debit Card
* Invoice Date – Transaction date
* Shopping Mall – The location where the purchase was made

## 🛠 Tools Used
* Python for data analysis and modeling
* Pandas for data manipulation
* Matplotlib & Seaborn for data visualization
* Prophet (by Meta) for time series forecasting
* Git & GitHub for version control and project sharing

## 🔎 Approach & Analysis

#### 1. Exploratory Data Analysis (EDA)
* Checked for missing values and handled them appropriately.
* Identified and removed duplicate records.
* Analyzed sales trends across time, categories, payment methods, and customer demographics.
* Visualized patterns using histograms, time series plots, and box plots.
#### 2. Data Preprocessing
* Converted invoice_date to datetime format.
* Aggregated sales data at the monthly level to prepare for forecasting.
#### 3. Time Series Forecasting using Prophet
* Used Facebook’s Prophet model, a robust tool for time series forecasting.
* Trained the model using historical monthly sales data.
* Generated future sales predictions with confidence intervals.
* Visualized trends, seasonality, and forecasted values.

## Key Insights & Business Recommendations
✔ Sales Trends: Identified high and low sales months, which can guide businesses in inventory planning and marketing campaigns.

✔ Seasonality Patterns: Observed repeating trends in certain months, indicating seasonal demand shifts that businesses can leverage.

✔ Forecasting Results: The Prophet model provided future sales predictions, helping businesses make data-driven decisions for upcoming months.

✔ Customer Preferences: Analyzed popular product categories and payment methods to optimize customer engagement strategies.
