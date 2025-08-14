# Customer-Chrun-Prediction
Customer Churn Prediction using Machine Learning
This project focuses on predicting customer churn for a subscription-based service using historical customer data.
By analyzing features such as demographics, usage behavior, and account details, the model identifies customers at risk of leaving, enabling businesses to take proactive retention measures.

🚀 Features
🧹 Data Preprocessing
Dropped irrelevant columns (RowNumber, CustomerId, Surname)

Encoded categorical variables using Label Encoding and One-Hot Encoding

Scaled numerical features with StandardScaler

🌲 Model Training
Implemented Random Forest Classifier for binary classification of churn vs. non-churn customers

📊 Model Evaluation
Measured performance using:

Accuracy Score

Classification Report

Confusion Matrix Visualization

📈 Visualization
Used Seaborn Heatmaps to visualize the confusion matrix

Created Feature Importance plot to identify key churn drivers

📉 Full Dataset Predictions
Generated churn predictions for all customers in the dataset

Created a DataFrame mapping RowNumber to Predicted_Churn labels

🛠 Tech Stack
Python

Pandas

NumPy

scikit-learn

Matplotlib

Seaborn

📂 Dataset
The dataset contains customer demographic, account, and behavioral data along with churn labels.

📌 Dataset Source: Kaggle - Customer Churn Dataset
(https://www.kaggle.com/datasets/shantanudhakadd/bank-customer-churn-prediction)
📊 Model Workflow
Load and explore dataset

Drop unnecessary columns

Encode categorical data

Scale features

Split into training and testing sets

Train Random Forest Classifier

Evaluate model performance

Visualize results (confusion matrix, feature importance)

Predict churn on full dataset

📈 Results
Achieved ~86% accuracy using Random Forest Classifier

Identified key drivers of churn such as credit score, tenure, and balance

Helps businesses in crafting data-driven customer retention strategies
