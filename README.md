# 🏡 California Housing Price Prediction Machine Learning Project

## 🔍 Overview

This project develops a **Machine Learning-based housing price prediction model** to estimate median house values in California. We use **Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and XGBoost** for data analysis, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

## 📊 Dataset

The dataset contains California housing information, including geographical coordinates, housing age, room counts, population, households, and median income.

- **Target Variable:** `median_house_value`
- **Input Features:** Geographical, demographic, and housing-related numerical features
- **Problem Type:** Supervised Learning — Regression

## 📌 Key Analysis & Findings

### 1️⃣ Feature Distribution Analysis

📌 Histograms were used to understand the distributions of numerical features and identify skewness and potential extreme values.

![Feature Distribution Analysis](/feature_distributions.png)

### 2️⃣ Outlier Analysis

📌 Boxplots were used to identify potential outliers in numerical features. These observations were investigated as potential extreme values rather than automatically removed.

![Outlier Analysis](/feature_boxplots.png)

### 3️⃣ Median Income vs. House Value

📌 Scatter plot analysis revealed a positive relationship between median income and median house value, indicating that higher-income areas generally tend to have higher house prices.

![Median Income vs House Value](/income_vs_house_value.png)

### 4️⃣ Correlation Heatmap

📌 The correlation heatmap highlights relationships between numerical features. `median_income` showed a strong positive correlation with `median_house_value`, while several housing and population features showed high correlations with one another.

![Correlation Heatmap](/correlation_heatmap.png)

## 🛠 Technologies Used

- **Python, Pandas, NumPy** – Data manipulation and numerical analysis
- **Matplotlib, Seaborn** – Exploratory data analysis and visualization
- **Scikit-learn** – Data preprocessing, Random Forest, and regression evaluation
- **XGBoost** – Gradient boosting regression

## 💡 Key Insights

✔ **Median income is strongly associated with house value**, with a positive Pearson correlation of approximately 0.67 in the analysis discussed.

✔ **Several numerical features are highly correlated**, including total bedrooms and households, indicating overlapping information among housing-related features.

✔ **Feature engineering** was used to create rooms per household, bedrooms per room, and population per household.

✔ **XGBoost outperformed Random Forest** in the reported model comparisons, achieving lower MAE and RMSE and a higher R² score.

✔ **The final reported model achieved an R² score of 0.8174**, with an MAE of 31,771.86 and an RMSE of 48,333.37. This indicates promising predictive performance, with remaining errors in house price estimates.

## 🚀 Why This Project Matters

📌 **For Real Estate Applications:** Demonstrates how machine learning can estimate house values using housing and geographical information.

📌 **For Data Analysts:** Demonstrates practical skills in EDA, correlation analysis, and data visualization.

📌 **For Data Scientists:** Demonstrates hands-on experience with **regression, feature engineering, Random Forest, XGBoost, and model evaluation using MAE, RMSE, and R²**.

📌 **For Employers:** Demonstrates practical experience with **Python, Machine Learning, Scikit-learn, XGBoost, Pandas, and data visualization**.
