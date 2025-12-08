# 📘 Telecom Customer Churn Analysis  
A machine learning project designed to identify customers most likely to churn, enabling telecom companies to take proactive retention measures.

---

## 📊 Dataset  
This project uses the publicly available telecom churn dataset from Kaggle:  
👉 **[Churn in Telecoms Dataset](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset)**

The dataset includes customer demographics, service plans, billing details, usage patterns, and a churn indicator.

---

## 📂 Repository Structure  

```
Telecom-Analysis/
│
├── Telecom_Customer_Churn.ipynb      # Full analysis notebook
├── Telecom_Customer_Churn.html       # Static HTML export of notebook
├── Telecom_Churn_presentation.pdf    # Executive summary presentation
│
├── .gitignore
├── .ipynb_checkpoints/
└── added pdf and html files/
```

---

# 🚀 Project Overview  

This project follows a standard data science workflow adapted for churn prediction:

### **1. Business Understanding**  
Telecom companies face revenue loss from customer churn. The goal is to identify which customers are at highest risk and what factors drive churn.

### **2. Data Understanding**  
Exploratory analysis identifies trends such as service call frequency, plan type, and usage patterns that correlate with churn.

### **3. Data Preparation**  
Data is cleaned, encoded, scaled, and split into training and test sets.  
Categorical features are one-hot encoded; numerical features are standardized.

### **4. Modeling**  
Two supervised learning models were built:

- **Logistic Regression** – baseline classifier  
- **Decision Tree (tuned via GridSearchCV)** – optimized for depth, split criteria, and leaf size  

### **5. Evaluation**  
Models were assessed using key classification metrics (Accuracy, Precision, Recall, F1, ROC-AUC).  
The tuned Decision Tree performed best.

### **6. Insights & Recommendations**  
Churn risk is heavily driven by:

- Number of customer service calls  
- Whether the customer has an International Plan  
- Total Day Charges  

These findings inform targeted retention strategies.

---

# 📈 Model Performance Summary  

| Metric | Logistic Regression | Decision Tree (Tuned) |
|--------|----------------------|------------------------|
| Accuracy | 0.874 | 0.938 |
| Precision | 0.651 | 0.832 |
| Recall | 0.283 | 0.717 |
| F1 Score | 0.394 | 0.770 |
| ROC-AUC | 0.803 | 0.844 |

**Best Model:** Tuned Decision Tree  
This model provides clearer decision boundaries and better captures nonlinear churn patterns.

---

# 💼 Business Impact  

The project’s results support:

- **Proactive retention** by identifying high-risk customers  
- **Data-driven decision-making** for service improvements  
- **Prioritization of key churn drivers** for marketing and customer service teams  

---

# 🛠 Technologies Used  

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

# 👤 Author  
**Rahaman Yusuf**  
Data Engineer & Aspiring Data Scientist  
GitHub: https://github.com/rahroy82  
