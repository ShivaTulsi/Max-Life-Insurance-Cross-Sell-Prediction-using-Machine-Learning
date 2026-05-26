Project Overview

This project focuses on predicting customer interest in cross-selling insurance products for Max Life Insurance using Machine Learning techniques.

Insurance companies already have large customer bases for existing policies. The goal of this project is to identify customers who are more likely to purchase additional insurance products. This helps the company improve marketing efficiency, customer targeting, and business revenue.

The project includes:

Data Cleaning
Exploratory Data Analysis (EDA)
Feature Engineering
Data Preprocessing
Machine Learning Model Building
Model Evaluation
Business Insights
Problem Statement

An insurance company wants to improve its cross-selling strategy by predicting whether existing customers would be interested in buying another insurance product.

The objective is to build a classification model that predicts customer response based on:

Customer demographics
Vehicle details
Insurance history
Premium information
Customer engagement history

This prediction helps the business:

Reduce marketing cost
Improve conversion rate
Target the right customers
Increase revenue
Dataset Features
Feature	Description
id	Unique customer ID
Gender	Male/Female
Age	Customer age
Driving_License	Whether customer has driving license
Region_Code	Region information
Previously_Insured	Already insured or not
Vehicle_Age	Vehicle age category
Vehicle_Damage	Previous vehicle damage history
Annual_Premium	Yearly premium amount
Policy_Sales_Channel	Sales channel used
Vintage	Customer association duration
Response	Target variable
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Google Colab / Jupyter Notebook
Machine Learning Algorithms Used
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
K-Nearest Neighbors (KNN)
XGBoost (optional)
Project Workflow
1. Data Collection

Imported dataset and checked:

Shape
Data types
Missing values
Duplicate values
2. Data Preprocessing

Performed:

Null value handling
Label Encoding
Feature scaling
Outlier treatment
3. Exploratory Data Analysis

Analyzed:

Age distribution
Gender analysis
Vehicle damage trends
Insurance interest patterns
Premium insights
4. Feature Engineering

Created useful transformed features to improve prediction performance.

5. Model Building

Split data into:

Training data
Testing data

Trained multiple ML classification models.

6. Model Evaluation

Evaluated using:

Accuracy
Precision
Recall
F1 Score
Confusion Matrix

Example:

Accuracy: 71%
Recall: 89%
F1 Score: 43%
Business Insights

Key findings from the analysis:

Customers with previous vehicle damage are more likely to buy insurance.
Middle-aged customers showed higher interest.
Previously uninsured customers had greater conversion probability.
Certain sales channels generated better responses.
Conclusion

The project successfully predicts customer interest in insurance cross-selling using Machine Learning models.

The developed solution can help insurance companies:

Improve targeted marketing
Increase customer conversion
Optimize business strategy
Reduce unnecessary outreach
