# UPI Fraud Detection using Machine Learning  

## Overview  
This project focuses on detecting fraudulent transactions in UPI (Unified Payments Interface) data using machine learning techniques. The objective is to analyze transaction patterns and build predictive models to classify transactions as fraudulent or legitimate.  

## Dataset  
The dataset used in this project is synthetically generated and contains **647 UPI transaction records** for the financial year 2023-2024. It includes various transaction-related features and fraud indicators.  

### Features:  
- **Transaction_ID**: Unique identifier for each transaction  
- **Date & Time**: Timestamp of the transaction  
- **Merchant_ID**: Unique identifier for the merchant  
- **Transaction Amount**: Amount transferred in the transaction  
- **Payment Method**: Mode of payment (UPI, linked bank account, etc.)  
- **Fraud Indicator**: Label indicating whether the transaction is fraudulent  

## Methodology  
1. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical variables  
   - Feature scaling and transformation  

2. **Exploratory Data Analysis (EDA)**  
   - Understanding transaction patterns  
   - Identifying fraud trends using visualization  

3. **Model Development**  
   - Implementing machine learning models such as:  
     - Logistic Regression  
     - Random Forest  
     - XGBoost  
     - Support Vector Machine (SVM)  
   - Hyperparameter tuning for improved accuracy  

4. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-score  
   - Confusion Matrix and ROC-AUC curve analysis  

## Technologies Used  
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Machine Learning**: Supervised learning models for classification  

