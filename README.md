# Max Life Insurance Cross-Sell Prediction using Machine Learning

## Project Overview

This project focuses on predicting whether existing insurance customers are likely to purchase additional insurance products using Machine Learning techniques.

Insurance companies already have a large customer base for existing policies. The goal of this project is to identify customers who are more likely to buy another insurance product. This helps improve marketing efficiency, customer targeting, and overall business revenue.

The project includes:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing
- Machine Learning Model Building
- Model Evaluation
- Business Insights

---

# Problem Statement

An insurance company wants to improve its cross-selling strategy by predicting whether existing customers would be interested in buying additional insurance products.

The objective is to build a classification model that predicts customer response based on:
- Customer demographics
- Vehicle details
- Insurance history
- Premium information
- Customer engagement history

This prediction helps the business:
- Reduce marketing costs
- Improve conversion rates
- Target the right customers
- Increase business revenue

---

# Dataset Features

| Feature | Description |
|---|---|
| id | Unique customer ID |
| Gender | Male/Female |
| Age | Customer age |
| Driving_License | Whether customer has driving license |
| Region_Code | Region information |
| Previously_Insured | Already insured or not |
| Vehicle_Age | Vehicle age category |
| Vehicle_Damage | Previous vehicle damage history |
| Annual_Premium | Yearly premium amount |
| Policy_Sales_Channel | Sales channel used |
| Vintage | Customer association duration |
| Response | Target variable |

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

---

# Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.model_selection import train_test_split
from sklearn.preprocessing import LabelEncoder, StandardScaler
from sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score
```

---

# Machine Learning Algorithms Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- XGBoost (Optional)

---

# Project Workflow

## 1. Data Collection

Imported the dataset and checked:
- Dataset shape
- Data types
- Missing values
- Duplicate values

---

## 2. Data Preprocessing

Performed:
- Null value handling
- Label Encoding
- Feature scaling
- Outlier treatment
- Data transformation

---

## 3. Exploratory Data Analysis (EDA)

Analyzed:
- Age distribution
- Gender distribution
- Premium trends
- Vehicle damage patterns
- Customer response analysis

Visualization techniques used:
- Count plots
- Histograms
- Heatmaps
- Boxplots

---

## 4. Feature Engineering

Created and transformed features to improve model performance and prediction accuracy.

---

## 5. Model Building

Split the data into:
- Training dataset
- Testing dataset

Trained multiple Machine Learning classification models.

Example:

```python
X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.2, random_state=42
)
```

---

## 6. Model Evaluation

Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Sample Results:

| Metric | Score |
|---|---|
| Accuracy | 71% |
| Precision | 28% |
| Recall | 89% |
| F1 Score | 43% |

---

# Key Insights

- Customers with previous vehicle damage were more likely to buy insurance.
- Middle-aged customers showed higher interest in cross-selling products.
- Previously uninsured customers had greater conversion probability.
- Certain sales channels performed better than others.

---

# Key Features

- End-to-end Machine Learning pipeline
- Real-world business use case
- Data preprocessing and cleaning
- Multiple ML model comparison
- Performance evaluation metrics
- Business-driven insights

---

# Folder Structure

```bash
Max-Life-Cross-Sell-Prediction/
│
├── data/
├── notebooks/
├── images/
├── models/
├── outputs/
├── README.md
├── requirements.txt
└── Max_Life_Cross_Sell.ipynb
```

---

# requirements.txt

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
```

---

# Business Applications

This project can help insurance companies:
- Improve targeted marketing campaigns
- Increase customer conversion rates
- Reduce unnecessary outreach
- Improve customer retention
- Optimize business strategy

---

# Future Enhancements

- Hyperparameter tuning
- Model deployment using Flask or Streamlit
- Real-time prediction system
- Deep learning implementation
- Cloud deployment

---

# Conclusion

This project successfully predicts customer interest in insurance cross-selling using Machine Learning classification algorithms. The developed solution helps businesses make data-driven decisions and improve customer targeting strategies.

---

# Resume Project Description

### Max Life Insurance Cross-Sell Prediction

Developed a Machine Learning classification model to predict customer interest in additional insurance products using customer demographics, insurance history, and behavioral data. Performed EDA, feature engineering, preprocessing, and model evaluation using Python and Scikit-learn.

---

# GitHub Topics / Tags

```text
machine-learning
data-science
insurance-analytics
classification
cross-sell-prediction
python
scikit-learn
eda
random-forest
insurance-project
```
