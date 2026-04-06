BigMart Sales Forecasting & Prediction

This project uses Machine Learning to predict the sales of various products across different BigMart outlets. 
By analyzing historical data, the model identifies which product and store features are the most important for driving revenue.

Project Review
The goal is to help BigMart understand the properties of products and stores that play a crucial role in increasing sales. 
This is a Regression problem where we predict the Item_Outlet_Sales.

Dataset
The dataset consists of 1559 products across 10 different stores.
Train.csv: Includes product details and actual sales (8,523 records).
Test.csv: Includes product details where we need to forecast sales (5,681 records).

Key Features Analyzed
Product Attributes: Item Weight, Fat Content, Visibility, Category, and MRP (Maximum Retail Price).
Store Attributes: Outlet Identifier, Establishment Year, Size, Location Type (Tier 1/2/3), and Outlet Type.

Tech Stack
Language: Python
Libraries: * Analysis: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Machine Learning: Scikit-learn (Linear Regression, Random Forest, XGBoost)

Project Workflow
Data Cleaning: Handled missing values in Item_Weight and Outlet_Size. Unified labels in Item_Fat_Content (e.g., merging 'LF' and 'low fat').
Exploratory Data Analysis (EDA): Discovered that Item_MRP has the strongest correlation with sales.
Feature Engineering: Calculated the age of outlets and simplified product categories.
Modeling: Built and compared multiple regression models to find the best fit.
Evaluation: Used RMSE (Root Mean Squared Error) to ensure the highest possible prediction accuracy.
