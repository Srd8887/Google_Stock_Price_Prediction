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
