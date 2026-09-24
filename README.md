# Credit Card Fraud Detection using Machine Learning

**IBM SkillsBuild | AICTE | BharatCares**  
**Data Analytics with AI Academic Internship 2026**

---

## Project Overview

This project builds an end-to-end **Credit Card Fraud Detection** system using machine learning.  
The goal is to accurately identify fraudulent transactions in a highly imbalanced real-world dataset while minimizing false positives.

**Dataset Source:**  
[Kaggle - Credit Card Fraud Detection (Machine Learning Group - ULB)](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

- Total Transactions: **284,807**
- Fraudulent Transactions: **492** (0.172%)
- Features: Time, Amount, V1–V28 (PCA-transformed), Class (target)

---

## Problem Statement

Credit card companies need reliable systems to detect fraudulent transactions in real time so that customers are not charged for purchases they did not make.  
Because fraud cases form less than 0.2% of all transactions, standard accuracy metrics are misleading. The project focuses on **Precision, Recall, F1-Score, and ROC-AUC**.

---

## Project Workflow

1. **Data Loading & Exploration**
2. **Exploratory Data Analysis (EDA)**
3. **Data Preprocessing** (Scaling + handling class imbalance)
4. **Model Building**
   - Logistic Regression
   - Random Forest Classifier
   - XGBoost Classifier
5. **Model Evaluation & Comparison**
6. **Business Insights & Recommendations**

---

## Technologies Used

- **Python 3.x**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Visualization
- **Scikit-learn** – Machine Learning models & metrics
- **Imbalanced-learn** – SMOTE for class imbalance
- **XGBoost** – Gradient boosting model
- **Jupyter Notebook** – Development environment

---

## How to Run the Project

### 1. Download the Dataset
1. Go to: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
2. Download `creditcard.csv`
3. Place the file in the same folder as the notebook

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook
```bash
jupyter notebook YourName_CreditCard_Fraud_Detection.ipynb
```

Or open the notebook in Google Colab / VS Code and run all cells.

---

## Project Structure

```
CreditCard_Fraud_Detection_Project/
├── YourName_CreditCard_Fraud_Detection.ipynb   # Main code
├── requirements.txt                            # Dependencies
├── README.md                                   # This file
└── YourName_ProjectReport.docx                 # Detailed project report
```

---

## Key Results (Expected)

| Model                  | Precision | Recall | F1-Score | ROC-AUC |
|------------------------|-----------|--------|----------|---------|
| Logistic Regression    | ~0.85–0.95| High   | High     | >0.95   |
| Random Forest          | High      | High   | High     | >0.97   |
| XGBoost                | Highest   | High   | Highest  | >0.98   |

*(Actual numbers will appear after you run the notebook)*

---

## Author

**Venkat Kalyan**  
IBM SkillsBuild Data Analytics with AI Internship  
BharatCares × AICTE × IBM  
September 2026

---

## License

This project is created for academic purposes as part of the IBM SkillsBuild Academic Internship.
