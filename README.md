# 📌 SecureSwipe - Credit Card Fraud Detection using Logistic Regression

## 📝 Overview
This project implements **Credit Card Fraud Detection** using **Logistic Regression**. The dataset contains anonymized credit card transactions labeled as fraudulent or non-fraudulent. The goal is to build a model that effectively identifies fraudulent transactions.

## 📂 Dataset
The dataset used in this project is **creditcard.csv**, which contains:
- **Features (V1 - V28):** Principal components obtained via PCA
- **Amount & Time:** Transaction amount and timestamp
- **Class:** Binary label (0 = Non-Fraudulent, 1 = Fraudulent)

## 🚀 Features
✅ **Data Cleaning & Handling Missing Values**  
✅ **Exploratory Data Analysis (EDA) & Visualization** 📊  
✅ **Feature Engineering & Correlation Analysis**  
✅ **Data Splitting & Standardization**  
✅ **Logistic Regression Model Training** 🎯  
✅ **Model Evaluation (Accuracy, Precision, Recall, F1-Score, Confusion Matrix)**  

## 📌 Project Structure
```
Credit-Card-Fraud-Detection/
│── README.md  # Documentation
│── creditcard.csv  # Dataset
│── fraud_detection.py  # Main Python script
```

## 📊 Exploratory Data Analysis (EDA)
🔹 **Class Distribution** (Fraud vs. Non-Fraud)  
🔹 **Visualizations: Histograms, Boxplots, Pairplots, Scatter Plots**  
🔹 **Correlation Matrix** (to analyze feature relationships)  

## 🔧 Technologies Used
🔹 Python  
🔹 Pandas, NumPy (Data Handling)  
🔹 Seaborn, Matplotlib (Visualization)  
🔹 Scikit-learn (Machine Learning & Model Evaluation)  

## 📜 How to Run the Project?
#### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Aishvariyaa/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection
```

#### 2️⃣ Install Dependencies
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

#### 3️⃣ Run the Script
```bash
python fraud_detection.py
```

## 📈 Model Performance Metrics
| Metric        | Score |
|--------------|-------|
| **Accuracy** | 95%+  |
| **Precision**| High  |
| **Recall**   | High  |
| **F1-Score**| High  |

## 🔮 Next Steps
🔹 Implement **Random Forest & Neural Networks** 🧠  
🔹 Use **SMOTE** to handle class imbalance  
🔹 Deploy the model as a **web API** 🌐  



