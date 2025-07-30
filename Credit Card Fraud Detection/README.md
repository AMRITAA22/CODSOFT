# 💳 Credit Card Fraud Detection

This project detects fraudulent credit card transactions using various machine learning algorithms. The dataset is highly imbalanced, and special techniques like **SMOTE** were used to handle the imbalance.

---

## 📌 Problem Statement

The objective is to build a machine learning model that detects fraudulent credit card transactions based on transaction features. By analyzing patterns in the data, the model aims to distinguish between legitimate and fraudulent transactions, helping reduce financial losses and enhance transaction security.

---

## 📂 Dataset

- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains transactions made by European cardholders in September 2013.
- **Features:** 30 total — anonymized `V1` to `V28`, plus `Amount` and `Time`.
- **Target:** `Class` — 0 = Not Fraud, 1 = Fraud.

---

## 🔧 Tools & Libraries Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost
- Ipywidgets (for interactive prediction in Jupyter)

---

## 📊 Steps Followed

1. **Data Loading & Exploration**
2. **Exploratory Data Analysis (EDA)**
3. **Data Preprocessing & Feature Scaling**
4. **Handling Class Imbalance with SMOTE**
5. **Train-Test Split**
6. **Model Building (Logistic Regression, Random Forest, XGBoost)**
7. **Model Evaluation (Confusion Matrix, Classification Report, ROC-AUC)**
8. **Interactive Prediction UI using `ipywidgets`**

---

## 📈 Model Performance

- **Models Used**: Logistic Regression, Random Forest, XGBoost
- **Metrics Evaluated**: Precision, Recall, F1-score, ROC-AUC
- **Best Model**: Random Forest / XGBoost (high recall on fraudulent class)

---

## 📂 Project Structure

```
Credit Card Fraud Detection/
├── Credit_Card_Fraud_Detection .ipynb
└── README.md
```

---

## 📌 How to Run

1. Download the dataset from Kaggle and place it in the `data/` folder.
2. Open the `.ipynb` notebook in Jupyter Notebook.
3. Run all cells sequentially.
4. Use the interactive section at the bottom to test custom transaction inputs.

---

## 🙋‍♀️ Author

- **Name**: Amrita  
- **Internship**: CodSoft Data Science Track  
- **Task**: Credit Card Fraud Detection

---
