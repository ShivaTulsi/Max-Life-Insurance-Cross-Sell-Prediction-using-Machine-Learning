# Max Life Insurance Cross-Sell Prediction using Machine Learning

## Project Overview

This project focuses on predicting whether existing insurance customers are likely to purchase additional insurance products using Machine Learning techniques.

The main objective is to help insurance companies identify potential customers for cross-selling campaigns based on customer demographics, vehicle information, insurance history, and behavioral patterns.

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

Insurance companies aim to improve their marketing strategy by predicting whether existing customers are interested in purchasing additional insurance products.

The goal of this project is to build a Machine Learning classification model that predicts customer response for cross-selling opportunities.

This helps businesses:
- Improve targeted marketing
- Increase conversion rates
- Reduce unnecessary outreach
- Enhance customer engagement
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

from sklearn.linear_model import LogisticRegression
from sklearn.ensemble import RandomForestClassifier
from sklearn.ensemble import GradientBoostingClassifier
```

---

# Machine Learning Models Used

The following Machine Learning classification models were implemented in this project:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

---

# Project Workflow

## 1. Data Collection

Imported the dataset and analyzed:
- Dataset shape
- Data types
- Missing values
- Duplicate records

---

## 2. Data Preprocessing

Performed:
- Null value handling
- Label Encoding
- Feature scaling
- Data transformation
- Outlier handling

---

## 3. Exploratory Data Analysis (EDA)

Analyzed:
- Customer age distribution
- Gender analysis
- Premium distribution
- Vehicle damage patterns
- Customer response trends

Visualization techniques used:
- Histograms
- Count plots
- Box plots
- Heatmaps

---

## 4. Feature Engineering

Created and transformed features to improve prediction accuracy and model performance.

---

## 5. Model Building

Split the dataset into training and testing datasets.

Example:

```python
X_train, X_test, y_train, y_test = train_test_split(
    X, y, test_size=0.2, random_state=42
)
```

Trained multiple Machine Learning models for classification prediction.

---

## 6. Model Evaluation

Evaluated models using:
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

- Customers with previous vehicle damage showed higher interest in purchasing insurance.
- Middle-aged customers had a greater probability of conversion.
- Previously uninsured customers were more likely to respond positively.
- Certain sales channels performed better in customer conversion.

---

# Key Features

- End-to-end Machine Learning pipeline
- Real-world insurance business use case
- Data preprocessing and cleaning
- Multiple model comparison
- Performance evaluation metrics
- Business-driven insights

---

# Business Applications

This project helps insurance companies:
- Improve customer targeting
- Optimize marketing campaigns
- Increase conversion rates
- Reduce marketing costs
- Improve decision-making using predictive analytics

---

# Future Enhancements

- Hyperparameter tuning
- Model deployment using Flask or Streamlit
- Real-time prediction system
- Deep learning integration
- Cloud deployment

---

# Conclusion

This project successfully predicts customer interest in insurance cross-selling using Machine Learning classification algorithms. The solution demonstrates how predictive analytics can support business decision-making and improve customer targeting strategies.

---

# Resume Project Description

### Max Life Insurance Cross-Sell Prediction

Developed a Machine Learning classification model to predict customer interest in additional insurance products using customer demographics, insurance history, and behavioral data. Performed EDA, feature engineering, preprocessing, and model evaluation using Logistic Regression, Random Forest, and Gradient Boosting algorithms using Python and Scikit-learn.

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
random-forest
gradient-boosting
eda
insurance-project
```
