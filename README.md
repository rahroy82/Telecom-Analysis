# Telecom Customer Churn Prediction - Phase 3 Project

## 📘 Overview
This project uses machine learning to predict telecom customer churn — identifying which customers are most likely to leave.  
Two models are built and compared:
- **Logistic Regression (Baseline Model)**  
- **Decision Tree (Tuned Model)**  

The tuned Decision Tree achieved superior performance, offering actionable insights to reduce customer churn through data-driven decision-making.

---

## ⚙️ Project Workflow

1. **Data Loading & Exploration:** Import and examine the telecom churn dataset.  
2. **Data Cleaning:** Standardize column names and encode the target variable.  
3. **Feature Engineering:** Separate numerical and categorical features for processing.  
4. **Preprocessing:** Scale numeric values and encode categorical variables.  
5. **Modeling:**  
   - Logistic Regression (baseline model)  
   - Decision Tree (baseline and tuned models)  
6. **Evaluation:** Compare both models on key metrics: Accuracy, Precision, Recall, F1, and ROC-AUC.  
7. **Feature Importance:** Identify top churn drivers (Customer Service Calls, International Plan, Day Charges).  
8. **Business Insights:** Translate results into actionable retention strategies.

---

## 📊 Key Results

| Metric | Logistic Regression | Decision Tree (Tuned) |
|:--------|:-------------------:|:---------------------:|
| Accuracy | 0.874 | 0.938 |
| Precision | 0.651 | 0.832 |
| Recall | 0.283 | 0.717 |
| F1 Score | 0.394 | 0.770 |
| ROC-AUC | 0.803 | 0.844 |

**Best Model:** Tuned Decision Tree  
**Key Drivers:** Customer Service Calls, International Plan, Total Day Charges  

---

## 💼 Business Impact
This model enables telecom companies to:
- Identify high-risk churn customers in advance.  
- Improve retention through targeted offers and service enhancements.  
- Optimize plan structures to enhance customer satisfaction and reduce turnover.

---

## 🧰 Tools & Libraries
- **Python:** pandas, numpy, matplotlib, seaborn  
- **Machine Learning:** scikit-learn (LogisticRegression, DecisionTreeClassifier, GridSearchCV, Pipeline)  
- **Visualization:** seaborn, matplotlib  

---

## 👤 Author
**Rahaman Yusuf**  
Data Engineer | Aspiring Data Scientist  
