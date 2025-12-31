**Project Title** - 
Bike Sharing Demand Prediction using Multiple Linear Regression

**Overview** - 
This project focuses on building a multiple linear regression model to predict daily demand for shared bikes in the US market. The analysis helps a bike-sharing company understand how various factors influence bike demand, enabling better business planning and revenue recovery after the Covid-19 pandemic.

**Business Problem** - 
BoomBikes, a US-based bike-sharing company, experienced a significant drop in revenue during the Covid-19 lockdown. To prepare for post-pandemic recovery, the company wants to understand the key drivers of bike demand so that it can optimize operations, pricing, and marketing strategies in advance.

**Objective** - 
Build a regression model to predict total daily bike rentals and identify the most significant variables influencing demand. Evaluate how well these variables explain variations in bike usage.

**Data Description** - 
The dataset contains daily bike rental information along with environmental and seasonal factors.
The target variable is cnt, representing total bike rentals including both casual and registered users.

**Key feature considerations include** - 
Categorical variables such as season and weathersit converted to categorical form
Year variable retained to capture demand growth trend
Casual and registered user counts excluded from predictors to avoid data leakage

**Approach** - 
Performed data cleaning and exploratory data analysis
Converted relevant numerical codes into categorical variables
Handled missing values and performed feature scaling
Split data into training and testing sets
Built a multiple linear regression model using statistically significant variables
Performed residual analysis to validate model assumptions
Evaluated model performance using R squared on the test dataset

**Key Insights** - 
Weather conditions and temperature strongly impact bike demand
Demand shows clear seasonal and yearly growth patterns
Working day and holiday variables significantly affect usage
The final model explains a high proportion of variance in bike demand

**Model Evaluation** - 
Model performance evaluated using R squared on the test dataset to measure predictive accuracy and generalization capability.

Tools and Technologies
Python
Pandas and NumPy
Matplotlib and Seaborn
Scikit learn
Statsmodels
Jupyter Notebook

**Deliverables** - 
One Jupyter Notebook containing data preparation, model building, predictions, and evaluation
Subjective questions answered separately in a PDF file

**Author** - Hritik Vijay Thorat
Data Analyst
Hritik Vijay Thorat
Data Analyst with interest in Regression Modeling and Business Analytics
