# 🎬 Film Analytics: Genre Trends, Budget & Revenue Prediction
> A comprehensive data science project that analyzes historical film data to uncover genre trends and utilizes advanced machine learning models to predict movie budgets and box office revenue.

![Python](https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Data_Analysis-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/ML-Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![CatBoost](https://img.shields.io/badge/Model-CatBoost-FFCC00?style=for-the-badge&logo=catboost&logoColor=black)
![Optuna](https://img.shields.io/badge/Tuning-Optuna-4A4A4A?style=for-the-badge&logo=optuna&logoColor=white)

---

## Project Overview

The film industry is high-risk and high-reward. This project aims to reduce that risk by providing data-driven insights. By analyzing movie features—such as genre, runtime, and creators—we can identify shifting audience preferences and build predictive models to estimate financial outcomes (Budget & Revenue) with high accuracy.

**Who is this for?**
* **Producers & Investors:** To estimate costs and potential ROI.
* **Content Strategists:** To understand which genres are currently trending.

---

## Key Objectives

1.  **📈 Genre Trend Analysis:**
    * Identifying high-revenue genres over specific time periods.
    * Visualizing shifts in audience preferences to spot emerging market trends.
2.  **💰 Budget Estimation:**
    * Predicting production costs based on pre-production features (Genre, Star Power, Runtime).
3.  **💸 Revenue Prediction:**
    * Forecasting global box office revenue using regression models to gauge financial success.

---

## Methodology & Techniques

### 1. Data Preprocessing & EDA
* **Multi-label Handling:** Decoded complex genre combinations (e.g., "Action, Sci-Fi, Thriller") into analyzable formats.
* **Outlier Detection:** Managed extreme values in budget/revenue to prevent model skewing.
* **Exploratory Data Analysis:** Visualized correlations between runtime, budget, and audience ratings.

### 2. Unsupervised Learning (Clustering)
* **K-Means Clustering:** Grouped films into meaningful "Archetypes" based on their features to find hidden patterns in successful movies.

### 3. Predictive Modeling (Machine Learning)
* **Algorithm:** Implemented **CatBoost Regressor**, a high-performance gradient boosting library ideal for categorical data.
* **Hyperparameter Tuning:** utilized **Optuna** to automate the search for optimal model parameters, significantly improving prediction accuracy.

---

## Tech Stack

| Category | Tools / Libraries |
| :--- | :--- |
| **Language** | Python |
| **Data Manipulation** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Machine Learning** | Scikit-learn, CatBoost |
| **Optimization** | Optuna |

---

## Key Outcomes & Insights

* **The "Genre" Factor:** Certain genre combinations consistently outperform others regardless of budget size.
* **Model Performance:** The integration of **CatBoost + Optuna** yielded a robust model capable of predicting revenue with a low margin of error compared to baseline linear regression.
* **Strategic Value:** The project proves that financial success is not random; it correlates strongly with identifiable features like runtime and production scale, offering a roadmap for smarter investment.
