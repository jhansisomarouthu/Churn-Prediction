**Project Overview:**
Customer churn poses a significant challenge for telecom companies, impacting both revenue and market share. This project leverages a comprehensive dataset and explores various machine learning models to predict customer churn, enabling effective targeted retention strategies.

**Key Features:**

**Data Preprocessing:** Addressed missing values, removed irrelevant columns, and performed feature selection by analyzing correlations and eliminating highly correlated features. Tackled class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).

**Exploratory Data Analysis (EDA):** Identified key churn drivers, such as account balance, outgoing activity, and service usage patterns. Visualized relationships between churn and factors like outgoing calls, SMS, and GPRS usage through insightful graphs.

**Predictive Modeling:** Trained nine machine learning models, including Decision Trees, Random Forest, and XGBoost. The XGBoost model delivered the highest F1 score and accuracy, with hyperparameter tuning further optimizing performance.

**Model Evaluation:** Evaluated models using metrics such as Accuracy, Precision, Recall, and F1 Score. The final XGBoost model achieved an accuracy of 80.4% on the test set.

**Feature Importance:** The most important features influencing churn prediction were customer lifetime, intake, and outgoing activity.

**Tools & Libraries:**

**Python:** Core programming language

**Pandas & NumPy:** For data manipulation

**Matplotlib & Seaborn:** For data visualization

**Scikit-learn & XGBoost:** For building and evaluating machine learning models

**Imbalanced-learn (SMOTE):** To handle class imbalance

**Results:**

**Best Model:** XGBoost Classifier

**Test Accuracy:** 80.4%

**Key Features:** Customer lifetime, intake, outgoing activity

**Future Scope:**
Focus on improving precision for churner predictions and exploring deep neural networks for enhanced accuracy, particularly with larger datasets.
