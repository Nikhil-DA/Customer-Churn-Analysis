
# 📊 Customer Churn Prediction

## 📌 Project Overview

This project focuses on predicting customer churn using machine learning techniques. The goal is to analyze telecom customer data, identify key factors driving churn, and build a predictive model that can help businesses take proactive actions to retain customers.

By the end of the project, we not only explored data insights but also deployed a **tuned Random Forest model** to achieve reliable predictions.

---

## 🎯 Objectives

* Perform **exploratory data analysis (EDA)** to understand customer behavior.
* Clean and preprocess data (handling missing values, encoding categorical features, etc.).
* Identify **key drivers of churn** (tenure, contract type, monthly charges, etc.).
* Build and evaluate **machine learning models** (Logistic Regression, Decision Trees, Random Forest).
* Tune the best model for **higher accuracy and balanced performance**.
* Save the final model using `joblib` for future deployment.

---

## 🛠️ Tech Stack & Tools

* **Python**  (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
* **Jupyter Notebook / VS Code** for development
* **Joblib** for model persistence
* **Git & GitHub** for version control

---

## 📂 Project Workflow

1. **Data Understanding & Cleaning**

   * Removed duplicates, handled missing values
   * Converted categorical features into numerical (dummy encoding)
   * Grouped tenure values into ranges for better interpretation

2. **Exploratory Data Analysis (EDA)**

   * Visualized churn distribution
   * Univariate and bivariate analysis (categorical & numerical features)
   * Correlation checks

3. **Feature Engineering & Preprocessing**

   * Created dummy variables (avoiding dummy variable trap)
   * Standardized numerical features

4. **Model Building & Evaluation**

   * Baseline models: Logistic Regression, Decision Tree, Random Forest
   * Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix
   * Chose **Random Forest** as final model

5. **Hyperparameter Tuning**

   * Used GridSearchCV for optimal parameters
   * Improved recall for minority class (Churn = 1)

6. **Model Saving**

   * Final model stored as `final_churn_model.pkl` using `joblib`

---

## 📈 Results

* **Best Model:** Tuned Random Forest
* **Accuracy (Test Set):** \~80%
* **Recall for Churn Class:** Significantly improved after tuning
* Key Insight: Contract type, tenure, and monthly charges were the strongest predictors of churn.

---

## 🚀 Future Improvements

* Deploy the model as a **web app** using Flask/Streamlit.
* Add **real-time prediction API** for businesses.
* Include **customer segmentation analysis** for better retention strategies.

---

## 📬 Contact

👤 **Nikhil Chauhan**
🔗 [LinkedIn](https://www.linkedin.com/in/nikhil-chauhan-755858371/)
📧 Email: *(chauhannikhil.email@gmail.com)*

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use, modify, and share with attribution.

---

✨ This project demonstrates end-to-end **Data Science workflow** – from raw data to actionable machine learning insights.


