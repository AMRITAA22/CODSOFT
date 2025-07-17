# 🎬 Movie Rating Prediction System

## 📌 Problem Statement
The goal of this project is to develop a machine learning model that predicts the rating of a movie based on its features such as **Genre, Director, Actors, Duration, Budget, and Votes**.

By analyzing historical movie data, we can estimate the expected ratings for new or existing movies based on their attributes.

---

## 🔍 Dataset
The dataset contains various features like:
- Name
- Genre
- Director
- Actors
- Duration
- Budget
- Votes
- Year
- Rating (Target Variable)

---

## 🔧 Tools & Technologies
- **Python**
- **Pandas & NumPy** for data handling
- **Matplotlib & Seaborn** for visualization
- **Scikit-learn** for machine learning algorithms
- **Streamlit** (Optional) for building an interactive web application

---

## 📊 Steps Performed

### 1. Data Preprocessing
- Handling missing values
- Encoding categorical variables (Genre, Director, Actors)
- Scaling numeric features if necessary

### 2. Exploratory Data Analysis (EDA)
- Understanding feature distributions
- Analyzing relationships between features and the movie rating
- Visualizing data using histograms, boxplots, and heatmaps

### 3. Model Building
- Splitting the dataset into **training and testing sets**
- Training regression models like:
  - Linear Regression
  - Random Forest Regressor
  - Decision Tree Regressor
- Evaluating models using **R² score** and **Mean Squared Error (MSE)**

### 4. Model Evaluation
- Testing model performance on unseen data
- Choosing the best-performing model for predictions

### 5. Optional: Streamlit Web App
An interactive Streamlit application allows users to:
- Select movie features through a UI
- Get real-time predictions of movie ratings

---

## 📈 Model Performance
- **Best Model:** Random Forest Regressor (example)
- **R² Score:** Achieved reasonable accuracy in predicting ratings

> *Note: The actual performance may vary based on data quality and preprocessing steps.*

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/movie-rating-prediction.git
cd movie-rating-prediction
