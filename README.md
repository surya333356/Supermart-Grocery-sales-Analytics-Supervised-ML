# Supermart-Grocery-sales-Analytics

![image](https://github.com/user-attachments/assets/f5abc010-40ef-4227-a75b-a1b8b00132e5)



# Project Type - EDA/Regression

# Project Summary -
This project aimed to analyze grocery sales data to uncover trends and predict future sales. Key tasks included cleaning the dataset, exploring sales patterns across regions and products, and identifying factors influencing profits.

Machine learning models like Linear Regression and Random Forest were applied for sales forecasting.

This project provided valuable insights into sales trends and customer behavior while laying the foundation for predictive modeling. Though the model accuracy needs improvement, the analysis offers actionable insights for optimizing sales and inventory management.

# Problem Statement-
The goal of the Supermart Grocery Sales Analytics project is to analyze historical grocery sales data to identify trends, patterns, and key drivers of sales performance. Additionally, the objective is to build a machine learning model to accurately predict future sales, enabling the business to optimize inventory management, pricing strategies, and promotional campaigns.

The project aims to address challenges such as:

Identifying underperforming products and regions.
Understanding the impact of factors like discounts, seasons, and customer preferences on sales.
Improving forecasting accuracy to minimize stock shortages and overstocking.

# Dataset-
The dataset includes 11 columns:

Order ID: Unique identifier for each order.
Customer Name: Name of the customer who placed the order.
Category: Main category of the purchased product.
Sub Category: Sub-category of the product.
City: City where the order was delivered.
Order Date: Date when the order was placed.
Region: Region of the city.
Sales: Total sales amount for the order.
Discount: Discount applied on the order.
Profit: Profit made from the order.
State: State where the order was delivered.

# Project Objectives-
# Data Cleaning and Preparation-
Convert date columns to datetime format.
Handle missing values and duplicates.
Extract and engineer features such as year and month from the date.

# Exploratory Data Analysis (EDA)-
Analyze sales distribution across different categories and sub-categories.

Identify the top-selling products and categories.
Examine monthly and yearly sales trends.
Explore the relationship between profit and discount.

# Predictive Modeling-
Build a linear regression model to predict sales based on features such as category, sub-category, city, region, state, discount, month, and year.
Evaluate model performance using metrics like Mean Squared Error (MSE) and R-squared.
The XGBoost model has performed exceptionally well on our dataset.

# Results

# Key Findings-
We have check the sales analysis that it has not outliers and it is normally distributed.
We have checked the profit distribution that it has outlier present and chart is right skewed.
We have checked from  chart that Eggs, Meat & Fish category shown max sales and oil and masala min sale.
Sales seem to be stronger in Q4 (October to December), with October, November, and December showing consistently high sales.Q1 (January to March) appears to have lower sales, especially in January and February.
We can see that from graph year vs sales, sales is increasing linearly. in 2015 sales min and in 2018 sales is max.
We can see from the  graph that Kanyakumari shows max sales.
From the graph we can see clearly that in West zone sale is maximum and North zone shows min sale.
Profit and sales are highly correlated.

# Model Performance-
That's an excellent result! With an R² score of 0.999 and a very low RMSE (~14.12), the XGBoost model has performed exceptionally well on our dataset. This indicates that the model has captured the patterns in the data accurately, and our sales predictions are now highly reliable.


# Conclusion-
We applied 3 models like-Linear regression,Random Forest,Gradient boosting in starting with hyperparameter optimization techniques (i.e., GridSearch CV, RandomSearch CV) but couldn't find best accuracy.

The tuned Random Forest model slightly improved the performance, but the R² score is still low (0.35), and the RMSE remains high. This suggests that the features in the dataset may not fully capture the variability of the target variable (Sales), or the relationships are highly non-linear and complex.

Create features that might capture hidden patterns, such as:

Order Month/Year extracted from the Order Date. Profit-to-Sales Ratio: A new feature showing the proportion of profit to sales. Discount Categories: Categorize discounts into bins (e.g., low, medium, high).

That's an excellent result! With an R² score of 0.999 and a very low RMSE (~14.12), the XGBoost model has performed exceptionally well on our dataset. This indicates that the model has captured the patterns in the data accurately, and our sales predictions are now highly reliable.

# Hurrah! You have successfully completed your Machine Learning Capstone Project !!!
