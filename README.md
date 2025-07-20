# 📈 Google Stock Price Prediction Using Linear Regression

In this project, I developed a machine learning model to **predict Google’s stock price** using **Linear Regression**, one of the foundational techniques in data science. This end-to-end project covers everything from data preprocessing to model evaluation and prediction — all based on real-world financial data.

## 🔍 Project Summary
Using historical stock price data of **Alphabet Inc. (GOOGLE)**, I built a regression model that predicts future prices based on key indicators such as Open, Close, High, Low, Volume, and Adjusted Prices. This approach demonstrates how even a simple linear model can produce **highly accurate predictions** with the right data handling and feature engineering.

## 📊 Workflow Overview
- **Data Cleaning & Preprocessing:** Removed outliers using the IQR method and visual checks via boxplots. Formatted date columns and handled irrelevant or missing values.
- **Exploratory Data Analysis (EDA):** Explored patterns and correlations using scatter plots, line graphs, and boxenplots. These helped in understanding stock behavior and feature relevance.
- **Model Building:** Implemented Linear Regression using `scikit-learn`. Evaluated performance using metrics like:
  - **R² Score:** 0.999 → Strong predictive power
  - **Adjusted R²:** Validated model stability
  - **MAE & RMSE:** Assessed model errors
- **Visualizations:** Created insightful charts like:
  - Actual vs. Predicted Price Plot
  - Error Distribution Boxplot
  - Volume & Price Time-Series Graphs

## 🧠 Key Takeaways
- Real-world data often needs **extensive cleaning** before modeling.
- Even a basic Linear Regression model can be powerful when **properly applied**.
- **Visualization is key** to understanding and communicating model performance.

## 🛠️ Tools Used
- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 💡 Real-World Relevance
This project is a great example of how data science can be applied in **finance** to support decision-making in **stock trading**, **investment**, or **risk analysis**.

---

📌 *Feel free to clone or fork the repository and explore the notebook!*

















# 📈 Google Stock Price Prediction using Linear Regression

![Google Stock](https://img.shields.io/badge/Model-Linear%20Regression-blue) ![Python](https://img.shields.io/badge/Made%20With-Python-yellow) ![License](https://img.shields.io/badge/License-MIT-green)

Predicting Google’s stock price using historical data and a Linear Regression model. This project showcases how simple statistical techniques, when combined with proper data preprocessing and feature engineering, can result in **highly accurate predictions (R² = 0.999)**.

---

## 🚀 Project Overview

This project aims to forecast the closing stock price of **Alphabet Inc. (GOOGL)** using **Linear Regression**. It walks through the entire data science pipeline — from **data cleaning** and **exploratory analysis** to **modeling** and **evaluation** — using real-world financial data.

---

## 🧩 Features & Workflow

### 📌 1. Data Preprocessing
- Cleaned the dataset and formatted timestamps
- Removed outliers using the IQR method
- Created new adjusted columns (adjClose, adjOpen, etc.)

### 📌 2. Exploratory Data Analysis (EDA)
- Visualized trends using line plots, scatter plots, and boxenplots
- Detected relationships between open, close, volume, and adjusted prices

### 📌 3. Modeling
- Built a **Linear Regression model** with `scikit-learn`
- Model trained on key price indicators to predict Close prices

### 📌 4. Evaluation
- **R² Score:** `0.999` → excellent model fit
- **Adjusted R²**, **MAE**, and **RMSE** were calculated
- Visualized Actual vs Predicted prices and error distribution

---

## 📊 Visual Results

![Actual vs Predicted](assets/actual_vs_predicted.png)  
*Figure: Predicted vs Actual Google Stock Prices*

![Error Boxplot](assets/error_boxplot.png)  
*Figure: Boxplot of Absolute Errors*

---

## 📦 Tech Stack

| Tool | Purpose |
|------|---------|
| 🐍 Python | Core programming |
| 📊 Pandas, NumPy | Data manipulation |
| 📈 Matplotlib, Seaborn | Visualization |
| 🤖 Scikit-learn | Model building |
| 📓 Jupyter Notebook | Analysis environment |

---

## 🧠 Key Learnings

- Clean, real-world stock data for modeling
- Use linear regression for financial predictions
- Evaluate regression models using statistical metrics
- Importance of data visualization in decision-making

---

## 💡 Real-World Application

This project reflects how **data science intersects with finance**, offering insights into price behavior and enabling better-informed investment decisions.

---

## 📁 Project Structure



