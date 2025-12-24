# ML-Project---Bank_Marketing-_Term_Deposit_Prediction

**Project Overview -**

Financial institutions invest heavily in marketing campaigns to promote term deposit products, but only a small fraction of customers respond positively.

This project aims to predict whether a customer will subscribe to a term deposit using machine learning techniques applied to demographic, financial, behavioral, and marketing interaction data.

The model helps banks: -

  •	Identify high-potential customers
  
  •	Reduce marketing costs
  
  •	Improve campaign conversion rates
  
  •	Enable data-driven decision making


**Problem Statement -**

Given historical customer and marketing data, build a binary classification model to predict the target variable:

TermDepositSubscribed

1 → Customer subscribed

0 → Customer did not subscribe

**About this Dataset -**

This dataset contains 100,000 banking customers along with demographic details, financial attributes, product holdings, behavioral activity, and marketing interaction records. It is designed for exploring customer profiles and predicting whether a client subscribes to a term deposit using the target variable TermDepositSubscribed (0/1).

With 45 meaningful features—including income, credit score, account balance, customer segment, previous campaign outcome, and contact details—this dataset provides a realistic foundation for analyzing customer decision behavior and building end-to-end predictive models.

Dataset Source - Kaggle

Dataset Name - Bank Marketing Dataset for Term Deposit Prediction

Dataset link - https://www.kaggle.com/datasets/nisargpatel344/bank-marketing-dataset-for-term-deposit-prediction


**Project Objectives -**

The objective of this project is to design and evaluate a machine learning–based classification framework for predicting customer subscription to term deposit products. The study focuses on systematic data preprocessing, feature engineering, and model evaluation to enhance predictive accuracy and support data-driven banking marketing decisions.


**Steps Performed in the Project -**
1.	Data Collection and Understanding
Acquired the dataset from Kaggle and examined its structure, feature types, and target variable.
2.	Exploratory Data Analysis (EDA)
Analyzed data distributions, correlations, and class imbalance to identify patterns and insights.
3.	Data Preprocessing
Handled missing values, encoded categorical variables, and scaled numerical features to prepare the data for modelling.
4.	Feature Engineering and Selection
Created derived features and selected relevant variables to improve model performance.
5.	Model Development
Implemented and trained multiple machine learning classification models.
6.	Model Evaluation
Assessed model performance using appropriate evaluation metrics such as Accuracy, Precision, Recall, F1-score, and ROC-AUC.
7.	Result Interpretation and Deployment
Interpreted results using feature importance techniques and prepared the model for deployment.

**Results -**

'XGBoost Classifier' model fits well with best performance evaluation. (Accuracy=68.25%)
Based on the XGBoost Classifier and the feature importance analysis, the top 5 features influencing whether a customer subscribes to a term deposit are:
1.	NumPrevCampaignContacts
2.	ResponsePropensity
3.	PrevCampaignOutcome
4.	HasPersonalLoan
5.	LastContactChannel
This means that these features are the most significant drivers in the XGBoost model's decision-making process.


