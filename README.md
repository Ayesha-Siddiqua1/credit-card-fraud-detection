# 💳 Credit Card Fraud Detection  

## 📌 Overview  
This project aims to **detect fraudulent credit card transactions** using **Machine Learning** techniques. The dataset contains anonymized credit card transactions labeled as **fraudulent or legitimate**. The objective is to build a model that can accurately classify fraudulent transactions.  

## 🔥 Features  
- **Exploratory Data Analysis (EDA)** to understand fraud patterns.  
- **Data Preprocessing**: Handling imbalanced data using **SMOTE**, feature scaling, and encoding.  
- **Machine Learning Models** to classify transactions as **fraudulent (1) or legitimate (0)**.  
- **Model Evaluation**: Accuracy, Precision, Recall, and F1-score.  

## 📂 Dataset  
The dataset used in this project is the **Credit Card Fraud Detection** dataset from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud).  

**Columns in the dataset:**  
- `Time`: Transaction timestamp.  
- `V1, V2, ..., V28`: Anonymized features (due to privacy concerns).  
- `Amount`: Transaction amount.  
- `Class`: **0 = Legitimate transaction, 1 = Fraudulent transaction**.  

## ⚙️ Installation  
### 1️⃣ Clone the repository  
```
git clone https://github.com/Ayesha-Siddiqua1/credit-card-fraud-detection.git  
cd credit-card-fraud-detection  
```

2️⃣ Install dependencies

Ensure you have Python installed, then install the required libraries:

```
pip install pandas numpy matplotlib seaborn scikit-learn 
```

📊 Exploratory Data Analysis (EDA)

Fraudulent transactions account for less than 0.2% of all transactions.
Imbalance handling: SMOTE (Synthetic Minority Over-sampling) is used to balance the dataset.
Correlation analysis: Identifies important features affecting fraud detection.

🤖 Machine Learning Models

The project uses multiple ML models, including:
Logistic Regression
Random Forest Classifier

I used Logistic Regression ML model to detect fraud transcation. You can also use Random Forest.

Model is evaluated using Accuracy, Precision, Recall, F1-score, and AUC-ROC Curve.

🚀 How to Run

Run the Python script to train the model and make predictions:
```
python fraud_detection.py
```

📈 Results

Random Forest Classifier achieved 99% precision on fraud cases.
Logistic Regression classifier achieved 94% precision on fraud cases.

🌟 Star this repository if you found it useful! 🚀
