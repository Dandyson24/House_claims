## Insurance Claims Classification – Capstone Project
### Project Overview

This capstone project focuses on building a classification model to predict whether an insurance policyholder will file a claim, using structured policy and property-level data. The project demonstrates an end-to-end data science workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, class imbalance assessment, model training, and evaluation.

The work is designed as a portfolio project, showcasing practical machine learning skills applied to real-world insurance and risk analytics.

### Problem Statement

Insurance providers need to proactively identify policies that are more likely to result in claims in order to:

Improve risk assessment

Optimize pricing and underwriting decisions

Allocate resources for claims management

This project answers the question:

Can we accurately predict whether a policy will result in a claim based on property and demographic characteristics?

### Dataset Description

The dataset contains policy-level information including:

Year of observation

Residential status

Building type

Building age

Number of windows

Property protection features

Geographic code

Claim indicator (target variable)

The target variable is binary, representing whether a claim was made or not.

###  Exploratory Data Analysis (EDA)

Key EDA steps include:

Assessment of missing values and data quality

Outlier examination

Visualization of claim distribution to assess class imbalance

Claim rate analysis by:

Year of observation

Residential status

Building type

Building age

Property protection features

Geographic location

These analyses helped identify patterns and variables strongly associated with claims.

### Data Preprocessing

The preprocessing pipeline includes:

Feature–target separation

Train–test split

Identification of numerical and categorical features

Scaling of numerical variables

One-hot encoding of categorical variables

Use of Scikit-learn Pipelines for reproducibility and clean modeling

### Model Development

Multiple classification models were trained and evaluated, including:

Logistic Regression

Regularized Logistic Regression

After performance comparison, Logistic Regression was selected and retrained due to its superior balance of accuracy and interpretability.

###  Model Evaluation

Model performance was assessed using:

Accuracy

Classification report (precision, recall, F1-score)

Validation of the target variable distribution

The final model demonstrates strong predictive performance while remaining interpretable for business decision-making.

###  Key Insights

Claims are not evenly distributed, indicating class imbalance

Certain property characteristics significantly influence claim likelihood

Geographic and structural features play an important role in risk profiling

Logistic Regression provides a strong baseline model for claims prediction

### Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook



### Future Improvements

Address class imbalance using SMOTE or class weighting

Compare additional models (Random Forest, XGBoost)

Perform hyperparameter tuning

Deploy the model as an API or dashboard for decision support

### Author

Andrew Okebugwu
Doctor | Public Health PhD | Data Analyst
Focused on healthcare and insurance analytics using Python, SQL, and Power BI.
