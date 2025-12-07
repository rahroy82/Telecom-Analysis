# 📘 Telecom Customer Churn Analysis  
Repository: **Telecom-Analysis**

This project focuses on predicting customer churn in the telecom industry using supervised machine learning models.  
The goal is to identify customers likely to leave and help telecom companies implement targeted retention strategies.

---

# 📊 Dataset  
The dataset used in this project comes from Kaggle:  
👉 **[Churn in Telecoms Dataset](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset)**  

The dataset contains customer demographics, service plans, service usage, billing information, and churn labels.

---

# 📂 Repository Structure  

Your repository (`Telecom-Analysis`) contains the following files and folders:

```
Telecom-Analysis/
│
├── .ipynb_checkpoints/                  # Auto-generated Jupyter Notebook backup files
├── .gitignore                           # Git ignore rules used for this project
├── README.md                            # Project documentation (this file)
│
├── Telecom_Customer_Churn.ipynb         # Main Jupyter Notebook (full analysis and model building)
├── Telecom_Customer_Churn.html          # HTML export of the notebook (static, view-only)
├── Telecom_Churn_presentation.pdf       # Executive summary presentation for stakeholders
│
└── added pdf and html files/            # Folder containing additional exports (PDFs/HTMLs)
```

---

# 🚀 How to Navigate This Repository  

### **1️⃣ Start Here — README.md**  
Gives you:
- Project purpose  
- Dataset source  
- Modeling overview  
- Navigation instructions  
- Final business insights  

---

### **2️⃣ View the Full Project Notebook**  
Choose how you want to read the analysis:

- **Interactive Version (Recommended):**  
  👉 `Telecom_Customer_Churn.ipynb`  
  Open using Jupyter Notebook, Jupyter Lab, or VS Code.

- **Static Browser Version:**  
  👉 `Telecom_Customer_Churn.html`  
  Open directly in any web browser.

This notebook includes:
- Data cleaning  
- Exploratory analysis  
- Preprocessing  
- Logistic Regression baseline model  
- Decision Tree baseline + tuned model (GridSearchCV)  
- Evaluation metrics  
- Feature importance  
- Business insights  

---

### **3️⃣ Review the Presentation (For Stakeholders)**  
👉 `Telecom_Churn_presentation.pdf`  

This PDF is ideal for:
- Business decision makers  
- Lightly technical audiences  
- Executive-level summaries  

It highlights:
- Business problem  
- Data overview  
- Modeling approach  
- Key metrics  
- Recommendations  

---

# ⚙️ Project Workflow  

1. **Load Dataset**  
2. **Explore Data & Understand Churn Patterns**  
3. **Clean and Transform Features**  
4. **Preprocess Numerical and Categorical Variables**  
5. **Build Models:**  
   - Logistic Regression (baseline)  
   - Decision Tree (baseline)  
   - Tuned Decision Tree (GridSearchCV)  
6. **Evaluate Model Performance**  
7. **Interpret Results & Identify Key Drivers of Churn**  
8. **Provide Business Recommendations**  

---

# 📈 Model Performance Summary  

| Metric | Logistic Regression | Decision Tree (Tuned) |
|--------|----------------------|------------------------|
| Accuracy | 0.874 | 0.938 |
| Precision | 0.651 | 0.832 |
| Recall | 0.283 | 0.717 |
| F1 Score | 0.394 | 0.770 |
| ROC-AUC | 0.803 | 0.844 |

### **Best Model:**  
🔥 **Tuned Decision Tree Classifier**

### **Top Churn Predictors Identified:**  
- Number of Customer Service Calls  
- Whether the Customer Has an International Plan  
- Total Day Charge  

---

# 💼 Business Impact  

The project provides insights that help telecom companies:

- Detect high-risk churn customers early  
- Improve customer retention strategies  
- Reduce service cancellations  
- Lower churn-related revenue losses  
- Develop better customer segmentation and outreach campaigns  

---

# 🛠 Tools & Technologies  

- **Python**  
- **Jupyter Notebook**  
- **Pandas, NumPy**  
- **Scikit-learn (LogisticRegression, DecisionTreeClassifier, GridSearchCV)**  
- **Matplotlib, Seaborn**  

---

# 👤 Author  
**Rahaman Yusuf**  
Data Engineer | Aspiring Data Scientist  
GitHub: https://github.com/rahroy82
