# 📈 Stock Price Prediction using Machine Learning

This project focuses on predicting Tesla's stock price movements using various machine learning classification models. By leveraging historical stock data, the project aims to classify whether the stock price will go up or down based on engineered features.

---

## 🧠 Project Overview

- Used historical Tesla stock dataset.
- Performed data preprocessing, scaling, and feature engineering.
- Trained multiple classification models including:
  - **Logistic Regression**
  - **Support Vector Classifier (SVC)**
  - **XGBoost Classifier**
- Evaluated model performance using classification metrics.

---

## 🛠️ Technologies & Libraries Used

- **Python**
- **NumPy** – Numerical operations  
- **Pandas** – Data manipulation and analysis  
- **Matplotlib** & **Seaborn** – Data visualization  
- **Scikit-learn (sklearn)** – ML models, preprocessing, train-test split, and evaluation  
- **XGBoost** – High-performance gradient boosting classifier  
- **Warnings** – To suppress unnecessary warnings

---

## 🔢 Machine Learning Pipeline

1. **Data Collection**  
   - Used historical Tesla stock data (manually or via `yfinance`/CSV)

2. **Data Preprocessing**  
   - Handled missing values, cleaned data  
   - Scaled features using **StandardScaler**

3. **Feature Selection & Engineering**  
   - Created predictive features based on price trends

4. **Model Building**  
   - Trained Logistic Regression, SVC, and XGBoost models  
   - Split data using **train_test_split**

5. **Evaluation**  
   - Measured performance using metrics like accuracy, precision, recall, and confusion matrix

---

## 📈 Visualizations

- Plotted correlations, class distributions, and model performance comparisons using **Matplotlib** and **Seaborn**.

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/tesla-stock-prediction.git
   cd tesla-stock-prediction
