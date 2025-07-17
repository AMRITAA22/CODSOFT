# 📈 Sales Prediction using Python (CodSoft Internship Task 4)

## 📝 Problem Statement

Sales prediction involves forecasting the amount of product sales based on factors like advertising expenditure on different platforms (TV, Radio, Newspaper). This helps businesses optimize marketing budgets and maximize sales.

In this project, we aim to predict **Sales** using various advertising channels using **Linear Regression** in Python.

---

## 📂 Dataset

We have used the **Advertising Dataset** from Kaggle:
- [Dataset Link](https://www.kaggle.com/code/ashydv/sales-prediction-simple-linear-regression/input)

### Dataset Columns:
- `TV`: Advertising budget for TV
- `Radio`: Advertising budget for Radio
- `Newspaper`: Advertising budget for Newspaper
- `Sales`: Actual sales figures

---

## 🔧 Tools & Libraries Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib (for Visualization)
- Scikit-learn (for Linear Regression & Evaluation)

---

## 🚀 Approach

1. **Import Libraries**
2. **Load Dataset**
3. **Exploratory Data Analysis (EDA)**:
   - Summary statistics
   - Data visualization with Pairplots and Heatmaps
4. **Data Preparation**
   - Selecting features (`TV`, `Radio`, `Newspaper`) as inputs
   - Target variable: `Sales`
   - Train-test split
5. **Model Building**
   - Linear Regression Model
6. **Model Evaluation**
   - R-squared Score
   - Mean Squared Error
7. **Visualization**
   - Plotting Actual vs Predicted sales
8. **Prediction on New Data**

---

## 📊 Results

The Linear Regression model was able to predict sales with a decent accuracy based on advertising budgets. The model's **R-squared score** and **Mean Squared Error (MSE)** were evaluated to check performance.

---

## 🎯 Conclusion

- TV and Radio advertising have significant impact on sales.
- Newspaper advertising has a lesser influence compared to TV and Radio.
- This model can assist businesses in making data-driven marketing decisions.

---


## 🙋‍♀️ Author

- **Name**: Amrita  
- **Internship**: CodSoft Data Science Track  
- **Task**: Titanic Survival Prediction

---
