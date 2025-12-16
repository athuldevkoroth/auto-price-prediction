![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-green?logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)

# 🚗 Automobile Price Prediction

A machine learning project that predicts automobile selling prices using regression models based on technical and performance-related features.

---

## 🚀 Overview

This project focuses on predicting the **selling price of automobiles** by analyzing key specifications such as engine size, horsepower, dimensions, fuel efficiency, and curb weight. The goal is to understand how these features influence vehicle pricing and to build a reliable regression model for price estimation.

---

## 🎯 Objective

- Analyze automobile feature data
- Identify key factors influencing car prices
- Build and evaluate regression models
- Predict automobile prices with good accuracy on unseen data

---

## 📂 Dataset

The dataset contains numerical attributes describing automobile specifications.

### Key Features

- **Engine & Performance**: engineSize, horsepower, compressionRatio, peakrpm  
- **Dimensions**: wheelbase, length, width, height, curbWeight  
- **Fuel Efficiency**: citympg, highwaympg  
- **Other**: bore, stroke, normalizedLosses  

**Target Variable:** Automobile selling price

---

## 🧹 Data Preprocessing

- Checked and handled missing values
- Removed duplicate records
- Dropped non-informative identifiers
- Tested outlier removal (no performance improvement)
- Applied feature scaling where required
- Final model trained on clean, consistent data

---

## 📊 Exploratory Data Analysis (EDA)

EDA was performed to:
- Understand price distribution
- Identify correlations between features and price
- Analyze the impact of engine size, horsepower, and curb weight

Key insight:
- Engine size and curb weight showed strong correlation with price.

---

## 🤖 Model Building

- Multiple regression models were tested
- Feature engineering was explored but excluded when it did not improve results
- Final model selected based on evaluation performance

---

## 📈 Evaluation

Model performance was evaluated using:
- **RMSE**
- **MAE**
- **R² Score**

The final model demonstrated good predictive accuracy and generalization.

---

## 🧪 Model Testing

The trained model was tested on unseen sample data to validate real-world usability and consistency of predictions.

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 👤 Author

**Athul**  
Machine Learning | Data Science | Data Analytics
