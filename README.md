# Fraud Detection System – Machine Learning Web App

# 🧠 Problem Statement :
Financial fraud is a major challenge in digital transactions. Fraudulent transactions cause significant financial losses to businesses and reduce customer trust.\

# 🎯 Objective :
The objective of this project is to:

Detect fraudulent transactions using machine learning

Build a robust classification model

Deploy the model using Flask

Provide a real-time prediction web interface

The system predicts whether a transaction is Fraudulent (1) or Legitimate (0) based on transaction-related features and this model generated accuracy score 97% 

# Demo 
![Uploading Screenshot 2026-03-26 205240.png…]()
<img width="1171" height="690" alt="Screenshot 2026-03-26 205308" src="https://github.com/user-attachments/assets/ee983334-34a6-403f-8458-a0706b516d44" />


# ⚙️ Approach Followed : 

# 🚀 Tech Stack Used

Python

Pandas & NumPy

Scikit-Learn

Flask

HTML & CSS

Joblib

📊 Dataset Overview

The dataset contains transaction-level data including:
 [Transaction amount,Transaction time,Merchant details,Customer details,Zip code information]

Other behavioral variables

The target variable:

Fraud → 1 (Fraudulent)

Fraud → 0 (Legitimate)

# 1️⃣ Data Preprocessing

Handled missing values

Handled missing values 

Encoded categorical variables using:

OneHotEncoding / ColumnTransformer

Applied full ML Pipeline to prevent data leakage

# 2️⃣ Exploratory Data Analysis (EDA)

Checked class imbalance

Analyzed fraud distribution

Identified high-risk transaction patterns

Feature importance analysis

# 3️⃣ Model Building

Implemented multiple classification models

Final model: XGBClassifier

Used train-test split for validation

Achieved strong performance on test data

Evaluation Metrics Used:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

# 4️⃣ Pipeline Implementation

Built a complete ML pipeline including:

Preprocessing

Encoding

Model training

This ensures:

No data leakage

Clean deployment

Production-ready workflow

# 5️⃣ Model Deployment

Saved trained model using joblib

Built Flask web application

Created:

templates/ (HTML frontend)

static/ (CSS styling)

Deployed locally for real-time prediction

Users can enter transaction details and instantly get fraud prediction.

# 💼 Business Impact

This solution can help businesses:

Reduce financial losses from fraud

Detect suspicious transactions in real time

Improve customer trust

Automate fraud monitoring systems

Support risk management teams

Even a small increase in fraud detection accuracy can save millions in transaction-heavy businesses.

