

# Customer Churn Prediction Project

📊 **Goal**: To predict whether a customer will churn (leave the service) or stay, using the Telco Customer Churn dataset.

---

## 🔍 Project Overview

This was one of my first **end-to-end machine learning projects**. The main aim was to explore the data, clean and preprocess it, build prediction models, and understand which factors contribute most to customer churn. 

I chose this project because churn is a **real-world business problem** faced by telecom, banking, and subscription-based industries.

---

## 🛠️ What I Did

* **Data Cleaning & Preprocessing**

  * Handled missing values and duplicates.
  * Converted categorical variables into dummy variables.
  * Dealt with class imbalance in the target variable.

* **Exploratory Data Analysis (EDA)**

  * Used visualizations (histograms, boxplots, bar charts) to explore customer behavior.
  * Found key trends: customers with shorter tenure and higher monthly charges churn more often.

* **Feature Engineering**

  * Created new grouped variables (e.g., tenure groups).
  * Scaled numerical features for better model performance.

* **Model Building & Evaluation**

  * Built classification models: Logistic Regression, Random Forest, and Gradient Boosting.
  * Evaluated models with Accuracy, Precision, Recall, F1-score, and ROC-AUC.
  * Focused on **Recall** since identifying churned customers is more important than overall accuracy.

---

## 📈 Key Insights

* Customers with **month-to-month contracts** and **no online security/tech support** are much more likely to churn.
* **Tenure** plays a big role — the shorter the customer relationship, the higher the churn risk.
* Even a small increase in customer retention can have a **huge impact on revenue**.

---

## 🚀 Tools & Technologies

* **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
* **Jupyter Notebook** for analysis & documentation

---

## 💡 Learnings

* Learned how to handle **imbalanced datasets**.
* Understood the importance of choosing the right evaluation metric.
* Improved my **EDA storytelling skills** — making plots that explain patterns clearly.

---

## 📂 Repository Structure

```
├── data/
│   ├── raw/                       # Original dataset (unchanged)
│   ├── final/                     # Final cleaned/processed dataset
│
├── outputs/
│   ├── final_churn_model.pkl      # Saved trained model
│
├── scripts/
│   ├── 01_EDA_Churn_Analysis.ipynb
│   ├── 02_Modeling_Churn_Prediction.ipynb
│
├── LICENSE                      
├── README.md                      
├── requirements.txt               

```

---

## 👤 Author

**Nikhil Chauhan**
🎓 MSc Statistics | Aspiring Data Analyst
🔗 [LinkedIn](https://www.linkedin.com/in/nikhil-chauhan-755858371/)


