# 🚗 Used Car Price Prediction

## 📌 Overview

This project aims to predict the selling price of used cars using Machine Learning. It demonstrates an end-to-end regression workflow, from data preprocessing and exploratory data analysis to model training and evaluation.

The objective is to understand the factors that influence used car prices and build a predictive model capable of estimating a vehicle's selling price accurately.

---

## 🎯 Objectives

* Explore and understand the dataset.
* Clean and preprocess the data.
* Perform Exploratory Data Analysis (EDA).
* Build a Machine Learning pipeline.
* Train a Linear Regression model.
* Evaluate model performance.
* Predict prices for unseen vehicles.

---

## 📂 Dataset

The dataset contains information about used vehicles, including several features that influence their market value.

Typical features include:

* Vehicle Brand
* Model
* Manufacturing Year
* Mileage
* Fuel Type
* Transmission
* Engine Size
* Horsepower
* Additional vehicle specifications

**Target Variable**

* Selling Price

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## 📊 Project Workflow

### 1. Data Loading

* Imported the dataset.
* Inspected the data structure.
* Checked data types.

### 2. Data Cleaning

* Handled missing values.
* Removed duplicate records.
* Verified dataset quality.

### 3. Exploratory Data Analysis (EDA)

Performed visual analysis to understand:

* Price distribution
* Feature relationships
* Correlations
* Outliers

Visualizations included:

* Histograms
* Scatter Plots
* Correlation Heatmap
* Boxplots

---

### 4. Data Preprocessing

Created a preprocessing pipeline using Scikit-learn to:

* Scale numerical features.
* Encode categorical variables.
* Prepare the data for model training.

---

### 5. Model Building

A **Linear Regression** model was trained using a Scikit-learn Pipeline to ensure consistent preprocessing and prediction.

---

### 6. Model Evaluation

The model was evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### Results

| Metric   |   Value |
| -------- | ------: |
| MAE      | ≈ 3,810 |
| RMSE     | ≈ 5,055 |
| R² Score |  ≈ 0.85 |

These results indicate that the model provides strong predictive performance for estimating used car prices.

---

## 📈 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Data Visualization
* Machine Learning
* Regression Analysis
* Scikit-learn Pipelines
* Model Evaluation
* Predictive Analytics

---

## 📁 Project Structure

```text
used-car-price-prediction/
│
├── data/
├── notebook/
│   └── Used_Car_Price_Prediction.ipynb
├── images/
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Future Improvements

Potential enhancements include:

* Compare multiple regression models (Random Forest, XGBoost, Gradient Boosting, CatBoost).
* Perform hyperparameter tuning.
* Deploy the model as a web application using Streamlit or Flask.
* Improve feature engineering.
* Add cross-validation for more robust evaluation.

---

## 💡 Key Takeaways

This project strengthened my understanding of the complete machine learning workflow, including data preprocessing, visualization, model development, evaluation, and predictive analytics using Python and Scikit-learn.
