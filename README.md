## 📊 Advertising Sales Prediction using Linear Regression
📌 Project Overview

Advertising plays a crucial role in influencing product sales, but understanding which advertising channel contributes the most is essential for effective budget allocation.
This project analyzes the relationship between advertising spend across TV, Radio, and Newspaper channels and product sales using Exploratory Data Analysis (EDA) and Linear Regression.

The project demonstrates a complete end-to-end machine learning workflow, from data understanding and assumption validation to model building and evaluation.

## 🎯 Problem Statement

The objective of this project is to analyze how different advertising media channels impact sales and to build a predictive model that estimates sales based on advertising expenditure. The goal is to provide data-driven insights that can help businesses optimize their marketing budgets and improve sales performance.

## 📂 Dataset Description

The dataset consists of the following variables:

| Feature   | Description                                          |
| --------- | ---------------------------------------------------- |
| TV        | Advertising budget spent on TV (in thousands)        |
| Radio     | Advertising budget spent on Radio (in thousands)     |
| Newspaper | Advertising budget spent on Newspaper (in thousands) |
| Sales     | Product sales (in thousands of units)                |

## 🧪 Project Workflow
1️⃣ Data Loading & Inspection

Loaded the dataset using Pandas

Checked data types and structure

Removed unnecessary index columns

Verified data consistency

## 2️⃣ Exploratory Data Analysis (EDA)

Generated descriptive statistics to understand data distribution

Identified range, mean, and variability of features

Visualized distributions using histograms and boxplots

## 3️⃣ Missing Value & Outlier Analysis

Checked for missing values

Used boxplots to detect outliers

Confirmed absence of extreme outliers suitable for regression modeling

## 4️⃣ Regression Assumption Validation

The following Linear Regression assumptions were validated:

No Extreme Outliers
Verified using boxplots

Linearity
Checked relationship between advertising channels and sales using scatter plots

Normality
Examined distribution of target variable and applied log transformation where required

Multicollinearity
Analyzed correlation between independent variables to ensure minimal dependency

## 5️⃣ Feature Engineering & Transformation

Separated independent and dependent variables

Applied log transformation to reduce skewness

Improved data suitability for regression modeling

## 6️⃣ Model Building

Trained a Linear Regression model

Learned relationships between advertising spend and sales

Used prepared and validated dataset

## 7️⃣ Model Evaluation

The model was evaluated using regression metrics such as:

R-squared (R²)

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

These metrics helped assess model accuracy and generalization ability.

## 📈 Key Insights

TV advertising has the strongest influence on sales

Radio advertising shows moderate impact

Newspaper advertising has relatively lower contribution

Data-driven marketing strategies can significantly improve ROI

## 🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

## 🚀 Conclusion

This project showcases how advertising data can be transformed into actionable business insights using data analytics and machine learning. By validating assumptions, applying appropriate transformations, and building a robust regression model, the project highlights the importance of data-driven decision-making in marketing and sales optimization.

## 📌 Future Enhancements

Try multiple regression or regularization techniques

Add feature interaction analysis

Deploy the model using Streamlit or Flask

Perform cross-validation for better generalization

## 🙌 Acknowledgements

This project was developed as part of a Data Analytics learning journey and serves as a practical implementation of regression concepts taught during training.

## 👤 Author

Bansi Shah
