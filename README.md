# 🚢 ML_Titanic Survival Project

## 📘 Overview
This project demonstrates a **machine learning pipeline** for predicting passenger survival on the Titanic dataset.  
The dataset contains a mix of **numeric and categorical features**, requiring preprocessing, feature engineering, one-hot encoding, and scaling.  
The main goal is to accurately predict **survival (0/1)** of passengers.

## 🧠 Project Highlights
- **Type:** Classification (Binary)  
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Dataset:** `titanic.csv` — mix of numeric & categorical features  

## ⚙️ Workflow
1. **Data Cleaning & Preprocessing** – handle missing values, extract titles, encode categorical features.  
2. **Exploratory Data Analysis (EDA)** – visualize distributions, density plots, boxplots, and correlation heatmaps.  
3. **Train/Test Split** – separate features (X) and target (y) for evaluation.  
4. **Spot-Check Models** – baseline performance with Logistic Regression, LDA, KNN, Naive Bayes, CART, and SVM.  
5. **Pipeline & Standardization** – scale numeric features and ensure models handle mixed data correctly.  
6. **Hyperparameter Tuning** – optimize parameters of SVM, Logistic Regression, Random Forest, and Gradient Boosting.  
7. **Model Evaluation** – Accuracy, Confusion Matrix, Classification Report.  

## 🚧 Challenges
- Mixed data types (numeric + categorical) required careful preprocessing and encoding.    
- Imbalanced survival classes affected model recall, requiring careful thresholding.  
- Hyperparameter tuning was crucial for ensemble and SVM performance.  

## 📊 Results
- **✅ Best Model:** Gradient Boosting Classifier  
- **🎯 CV Accuracy:** ~84.2%  
- **📉 Test Accuracy:** ~81.6%  
- Minor class prediction improved after proper preprocessing and hyperparameter tuning.  

## 💡 Skills Used
- 🐍 Python  
- 🤖 Machine Learning  
- 📊 Data Science  
- 📈 Ensemble Learning & Model Optimization   

## 📁 Files Included
- `Titanic.ipynb` → Main notebook with preprocessing, training, and evaluation  
- `titanic.csv` → Dataset (numeric + categorical)  

## 📬 Contact
- **Email:** amirhossin6825@gmail.com  
- **Telegram:** [@AmirHossin6825](https://t.me/AmirHossin6825)
