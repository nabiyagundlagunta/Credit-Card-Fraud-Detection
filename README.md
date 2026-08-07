# Credit Card Fraud Detection Using Machine Learning

## 📌 Project Overview

Credit card fraud is a major problem in digital financial transactions. This project uses Machine Learning to identify potentially fraudulent credit card transactions.

The model classifies transactions into two categories:

- `0` → Normal Transaction
- `1` → Fraudulent Transaction

## 🎯 Objective

The main objective of this project is to develop a machine learning model that can detect fraudulent credit card transactions.

The project includes:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature scaling
- Train-test splitting
- Machine learning model training
- Prediction
- Model evaluation

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## 📊 Dataset

The project uses a credit card transaction dataset containing transaction features such as:

- Time
- V1 to V28
- Amount
- Class

The `Class` column is the target variable:

- `0` = Normal
- `1` = Fraud

The dataset is not included in this repository because of its size.

## 🔍 Exploratory Data Analysis

The project performs EDA to understand:

- Normal and fraudulent transaction counts
- Transaction amount distribution
- Differences between normal and fraudulent transactions
- Correlation between features

## 🤖 Machine Learning Model

The project uses **Logistic Regression** for classification.

The data is divided into:

- 80% training data
- 20% testing data

The `Amount` feature is standardized using `StandardScaler`.

## 📈 Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

Because fraud transactions are much fewer than normal transactions, precision, recall, and F1-score are important evaluation metrics.

### Fraud Class Results

- Precision: 0.57
- Recall: 0.57
- F1 Score: 0.57

## 📁 Project Files

| File | Description |
|------|-------------|
| `credit_card_fraud_detection.ipynb` | Complete Google Colab project |
| `credit_card_fraud_model.pkl` | Trained Logistic Regression model |
| `scaler.pkl` | Feature scaling model |

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Logistic Regression
   ↓
Predictions
   ↓
Model Evaluation
