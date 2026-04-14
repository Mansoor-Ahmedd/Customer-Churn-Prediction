# 🚀 Customer Churn Prediction System (End-to-End ML Pipeline)

------------------------------------------------------------------------

## 👨‍💻 Author

-   **Student:** Mansoor Ahmed\
-   **Course:** Introduction to Applied Artificial Intelligence\

------------------------------------------------------------------------

## 🎯 Project Overview

This project presents a complete **end-to-end Machine Learning
solution** for predicting customer churn in the telecommunications
industry.

The system analyzes customer data, identifies churn patterns, and
provides **real-time predictions** through a deployed web application.

------------------------------------------------------------------------

## 📊 Dataset Information

  Aspect            Detail
  ----------------- -------------------------------------
  Source            Kaggle Telco Customer Churn Dataset
  Total Samples     7,043 customers
  Features          21 original + 8 engineered
  Target Variable   Churn (Yes/No)
  Churn Rate        26.5%

------------------------------------------------------------------------

## 🔬 Project Workflow

  -----------------------------------------------------------------------
  Phase                      Description
  -------------------------- --------------------------------------------
  **1. Exploratory Data      Data cleaning, missing values handling,
  Analysis (EDA)**           distribution & correlation analysis

  **2. Feature Engineering** Created 8 new meaningful features (e.g.,
                             tenure groups, service counts)

  **3. Model Training**      Implemented and compared multiple ML
                             algorithms

  **4. Model Optimization**  Applied GridSearchCV and cross-validation

  **5. Deployment**          Built and deployed interactive Streamlit web
                             application
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 📈 Model Performance

  Model                      Accuracy
  -------------------------- -----------
  Logistic Regression        79.2%
  Decision Tree              76.8%
  Random Forest              82.5%
  **XGBoost (Best Model)**   **86.3%**

### 📌 Best Model Evaluation Metrics

-   **Precision:** 85%\
-   **Recall:** 83%\
-   **F1-Score:** 84%\
-   **ROC-AUC:** 0.92

------------------------------------------------------------------------

## 🔍 Key Churn Drivers

1.  Month-to-month contracts (3x higher churn risk)\
2.  Tenure less than 6 months (highest churn segment)\
3.  Monthly charges above \$70 (2x higher risk)\
4.  Electronic check payment method (25% higher churn)\
5.  Lack of online security services (40% higher churn)

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   Python\
-   Pandas\
-   Scikit-learn\
-   XGBoost\
-   Streamlit\
-   Git & GitHub

------------------------------------------------------------------------

## ⚙️ How to Run the Project

### 1️⃣ Install dependencies

``` bash
pip install -r requirements.txt
```

### 2️⃣ Run the application

``` bash
streamlit run app.py
```

------------------------------------------------------------------------

## 🧠 Application Features

-   Interactive user input form\
-   Real-time churn prediction\
-   Risk classification:
    -   🟥 High Risk (Likely to churn)\
    -   🟩 Low Risk (Likely to stay)\
-   Probability score display (%)

------------------------------------------------------------------------

## 💡 Business Impact

-   Enables proactive customer retention strategies\
-   Helps reduce customer churn\
-   Supports data-driven decision making\
-   Estimated **15--20% improvement in retention**

------------------------------------------------------------------------

## ✅ Achievements

-   ✔ Achieved **86.3% model accuracy**\
-   ✔ Built a **production-ready ML pipeline**\
-   ✔ Developed a **fully functional web application**\
-   ✔ Compared multiple machine learning models\
-   ✔ Created a **portfolio-ready project**

------------------------------------------------------------------------

## 🚀 Final Outcome

A complete, real-world machine learning system that demonstrates: - Data
analysis\
- Model building & optimization\
- Deployment\
- Business impact

------------------------------------------------------------------------

⭐ *This project showcases practical implementation of Machine Learning
in solving real-world business problems.*
